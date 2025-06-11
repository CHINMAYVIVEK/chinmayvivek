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


<p align="center">
  <!-- Languages -->
  <img alt="Rust" src="https://img.shields.io/badge/-Rust-000000?style=for-the-badge&logo=rust&logoColor=white" />
  <img alt="Golang" src="https://img.shields.io/badge/-Golang-00ADD8?style=for-the-badge&logo=go&logoColor=white" />
  <img alt="Python" src="https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img alt="PHP" src="https://img.shields.io/badge/-PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" />
</p>

<p align="center">
  <!-- Frameworks -->
  <img alt="Tauri" src="https://img.shields.io/badge/-Tauri-FFFFFF?style=for-the-badge&logo=tauri&logoColor=000000" />
  <img alt="Dioxus" src="https://img.shields.io/badge/-Dioxus-1A1A1A?style=for-the-badge&logo=rust&logoColor=white" />
  <img alt="Gorilla Mux" src="https://img.shields.io/badge/-Gorilla_Mux-00ADD8?style=for-the-badge&logo=go&logoColor=white" />
  <img alt="Flask" src="https://img.shields.io/badge/-Flask-000000?style=for-the-badge&logo=flask&logoColor=white" />
  <img alt="FastAPI" src="https://img.shields.io/badge/-FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
</p>

<p align="center">
  <!-- Databases -->
  <img alt="MySQL" src="https://img.shields.io/badge/-MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
  <img alt="MongoDB" src="https://img.shields.io/badge/-MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
  <img alt="PostgreSQL" src="https://img.shields.io/badge/-PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" />
</p>

<p align="center">
  <!-- DevOps -->
  <img alt="Docker" src="https://img.shields.io/badge/-Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img alt="Git" src="https://img.shields.io/badge/-Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img alt="Linux" src="https://img.shields.io/badge/-Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
</p>

<p align="center">
  <!-- Frontend -->
  <img alt="HTMX" src="https://img.shields.io/badge/-HTMX-000000?style=for-the-badge" />
  <img alt="HTML5" src="https://img.shields.io/badge/-HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img alt="SCSS" src="https://img.shields.io/badge/-SCSS-CC6699?style=for-the-badge&logo=sass&logoColor=white" />
  <img alt="Bootstrap" src="https://img.shields.io/badge/-Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" />
  <img alt="Tailwind CSS" src="https://img.shields.io/badge/-Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white" />
</p>

<p align="center">
  <!-- AI/ML -->
  <img alt="TensorFlow" src="https://img.shields.io/badge/-TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
  <img alt="PyTorch" src="https://img.shields.io/badge/-PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img alt="Hugging Face" src="https://img.shields.io/badge/-Hugging_Face-FB6C0F?style=for-the-badge&logo=huggingface&logoColor=white" />
  <img alt="OpenCV" src="https://img.shields.io/badge/-OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" />
  <img alt="LangChain" src="https://img.shields.io/badge/-LangChain-000000?style=for-the-badge" />
  <img alt="GPT APIs" src="https://img.shields.io/badge/-GPT_APIs-434343?style=for-the-badge" />
</p>

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
