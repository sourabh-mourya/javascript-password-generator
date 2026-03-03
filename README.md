# ðŸ” Password Generator

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Security](https://img.shields.io/badge/Security-Focused-green?style=for-the-badge&logo=shield&logoColor=white)
![No Dependencies](https://img.shields.io/badge/Dependencies-None-blue?style=for-the-badge)

A simple and responsive **Password Generator** web app built with **HTML, CSS, and JavaScript** â€” developed while learning frontend development and basic security concepts.

Generates **strong, secure, and fully customizable passwords** instantly in the browser â€” no backend, no data sent anywhere.

---

## ðŸ“¸ Demo Preview

> *(Add your screenshot here)*

```
![Project Screenshot](screenshot.png)
```

---

## âœ¨ Features

- ðŸŽšï¸ Adjustable password length via real-time slider **(6â€“20 characters)**
- ðŸ”  Toggle **Uppercase** letters (A-Z)
- ðŸ”¡ Toggle **Lowercase** letters (a-z)
- ðŸ”¢ Toggle **Numbers** (0-9)
- ðŸ”£ Toggle **Special Characters** (!@#$%^&*)
- âš¡ One-click instant password generation
- ðŸ“± Fully responsive design (mobile-friendly)
- ðŸ”’ 100% client-side â€” **no data is stored or transmitted**

---

## ðŸ› ï¸ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Page structure and markup |
| CSS3 | Styling, slider UI and responsive layout |
| JavaScript (ES6+) | Password logic, randomization and DOM manipulation |
| No external libraries | Zero dependencies â€” pure vanilla JS |

---

## ðŸ“‚ Project Structure

```
ðŸ“¦ Password-Generator
 â”£ ðŸ“œ index.html      â†’ Main HTML structure
 â”£ ðŸ“œ style.css       â†’ Styling and responsive design
 â”£ ðŸ“œ script.js       â†’ Password generation logic
 â”— ðŸ“œ README.md       â†’ Project documentation
```

---

## âš™ï¸ How It Works

1. User selects desired **password length** using the slider.
2. User toggles which **character types** to include.
3. On clicking **Generate Password**, JavaScript:
   - Builds a character pool from selected options
   - Uses `Math.random()` to randomly pick characters
   - Assembles and displays the final secure password
4. Password is rendered instantly â€” all logic runs **in the browser**.

> ðŸ” **Security Note:** This tool uses `Math.random()` which is sufficient for general-purpose passwords. For cryptographically secure generation, `crypto.getRandomValues()` (Web Crypto API) is the recommended upgrade â€” listed in future improvements.

---

## ðŸš€ How to Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/your-username/password-generator.git

# 2. Navigate into the project folder
cd password-generator

# 3. Open index.html in your browser
# (No build tools, servers, or installs needed!)
```

---

## ðŸŽ¯ What I Learned

This project helped me understand and practice:

- **DOM manipulation** and dynamic UI updates
- **Event handling** in JavaScript (sliders, checkboxes, buttons)
- Working with **random number generation** (`Math.random()`)
- Building **character pool logic** programmatically
- Designing **responsive layouts** using CSS
- Basics of **client-side security thinking**

---

## ðŸ”® Future Improvements

- [ ] Use **`crypto.getRandomValues()`** for cryptographically secure passwords
- [ ] Add **password strength indicator** (Weak / Medium / Strong)
- [ ] Add **copy-to-clipboard** button with feedback toast
- [ ] Add **dark / light mode** toggle
- [ ] Show **entropy score** of the generated password
- [ ] Improve UI with smooth animations and transitions

---

## ðŸ¤ Connect With Me

If you found this project useful, feel free to â­ star the repo and connect!

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/your-username)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/your-username)

---

> *Built with â¤ï¸ while learning frontend development â€” with a security-first mindset.*
