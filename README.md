## N0067H (SeungYeop Ryu)

```rust
#[derive(Debug)]
pub struct Engineer {
    pub role: &'static str,
    pub languages: &'static [&'static str],
    pub interests: &'static [&'static str],
    pub environments: &'static [&'static str],
}

pub const N0067H: Engineer = Engineer {
    role: "Software Engineer",

    languages: &[
        "Rust",
        "C++",
    ],

    interests: &[
        "OS Internals",
        "Networking",
        "Programming Languages",
        "Reverse Engineering",
    ],

    environments: &[
        "Windows / WSL",
        "Arch Linux",
    ],
};
```
