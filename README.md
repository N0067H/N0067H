# NoobTh
```rust
#[derive(Debug)]
struct Me<'a> {
    name: String,
    tech: Vec<&'a str>,
    favorite_lang: Vec<&'a str>,
}

impl<'a> Default for Me<'a> {
    fn default() -> Self {
        Me {
            name: "NoobTh".to_string(),
            tech: vec![
                "Go",
                "C++",
                "C#",
            ],
            favorite_lang: vec![
                "C++", "Rust", "C#", "Typescript"
            ],
        }
    }
}

fn main() {
    println!("{:?}", Me::default());
}
```

> ***thx to [@wHoIsDReAmer](https://github.com/wHoIsDReAmer) for the profile reference.***
