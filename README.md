# 🎬 Netflix Analytics Dashboard — Power BI

A branded, single-page Power BI dashboard analyzing Netflix streaming 
data across content genres, viewer demographics, watch behavior, 
stream quality, and global content availability — designed to help 
streaming platforms make data-driven decisions on content strategy 
and user retention.

---

## 📊 Dashboard Preview

![Netflix Dashboard](netflix_dashboard.png)

---

## 🎯 Problem Statement

Streaming platforms generate massive behavioral data but struggle to 
translate it into clear content and retention strategy. This dashboard 
consolidates Netflix viewing data into one interactive report — 
enabling content teams to identify peak viewing days, top-performing 
genres, user segment health, and geographic content gaps at a glance.

---

## 📁 Dataset

- **Source:** Netflix streaming analytics dataset
- **Domain:** Entertainment / Streaming Intelligence
- **Genres covered:** Anime, Documentary, Mini-Series, Movie

---

## 🔑 Key KPIs

| Metric | Value |
|---|---|
| Average Rating | 7.36 |
| Total Views | 85.30K |
| Average Cost | $349.13 |
| Avg Duration | 52.06 min |

---

## 📌 Dashboard Features

### Genre Filter
- Interactive buttons (Anime, Documentary, Mini-Series, Movie)
  filter all visuals simultaneously for genre-specific deep dives

### Avg Watch Duration by Day
- Bar chart ranking all 7 days by average watch time
- Saturday and Friday show highest engagement — key insight 
  for scheduling new content drops

### Age Rating Distribution
- Donut chart breaking down content by certification:
  A (21%), U/A 7+ (20.5%), U/A 16+ (20%), U/A 13+ (19.5%), 
  and others
- Near-equal distribution indicates a broad, diverse content library

### Stream Quality Breakdown
- Donut chart showing quality tier split:
  Dolby Vision (24.5%), 1080p (20%), 480p (19.5%), 720p (19%), 
  4K HDR (17%)
- High-quality streams (Dolby + 4K) represent ~42% of views

### Content Availability by Country
- Bar chart across 10 countries: India leads, followed by 
  Spain, Germany, Brazil, South Korea, France, Mexico, UK, 
  USA, Japan
- Reveals geographic content concentration and expansion gaps

### User Segments Distribution
- Horizontal bar chart ranking 6 user types:
  Re-Activated > Binge Watcher > Casual Viewer > New User > 
  Churned > Power User
- Re-Activated users being the largest segment signals strong 
  win-back campaign effectiveness but also churn risk

---

## 💡 Key Business Insights

- **Saturday and Friday are peak viewing days** — new content 
  releases and promotional pushes should target Thursday evening 
  to capture weekend audiences
- **Re-Activated users are the largest segment** — the platform 
  is successfully winning back churned users, but this also signals 
  an underlying retention problem worth investigating
- **Dolby Vision and 4K HDR make up 42% of streams** — premium 
  quality content is in high demand; investing in high-definition 
  originals is likely to pay off
- **India leads content availability by a wide margin** — other 
  large markets like USA and UK show lower availability, 
  representing untapped growth opportunity
- **Age rating distribution is near-uniform** — Netflix's library 
  successfully caters to all age groups with no single demographic 
  dominating

---

## 🛠️ Tools Used

- **Power BI Desktop** — Dashboard design, DAX measures, 
  custom Netflix branding, genre filter buttons
- **DAX** — KPI card calculations, average metrics, 
  segment aggregations
- **Custom Theme** — Netflix red/black color scheme applied 
  throughout for professional branded presentation

---

## 📂 Files in This Repository

| File | Description |
|---|---|
| `netflix (tudummm) dashboard` | Power BI dashboard file |
| `netflix_dashboard_data.csv` | Raw dataset used for analysis |
| `netflix_dashboard.png` | Dashboard preview screenshot |

---

## 🚀 How to Use

1. Download `netflix_analytics_dashboard.pbix`
2. Open in **Power BI Desktop** (free from Microsoft)
3. Use the **Genre buttons** at the top to filter all visuals
4. Hover over any chart for detailed tooltips

---

## 👤 Author

**Abhinav Verma**  
Aspiring Data & Business Analyst | Power BI · SQL · Excel  
📧 abhinavverma03985@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/abhinav-verma-56147b40a) |
[GitHub](https://github.com/abhi03985)
