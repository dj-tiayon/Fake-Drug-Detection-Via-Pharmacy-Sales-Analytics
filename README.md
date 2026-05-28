# Fake Drug Detection via Pharmacy Sales Analytics
**Using Excel and Power BI to identify suspicious pharmaceutical distribution patterns and support counterfeit drug monitoring in Nigeria.**

## 📌 Project Overview

This project analyzes pharmacy sales transactions to identify suspicious drug distribution patterns that may indicate counterfeit or substandard medicines within the pharmaceutical supply chain in Nigeria.

Using Excel and Power BI, the analysis focuses on detecting anomalies related to unusually low drug prices, abnormal sales quantities, unknown brands, supplier behavior, and near-expiry drugs.

An interactive Power BI dashboard was developed to support data-driven decision-making by helping stakeholders:

- 💊 Detect suspicious drug transactions
- 🚨 Identify high-risk suppliers and pharmacies
- 📉 Monitor unusual pricing and sales patterns
- 🔍 Investigate potential counterfeit drug activity
- 🏥 Support public health monitoring and regulatory actions

The project combines anomaly detection, risk scoring, and business storytelling techniques to transform raw pharmacy sales data into actionable insights for non-technical stakeholders.

## 🚨 Business Problem

Counterfeit and substandard medicines remain a major public health challenge in Nigeria, particularly in areas where pharmaceutical supply chains are difficult to monitor and regulate effectively.

Suspicious activities such as unusually low drug prices, unknown brands, abnormal sales spikes, unreliable suppliers, and near-expiry drugs can easily go unnoticed when relying solely on manual inspections and traditional monitoring methods.

To support better pharmaceutical surveillance and risk monitoring, this project analyzes pharmacy sales data to answer the following key business questions:

1. 💰 Which pharmacies sell drugs at significantly lower prices than expected?
2. 🏷️ Are there brands with high sales volumes but unknown or unverified origins?
3. 🚚 Are specific suppliers frequently associated with suspicious transactions?
4. 🌍 How do suspicious sales patterns differ between urban and rural locations?
5. ⏳ Are near-expiry drugs being distributed at concerning levels?

The goal is to help health stakeholders identify high-risk transactions, improve supplier oversight, and support data-driven regulatory decision-making.

## 🛠️ Tools & Skills Used

### 📊 Data Analysis & Visualization

- Power BI
- Excel
- DAX

### 🧹 Data Preparation
- Data Cleaning
- Data Transformation
- Data Validation
- Feature Engineering

### 📈 Analytical Techniques
- Anomaly Detection
- Risk Scoring
- KPI Development
- Trend Analysis

### 🎨 Dashboard & Reporting
- Interactive Dashboard Design
- Business Storytelling
- Data Visualization
- Drill-Through Analysis

### 💼 Domain & Business Skills
- Pharmaceutical Risk Monitoring
- Counterfeit Drug Detection
- Insight Generation
- Decision Support Analytics

## 🧹 Data Preparation & Modeling

The project involved working with pharmacy transaction data containing drug sales, supplier information, pricing details, pharmacy locations, expiry dates, and brand information.

Several data cleaning and transformation steps were performed to improve data quality and prepare the dataset for analysis.

### 🔧 Key Data Preparation Steps

- Cleaned missing and inconsistent values
- Standardized categorical fields and naming formats
- Corrected data types for dates and numeric fields
- Created calculated columns and DAX measures
- Engineered anomaly detection features
- Built risk flags and risk scoring logic
- Developed KPIs for monitoring suspicious transactions

### ⚙️ Anomaly Detection Logic

Drugs were flagged as suspicious if they met one or more of the following conditions:

- 💰 Drug price was less than 70% of the average category price
- 📦 Quantity sold exceeded 1.5× the average quantity
- ⏳ Drug expiry date was less than 6 months away
- 🏷️ Drug was associated with an unknown or unverified brand

### 🚩 Anomaly Flags Created

The following anomaly flags were created to identify suspicious transactions:

- 💰 Low Price Flag
- 📦 High Quantity Flag
- ⏳ Near Expiry Flag
- 🏷️ Unknown Brand Flag

These flags were combined to generate transaction-level risk scores and support anomaly detection analysis.

### 📊 KPIs Developed

The following KPIs were developed to monitor suspicious pharmaceutical activity:

- % Suspicious Transactions
- % Low Price Transactions
- % Unknown Brand Sales
- % Near Expiry Drugs
- % Rural Risk
- Top Risky Supplier

### 🧩 Data Modeling

The cleaned dataset was modeled in Power BI to support:
- Interactive filtering
- Supplier Drill-Through Investigation Page
- KPI tracking
- Comparative analysis across suppliers, pharmacies, brands, and locations

## 📊 Dashboard Structure

The Power BI dashboard was designed as a multi-page investigative report to help non-technical health stakeholders monitor suspicious pharmaceutical activity and investigate potential counterfeit drug distribution patterns.

The report follows a progressive storytelling structure:

- 📌 Page 1 focuses on overall pharmaceutical risk monitoring
- 🔍 Page 2 explores suspicious sales patterns and anomaly drivers
- 🧪 Page 3 provides detailed supplier-level investigation

---

## 📄 Page 1 — Drug Risk Overview

### 🎯 Purpose
Provide a high-level overview of suspicious pharmaceutical activity and highlight major risk indicators across the supply chain.

### 🖼️ Dashboard Preview
[Insert Dashboard Screenshot Here]

### 💡 Key Focus
Help stakeholders quickly understand the overall level of pharmaceutical risk and identify major anomaly trends.

---

## 📄 Page 2 — Risk Investigation

### 🎯 Purpose
Explore suspicious sales behavior, investigate supplier-related risks, and analyze anomaly patterns in greater detail.

### 🖼️ Dashboard Preview
[Insert Dashboard Screenshot Here]

### 💡 Key Focus
Support deeper investigation into suspicious suppliers, brands, and transaction patterns contributing to counterfeit drug risk.

---

## 📄 Page 3 — Supplier Analysis

### 🎯 Purpose
Provide a detailed investigation page for analyzing supplier-specific suspicious activity.

### 🖼️ Dashboard Preview
[Insert Dashboard Screenshot Here]

### 💡 Key Focus
Help stakeholders understand why a supplier is considered high-risk and identify the main drivers behind suspicious transactions.


## 🔍 Key Insights

### 1️⃣ High Level of Suspicious Drug Activity

Approximately **60% of pharmacy transactions** were flagged as suspicious based on anomaly indicators such as low pricing, unknown brands, high sales quantities, and near-expiry drugs.

This suggests a potentially high circulation of counterfeit or unsafe drugs within the pharmaceutical supply chain.

---

### 2️⃣ Low Pricing Was the Strongest Risk Indicator

Low-price transactions represented the largest share of suspicious activity, indicating that unusually cheap drugs may be a major warning sign of counterfeit distribution.

This highlights the importance of monitoring pricing inconsistencies across pharmacies and suppliers.

---

### 3️⃣ Certain Suppliers Showed Exceptionally High Risk Levels

Some suppliers recorded anomaly rates above 60%, with **Russell Group** identified as the top risky supplier.

This suggests that supplier behavior may play a major role in suspicious pharmaceutical distribution patterns.

---

### 4️⃣ Unknown Brands Recorded High Sales Activity

Several unknown or less traceable brands generated significant transaction volumes despite lacking strong verification indicators.

This raises concerns about product authenticity and supplier transparency.

---

### 5️⃣ Suspicious Activity Was High Across Both Urban and Rural Areas

The analysis showed elevated suspicious transaction rates in both urban and rural settings, suggesting that counterfeit drug risks are widespread rather than location-specific.

---

### 6️⃣ Expiry-Related Risks Were Present but Less Dominant

Near-expiry drugs contributed to suspicious activity but represented a smaller share of anomalies compared to pricing and supplier-related risks.

This suggests that pricing irregularities and supplier behavior are stronger indicators of potential counterfeit activity.

## ✅ Recommendations & Implementation Plan

| Recommendation | Action Steps | Expected Impact |
|---|---|---|
| 💰 Strengthen Drug Pricing Monitoring | Implement automated alerts for drugs sold significantly below average market price thresholds. | Reduce the circulation of suspicious low-cost drugs and improve early counterfeit detection. |
| 🚚 Audit High-Risk Suppliers | Conduct regular investigations and compliance checks on suppliers with high anomaly rates. | Improve supplier accountability and reduce suspicious pharmaceutical distribution. |
| 🏷️ Improve Brand Verification Processes | Establish a verified supplier and brand registry for pharmacies and distributors. | Increase transparency and reduce the distribution of unverified drug brands. |
| 🌍 Expand Monitoring Across Rural Areas | Increase pharmaceutical inspections and monitoring activities in underserved regions. | Improve counterfeit drug detection in both urban and rural communities. |
| ⏳ Enhance Expiry Tracking Systems | Introduce stronger inventory monitoring and expiry management procedures. | Reduce the risk of distributing unsafe or near-expiry drugs. |
| 📊 Deploy Real-Time Risk Monitoring Dashboards | Use Power BI dashboards for continuous anomaly tracking and supplier monitoring. | Enable faster data-driven decision-making and proactive risk management. |

## 💼 Business Impact

This project demonstrates how data analytics can support pharmaceutical risk monitoring and help detect suspicious drug distribution patterns using transactional sales data.

By combining anomaly detection techniques with interactive dashboard reporting, the analysis helps stakeholders:

- 💊 Identify potentially counterfeit or unsafe drugs
- 🚨 Detect high-risk suppliers and pharmacies
- 📉 Monitor unusual pricing and sales behaviors
- 🔍 Improve supplier oversight and investigation processes
- 📊 Support data-driven regulatory decision-making
- 🌍 Monitor pharmaceutical risks across urban and rural locations
- 🏥 Strengthen pharmaceutical supply chain transparency

The analysis revealed that pricing irregularities and supplier behavior were the strongest indicators of suspicious pharmaceutical activity, highlighting the importance of proactive monitoring systems in protecting public health.

## 🧠 Skills Demonstrated

Through this project, the following analytical and technical skills were demonstrated:

### 📊 Data Analysis & Visualization
- Power BI Dashboard Development
- Interactive Data Visualization
- KPI Design & Monitoring
- Business Storytelling

### 🧹 Data Preparation & Transformation
- Data Cleaning
- Data Validation
- Data Transformation
- Feature Engineering

### 📈 Analytical Techniques
- Anomaly Detection
- Risk Scoring
- Trend Analysis
- Comparative Analysis

### ⚙️ Technical Skills
- DAX Calculations
- Excel Analysis
- Data Modeling

### 💼 Business & Domain Skills
- Pharmaceutical Risk Monitoring
- Counterfeit Drug Detection
- Insight Generation
- Decision Support Analytics

## 🏁 Conclusion

This project demonstrated how pharmacy sales analytics can be used to detect suspicious pharmaceutical distribution patterns and support counterfeit drug monitoring efforts in Nigeria.

By applying anomaly detection logic, risk scoring techniques, and interactive Power BI reporting, the analysis identified unusually low pricing, high-risk suppliers, unknown brands, and near-expiry drugs as key indicators of suspicious activity within the pharmaceutical supply chain.

The project highlights the value of combining data analytics, business understanding, and visual storytelling to support public health monitoring and improve data-driven decision-making for non-technical stakeholders.

## 🌟 Portfolio Highlights

- 💊 Built a multi-page interactive Power BI dashboard for pharmaceutical risk monitoring
- 🚨 Applied anomaly detection techniques to identify suspicious drug transactions
- 📊 Developed KPI-driven reporting for non-technical health stakeholders
- 🔍 Designed supplier-level investigation and drill-through analysis pages
- 📈 Identified high-risk suppliers, unknown brands, and unusual pricing patterns
- 🧠 Combined analytical thinking, business storytelling, and dashboard design
- 🏥 Explored the use of data analytics in supporting public health and counterfeit drug monitoring

## 📚 What I Learned

Through this project, I gained hands-on experience in applying data analytics techniques to a real-world public health problem.

Some key lessons and takeaways included:

- 💊 How anomaly detection can be used to identify suspicious pharmaceutical activity
- 📊 How to design KPI-driven dashboards for non-technical stakeholders
- 🧹 The importance of proper data cleaning and feature engineering in analytical projects
- 🔍 How drill-through analysis supports deeper investigation and storytelling
- 📈 How to transform business questions into actionable insights
- 🎨 The value of clear dashboard design and visual storytelling in decision-making
- 🏥 How analytics can support public health monitoring and pharmaceutical risk management
