# Hello, I'm NoobTh (SeungYeop Ryu)
```rust
#[derive(Debug)]
struct Me<'a> {
    name: String,
    languages: Vec<&'a str>,
}

impl<'a> Default for Me<'a> {
    fn default() -> Self {
        Self {
            name: "NoobTh".into(),
            languages: vec![
                "C++", "Go", "Rust", "Java", "C#"
            ],
        }
    }
}

fn main() {
    println!("{:?}", Me::default());
}
```

---

> inspired by [@wHoIsDReAmer](https://github.com/wHoIsDReAmer)
