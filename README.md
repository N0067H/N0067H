<table>
  <tr>
    <td valign="top">

```rust
#[derive(Debug)]
pub struct Profile {
    pub name: &'static str,
    pub role: &'static str,
    pub languages: &'static [&'static str],
    pub interests: &'static [&'static str],
    pub environments: &'static [&'static str],
}

pub const ME: Profile = Profile {
    name: "SeungYeop Ryu",
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
        "NixOS (with Hyprland)",
    ],
};
```
</td>
<td valign="top">
  <a href="https://github.com/kittinan/spotify-github-profile">
    <img
      src="https://spotify-github-profile.kittinanx.com/api/view?uid=31ym3phyazhq3qomcvpudonlhxge&cover_image=true&theme=default&show_offline=false&background_color=121212&interchange=false&profanity=false&hide_remaster=false"
    />
  </a>
</td>
