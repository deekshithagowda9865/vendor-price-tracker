🥦 MandiBhav — vendor Price Tracker

**Track · Compare · Alert · Manage**

A zero-setup, single HTML file web app for tracking vegetable and grocery prices from local Indian mandis. Buyers compare prices, view trends, and set alerts. Vendors log in to publish daily prices.

[![HTML5](https://img.shields.io/badge/Built%20with-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![JavaScript](https://img.shields.io/badge/Vanilla-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![CSS3](https://img.shields.io/badge/Styled%20with-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Zero Setup](https://img.shields.io/badge/Setup-Zero-22C55E?style=flat-square)](#getting-started)
[![MIT License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)
[![Live Demo](https://img.shields.io/badge/🌐_Live-Demo-F97316?style=flat-square)](https://your-username.github.io/mandibhav/mandibhav.html)

[**View Live Demo**](https://your-username.github.io/mandibhav/mandibhav.html) · [**Download HTML**](mandibhav.html) · [**Report Bug**](https://github.com/your-username/mandibhav/issues)

</div>

---

## 📸 Screenshots

<div align="center">

### 🏠 Price Board
> Browse live prices by city, category, and item. Click any card to open the trend chart.

```
┌─────────────────────────────────────────────────────────────────────────────┐
│  🥦 MandiBhav  [LIVE]    Price Board  Compare  Alerts    Login  Register    │
├─────────────────────────────────────────────────────────────────────────────┤
│  Today's Mandi Prices                                                       │
│  Live vegetable & grocery prices from local mandis                          │
│                                                                             │
│  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐                      │
│  │ 📋           │  │ 🏪           │  │ 📉           │                      │
│  │ 156          │  │ 5            │  │ ₹20          │                      │
│  │ Prices Listed│  │ Active Mandis│  │ Lowest Today │                      │
│  │              │  │ Bengaluru    │  │ Potato       │                      │
│  └──────────────┘  └──────────────┘  └──────────────┘                      │
│                                                                             │
│  [Bengaluru ▼]  [Search item...]  [All] [Vegetables] [Fruits] [Grains]     │
│                                                                             │
│  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐   │
│  │ 🥬      ₹30  │  │ 🥬      ₹25  │  │ 🥬      ₹20  │  │ 🥬      ₹40  │   │
│  │ Tomato       │  │ Onion        │  │ Potato       │  │ Carrot       │   │
│  │ Vegetables   │  │ Vegetables   │  │ Vegetables   │  │ Vegetables   │   │
│  │ ─────────── │  │ ─────────── │  │ ─────────── │  │ ─────────── │   │
│  │ 🏪 KR Market │  │ 🏪 Yeshwanth │  │ 🏪 Jayanagar │  │ 🏪 KR Market │   │
│  │ 📍 560002    │  │ 📍 560022    │  │ 📍 560041    │  │ 📍 560002    │   │
│  │ ● In Stock   │  │ ● In Stock   │  │ ◑ Limited    │  │ ● In Stock   │   │
│  └──────────────┘  └──────────────┘  └──────────────┘  └──────────────┘   │
└─────────────────────────────────────────────────────────────────────────────┘
```

### 📈 Price Trend Chart
> Click any item card to instantly see its 7, 14, or 30-day price history.

```
┌─────────────────────────────────────────────────────────────────────────────┐
│  📈 Tomato — Price Trend                          [7D]  [14D]  [30D]  [✕]  │
│  in Bengaluru · ₹ per kg                                                    │
│                                                                             │
│  ₹45 ┤                                                                      │
│      │         ╭──╮                                                         │
│  ₹35 ┤  ╭──╮  ╯  ╰──╮     ╭──╮                                             │
│      │ ╭╯  ╰──╯      ╰────╯  ╰─────── avg ──────                           │
│  ₹25 ┤─╯                         - - min - -  - - max - -                  │
│      └──────────────────────────────────────────────────                    │
│        Jun 13  Jun 15  Jun 17  Jun 19                                       │
│                                                                             │
│  — Avg Price    - - Min Price    - - Max Price                              │
└─────────────────────────────────────────────────────────────────────────────┘
```

### ⚖️ Compare Vendors
> Find the cheapest mandi for any item in your city.

```
┌─────────────────────────────────────────────────────────────────────────────┐
│  Compare Prices                                                             │
│  Find the cheapest mandi for any item in your city                         │
│                                                                             │
│  [Item: Tomato          ]  [City: Bengaluru ▼]  [Compare →]               │
│                                                                             │
│  ┌─────────────┐  ┌─────────────┐  ┌─────────────┐                        │
│  │ ₹26          │  │ ₹29.3        │  │ ₹33          │                        │
│  │ Cheapest     │  │ Average      │  │ Highest      │                        │
│  └─────────────┘  └─────────────┘  └─────────────┘                        │
│                                                                             │
│  Rank  Mandi            Location        Phone       Price   Stock  Savings  │
│  ────  ───────────────  ──────────────  ──────────  ──────  ─────  ───────  │
│  🥇   KR Market        Bengaluru 560002 9876543210  ₹26     ✅     Best!   │
│  🥈   Jayanagar Mandi  Bengaluru 560041 9876543212  ₹29    ✅     ₹3 more │
│  🥉   Yeshwanthpur     Bengaluru 560022 9876543211  ₹33    ◑ Ltd  ₹7 more │
└─────────────────────────────────────────────────────────────────────────────┘
```

### 🔔 Price Alerts
> Set a target price and get flagged the moment a vendor posts below it.

```
┌─────────────────────────────────────────────────────────────────────────────┐
│  Price Alerts                                                               │
│                                                                             │
│  ┌──────────────────────────────┐  ┌──────────────────────────────────┐    │
│  │ 🔔 Create Alert              │  │ 📋 My Alerts                     │    │
│  │                              │  │                                  │    │
│  │ Your Email                   │  │ [Enter email...]    [View]       │    │
│  │ [you@example.com           ] │  │                                  │    │
│  │                              │  │ ┌──────────────────────────────┐ │    │
│  │ Item                         │  │ │ Tomato in Bengaluru          │ │    │
│  │ [Tomato                    ] │  │ │ Alert when ≤ ₹25/unit   [✕] │ │    │
│  │                              │  │ └──────────────────────────────┘ │    │
│  │ City        [Bengaluru ▼]    │  │ ┌──────────────────────────────┐ │    │
│  │                              │  │ │ Onion in Bengaluru [TRIGGERED]│ │    │
│  │ Alert when price ≤ ₹         │  │ │ Alert when ≤ ₹20/unit   [✕] │ │    │
│  │ [25                        ] │  │ └──────────────────────────────┘ │    │
│  │                              │  └──────────────────────────────────┘    │
│  │ [      Set Alert      ]      │                                          │
│  └──────────────────────────────┘                                          │
└─────────────────────────────────────────────────────────────────────────────┘
```

### 🏪 Vendor Dashboard
> Vendors manage their daily price listings and see live stats.

```
┌─────────────────────────────────────────────────────────────────────────────┐
│  Vendor Dashboard                              [View Board]                 │
│  KR Market · Bengaluru                                                      │
│                                                                             │
│  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐                      │
│  │ 📋           │  │ 💰           │  │ ✅           │                      │
│  │ 12           │  │ ₹44.2        │  │ 10           │                      │
│  │ Items Today  │  │ Avg Price    │  │ In Stock     │                      │
│  └──────────────┘  └──────────────┘  └──────────────┘                      │
│                                                                             │
│  [📋 My Prices]  [➕ Add / Update Price]                                    │
│                                                                             │
│  Item       Category    Price   Unit  Stock       Action                   │
│  ─────────  ──────────  ──────  ────  ──────────  ──────                   │
│  Tomato     Vegetables  ₹30     kg    ✅ Available  🗑️                     │
│  Onion      Vegetables  ₹25     kg    ✅ Available  🗑️                     │
│  Apple      Fruits      ₹120    kg    ◑ Limited    🗑️                     │
│  Rice       Grains      ₹55     kg    ✅ Available  🗑️                     │
└─────────────────────────────────────────────────────────────────────────────┘
```

</div>

---

## 🚀 Getting Started

**The fastest possible start:**

```bash
# 1. Download the file
# Click mandibhav.html above → Download

# 2. Open it
double-click mandibhav.html
# That's it. No install. No terminal. No setup.
```

**Or clone the repo:**

```bash
git clone https://github.com/your-username/mandibhav.git
cd mandibhav

# Windows
start mandibhav.html

# Mac
open mandibhav.html

# Linux
xdg-open mandibhav.html
```

---

## ✨ Features

### 👥 For Buyers

| Feature | Description |
|---|---|
| 🏠 **Live Price Board** | Browse today's prices filtered by city, category, and item name |
| 📈 **Trend Chart** | Click any item to see a 7 / 14 / 30-day SVG line chart (avg, min, max) |
| ⚖️ **Vendor Compare** | Rank all mandis by price for any item in your city |
| 🔔 **Price Alerts** | Set a target price — alerts trigger instantly when a vendor posts below it |

### 🏪 For Vendors

| Feature | Description |
|---|---|
| 📝 **Register** | Sign up with mandi name, city, pincode, and contact details |
| 📊 **Dashboard** | See today's listings, average price, and in-stock count |
| 📤 **Publish Prices** | Post any item with category, unit, and stock status |
| 🔔 **Alert Integration** | Publishing a price auto-triggers matching buyer alerts |

### ⚙️ Technical Highlights

| Detail | Value |
|---|---|
| File size | Single `.html` file |
| Dependencies | Zero — no npm, no CDN, no framework |
| Chart library | None — SVG drawn with vanilla JS coordinate math |
| Data storage | `localStorage` for alerts and vendor sessions |
| Setup required | None — double-click to open |

---

## 🔑 Demo Login Credentials

Explore the vendor dashboard without registering:

| Email | Password | Mandi | City |
|---|---|---|---|
| `ramesh@krmarket.com` | `password123` | KR Market | Bengaluru |
| `suresh@ymandi.com` | `password123` | Yeshwanthpur Mandi | Bengaluru |
| `priya@jmandi.com` | `password123` | Jayanagar Mandi | Bengaluru |
| `ahmed@crawford.com` | `password123` | Crawford Market | Mumbai |
| `sunita@azadpur.com` | `password123` | Azadpur Mandi | Delhi |

---

## 🗂️ Pre-seeded Demo Data

The app loads with realistic demo data out of the box:

| Detail | Value |
|---|---|
| Vendors / Mandis | 5 across Bengaluru, Mumbai, Delhi |
| Items tracked | 18 (Tomato, Onion, Potato, Rice, Milk, Apple...) |
| Categories | Vegetables, Fruits, Grains, Spices, Dairy |
| Price history | 30 days per item per vendor |
| Total records | ~2,700 price data points |
| Price variation | ±30% random walk around real base prices |

**Items included:**

```
Vegetables:  Tomato · Onion · Potato · Carrot · Brinjal · Capsicum
             Cabbage · Spinach · Beans · Pumpkin
Fruits:      Banana · Apple · Mango
Grains:      Rice · Wheat
Spices:      Turmeric · Chilli
Dairy:       Milk
```

---

## 🏗️ Project Structure

```
mandibhav/
└── mandibhav.html            ← entire app (markup + styles + logic)
    │
    ├── <style>               CSS — layout, grid, components, responsive
    │
    ├── HTML pages (shown/hidden via JS)
    │   ├── #page-home        price board with stats, filters, chart
    │   ├── #page-compare     vendor comparison table
    │   ├── #page-alerts      create + view price alerts
    │   ├── #page-dashboard   vendor stats + price management
    │   ├── #page-login       vendor sign in
    │   └── #page-register    new vendor registration
    │
    └── <script>
        ├── Data layer
        │   ├── MANDIS[]          5 pre-seeded vendor objects
        │   ├── BASE_PRICES{}     18 items with realistic ₹ prices
        │   ├── genPrices()       generates 30 days × all vendors × all items
        │   └── localStorage      alerts + vendor session persistence
        │
        ├── Router
        │   └── showPage()        switches active page, updates nav
        │
        ├── Home page
        │   ├── renderHome()      entry point
        │   ├── applyFilters()    city / category / search
        │   ├── renderGrid()      price card HTML generation
        │   └── renderStats()     today's summary counts
        │
        ├── Chart
        │   ├── selectItem()      opens chart for clicked item
        │   ├── drawChart()       SVG path math (no library)
        │   ├── setChartDays()    7 / 14 / 30 day toggle
        │   └── closeChart()      hides chart, clears selection
        │
        ├── Compare
        │   ├── runCompare()      filters + deduplicates + sorts
        │   └── populateItemSuggestions()  datalist for autocomplete
        │
        ├── Alerts
        │   ├── createAlert()     stores to localStorage + checks trigger
        │   ├── fetchAlerts()     loads by email from localStorage
        │   └── deleteAlert()     removes single alert
        │
        ├── Auth
        │   ├── doLogin()         credential check against vendor list
        │   ├── doRegister()      creates new vendor object
        │   ├── logout()          clears localStorage session
        │   └── updateAuthNav()   shows/hides login vs dashboard links
        │
        └── Dashboard
            ├── renderDashboard() stats + today's price table
            ├── publishPrice()    adds price + triggers alerts
            ├── deleteMyPrice()   removes from in-memory array
            └── switchTab()       my prices ↔ add price tabs
```

---

## 🔄 How It Works

```
App loads
    │
    ├── genPrices() generates ~2,700 price records in memory
    │   (30 days × 5 vendors × 18 items, ±30% price variation)
    │
    └── showPage('home')
            │
            ├── getTodayPrices(city) filters to today's records
            ├── applyFilters() applies category + search
            ├── renderGrid() renders price cards
            │
            ├── Click a card
            │       └── drawChart(item, city, days)
            │               SVG path = coordinate math on grouped data
            │               No charting library used
            │
            ├── Compare page
            │       └── runCompare()
            │               filters today + city + item
            │               deduplicates by vendorId
            │               sorts by pricePerKg ascending
            │
            ├── Alerts page
            │       └── createAlert()
            │               checks if today's price already ≤ target
            │               saves to localStorage
            │
            └── Vendor logs in → publishPrice()
                        adds to allPrices array
                        loops alerts → triggers matching ones
                        re-renders dashboard
```

---



## 🛣️ Roadmap

- [x] Live price board with city and category filters
- [x] 7 / 14 / 30-day SVG price trend chart
- [x] Vendor comparison table with savings column
- [x] Price alerts stored in localStorage
- [x] Vendor login, registration, and dashboard
- [x] Publish and delete prices from dashboard
- [x] Auto-trigger alerts when vendor publishes a matching price
- [ ] Backend API (Node.js + MongoDB) for real data persistence
- [ ] Real email notification when alert triggers (Nodemailer / SendGrid)
- [ ] WhatsApp alert via Twilio API
- [ ] Government Agmarknet API for real mandi price data
- [ ] PWA support — offline access + home screen install
- [ ] Mobile app (React Native)
- [ ] Multi-language support (Kannada, Hindi, Tamil)

---

## 🧠 What I Learned

- How to architect a complete multi-page SPA in vanilla JS — using a `showPage()` router and in-memory state, without React or any framework
- How to draw SVG line charts from scratch using coordinate math on `<path>` elements — no Recharts, no Chart.js
- How `localStorage` enables data persistence across refreshes without a backend
- How to generate realistic seeded demo data using a random walk around a base price — ±30% variation feels real without being random noise
- Why deduplication matters: showing one price per vendor per item rather than one row per stored record
- The trade-off between a single-file app (instantly shareable, zero setup) and a full-stack app (persistent, scalable, real auth)
- How to write reusable render functions that take data and produce HTML strings — the pattern that leads naturally into learning React

---

## 🤝 Contributing

Contributions are welcome!

```bash
# Fork the repo
git checkout -b feature/your-feature-name
git commit -m "Add: brief description of change"
git push origin feature/your-feature-name
# Open a Pull Request
```

Since this is a single-file app, keep changes focused — one feature per PR makes reviews fast.

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details. 
---

## 👤 Author

**Your Name**
- GitHub: [deekshithagowda9865](https://github.com/deekshithagowda9865)
- LinkedIn: https://www.linkedin.com/in/deekshitha-gowda-02365a384
- Email: deekshithagowda9865@gmail.com

---

<div align="center">

Made with ❤️ to solve a real India-specific problem

⭐ Star this repo if it helped you learn something!

</div>

