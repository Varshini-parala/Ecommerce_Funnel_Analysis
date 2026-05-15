# 🛒 E-Commerce Funnel Analysis

A comprehensive end-to-end funnel analysis project analyzing 10,000 user sessions across a 4-stage e-commerce purchase journey — from Browse to Purchase — using Python, Pandas, Plotly, and Seaborn.

---

## 📌 Project Overview

This project investigates where and why users drop off during an e-commerce purchase funnel. By analyzing session-level data across device types, regions, channels, and product categories, the analysis uncovers actionable insights to improve conversion rates and recover lost revenue.

**Funnel Stages Analyzed:**
```
Browse → Add to Cart → Checkout → Purchase
```

---

## 📊 Key Findings

| Metric | Value |
|---|---|
| Total Sessions | 10,000 |
| Overall Conversion Rate | 10.80% |
| Total Revenue | $1,176,405.78 |
| Average Order Value | $1,089.26 |
| Total Orders | 1,080 |
| Bounce Rate | 89.20% |
| Avg Session Duration | 4.08 minutes |

### Stage-to-Stage Conversion Rates
| Transition | Conversion Rate | Drop-off Rate |
|---|---|---|
| Browse → Add to Cart | 70.59% | 29.41% |
| Add to Cart → Checkout | 49.92% | 50.08% |
| Checkout → Purchase | 30.65% | 69.35% ⚠️ |

> **Biggest drop-off:** Checkout → Purchase stage at **69.35%** — the primary area for UX improvement.

### Revenue Opportunity
- 💰 Cart abandonment recovery potential: **$3,839,595.34**

---

## 🔍 Segment Insights

- **Best Channel:** Organic — 11.19% conversion rate
- **Best Region:** South — 11.25% conversion rate
- **Best Product Category:** Beauty — 11.43% conversion rate

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python | Core analysis and scripting |
| Pandas | Data cleaning and transformation |
| NumPy | Numerical computations |
| Plotly | Interactive dashboards |
| Matplotlib & Seaborn | Static visualizations |
| Excel (openpyxl) | Report export |

---

## 📁 Project Structure

```
ecommerce-funnel-analysis/
│
├── funnel_analysis.ipynb       # Main analysis notebook
├── funnel_analysis_data.csv    # Dataset
└── README.md
```

---

## 🚀 How to Run

1. **Clone the repository**
```bash
git clone https://github.com/Varshini-parala/ecommerce-funnel-analysis.git
cd ecommerce-funnel-analysis
```

2. **Install dependencies**
```bash
pip install pandas numpy matplotlib seaborn plotly openpyxl
```

3. **Run the notebook**
```bash
jupyter notebook funnel_analysis.ipynb
```

---

## 📈 Visualizations

The project includes a comprehensive multi-chart Plotly dashboard covering:
- Overall funnel conversion rates
- Stage-to-stage drop-off rates
- Revenue by funnel stage
- Session duration by stage
- Channel performance comparison
- Regional funnel progression
- Device and product category conversion rates
- Daily and hourly trends

---

## 💡 Strategic Recommendations

1. **Fix Checkout UX** — 69.35% drop-off at the Purchase stage indicates friction in the checkout flow (payment issues, trust signals, or form complexity)
2. **Recover cart abandonment** — 50.08% of users who reach Checkout don't convert, representing a **$3.84M revenue opportunity** via email retargeting or exit-intent prompts
3. **Scale Organic channel** — highest conversion rate at 11.19%; increase SEO and content marketing investment
4. **Replicate South region strategies** — best-performing region; apply its approach to underperforming regions
5. **Promote Beauty category** — highest conversion at 11.43%; feature it prominently in campaigns

---

## 📄 Dataset

The dataset contains **21,663 event records** across **10,000 unique sessions** with the following columns:

| Column | Description |
|---|---|
| User_ID | Unique user identifier |
| Session_ID | Unique session identifier |
| Event | Funnel stage event (Browse/Add to Cart/Checkout/Purchase) |
| Timestamp | Event timestamp |
| Device | Device type (Mobile/Desktop/Tablet) |
| Region | Geographic region |
| Channel | Acquisition channel (Organic/Paid/Email/Social) |
| Product_Category | Product category |
| Revenue | Revenue generated |
| Bounce_Flag | Whether session bounced |

---

## 👩‍💻 Author

**Varshini Parala**  
Computer Science (Data Science) Undergraduate — Vignan University  
📧 231fa23045@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/varshini-parala-99a464330) | [GitHub](https://github.com/Varshini-parala)

---

## ⭐ If you found this project useful, give it a star!
