# 🧠 Market & Competitor Analysis - UK Online Fashion (ASOS Dataset)

> *“Everyone sells the same trench coat. I just proved it with data.”*  

---

## 🕹️ Project Overview

The UK online fashion industry is basically a giant closet stuffed with mid-priced jeans and “must-have” blazers that everyone already owns.  

So I decided to treat it like a business analyst would - but with honesty.  
This project analyzes **30,000+ ASOS product listings** to identify where the market is saturated, who’s shouting the loudest, and where there’s actually space to breathe (spoiler: it’s *Activewear*).  

**Goal:**  
Help a hypothetical startup (*FlexWear*) decide where to enter the UK fashion market - and how to not die in the mid-tier pricing war.  

---

## 🎯 Business Objective

A new fashion startup wants to enter the UK market.  
They don’t want to be *another ASOS clone*.  

As a consultant (and chaos translator), I was tasked to:  
- Identify **market gaps** and **competitive density**  
- Analyze **price positioning** across categories  
- Recommend a **data-driven entry strategy**

**Stakeholder:**  
The Strategy Lead - someone who says *“I just need insights, not a 20-tab Excel file.”*  

---

## 🧩 Dataset Details

**Source:** ASOS UK product listings (public dataset) [https://www.kaggle.com/code/rajatraj0502/asos-e-commerce-dataset-30-845-products/input] 
**Rows:** ~30,000 products  

**Key Fields:**  
- Product Name  
- Brand  
- Category  
- Price (cleaned, because half said “From 42.50” like a riddle)  
- Price Band (Low / Mid / Premium / High-End)

**Tools Used:**  
- Power BI → Visualization & Analysis  
- Excel / Power Query → Data Cleaning 

---

## 🧹 Data Cleaning Steps (and mini drama)

- Removed **null rows** that contributed nothing (like unpaid interns)  
- Cleaned price column → extracted numeric values from strings like “From 42.50”  
- Created **Price Bands**:
  - Low: < £20  
  - Mid: £20–£50  
  - Premium: £50–£100  
  - High-End: > £100  
- Grouped products by **Category Group** → Activewear / Outerwear / Other  

---

## 📊 Dashboard Overview (Power BI)

### 1️⃣ **Brand Assortment Analysis**
*Who’s flooding the market?*  
→ ASOS 4505, Stradivarius, and Topshop are the loudest voices in a very crowded room.  

**Insight:**  
> The mid-tier segment is **heavily saturated** with lookalike brands. Competing here means entering a price war armed only with discount codes.  

---

### 2️⃣ **Price Distribution**
*Where’s the money actually flowing?*  

| Price Band | Products | Observation |
|-------------|-----------|-------------|
| Low (£0–20) | 6.5K | “Budget chic” – crowded and disposable |
| Mid (£20–50) | 16.6K | The noisy middle — everyone’s here |
| Premium (£50–100) | 5.3K | Sparse, stylish, and profitable |
| High-End (£100+) | 1.5K | Exclusive, but limited volume |

**Insight:**  
> 55% of the market is mid-tier, meaning everyone’s fighting over the same price-conscious customers.  
> The sweet spot? **Upper-mid range (£50–£80)** - looks premium, feels affordable.  

---

### 3️⃣ **Market Saturation Map (Heatmap)**
*Category vs Price Band — where the chaos lives.*

| Category | Low | Mid | Premium | High-End | Interpretation |
|-----------|------|------|----------|-----------|----------------|
| Activewear | 78 | 74 | 8 | 0 | “Hello? Anyone here?” – Huge opportunity |
| Other | 6,383 | 15,535 | 4,201 | 1,012 | The Hunger Games of fast fashion |
| Outerwear | 84 | 1,036 | 1,091 | 469 | Respectably premium, brand-driven |

**Insight:**  
> Activewear is an *under-served niche*, while “Other” apparel is drowning in supply.  
> Translation: stop making blouses, start making breathable gym tees.  

---

## 💡 Key Insights

1️⃣ **Mid-tier Madness:**  
Everyone’s obsessed with affordability; nobody’s selling value.  

2️⃣ **Premium Gap:**  
The £50–£100 range is a lonely place — perfect for brands that can blend quality and style.  

3️⃣ **Activewear Opportunity:**  
Under-supplied, growing fast, and socially trend-friendly.  

4️⃣ **Outerwear Prestige:**  
Crowded with high-end names but stable; use it as an expansion category later.  

---

## 🧭 Strategy Recommendations

| Area | Move | Why |
|------|------|-----|
| **Market Entry** | Start with **Activewear** | Underserved and growing |
| **Price Positioning** | **£50–£80** | Avoids price war, looks premium |
| **Brand Identity** | Focus on **“Affordable Performance”** | The sweet spot between Gymshark and ASOS |
| **Marketing** | Partner with **local influencers** | Sell lifestyle, not just leggings |
| **Expansion Plan** | Move into **Outerwear** post-brand trust | Build a premium perception organically |

---

## 🧠 Conclusion

The UK fashion market doesn’t need another mid-tier brand selling £25 t-shirts with “Be Kind” written on them.  
It needs **Activewear that performs, looks good, and doesn’t apologize for not being £15.**  

In short:  
> “Don’t join the noise. Be the calm, confident brand that everyone else wishes they’d thought of first.”  

---

## 🖼️ Power BI Dashboard Pages

- Page 1: **Brand Overview** (Count of Products by Brand)  
- Page 2: **Price Analysis** (Distribution + Avg Price KPI)  
- Page 3: **Market Saturation Heatmap**  

---

## 🏁 Results Snapshot

| KPI | Value |
|-----|-------|
| Total Products | 29,971 |
| Activewear Share | 0.5% |
| Mid-tier Density | 55% |
| Identified Opportunity | Premium Activewear (£50–£80) |

---

## ✍️ Author

**Shyam**  
🎓 MSc Business Analytics, University of Exeter  
💻 Ex–Software Developer (3+ years experience)  
📊 Aspiring Business / Insight Analyst | UK  

> *“I turn messy datasets into market stories - with a bit of absurd humor and a lot of tea.”*  

---

## 🔖 Tags

`#BusinessAnalytics` `#PowerBI` `#MarketAnalysis` `#DataVisualization` `#Consulting` `#ASOS` `#InsightAnalyst` `#PortfolioProject`  
