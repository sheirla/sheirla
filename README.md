
```rust
fn main() {
    println!("Hello, World 👋!");

    let skills = ["Rust", "TypeScript", "React", "Next.js","Tauri","Electron","React Native", "Flutter", "Go", "Laravel"];
    for skill in skills {
        println!("💡 I love working with: {}", skill);
    }

    if let Ok(_) = try_something_new("Rust") {
        println!("🚀 Always learning something new!");
    }
}

fn try_something_new(topic: &str) -> Result<(), &'static str> {
    if topic == "Rust" {
        Ok(())
    } else {
        Err("Hmm, not today.")
    }
}
```
