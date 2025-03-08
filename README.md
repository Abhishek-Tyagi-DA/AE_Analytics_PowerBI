# **Adverse Event Reporting Dashboard | Power BI**  

<img src="https://github.com/user-attachments/assets/83646fbb-40bd-492c-b98b-d27f6fc47275" alt="Dashboard Image" width="700" height="300">

## **Overview**  
This project analyzes **adverse event reports** related to **foods, dietary supplements, and cosmetics** using data from the **CFSAN Adverse Event Reporting System (CAERS)**. The goal is to identify trends, patterns, and potential risks associated with various **FDA-regulated products**.  

The **interactive Power BI dashboard** helps users explore:  
- 📅 **Time-based trends** in adverse event reporting  
- 🏭 **Industry-wise product impact analysis**  
- 🏥 **Most reported symptoms and outcomes**  
- 🧑‍🤝‍🧑 **Demographics of affected individuals**  
- 🔍 **Correlation between age and symptom severity**  

---

## **Dataset Information**  
The dataset covers reports from **2004 to Q2 2017**, capturing:  
- **Report Details:** Unique report ID, event start date, report submission date  
- **Product Information:** Brand names, product role, FDA industry classification  
- **Demographics:** Age, gender of affected individuals  
- **Event Outcomes:** Hospitalization, ER visits, serious/non-serious injuries  
- **Symptoms:** Coded symptoms reported per event  

📂 **Data Source:** CAERS_ASCII_2004_2017Q2.csv  

![Data Flow](https://github.com/user-attachments/assets/a9c4e6fd-472e-4868-bdb5-f41f73099c62)  

---

## **Tools Used**  
- **Power BI**: Data visualization & dashboard creation  
- **DAX (Data Analysis Expressions)**: Custom calculations & analytics  
- **Excel**: Data preprocessing & cleanup  

![Tech Stack](https://github.com/user-attachments/assets/8a533972-9e5d-40ca-833c-5086a4f4bc75)  
![Trend Analysis](https://github.com/user-attachments/assets/644808e1-d6b7-488b-b33c-9548450af82b)  
![Dashboard Overview](https://github.com/user-attachments/assets/ae2225ff-d14a-4f5f-8182-9a43b36d838c)  
![Dashboard Preview](https://github.com/user-attachments/assets/7b95ce25-6d4e-4aa9-859a-24aa7f41665d)

---

## **Project Workflow**  

### **1. Data Cleaning & Preprocessing**  
✔ **Handled missing values** for event dates, ages, and symptoms.  
✔ **Standardized data types** (date formats, numerical conversions).  
✔ **Removed duplicates** and ensured data consistency.  

### **2. Data Modeling & DAX Measures**  
📌 **Time Intelligence:** Calculated monthly & yearly trends of adverse events.  
📌 **Age Grouping:** Categorized age groups to analyze risk patterns.  
📌 **Symptom Frequency Analysis:** Ranked the most reported symptoms.  
📌 **Industry-Outcome Relationship:** Mapped industries to reported health outcomes.  
📌 **Correlation Analysis:** Examined age vs. symptom severity patterns.  

### **3. Dashboard Creation & Visualizations**  
📊 **Adverse Event Trends:** Time-series analysis of reported cases.  
📊 **Industry vs. Outcome Analysis:** Mapping industries to reported outcomes.  
📊 **Symptom Analysis:** Most frequently reported symptoms in adverse events.  
📊 **Demographic Insights:** Age and gender distribution of affected individuals.  
📊 **FDA Industry Breakdown:** Categorization of affected product types.  


---

## **Key Insights & Findings**  

### **1️⃣ Adverse Event Trends Over Time**  
📅 **Increasing Reports:**  
- **Adverse event reports increased significantly post-2010**, peaking in **2015-2016**.  
- The rise in cases suggests **greater consumer awareness** and possibly **increased regulatory reporting**.  

📅 **Seasonal Patterns:**  
- Certain months saw **spikes in reported cases**, possibly correlating with **seasonal food consumption** or **holiday-related dietary changes**.  

📅 **Regulatory Impact:**  
- Changes in **FDA regulations** around **2011 and 2016** might have contributed to fluctuations in reporting rates.
- 
![Image](https://github.com/user-attachments/assets/10606261-ab52-422d-bb59-b0222509ce58)

---

### **2️⃣ Industry & Product Analysis**  
🏭 **Most Reported Industries:**  
- **Dietary supplements** had the **highest number of adverse event reports**, followed by:  
  - **Bakery products** 🥐  
  - **Dairy products (Ice Cream, Cheese)** 🧀  
  - **Cosmetics (Hair dyes, Skincare products)** 💄  

🏭 **High-Risk Products Identified:**  
- **Energy drinks and weight-loss supplements** were frequently linked to severe reactions such as **palpitations, nausea, and hospitalizations**.  
- **Dairy & bakery products** were commonly associated with **allergic reactions**.  

![Image](https://github.com/user-attachments/assets/a9053fd5-e78e-431e-b00c-4068ac8e3948)

---

### **3️⃣ Demographic & Symptom Analysis**  
🧑‍🤝‍🧑 **Gender-based Trends:**  
- **Women reported 60-65% of all adverse events**, significantly higher than men.  
- This could be due to **higher usage of dietary supplements & cosmetics** among women.

🩺 **Most Commonly Reported Symptoms:**  
1️⃣ **Nausea & Vomiting** 🤢  
2️⃣ **Allergic Reactions (Rashes, Swelling, Itching)** 🤧  
3️⃣ **Palpitations & Dizziness** 💓  
4️⃣ **Gastrointestinal Issues (Diarrhea, Stomach pain)** 🤕  

![Image](https://github.com/user-attachments/assets/7830c236-6d4c-4940-882e-53d32a89255d)

---

## **Power BI Dashboard Features**  
🚀 **Dynamic Filters:** Explore data by **industry, demographics, and time range**.  
🚀 **Interactive Visuals:** Hover-over insights, slicers, and drill-through pages.  
🚀 **Trend Analysis:** Identify peaks and seasonal patterns in reports.  
🚀 **Industry Impact Analysis:** Compare adverse events across product categories.  

---

## **Future Enhancements**  
🔹 **Predictive Modeling:** Use AI to forecast high-risk product categories.  
🔹 **Severity Index:** Develop a **severity score** for reported symptoms.  
🔹 **Geospatial Analysis:** Visualize regional patterns (if geographical data is available).  
🔹 **Sentiment Analysis:** Extract consumer feedback on reported events.  

---

## **Contact**  
📩 **Email:** [abhityagi4733@gmail.com](mailto:abhityagi4733@gmail.com)  
🔗 **LinkedIn:** [linkedin.com/in/abhishektyagi02](https://linkedin.com/in/abhishektyagi02)  
🔗 **GitHub:** [github.com/abhishek-tyagi-da](https://github.com/abhishek-tyagi-da)  

⭐ *If you found this project useful, consider giving it a star! ⭐*  
