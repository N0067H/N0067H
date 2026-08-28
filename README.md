```rust
#[derive(Debug)]
pub struct Engineer {
    pub name: &'static str,
    pub role: &'static str,
    pub languages: &'static [&'static str],
    pub interests: &'static [&'static str],
    pub environments: &'static [&'static str],
}

pub const ME: Engineer = Engineer {
    name: "SeungYeop Ryu"
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
