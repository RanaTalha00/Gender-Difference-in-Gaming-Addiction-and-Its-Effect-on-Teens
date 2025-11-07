# 🎮 Gender Difference in Gaming Addiction and Its Effect on Teens

## 🧭 Project Description  
This project investigates **gender differences in gaming addiction among teens** and its psychological, social, and academic effects.  
By combining **quantitative analysis in RStudio** with **interactive visualization in Power BI**, the research identifies how gaming behaviors, mental health, and self-esteem vary across genders and socioeconomic backgrounds.  

---

## 📊 Research Objectives  
- Analyze gender-based differences in gaming addiction levels.  
- Evaluate the impact of gaming addiction on **mental health** and **self-esteem**.  
- Explore relationships between **gaming habits**, **income**, and **education**.  
- Present results through **statistical models** and **Power BI dashboards**.

---

## 🧩 Dataset Overview  
**File Name:** `Gender Difference in Gaming Addiction and its affect on the Health of Teens.xlsx`  
**Source:** Survey-based, coded in SPSS → exported to Excel → analyzed in RStudio → visualized in Power BI  

### 🧠 Variables Summary  

| Code | Variable | Description |
|------|-----------|-------------|
| GI01 | Age | Continuous numeric variable |
| GI02 | Gender | Male = 0, Female = 1 |
| GI03 | Residential Area | Rural = 0, Urban = 1 |
| GI04 | Employment Status | Unemployed = 0, Employed = 1 |
| GI05 | Years of Education | < 12 years = 1, 12 years = 2, Others = 3 |
| GI06 | Monthly Family Income | <30K = 1, 30–50K = 2, 70–100K = 3, >100K = 4 |
| GI07–GI11 | Gaming behavior indicators |
| AGA01–AGA09 | Gaming addiction scale (Likert 1–5) |
| AGH01–AGH09 | Depression scale (Likert 1–5) |
| AMH01–AMH07 | Anxiety scale (Likert 1–5) |
| ASE01–ASE10 | Self-esteem scale (Likert 1–5) |

---

## 🧮 Statistical Analysis (RStudio)

### 1️⃣ Data Preparation
- Imported `.xlsx` file using **readxl**.  
- Cleaned and recoded categorical variables (Gender, Area, Education, Income).  
- Created composite scales:  
  - `Addiction_Score` → mean of AGA items  
  - `Depression_Score` → mean of AGH items  
  - `Anxiety_Score` → mean of AMH items  
  - `SelfEsteem_Score` → mean of ASE items  

### 2️⃣ Statistical Tests  
- **Descriptive Analysis** → Mean, SD, and Frequency  
- **Independent Samples t-test** → Gender difference in gaming addiction  
- **Correlation Analysis** → Addiction vs Mental Health & Self-Esteem  
- **Regression Analysis** → Predicting psychological impact based on addiction & demographics  

### 3️⃣ Visualizations (R ggplot2)
- Boxplots for gender comparison  
- Scatterplots for addiction vs self-esteem, anxiety, depression  
- Correlation matrix for all psychological variables  
- Exported clean dataset → `Final_GamingAddiction_Data.csv`  

---

## 📈 Power BI Dashboards  

### 🔹 Dashboard 1 — *Gender Difference & Health Impact*
Interactive visuals:
- Different game preferences by gender  
- Addiction effects on self-esteem  
- Gaming addiction by category of games  
- Mental health correlation with gaming addiction  
- Social relation impact chart  
- **KPI cards:** Average Self-Esteem, Anxiety, Depression, Gaming Hours, Devices Used  
- **Slicers:** Gender, Education, Area, Game Type

### 🔹 Dashboard 2 — *Regression & Statistical Analysis*
Key visuals:
- Gender-based academic & social impact of gaming addiction  
- Gaming device preferences by gender  
- Addiction vs self-esteem scatterplot  
- Time spent vs addiction level  
- Bubble chart (Monthly income vs gaming addiction)  
- Correlation matrix between addiction & health indicators  

---

## 📦 Output Files  
| File | Description |
|------|--------------|
| `Final_GamingAddiction_Data.csv` | Cleaned dataset for Power BI visualization |
| `R_Analysis_Script.R` | Full RStudio analysis code |
| `PowerBI_Dashboard.pbix` | Power BI dashboard file |
| `Dash_1.png`, `Dash_2.png` | Dashboard screenshots for GitHub display |

---

## ⚙️ Tools & Technologies  
- **SPSS** → Data coding & export  
- **RStudio** → Statistical analysis & scoring  
- **Power BI** → Dashboard & KPI visualization  
- **Excel** → Intermediate cleaning & merging  

---

## 🧾 Key Insights  
- Males exhibited **higher gaming addiction levels** on average than females.  
- Gaming addiction correlated **negatively with self-esteem** and **positively with anxiety & depression**.  
- **Mobile gaming** was most popular across both genders.  
- Teens from **higher-income families** spent more time gaming, but addiction intensity remained similar.  

---

## 🚀 How to Reproduce  
1. Download the dataset: `Final_GamingAddiction_Data.csv`  
2. Open `R_Analysis_Script.R` in RStudio  
3. Run the analysis to reproduce statistics & clean output  
4. Import the CSV into **Power BI Desktop (Free)**  
5. Use slicers to explore insights by gender, education, or game type  

---

## 🧑‍💻 Author  
**Talha Ikram Rana**  
Jr. Data Analyst and Researcher  
🌐 Linked: [https://www.linkedin.com/in/rana-talha-ikram-36a7b2202/]

---

## 🪶 Abstract  
This research examines how gaming addiction differs between male and female teens and how it affects their psychological well-being, social behavior, and academic life.  
Through statistical modeling in RStudio and interactive dashboards in Power BI, the project reveals that **gender, income, and gaming habits** significantly influence **addiction intensity and mental health outcomes**, providing valuable insights into digital behavior patterns among youth.  
