# 📊 Instagram Analytics Dashboard

An interactive **Power BI Dashboard** built to analyze Instagram account performance — covering engagement trends, reach & impressions, media type breakdown, and content category insights.

---

## 🖼️ Dashboard Preview

![Instagram Analytics Dashboard](dashboard_preview.png)

---

## 📌 Key KPIs

| Metric | Value |
|---|---|
| Total Likes | 106K |
| Total Followers | 31K |
| Total Comments | 3K |
| Total Reach | 1M |
| Total Shares | 5K |

---

## 🔄 Project Workflow

### Step 1 — Data Collection
- Raw Instagram analytics data collected in CSV format
- Dataset contains post-level data with metrics like likes, comments, reach, impressions, shares, saves etc.

---

### Step 2 — Data Cleaning (Power Query)

- ✅ Removed duplicate rows
- ✅ Removed null/blank values from key columns
- ✅ Changed data types — post_date to Date, post_hour to Whole Number
- ✅ Extracted Month and Day of Week from post_datetime column
- ✅ Trimmed and cleaned text columns (content_category, media_type, traffic_source)
- ✅ Replaced inconsistent category names

---

### Step 3 — Calculated Columns (DAX)

- Engagement Rate column
- Performance Bucket Label (High / Medium / Low)
- Post Hour Label

---

### Step 4 — DAX Measures Created

- Total Likes
- Total Followers
- Total Comments
- Total Reach
- Total Shares
- Average Engagement Rate
- Total Impressions
- Total Saves

---

### Step 5 — Dashboard Building (Power BI)

| Visual | Chart Type |
|---|---|
| KPI Cards | Card Visual |
| Engagement Rate by Month | Area Line Chart |
| Reach vs Impressions | Line Chart |
| Engagement by Media Type | Donut Chart |
| Top Content Categories | Horizontal Bar Chart |
| Engagement by Day of Week | Clustered Bar Chart |
| Total Reach | Gauge Chart |

---

## 💡 Key Insights

- 🥇 Fashion content drives the highest engagement at 32.85%
- 📷 Image & Carousel posts outperform Reels
- 📅 Start of the week shows peak engagement
- 🔁 Carousel posts have the highest share rate

---

## 🛠️ Tools Used

- Power BI Desktop
- Power Query
- DAX
- Excel / CSV

---

⭐ If you found this helpful, give it a star!
