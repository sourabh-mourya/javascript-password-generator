# Password Generator

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![No Dependencies](https://img.shields.io/badge/Dependencies-None-blue?style=for-the-badge)

A simple and responsive **Password Generator** built with HTML, CSS, and JavaScript. Generates strong, customizable passwords instantly in the browser — no backend, no data sent anywhere.

---

## Demo

> *(Add your screenshot here)*

---

## Features

- Adjustable password length via slider **(6–20 characters)**
- Toggle **Uppercase** letters (A–Z)
- Toggle **Lowercase** letters (a–z)
- Toggle **Numbers** (0–9)
- Toggle **Special Characters** (!@#$%^&*)
- One-click instant password generation
- Fully responsive and mobile-friendly
- 100% client-side — **no data is stored or transmitted**

---

## Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Page structure and markup |
| CSS3 | Styling and responsive layout |
| JavaScript (ES6+) | Password logic and DOM manipulation |

---

## Project Structure

```
password-generator/
├── index.html      → Main HTML structure
├── style.css       → Styling and responsive design
├── script.js       → Password generation logic
└── README.md       → Project documentation
```

---

## How It Works

1. Select the desired **password length** using the slider.
2. Toggle which **character types** to include.
3. Click **Generate Password** — JavaScript builds a character pool from your selections, picks characters randomly, and displays the result instantly.

> **Note:** This project uses `Math.random()` for general-purpose password generation. For cryptographically secure passwords, `crypto.getRandomValues()` (Web Crypto API) is the recommended approach — listed in future improvements.

---

## Getting Started

```bash
# Clone the repository
git clone https://github.com/your-username/password-generator.git

# Open in browser
cd password-generator
# Simply open index.html — no build tools or installs needed
```

---

## What I Learned

- DOM manipulation and dynamic UI updates
- Event handling (sliders, checkboxes, buttons)
- Random number generation with `Math.random()`
- Building character pool logic programmatically
- Responsive layout design with CSS
- Basics of client-side security thinking

---

## Future Improvements

- [ ] Use `crypto.getRandomValues()` for cryptographically secure generation
- [ ] Add a password strength indicator (Weak / Medium / Strong)
- [ ] Add copy-to-clipboard button with feedback
- [ ] Add dark / light mode toggle
- [ ] Show entropy score of the generated password

---

## Connect

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/your-username)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/your-username)

---

*Built while learning frontend development — with a security-first mindset.*
If you found this project useful, feel free to â­ star the repo and connect!

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/your-username)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/your-username)

---

> *Built with â¤ï¸ while learning frontend development â€” with a security-first mindset.*
