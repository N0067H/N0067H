# NoobTh
> As a programmer for 8 years I’ve grown by obsessing over the question “Why does this work the way it does?”<br>
> While others focus on results, I’ve spent my time dissecting code flows, runtime behaviors, and language mechanisms.<br>
> My goal is to be a developer who solves problems with evidence and logic.<br>

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
