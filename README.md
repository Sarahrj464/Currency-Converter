# 💱 Currency Converter

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=flat&logo=javascript&logoColor=black)
![API](https://img.shields.io/badge/API-Fawaz%20Currency-00C896?style=flat)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat)

> A real-time currency converter that supports **150+ world currencies** with live exchange rates and country flags — built with pure HTML, CSS, and JavaScript.

---

## 🌐 Live Demo

> 🔗 [Click here to view live](https://sarahrj464.github.io/Currency-Converter/currency.html)

---

## ✨ Features

- 🔄 Convert between **150+ currencies** in real time
- 🏳️ Dynamic **country flags** update with currency selection
- 📡 Live exchange rates via **Fawaz Currency API** (no API key needed)
- 🇵🇰 Defaults to **USD → PKR** on load
- ✅ Auto-corrects empty or invalid amount to `1`
- ⚡ Instant result on page load — no button click needed

---

## 🛠️ Built With

| Technology | Purpose |
|------------|---------|
| HTML5 | Structure & form layout |
| CSS3 | Styling & responsive design |
| JavaScript (ES6+) | Logic, Fetch API, DOM manipulation |
| [Fawaz Currency API](https://github.com/fawazahmed0/exchange-api) | Live exchange rates (free, no key) |
| [Flags API](https://flagsapi.com/) | Country flag images |

---

## 📁 Project Structure

```
Currency-Converter/
├── currency.html     ← Main HTML file
├── currency.css      ← Styling
├── app.js            ← Core logic (fetch, DOM, flags)
└── codes.js          ← 150+ currency → country code map
```

---

## ⚙️ How It Works

1. On page load, all **150+ currencies** are populated in both dropdowns from `codes.js`
2. Default selection is **USD (From)** and **PKR (To)**
3. When the user clicks **"Get Exchange Rate"**, it:
   - Fetches live data from the **Fawaz Currency API**
   - Calculates: `amount × rate`
   - Displays: `1 USD = 278.67 PKR`
4. Flags update automatically when currency changes

---

## 🚀 Getting Started

No installation needed! Just open in browser:

```bash
git clone https://github.com/Sarahrj464/Currency-Converter.git
cd Currency-Converter
# Open currency.html in your browser
```

Or simply double-click `currency.html` to run locally.

---

## 📡 API Used

**Fawaz Ahmed Currency API**
- Free & open source — no API key required
- Endpoint: `https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies/{currency}.json`
- GitHub: [fawazahmed0/exchange-api](https://github.com/fawazahmed0/exchange-api)

---

## 🙏 Credits

Built while learning JavaScript from **Apna College** by **Shradha Khapra Didi** 💙

[![Apna College](https://img.shields.io/badge/YouTube-Apna%20College-FF0000?style=flat&logo=youtube)](https://www.youtube.com/@ApnaCollegeOfficial)

---

## 👩‍💻 Author

**Sarah** — [@Sarahrj464](https://github.com/Sarahrj464)

---

*Made with 💙 and lots of `console.log()` debugging*
