# Train Ticket Analytics Dashboard

A Power BI project analyzing user behavior and conversion performance of an online train ticket booking platform.

---

## 📌 Project Overview

This project was conducted to help the Product Owner and Marketing Team gain a clear understanding of the current performance of the Train product. The main goals are to:

- Identify bottlenecks in the user journey
- Analyze traffic patterns by time, route, and trip type
- Measure funnel conversion rates
- Provide actionable recommendations for improvement

### Analysis Process
1. Understand requirements & data
2. Data cleaning and preparation (Power Query)
3. Exploratory Data Analysis (EDA)
4. Funnel Analysis
5. In-depth analysis (by Route, Time, Trip Style)
6. Extract insights & recommendations

---

## 📊 Data Overview

| Metric              | Value                     |
|---------------------|---------------------------|
| Total Records       | 398,121                   |
| Reporting Period    | March 2026 – April 2026   |
| Data Source         | Website Analytics         |
| Key Dimensions      | Time, Funnel, Route, Trip |

**Main Event Categories:**
- View Load
- Trip Select
- Seat Select
- Information Fill
- Payment Method
- Checkout

---

## 📈 Key Performance Indicators

| KPI                        | Value     |
|----------------------------|-----------|
| Total Events               | ~398K     |
| Average Events per Day     | ~13K      |
| Overall Conversion Rate    | **1.19%** |
| Total View Load            | ~261K     |
| Total Checkout             | ~3.1K     |

---

## 🗂️ Dashboard Structure

The Power BI report contains 2 main pages:

### 1. Route and Traffic Dashboard
Provides an overview of traffic volume and user behavior:

- Total Events by Day
- Total Events by Hour
- Total Events by Route (Top routes)
- Total Events by Funnel Step
- Total Events by Trip Search Style (One-way vs Round-trip)

**Key observations:**
- One-way trips dominate with **81.11%** of total events
- Round-trip accounts for only **18.89%**
- Highest volume routes: Hồ Chí Minh – Nha Trang, Hồ Chí Minh – Hà Nội, Hồ Chí Minh – Đà Nẵng

### 2. Funnel and Conversion Dashboard
Focuses on conversion performance across the booking funnel:

| Funnel Step          | Events   | % of Previous Step | % of Total |
|----------------------|----------|--------------------|------------|
| 1. View Load         | 260,657  | -                  | 65%        |
| 2. Trip Select       | 85,466   | 33%                | 21%        |
| 3. Seat Select       | 19,740   | 23%                | 5%         |
| 4. Information Fill  | 5,652    | 29%                | 1%         |
| 5. Payment Method    | 6,795    | 120%               | 2%         |
| 6. Checkout          | 3,099    | 46%                | 1%         |

- **Overall Conversion (View Load → Checkout):** 1.19%
- **Biggest Drop-off:** View Load → Trip Select

---

## 🔍 Key Findings

1. **Biggest drop-off occurs at the beginning of the funnel**  
   Only 33% of users move from View Load to Trip Select, and only 23% continue to Seat Select. Most users appear to visit the platform mainly to check prices or compare options rather than to complete a booking immediately.

2. **Many high-traffic routes have very low conversion**  
   Routes such as Hồ Chí Minh – Nha Trang, Hồ Chí Minh – Hà Nội and Hồ Chí Minh – Đà Nẵng generate high View Load but produce very few or almost no Checkouts.

3. **Some routes convert unusually well**  
   The Đà Nẵng – Huế route recorded the highest number of Checkouts (263) despite having only a medium level of View Load.

4. **Traffic shows clear time patterns**  
   - A sharp drop in traffic occurred after day 25 of the period.  
   - Peak activity is concentrated in the evening, especially around 21:00.

---

## 💡 Recommendations

1. **Improve UX of the Route listing page and Trip selection step**  
   Highlight key information (price, available seats, duration) earlier in the journey and reduce the number of required actions.

2. **Optimize high-traffic, low-conversion routes specifically**  
   Apply tailored experiences and policies for routes that attract many views but convert poorly.

3. **Learn from high-performing routes**  
   Analyze what makes routes like Đà Nẵng – Huế convert better and apply those learnings to other routes.

4. **Boost engagement during peak hours (20:00 – 22:00)**  
   Increase promotional visibility and remarketing efforts in the evening time window when users are most active.

5. **Investigate the traffic drop after day 25**  
   Check whether the decline was caused by seasonality, marketing campaign changes, or technical issues.

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** – Dashboard design and visualization
- **Power Query** – Data cleaning and transformation
- **DAX** – Calculated metrics (Conversion Rate, Drop-off Rate, Average Events per Day, etc.)

---

## ✍️ Author

**Ngọc Linh**  
Data Analyst  
Email: ngoclinhpt601@gmail.com

---

## 📄 License

This project is intended for portfolio and educational purposes.  
Feel free to use and adapt it with proper attribution.
