# NoobTh
> As a programmer for 8 years I’ve grown by obsessing over the question “Why does this work the way it does?”<br>
저는 8년동안 프로그래머로서 "이건 왜 이렇게 돌아가지?"라는 의문을 가지고 성장했습니다.<br>

> While others focus on results, I’ve spent my time dissecting code flows, runtime behaviors, and language mechanisms.<br>
남들이 결과에 집중할 때, 저는 코드의 흐름과 런타임의 동작, 그리고 언어의 매커니즘을 이해하기 위해 시간을 쏟았습니다.<br>

> My goal is not to be a loud developer who just talks, but a grounded one who solves problems with evidence and logic.<br>
입만 시끄러운 개발자가 아닌. 논리와 이유에 기반해 문제를 해결하는 현실적인 개발자가 되고자 합니다.<br>

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

> *thx to [@wHoIsDReAmer](https://github.com/wHoIsDReAmer) for the profile reference.*
