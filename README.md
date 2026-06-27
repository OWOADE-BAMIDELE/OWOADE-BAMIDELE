from pathlib import Path

content = r"""# Hi there 👋, I'm Owoade Bamidele

💻 Passionate Developer | 🚀 Tech Enthusiast | 🌍 Based in Nigeria

Welcome to my GitHub profile!  
I enjoy building software, learning new technologies, and solving real-world problems through code.

---

## 🚀 About Me

- 🔭 I’m currently working on: **Awesome Projects**
- 🌱 I’m currently learning: **New Technologies & Frameworks**
- 👯 I’m looking to collaborate on: **Open Source Projects**
- 💬 Ask me about: **Web Development, Programming, and Tech**
- ⚡ Fun fact: **I love turning ideas into reality with code**

---

## 🛠️ Tech Stack

### Languages
![JavaScript](https://img.shields.io/badge/-JavaScript-black?style=flat-square&logo=javascript)
![Python](https://img.shields.io/badge/-Python-black?style=flat-square&logo=python)
![HTML5](https://img.shields.io/badge/-HTML5-black?style=flat-square&logo=html5)
![CSS3](https://img.shields.io/badge/-CSS3-black?style=flat-square&logo=css3)

### Frameworks & Tools
![React](https://img.shields.io/badge/-React-black?style=flat-square&logo=react)
![Node.js](https://img.shields.io/badge/-Node.js-black?style=flat-square&logo=node.js)
![Git](https://img.shields.io/badge/-Git-black?style=flat-square&logo=git)
![GitHub](https://img.shields.io/badge/-GitHub-black?style=flat-square&logo=github)
![VS Code](https://img.shields.io/badge/-VSCode-black?style=flat-square&logo=visual-studio-code)

---

## 📊 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=OWOADE-BAMIDELE&show_icons=true&theme=tokyonight)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=OWOADE-BAMIDELE&layout=compact&theme=tokyonight)

---

## 🔥 GitHub Streak

![GitHub Streak](https://streak-stats.demolab.com?user=YOUR_USERNAME&theme=tokyonight)

---

## 🌐 Connect With Me

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=linkedin)](https://linkedin.com/in/YOUR_LINK)
[![Twitter](https://img.shields.io/badge/-Twitter-black?style=flat-square&logo=x)](https://twitter.com/YOUR_HANDLE)
[![Portfolio](https://img.shields.io/badge/-Portfolio-black?style=flat-square&logo=firefox)](https://YOUR_WEBSITE.com)
[![Email](https://img.shields.io/badge/-Email-red?style=flat-square&logo=gmail)](mailto:owoadeoluwabamidele@gmail.com)

---

## ✨ Quote I Live By

> “Code. Learn. Build. Repeat.”

---

⭐ Thanks for visiting my profile!
"""

path = Path("/mnt/data/readme.md")
path.write_text(content, encoding="utf-8")

print(f"README markdown file created at: {path}")
