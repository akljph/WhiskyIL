# 🥃 WhiskyPrice IL — Israel Whisky Price Tracker

[![GitHub Pages](https://img.shields.io/badge/Live_Site-GitHub_Pages-2ea44f?style=for-the-badge&logo=github)](https://akljph.github.io/whiskyil/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-amber.svg?style=for-the-badge)](LICENSE)

An open-source, client-side web application that tracks and compares whisky prices across major Israeli supermarkets and specialty online liquor stores, helping buyers find the absolute lowest price in New Israeli Shekels (₪).

🌐 **Live Demo:** [https://akljph.github.io/whiskyil/](https://akljph.github.io/whiskyil/)

---

## ✨ Features

- 🎯 **Lowest Price Detection**: Automatically calculates and highlights the cheapest retailer for every single bottle.
- 🔗 **Direct Purchase Deeplinks**: Every *"Take me to this deal"* button links directly to the store's exact product page—no landing pages or generic search roots.
- 📏 **Strict Volume Disambiguation**: Identical labels with different bottle volumes (e.g., 700ml vs. 1000ml / 1 Liter) are treated as separate items with distinct unit metrics (₪/100ml).
- 🏪 **Comprehensive Store Comparison Modal**: Compare all available supermarket and liquor shop listings side-by-side with stock status and savings calculations.
- ⚡ **Instant Client-Side Filtering**: Real-time search by brand, category, volume, or vendor, plus sorting by price, max percentage savings, and alphabetical order.
- 📱 **Fully Responsive Modern UI**: Dark-mode amber aesthetics tailored for mobile screens and desktop monitors alike.

---

## 🛒 Monitored Israeli Stores & Supermarkets

| Category | Stores Included |
| :--- | :--- |
| **Major Supermarkets** | Osher Ad (אושר עד), Rami Levi (רמי לוי), Shufersal (שופרסל), Yochananof (יוחננוף) |
| **Online Liquor Retailers** | iDrink (איי דרינק), Paneco (פאנקו), Bana Mashkaot (בנא משקאות), Hermitage (הרמיטאז') |
| **Specialty Stores** | Drink Shop / GetDrink, Wine & More, Eliyahu Mashkaot (אליאסי) |

---

## 📂 Project Structure

```text
whiskyil/
├── index.html        # Main single-file web application (HTML5 + Tailwind CSS + Vanilla JS)
└── README.md         # Repository documentation and deployment guide
```

---

## 🚀 Getting Started Locally

You don't need Node.js or any build steps to run this project locally:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/akljph/whiskyil.git
   cd whiskyil
   ```

2. **Open in your browser:**
   - Double-click `index.html`, or
   - Run a quick local server:
     ```bash
     npx serve .
     # or
     python3 -m http.server 8000
     ```

---

## 🌐 Hosting & Deployment

### GitHub Pages (100% Free)
1. Push your code to the `main` branch of a public repository.
2. Go to **Settings** → **Pages**.
3. Under **Build and deployment**, select:
   - **Source:** Deploy from a branch
   - **Branch:** `main` / `/(root)`
4. Save and allow 60 seconds for GitHub Actions to build. Your site will be live at:
   `https://<your-username>.github.io/<repo-name>/`

---

## ⚖️ Legal Disclaimer

Prices are aggregated for informational purposes from publicly accessible online storefronts in Israel. Product names, trademarks, and logos belong to their respective owners. Alcohol consumption is prohibited under the age of 18. Excessive consumption of alcohol is hazardous to health.

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
