# Flake
❄️ A statically typed, functional, friendly language for WASM.

# Example
```flake
type Cat {
	fish: Int
}

impl Cat {
	fn get_fish(self: Cat) -> Int {
		 return self.fish 
	}
}

fn main() {
	let cat = Cat { food: 34 }
	io.println(cat.get_fish().to_string())
}
```
