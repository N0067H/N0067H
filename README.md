# NoobTh
```rust
#[derive(Debug)]
struct Me<'a> {
    name: String,
    tech: Vec<&'a str>,
    favorite_lang: Vec<&'a str>,
}

impl Default for Me {
    fn default() -> Self {
        Self {
            name: "NoobTh".into(),
            languages: vec![
                "C++",
                "Go",
                "Rust",
                "Java"
            ]
        }
    }
}

fn main() {
    println!("{:?}", Me::default());
}
```

---

> inspired by [@wHoIsDReAmer](https://github.com/wHoIsDReAmer)
