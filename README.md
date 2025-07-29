# Flake
❄️ A statically typed, functional, friendly language for WASM.

# Example
```flake
import std::io

type Cat {
  fish: I16,
  health: F32,
} impl {
  fn get_fish(cat: Cat) -> Int {
    return cat.fish 
  }
}

fn main() {
	io.println(cat.get_fish().to_string())
}
```
