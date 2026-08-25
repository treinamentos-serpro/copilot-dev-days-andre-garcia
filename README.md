🌐 [Português (BR)](README.pt_BR.md) | [Español](README.es.md)

<div align="center">

# 🎉 Soc Ops

### Social Bingo — Break the ice, make connections, have fun!

> Find people who match the prompts. Get **5 in a row** and shout **Bingo!** 🏆

[![Java 21](https://img.shields.io/badge/Java-21-orange?logo=openjdk)](https://adoptium.net/)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.4.2-brightgreen?logo=springboot)](https://spring.io/projects/spring-boot)
[![Build](https://img.shields.io/github/actions/workflow/status/treinamentos-serpro/copilot-dev-days-andre-garcia/pages.yml?label=deploy&logo=githubactions)](../../actions)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

**[🎮 Live Demo](https://treinamentos-serpro.github.io/copilot-dev-days-andre-garcia/) · [📚 Lab Guide](workshop/GUIDE.md) · [🤝 Contributing](CONTRIBUTING.md)**

</div>

---

## ✨ What is Soc Ops?

**Soc Ops** is an open-source **Social Bingo** web app built with Spring Boot and Thymeleaf. It's perfect for workshops, onboarding sessions, and in-person meetups — each player gets a unique 5×5 bingo card filled with icebreaker prompts. Mingle, mark off matches, and be the first to complete a row!

| Feature | Details |
|---------|---------|
| 🃏 **Dynamic cards** | Randomized 5×5 board on every load |
| 🏆 **Win detection** | Automatic row/column/diagonal check |
| 📱 **Responsive** | Works on mobile, tablet, and desktop |
| 🚀 **Zero friction** | No login, no database — just open and play |

---

## 🚀 Quick Start

**Prerequisites:** [Java 21 JDK](https://adoptium.net/) · Maven Wrapper (included)

```bash
# Clone & run
git clone https://github.com/treinamentos-serpro/copilot-dev-days-andre-garcia.git
cd copilot-dev-days-andre-garcia/socops
./mvnw spring-boot:run
# 👉 Open http://localhost:8080
```

---

## 🛠️ Development Commands

```bash
cd socops

# Run locally
./mvnw spring-boot:run

# Build
./mvnw clean package

# Test
./mvnw test
```

> Deploys automatically to GitHub Pages on push to `main`.

---

## 📚 Lab Guide — GitHub Copilot Agent Workshop

This repo is the foundation for a **hands-on Copilot agent lab**. Follow the guide to build, redesign, and extend Soc Ops using GitHub Copilot's agent features.

| Part | Title | Time |
|------|-------|------|
| [**00**](workshop/00-overview.md) | Overview & Checklist | — |
| [**01**](workshop/01-setup.md) | Setup & Context Engineering | 15 min |
| [**02**](workshop/02-design.md) | Design-First Frontend | 15 min |
| [**03**](workshop/03-quiz-master.md) | Custom Quiz Master | 10 min |
| [**04**](workshop/04-multi-agent.md) | Multi-Agent Development | 20 min |

> 📝 All guides are available offline in the [`workshop/`](workshop/) folder.

---

## 🤝 Contributing

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) and follow the [Code of Conduct](CODE_OF_CONDUCT.md).

---

<div align="center">

Made with ☕ and [Spring Boot](https://spring.io/projects/spring-boot) · [MIT License](LICENSE)

</div>
