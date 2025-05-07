# 📊 User Lifecycle & Monetization Analytics (GA4 eCommerce)

## 🔍 Overview
This project analyzes user behavior, engagement, and monetization using Google Analytics 4 sample eCommerce data.  
With SQL and BigQuery, I explored the full user journey — from first visit to purchase — and calculated core product and business KPIs.

---

## 🧰 Tools & Technologies
- **SQL (BigQuery)**: CTEs, LAG, SAFE_DIVIDE, DATE_DIFF, REGEXP
- **Visualization**: Tableau
- **Dataset**: `bigquery-public-data.ga4_obfuscated_sample_ecommerce.events_*`

---

## 🎯 Business Questions
- How many users return after 1, 7, or 30 days?
- What’s the conversion rate between funnel steps?
- How long does it take a user to convert?
- How much revenue is generated per user?
- What share of users churn or return daily?

---

## 📈 Key Metrics

### 👣 Funnel & Conversion
- Unique users by stage: `page_view → view_item → add_to_cart → begin_checkout → purchase`

### 🔁 Retention & Churn
- Retention Rate: Day 1 / Day 7 / Day 30  
- Churn Rate: Users inactive for 30+ days

### 💰 Monetization
- Total Revenue from purchases
- **ARPU** – Average Revenue per User  
- **ARPPU** – Average Revenue per Paying User

### ⏱️ Conversion Speed
- Average Days to Convert (first session → first purchase)  
- Min / Max days to convert

### 📅 Activity & Stickiness
- **DAU** – Daily Active Users  
- **MAU** – Monthly Active Users  
- **Stickiness** = DAU / MAU

---

## 📊 Dashboard Structure (Tableau)

| Sheet Title | Description |
|-------------|-------------|
| **Retention Rates** | % of users who returned after 1, 7, or 30 days |
| **Conversion Funnel** | Drop-off visualization through user journey |
| **Revenue Metrics** | ARPU, ARPPU, Total Revenue, Paying Rate |
| **Time to Convert** | Days from first visit to first purchase |
| **DAU / MAU & Stickiness** | User engagement by day and month |

> 📸 Dashboard screenshots will be available in the `/visuals/` folder.

---

## 💡 What I Learned
- How to build full-funnel analytics with GA4 event-level data
- SQL-based cohort and retention analysis
- Monetization metrics and user segmentation (ARPU, ARPPU, churn)
- Structuring lifecycle insights for dashboarding in Tableau

---

## 📁 Folder Structure

## 👩‍💻 Author
**Yana Prozhuhan**  
📍 Based in Portugal | 💼 Open to junior data roles
