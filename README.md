# 🛒 Blinkit Sales Dashboard (Power BI)

An interactive, single-page **Power BI dashboard** that analyses sales and customer-rating performance for **Blinkit** (India's last-minute delivery app) across outlets, locations, item types and fat-content categories.

> 📁 **File:** `BLINKIT_DASHBOARD.pbix`

---

## 📌 Overview

This dashboard turns the *BlinkIT Grocery Data* dataset into a clean, filterable view that helps answer questions like:

- How much are we selling overall, and what is the average sale per item?
- Which outlet sizes, locations and outlet types drive the most revenue?
- How do customer ratings vary by item type, fat content and outlet location?
- How has revenue changed by outlet establishment year?

---

## 📊 Dashboard Features

### KPI Cards
| KPI | Description |
|-----|-------------|
| **Total Sales** | Sum of sales across the current filter selection |
| **Avg Sales** | Average sales per item/order |
| **No. of Items** | Count of items sold |
| **Avg Rating** | Average customer rating |

### Visuals
| Visual | Purpose |
|--------|---------|
| **Line chart** – Total sales by *Outlet Establishment Year* | Revenue trend across outlet vintages |
| **Donut chart** – Total sales by *Outlet Size* | Revenue share of Small / Medium / High outlets |
| **Funnel chart** – Total sales by *Outlet Location Type* | Compare Tier 1, Tier 2 and Tier 3 cities |
| **Donut chart** – Avg rating by *Item Fat Content* | Rating split between Low Fat and Regular items |
| **Bar chart** – Avg rating by *Item Type* | Rating comparison across product categories |
| **Clustered bar chart** – Avg rating by *Outlet Location Type* and *Item Fat Content* | Fat content performance by location |
| **Matrix / table** – by *Outlet Type* | Total Sales, Avg Sales, No. of Items, Avg Rating and Item Visibility in one view |

### Interactivity
- **Filter panel** with dropdown slicers for:
  - Outlet Location Type
  - Outlet Size
  - Item Type
- **Metric selector** slicer to switch between rating/sales measures
- **Cross-filtering** between visuals (click a slice or bar to filter the rest of the page)
- **"Clear all slicers"** button to reset the page in one click

### Design
- Blinkit-inspired **yellow (`#FFD200`) and green** colour palette
- Custom KPI icons and background images
- Segoe UI Semibold typography
- 1400 × 800 canvas, fit-to-page

---

## 🧮 Data Model

**Table:** `BlinkIT Grocery Data`

| Column | Description |
|--------|-------------|
| Item Type | Product category (e.g. Dairy, Snack Foods, Fruits & Vegetables) |
| Item Fat Content | Low Fat / Regular |
| Item Visibility | Share of display area allotted to the item |
| Outlet Establishment Year | Year the outlet opened |
| Outlet Size | Small / Medium / High |
| Outlet Location Type | Tier 1 / Tier 2 / Tier 3 |
| Outlet Type | Type of outlet |
| Sales | Sales value per item |
| Rating | Customer rating |

**DAX measures used:** `total sales`, `AVG sales`, `no. of items`, `avg rating`

---

## 🛠️ Tools & Skills Demonstrated

- **Power BI Desktop** – report design, slicers, cross-filtering, KPI cards
- **DAX** – measures for totals, averages and counts
- **Data modelling & visualisation** – donut, funnel, line, bar and matrix visuals
- **Dashboard UX** – filter panel, reset button, branded colour theme

---

## 🚀 How to Use

1. **Clone** or download this repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   ```
2. Install [**Power BI Desktop**](https://powerbi.microsoft.com/desktop/) (free, Windows).
3. Open `BLINKIT_DASHBOARD.pbix`.
4. Use the **Filter Panel** on the left and click on any chart element to explore the data.

---

## 📷 Screenshot

<!-- Add a screenshot of your dashboard here -->
![Dashboard Preview]<img width="1153" height="645" alt="image" src="https://github.com/user-attachments/assets/0786053b-e120-4045-842a-5eae4ad1f18b" />


---

## 💡 Key Insights

<!-- Fill these in with findings from your own analysis, for example: -->
- Which outlet size contributes the most revenue?
- Which city tier performs best?
- Which item types receive the highest ratings?

---

## 📂 Repository Structure

```
├── BLINKIT_DASHBOARD.pbix   # Power BI report
├── images/                  # Dashboard screenshots
└── README.md
```

---

## 🙋 Author

**Your Name**
[LinkedIn]https://www.linkedin.com/in/vedant-sharma-491847410/] · [GitHub](https://github.com/vedantsharmaa-VS)

---

## 📄 License

This project is for learning and portfolio purposes. The Blinkit name and logo belong to their respective owners.
