# NoobTh
<a href="https://noobth.dev/" target="_blank">https://noobth.dev/</a>
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
            lang: vec![
                "C++", "Rust", "Go",
                "Java", "C#",
                "JavaScript", "TypeScript"
            ],
        }
    }
}

fn main() {
    println!("{:?}", Me::default());
}
```

> ***thx to [@wHoIsDReAmer](https://github.com/wHoIsDReAmer) for the profile reference.***

---

<img alt="image" src="https://imgs.xkcd.com/comics/cant_sleep.png" />
