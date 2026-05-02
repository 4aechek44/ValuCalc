<div align="center">

# 💱 ValuCalc

**Multi-currency converter with live exchange rates**

[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![money.js](https://img.shields.io/badge/money.js-0.2.0-green?style=flat-square)](https://openexchangerates.github.io/money.js/)

</div>

---

## About

ValuCalc is a lightweight, zero-framework browser currency converter.  
The key idea: add **multiple currencies** together and get the total in one target currency.

> `$2 + ₽15 + ¥500` → how much is that in `€`?

Rates are fetched in real time via [open.er-api.com](https://open.er-api.com).

---

## Features

- 🔄 **Multi-source conversion** — stack several currencies and convert them all at once
- 📊 **Live rates sidebar** — grouped by RUB pairs, major world pairs, and CIS
- 🌍 **35+ currencies** — USD, EUR, RUB, JPY, CNY, KZT, BYN, AMD and more
- ⚡ **No build step** — pure vanilla JS, open and run
- 🎨 **Custom select** with the full list of available currencies
- 💫 **Animations** — staggered rate rows, result flash effect

---

## Stack

| Technology | Role |
|---|---|
| HTML5 / CSS3 | markup and styling |
| Vanilla JS | conversion logic and UI |
| [money.js](https://openexchangerates.github.io/money.js/) | cross-base currency math |
| [open.er-api.com](https://open.er-api.com) | live exchange rates |

---

## Getting Started

Open link
[https://4aechek44.github.io/ValuCalc/](https://4aechek44.github.io/ValuCalc/)

## Usage

1. Pick a currency in the **"I have"** block and enter an amount
2. Hit `+` to add another currency with its own amount
3. Choose the **target currency** in the "Result" block
4. Click **"Convert"** — the total appears instantly

---

## Project Structure

```
ValuCalc/
├── converter.html    # all UI and logic
├── converter.css     # styles
└── package.json      # dependency: money.js
```

---

<div align="center">

Made by [4aechek44](https://github.com/4aechek44)

</div>
