# portfolio-website
Modern animated portfolio — Full Stack Developer &amp; AI Engineer | Python · Django · React.js | Built with HTML/CSS/JS · EmailJS · GitHub Pages

# 🚀 Shreyash Secretary — Personal Portfolio Website

> Full Stack Developer · Python & Django Engineer · AI Integration Specialist

A modern, animated single-file portfolio website built with pure HTML, CSS, and JavaScript. Features a custom glowing cursor with trailing tail, animated aurora background, 3D rotating hero visual, dual-direction skill marquees, AI learning journey section, and a live contact form powered by EmailJS.

---

## 🌐 Live Demo

**[shreyashsecretary.github.io/portfolio](https://ssecretary.github.io/portfolio-website/)**

---

## ✨ Features

- 🎨 **Custom animated cursor** — glowing dot with trailing tail effect
- 🌌 **Aurora background** — warm animated color orbs (orange, violet, amber, rose)
- 🎲 **3D rotating hero cube** — showcasing tech stack on each face
- 📜 **Dual infinite marquees** — core skills and AI skills scrolling in opposite directions
- ⌨️ **Typewriter effect** — cycling through role titles
- 🤖 **AI Learning Journey section** — transparent progress timeline with live terminal animation
- 📊 **Animated skill bars** — triggered on scroll
- 📬 **Live contact form** — powered by EmailJS, sends directly to Gmail
- 📄 **Embedded resume download** — PDF baked into the file, no extra upload needed
- 🔢 **Counter animations** — stats count up on scroll
- 📱 **Fully responsive** — works on all screen sizes
- ⚡ **Zero dependencies** — single HTML file, no build step needed

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Structure | HTML5 |
| Styling | CSS3 (custom properties, animations, grid, flexbox) |
| Interactivity | Vanilla JavaScript (ES6+) |
| Email | EmailJS Browser SDK v4 |
| Fonts | Google Fonts — Outfit, DM Sans, JetBrains Mono |
| Deployment | GitHub Pages |

---

## 📁 Project Structure

```
portfolio/
│
├── index.html          # Entire website — all CSS, JS, and resume PDF embedded
└── README.md           # This file
```

---

## 🚀 Deployment

This project is deployed on **GitHub Pages** and requires zero configuration.

### Deploy your own copy

```bash
# 1. Fork or clone this repo
git clone https://github.com/ssecretary/portfolio.git
cd portfolio

# 2. Edit index.html with your own details

# 3. Push to GitHub
git add .
git commit -m "Update portfolio"
git push origin main

# 4. Enable GitHub Pages
# Go to Settings → Pages → Source: Deploy from branch (main / root)
# Live at: https://yourusername.github.io/portfolio
```

---

## 📬 Contact Form Setup (EmailJS)

The contact form uses [EmailJS](https://emailjs.com) to send emails without a backend.

To configure for your own use:

1. Sign up at [emailjs.com](https://emailjs.com)
2. Connect your Gmail under **Email Services**
3. Create an email template with these variables:
   ```
   {{from_name}}   {{from_email}}   {{subject}}   {{message}}
   ```
4. Replace these values in `index.html`:
   ```javascript
   emailjs.init("YOUR_PUBLIC_KEY");
   emailjs.send("YOUR_SERVICE_ID", "YOUR_TEMPLATE_ID", {...})
   ```
5. Add your GitHub Pages URL to **EmailJS → Account → Allowed Origins**

---

## 🎨 Color Palette

| Variable | Color | Usage |
|---|---|---|
| `--or` | `#f97316` | Primary orange — main accent |
| `--am` | `#fbbf24` | Amber — secondary accent |
| `--vi` | `#a855f7` | Violet — AI/learning sections |
| `--ro` | `#f43f5e` | Rose — error states |
| `--gr` | `#22c55e` | Green — success states |
| `--bg` | `#06050a` | Deep dark background |

---

## 📄 Sections

| Section | Description |
|---|---|
| **Hero** | Name, animated role titles, stats, social links, 3D cube |
| **About** | Bio, experience timeline, bento grid info cards |
| **Skills** | Tech stack grid, AI skills (with learning indicators), proficiency bars |
| **AI Journey** | 6-step learning roadmap with live terminal animation |
| **Services** | 6 service cards covering what I offer |
| **Projects** | Featured work — ChatInc, Gridkey, ArcelorMittal |
| **Contact** | Live EmailJS form + direct contact links |

---

## 🙋 About Me

**Shreyash Secretary** — Full Stack Developer with 5+ years of experience building production-grade web applications across fintech, enterprise manufacturing, and real-time communication platforms. Expert in Python, Django, and React.js. Actively building AI/LLM engineering skills.

📧 shreyashsecretary@gmail.com
🔗 [LinkedIn](https://www.linkedin.com/in/shreyash-secretary-81325b1b2/)
🐙 [GitHub](https://github.com/ssecretary)

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

Feel free to use it as inspiration for your own portfolio — just replace the content with your own details.

---

<div align="center">
  <p>Built with ❤️ and lots of ☕ by Shreyash Secretary</p>
  <p>⭐ Star this repo if you found it helpful!</p>
</div>
