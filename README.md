# Hey there, I’m Chinmay Vivek 👋

🚀 **Builder of fast AI products | Rustacean | Golang Lover | Python Enthusiast | PHP Dev**

---

<p align="center">
  <i><b>Let's connect and create something amazing together!</b></i>
</p>

<p align="center">
  <a href="https://www.chinmayvivek.com/" target="_blank" rel="noopener">
    <img height="30" src="https://img.shields.io/badge/Website-036be4.svg?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website"/>
  </a>
  &nbsp;
  <a href="https://www.linkedin.com/in/chinmayvivek/" target="_blank" rel="noopener">
    <img height="30" src="https://img.shields.io/badge/LinkedIn-blue.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
</p>

---
<!-- ![Profile Views](https://komarev.com/ghpvc/?username=ChinmayVivek&style=for-the-badge) -->

## ✨ Explore My Code Snippets & Experiments on Gist!

<p align="center">
  <a href="https://gist.github.com/CHINMAYVIVEK" target="_blank" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/Explore-Gists-blue?style=for-the-badge&logo=github" alt="Gist Badge"/>
  </a>
</p>

> Dive into my collection of mini-projects, useful snippets, and experiments. Perfect for quick inspiration or collaboration!

---
## 👨‍💻 Who am I?

```rust
struct Developer {
    name: &'static str,
    what_i_do: &'static [&'static str],
    skills: &'static [(&'static str, &'static [&'static str])],
}

impl Developer {
    fn new(
        name: &'static str,
        what_i_do: &'static [&'static str],
        skills: &'static [(&'static str, &'static [&'static str])],
    ) -> Self {
        Self {
            name,
            what_i_do,
            skills,
        }
    }

    fn print_profile(&self) {
        println!("👤 Developer: {}\n", self.name);

        println!("🎯 What I do:");
        for &area in self.what_i_do {
            println!("- {}", area);
        }

        println!("\n🛠️ Skills:");
        for &(category, tools) in self.skills {
            print!("- {}: ", category);
            for (i, &tool) in tools.iter().enumerate() {
                if i > 0 {
                    print!(", ");
                }
                print!("{}", tool);
            }
            println!();
        }

        println!("\n🤝 Let's connect and build something great together!");
    }
}

static WHAT_I_DO: &[&str] = &[
    "Helping Founders Build & Launch AI Products Fast 🚀",
    "Go, Rust, Python, LLMs, GenAI, CV",
    "MVPs to Scalable Systems",
    "Product Engineer",
    "AI/ML Consultant",
];

static SKILLS: &[(&str, &[&str])] = &[
    ("Languages", &["Rust", "Golang", "Python", "PHP"]),
    ("Frameworks", &["Tauri", "Dioxus", "Gorilla Mux", "Flask", "Fast API"]),
    ("Databases", &["MySQL", "MongoDB", "PostgreSQL"]),
    ("DevOps", &["Docker", "Git", "Linux"]),
    ("Frontend", &["HTMX", "HTML/SCSS", "Bootstrap", "Tailwind CSS"]),
    ("AI/ML", &[
        "TensorFlow", "PyTorch", "Hugging Face Transformers",
        "OpenCV", "LangChain", "GPT APIs",
    ]),
];

fn main() {
    let chinmay = Developer::new("Chinmay Vivek", WHAT_I_DO, SKILLS);
    chinmay.print_profile();
}


```

---

## 🚀 Tech Stacks I Rock

| Category   | Tools                                                          |
| ---------- | -------------------------------------------------------------- |
| Languages  | Rust, Golang, Python, PHP                                      |
| Frameworks | Tauri, Dioxus, Gorilla Mux, Flask, Fast API                    |
| Databases  | MySQL, MongoDB, PostgreSQL                                     |
| DevOps     | Docker, Git, Linux                                             |
| Frontend   | HTMX, HTML/SCSS, Bootstrap, Tailwind CSS                       |
| AI/ML      | TensorFlow, PyTorch, Hugging Face, OpenCV, LangChain, GPT APIs |

---

## 📊 GitHub Insights

![Top Languages](https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=ChinmayVivek\&theme=onedark)
![Most Commit Language](https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=ChinmayVivek\&theme=onedark)

---

## 🏆 GitHub Trophies

<p align="left">
  <a href="https://github.com/ryo-ma/github-profile-trophy">
    <img src="https://github-profile-trophy.vercel.app/?username=ChinmayVivek&theme=onedark" alt="Trophies" />
  </a>
</p>

---

✨ **Show some ❤️ by starring repositories and connecting!**

---
