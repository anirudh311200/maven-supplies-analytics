# 📊 Tableau | Executive Sales Performance & Profitability Analysis

## 🚀 Project Overview

This project delivers an **executive-grade Tableau analytics solution** built to answer a single, critical business question:

**What truly drives sales, profit, and loss — and why?**

Rather than maximizing visual complexity, this solution prioritizes **clarity, causality, and business logic**.  
Interactive dashboards and guided analytical stories move beyond surface-level reporting to explain the **economic mechanics** behind performance — enabling confident, defensible decision-making.

The design is intentionally minimalist, ensuring that every visual earns its place and directly supports insight generation.

---

## 🧠 Executive Questions Answered

- Which regions and cities genuinely drive *profitable* growth?
- Are high sales translating into profit — or masking structural losses?
- How do discounting behaviors impact margins at a sub-category level?
- Which products should be scaled, fixed, or deprioritized?
- Is profitability driven by volume, pricing power, or order economics?

---

## 🛠️ Tools & Capabilities Demonstrated

- Tableau Desktop / Tableau Public
- Advanced calculated fields & parameters
- Conditional color logic for financial interpretation
- Interactive dashboard actions & cross-filtering
- Executive KPI (BAN) design principles
- Business-first analytical storytelling

---

## 📈 Executive Dashboard — Performance at a Glance

![Executive Dashboard](visuals/executive_dashboard.png)

### Purpose  
Provide leadership with a **single, authoritative view** of overall performance while preserving the ability to drill into detail instantly.

### What This Dashboard Enables
- Immediate visibility into YTD Sales, Profit %, Quantity, and Avg Discount
- Identification of geographic concentration and risk at the city level
- Target attainment tracking across regions
- Recognition of seasonal and trend-based performance patterns
- Clear understanding of revenue mix by segment and sub-category

This dashboard answers *“How are we doing?”* in seconds — without sacrificing analytical depth.

---

## 🌍 Geographic Performance — Sales & Profit by City

![Sales & Profit by City](visuals/sales_profit_by_city_map.png)

This view reveals **where revenue is generated and where profit is retained**.

- Bubble size represents total sales by city
- Color encodes profit percentage (loss → profit)
- Tooltips expose each city’s contribution to state-level sales
- Filters allow rapid geographic isolation and comparison

**Business Value:**  
Surfaces cities that generate strong revenue but weak or negative margins — a critical executive blind spot.

---

## 🎯 Sales vs Goal — Regional Accountability

![Sales vs Goal by Region](visuals/sales_vs_goal_by_region.png)

This view compares actual regional sales against predefined targets.

- Bars represent actual sales
- Reference lines indicate regional goals
- Color logic instantly highlights over- and under-performance

**Business Value:**  
Transforms static targets into visible, actionable accountability.

---

## 📉 Sales & Profit Trend — Monthly Dynamics

![Sales & Profit by Month](visuals/sales_profit_by_month.png)

A dual-axis view combining:
- Sales (bars)
- Profit (line)

This chart highlights:
- Seasonality effects
- Divergence between revenue growth and profitability
- Critical inflection points over time

**Business Value:**  
Ensures growth is evaluated through a profitability lens, not revenue alone.

---

## 🧩 Revenue Mix — Sales by Sub-Category

![Sales by Sub-Category](visuals/sales_by_subcategory_treemap.png)

This treemap illustrates how revenue is distributed across categories and sub-categories.

- Highlights true revenue drivers
- Preserves clarity through selective labeling
- Enables quick identification of scale versus fragmentation

---

## 👥 Customer Concentration — Top Customers by Sales

![Top Customers by Sales](visuals/top_customers_by_sales.png)

This view identifies **revenue concentration risk** using a dynamic Top-N framework.

- Default view displays the Top 25 customers
- Parameter allows executives to redefine “Top” instantly
- Visual separation between Top-Tier and non-Top-Tier customers

**Key Insight:**  
A small subset of customers contributes a disproportionate share of total revenue, introducing dependency risk.

---

## 📊 Dashboard — Drivers of Profit & Loss (Analytical Core)

![Drivers of Profit & Loss](visuals/drivers_of_profit_and_loss_dashboard.png)

This dashboard represents the **analytical core** of the project.

Rather than describing outcomes, it explains **why they occur** by connecting:

- Sales & Profitability by Sub-Category
- Profit Margin by Sub-Category
- Discount Impact Analysis
- Average Order Value vs Order Count

### Interaction Design  
All visuals are fully cross-filtered.  
Selecting any element dynamically reshapes the remaining views, enabling rapid root-cause analysis without losing context.

---

## 📖 Story — Top Cities & Sub-Categories

### NYC: The Largest Sales Contributor

![NYC Story](visuals/story_top_cities_nyc.png)

- NYC leads national sales contribution
- Strong profitability accompanies high volume
- Key sub-category drivers:
  - Furniture → Chairs
  - Office Supplies → Binders
  - Technology → Phones
- Peak sales and profit occur concurrently in September 2018

**Insight:**  
NYC’s performance is diversified across categories rather than dependent on a single product line.

---

### Western Region: Sustained Regional Leadership

![West Region Story](visuals/story_top_cities_west_region.png)

- The Western region outperforms all others in YTD sales
- Product leadership differs materially from NYC
- Highlights how geography reshapes product economics

---

### Chairs: A High-Volume Sales Driver

![Chairs Story](visuals/story_top_cities_chairs.png)

- Chairs generated significant peak-period sales
- High volume with moderate margins
- Reinforces the need to balance scale with profitability discipline

---

## 📖 Story — Sub-Category Profit & Loss Drivers

This story moves from observation to explanation by isolating the economic behavior of individual sub-categories.

---

### Tables: High Sales, Persistent Losses

![Tables Loss Driver](visuals/story_tables_loss_driver.png)

Despite strong revenue generation, **Tables** produce the largest absolute losses.

- Negative profit margin
- Exceptionally high average discounting
- High order volume combined with low average order value

**Finding:**  
Losses are driven by pricing and discount structure rather than demand weakness.

---

### Copiers: Low Volume, Exceptional Profitability

![Copiers Profit Driver](visuals/story_copiers_profit_driver.png)

Copiers demonstrate the inverse economic model.

- Very high profit margins
- Extremely high average order value
- Moderate discounting
- Low order volume with strong profit per transaction

**Finding:**  
Pricing power and order economics drive sustainable profitability.

---

## 📱 Multi-Device Accessibility

The dashboards are designed for **desktop, tablet, and mobile consumption**, ensuring accessibility for executives across devices without compromising analytical integrity.

---

## 🖼️ Full Visuals Gallery

All dashboards, analytical views, and story slides are available in the [`visuals/`](visuals/) folder, including additional supporting visuals not embedded directly in this README.

---

## 💾 How to View the File

The complete Tableau analysis is packaged in:

`maven_supplies_analysis.twbx`

Open the file in **Tableau Desktop** or **Tableau Public** to explore:
- Interactive dashboards
- Cross-filtering and actions
- Parameters and drill-down analysis
- Story-driven analytical narratives

---

## 🏁 Final Takeaway

This project demonstrates a complete executive analytics workflow — from high-level performance monitoring to detailed root-cause diagnosis.

It illustrates how Tableau can be used not merely to report results, but to **explain business outcomes and support strategic decision-making**.
