# 🚗 Vehicle Insurance Analysis Project

![License](https://img.shields.io/badge/Status-Completed-brightgreen) ![Python](https://img.shields.io/badge/Python-3.8%2B-blue) ![EDA](https://img.shields.io/badge/Type-Exploratory%20Data%20Analysis-orange)

---
## ✨ About Me
HI! I'm Sujata, a data analyst passionate about uncovering insights from data to support strategic business decisions.
🚗 In this Vehicle Insurance Analysis project, I explored customer and vehicle attributes to identify key drivers of insurance interest and claim likelihood for smarter, targeted policy offerings.

## 📌 Objective

To provide **personalized vehicle insurance offerings** by analyzing customer profiles, vehicle attributes, and claim likelihood — thereby improving customer targeting and optimizing underwriting processes.

---

## 📂 Dataset Overview

The dataset contains **381,109 records** with the following key features:

- 👤 **Customer Profile**: Gender, Age, Region Code, Driving License  
- 🚘 **Vehicle Info**: Vehicle Age, Vehicle Damage, Previously Insured  
- 💰 **Policy Details**: Annual Premium, Sales Channel, Vintage  
- 🎯 **Target Variable**: Response (Interest in Insurance)

---

## 🧹 Data Cleaning

- ✅ Handled missing values (none found)
- 🔁 Removed duplicates
- 🔢 Converted float to integers where needed (e.g., Region_Code)
- 🔄 Categorical encoding for Gender, Vehicle_Damage
- 🧮 Outlier capping on `Annual_Premium` using IQR method

---

## 📊 Exploratory Data Analysis

### 🧍 Gender Distribution
- Majority of applicants are male
- Claim behavior is relatively similar across genders

### 📈 Age Distribution
- Most applicants are aged **20–30**
- Claim interest drops significantly after age 60

### 🚘 Vehicle Age
- Vehicles aged **>2 years** have the highest claim rate (~29%)
- New vehicles show lower claim interest

### 🔧 Vehicle Damage
- Damaged vehicles are **far more likely** to result in a claim

### 🧾 Previously Insured
- Uninsured individuals have **higher claim interest**
- Previously insured users are typically low-risk

### 💸 Annual Premium
- Premiums mostly range from ₹20,000 to ₹45,000
- Skewed distribution with outliers capped at ₹61,892.50

### 🗺️ Region Analysis
- Certain regions show **high claim rates** — suitable for localized targeting

### 💻 Policy Sales Channel
- Some channels have high engagement but **low claim interest**
- Optimizing channel performance is crucial for conversion

---

## 📈 Feature Analysis

| Feature | Insight | Strategic Action |
|--------|---------|------------------|
| Age | Young users (<30) show higher claim interest | Offer targeted discounts |
| Vehicle Age | Older vehicles → higher claims | Introduce wear & tear coverage |
| Vehicle Damage | Strong predictor of claim | Include in underwriting logic |
| Region Code | Region-wise claim variation | Launch regional campaigns |
| Sales Channel | Some channels underperform | Reallocate digital marketing spend |
| Annual Premium | Higher premiums linked to claims | Balance price vs perceived risk |

---

## 📊 Visualizations

- 📌 Countplots, Histograms, Violin & Box Plots
- 🔥 Heatmaps for Correlation Analysis
- 🧩 Claim Frequency by Region, Age, Sales Channel
- 📍 Pie charts to represent vehicle damage impact

---

## 🧠 Key Insights

- ✅ Claim likelihood is **highly influenced** by:
  - Vehicle damage
  - Previous insurance status
  - Age and vehicle age

- 🚩 Majority of customers **don’t opt** for insurance (Response = 0)
- 🛠️ Predictive modeling can be enhanced using vehicle damage, age, and region code

---

## 💡 Strategic Recommendations

- 🎯 Target younger, uninsured users with flexible, affordable plans
- 🧰 Create bundled policies for older vehicles (>2 years)
- 📍 Focus on regions with high conversion potential
- 🔄 Use previous insurance status and vehicle damage in risk scoring
- 📢 Improve underperforming sales channels with better targeting

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| `Python` | Programming |
| `Pandas` | Data wrangling |
| `NumPy` | Numerical operations |
| `Matplotlib / Seaborn` | Data visualization |
| `Google Collab` | Development environment |

---

## 📎 Project Structure


📦 Vehicle_Insurance_Analysis/
├── 📄 README.md
├── 📁 data/
│ └── Vehicle_Insurance.csv
├── 📁 notebooks/
│ └── vehicle_insurance_analysis.ipynb
└── 📊 outputs/
└── graphs, charts, heatmaps


---

## ✅ Conclusion

This project helped me develop actionable business insights from insurance data using statistical EDA and visualization techniques. It reflects my ability to **translate real-world problems into data-driven strategies**, especially in risk-based domains like insurance.

---

## 🙌 Acknowledgments

Thanks to the open-source data community for providing rich datasets and inspiration!

---
## 🙏 Gratitude

<p> I would like to sincerely thank my mentor <mark>Miss Sheetal Gupta</mark> and my institute <mark>SkillCircle</mark> for their continuous guidance, encouragement, and support throughout my learning journey.</p>


---
## 🤝 Get in Touch
I'd love to connect and collaborate on data-driven projects, analytics roles, or anything related to insights and innovation. Feel free to reach out!

📧 Email: [Sujataattri5@gmail.com]

💼 LinkedIn: [www.linkedin.com/in/sujata-ab727236a]

🐙 GitHub: [https://github.com/Sujata1204]

> 💼 **Project Type**: Real-world EDA | 📍 **Domain**: Insurance Analytics | 🎯 **Focus**: Business Insights & Risk Profiling


