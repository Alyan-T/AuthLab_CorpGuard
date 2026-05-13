# CorpGuard Employee Portal - AuthLab

**Interactive Web Security Education Playground**

A fully front-end simulation of a corporate employee portal that deliberately exposes six common web vulnerabilities. Toggle between **Vulnerable** and **Secure** modes to see how attacks work and how they are prevented — all in real time.

![HTML](https://img.shields.io/badge/HTML-5-orange) ![CSS](https://img.shields.io/badge/CSS-3-blue) ![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow)

---

## About the Project

The **CorpGuard Employee Portal** is a purely client-side educational tool that teaches web security through interactive demonstrations. It covers the most common OWASP Top 10 risks, plus an entire **AuthLab** section dedicated to authentication threats such as JWT attacks, 2FA bypass, digital signatures, and CSRF.

All password hashes are computed **dynamically in the browser** using the Web Crypto API (SHA‑256), so the secure storage display always matches the plaintext password — no manual updates needed.

---

## Features

- **6 Security Tabs**  
  `SQL Injection` · `Access Control (IDOR)` · `XSS & Session Hijacking` · `Cryptography (Plaintext Passwords)` · `AI Anomaly Detection` · `AuthLab (PKI/2FA/JWT/CSRF)`

- **Dual‑Mode Toggle**  
  Switch between **Vulnerable** and **Secure** on every tab. Instantly see how the code, behaviour, and results change.

- **Dynamic Password Hashing**  
  In Secure mode, the Cryptography tab generates real SHA‑256 hashes from the plaintext password using the browser’s `crypto.subtle` API.

- **Real Code Examples**  
  PHP snippets displayed in syntax‑highlighted panels switch automatically to show the vulnerable or secure implementation.

- **Professional Icons**  
  All icons come from **Font Awesome 6** (no emojis) for a clean, corporate look.

- **Responsive Design**  
  Fully functional on mobile and desktop with a collapsible sidebar.

- **No Backend Required**  
  All data is simulated with `setTimeout`‑based Promises, making the project easy to run and share.

---

##  Technology Stack

- **HTML5** – Semantic structure  
- **CSS3** – Custom dark theme with CSS variables  
- **JavaScript (ES6+)** – All logic, async/await, Web Crypto API, DOM manipulation  
- **Font Awesome 6** – Vector icons via CDN  
- **Google Fonts** – Syne, IBM Plex Mono, DM Sans  

---

##  How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/corpguard-authlab.git
   cd corpguard-authlab
