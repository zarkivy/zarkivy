```Rust
impl Zarkivy {
    pub fn about() -> Self {
        Self {
            name: "Kevin Zhang",
            birthday: 1999,
            email: "zarkivy@outlook.com",
            school: "Beijing Institute of Technology",
        }
    }
}

impl Programmer for Zarkivy {
    fn topics(&self) -> Vec<&'static str> {
        vec!["OS", "Embeded", "Virtualization"]
    }

    fn languages(&self) -> Vec<&'static str> {
        vec!["Rust", "Python", "C", "C++", "Bash"]
    }
}

impl Cybersecurity for Zarkivy {
    fn topics(&self) -> Vec<&'static str> {
        vec![
            "Embeded Security",
            "Pwn",
            "Fuzz Testing",
            "Program Analysis",
        ]
    }
}
```
