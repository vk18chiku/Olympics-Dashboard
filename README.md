# 🏅 **Olympics Analysis Dashboard**

---

**📊 Project Overview**  
This Power BI project analyzes 120+ years of Olympic history through an interactive dashboard. The dashboard explores athlete achievements, country performances, sports trends, and medal patterns to provide a comprehensive view of global sports.

---

**📁 Dataset**  
- **Source:** [120 years of Olympic history: athletes and results](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results)  
- **Description:** Dataset contains detailed records of Olympic athletes, sports, events, medals, and participating countries from 1896 to 2016.

---

**🛠️ Tools & Technologies Used**  
- **Python (pandas)** – for data cleaning, transformation, and preprocessing  
- **Power BI** – for data modeling, DAX measures, and interactive dashboard creation  
- **DAX (Data Analysis Expressions)** – for dynamic KPIs, rankings, age calculations  

---

**⚙️ Data Preparation (pandas)**  
- Removed duplicates and irrelevant columns  
- Filled missing values (e.g., age, medal info)  
- Converted data types (e.g., year as integer, age as numeric)  
- Created new columns (e.g., age groups, medal flags)  
- Exported cleaned data to CSV for Power BI  

---

**📂 Dashboard Pages**

**1️⃣ Overview Page**  
- Displays total athletes, medals, countries, and events  
- Timeline comparison of Summer vs Winter Olympics  
- Year-wise medal distribution  

**2️⃣ Country Performance**  
- Total medals by year for selected country  
- Top 5 sports per country  
- Best performing athletes  
- Medal breakdown (Gold/Silver/Bronze)  

**3️⃣ Athlete Insights**  
- Filters for gender, age, country, and sport  
- Youngest and oldest medalists  
- Athletes with highest medal counts  

**4️⃣ Sports & Events Analysis**  
- Medal trends by sport over time  
- Event count per Olympic edition  
- Most popular sports by athlete participation  

**5️⃣ Global Map**  
- Medals by country visualized on world map  
- Clickable countries showing medal stats  

---

**❓ Key Questions Answered**
- Which country has won the most Olympic medals?  
- How has India’s performance evolved over time?  
- What are the top 10 medal-winning sports?  
- Which athletes have the highest medal count?  
- How does gender distribution vary across sports?  
- In which years were the most medals awarded?  
- What is the average age of gold medal winners?  

---

**🚀 DAX Highlights**
- Dynamic Top N (sports, athletes) measures  
- Age calculation for youngest/oldest medalists  
- Gender-wise medal distribution  
- Year-over-year medal growth  
- Custom tooltips and drill-through logic  

---

**💡 Future Enhancements**
- Add data for 2020 and 2024 Olympics  
- Include Paralympics analysis  
- Integrate predictive trends for future medals  

---

**📌 How to Run**
1️⃣ Use **pandas** to clean the dataset (sample Python script can be shared).  
2️⃣ Export cleaned data to CSV.  
3️⃣ Import CSV into Power BI.  
4️⃣ Build visuals using provided DAX measures and slicers.  

---

**🔗 Dashboard Link**  
👉 [View the live dashboard on Power BI](https://app.powerbi.com/view?r=eyJrIjoiMTc3NTZmY2QtNzFkNS00Y2VjLWJlZGEtODRjNDZkOTRkMGFjIiwidCI6ImI1M2FmNGY3LTE2ZTUtNGJjOC1iNjM5LWZjNTE0YTA0ZDllYiJ9)

