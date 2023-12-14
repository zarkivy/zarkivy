```Rust
impl Zarkivy {
    pub fn about() -> Self {
        Self {
            name: "Kevin Zhang",
            birth: 1999,
            email: "zarkivy@outlook.com",
            school: "Beijing Institute of Technology",
        }
    }
}

impl Programmer for Zarkivy {
    fn topics(&self) -> Vec<&'static str> {
        vec!["IaaS", "Container", "Virtualization", "Kernel"]
    }

    fn languages(&self) -> Vec<&'static str> {
        vec!["Rust", "Python", "Golang", "C", "C++", "Bash"]
    }
}
```
