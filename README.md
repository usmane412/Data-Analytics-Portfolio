# Data-Analytics-Portfolio
# 🚢 Titanic Passenger Analysis

![Titanic Dashboard](screenshots/Titanic_Dashboard.png)

## 📌 Project Overview

The **Titanic Passenger Analysis** is a data analytics project focused on exploring passenger demographics, survival patterns, passenger class, gender, family size, embarkation locations, passenger titles, and cabin information from the Titanic dataset.

The project demonstrates the process of transforming raw passenger data into meaningful business-style insights through **data cleaning, data transformation, analysis, and interactive visualization** using Microsoft Power BI.

The goal of this project is to understand the factors and patterns associated with passenger survival and provide a clear visual representation of the dataset.

---

## 🎯 Project Objectives

The analysis was designed to answer the following questions:

- How many passengers were on the Titanic?
- How many passengers survived and how many died?
- What was the survival rate?
- How did survival differ between male and female passengers?
- How were passengers distributed across passenger classes?
- Which passenger class had the highest number of passengers?
- How did passenger class relate to passenger deaths?
- Which embarkation location had the highest number of passengers?
- What was the distribution of passengers by family size?
- How were passengers distributed by gender?
- What passenger titles were most common?
- What patterns can be observed from cabin information?

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **Microsoft Power BI** | Data visualization and dashboard development |
| **Power Query** | Data cleaning and transformation |
| **Microsoft Excel** | Data preparation and initial data inspection |
| **DAX** | Measures and calculations |
| **GitHub** | Project documentation and portfolio |

---

## 📊 Dataset

The dataset contains information about passengers who travelled on the Titanic.

Key fields used in the analysis include:

- `PassengerId`
- `First Name`
- `Last Name`
- `Title`
- `Sex`
- `Age`
- `Parch`
- `SibSp`
- `Family Size`
- `Fare`
- `Pass.Class`
- `Ticket`
- `Cabin`
- `Embark`
- `Status`

The `Status` field was used to distinguish between passengers who **survived** and those who **died**.

---

## 🧹 Data Cleaning & Transformation

The dataset was prepared using **Power Query** before being loaded into Power BI.

The main preparation steps included:

1. Reviewing the structure and quality of the raw dataset.
2. Checking for missing and inconsistent values.
3. Assigning appropriate data types to columns.
4. Cleaning passenger information.
5. Extracting passenger titles from passenger names.
6. Creating a **Family Size** column.
7. Organizing passenger class information.
8. Preparing embarkation data for visualization.
9. Creating fields required for passenger survival analysis.
10. Loading the cleaned dataset into Power BI.

These transformations helped ensure that the data was suitable for analysis and visualization.

---

# 📈 Dashboard

The Power BI dashboard provides an interactive overview of Titanic passenger data.

### Key Performance Indicators

The dashboard shows:

| Metric | Result |
|---|---:|
| 👥 Total Passengers | **891** |
| ⚰️ Passengers Died | **549** |
| 🛟 Passengers Survived | **342** |
| 📉 Survival Rate | **38.4%** |
| 📉 Death Rate | **61.6%** |

---

## 📊 Visualizations

### 1. Passengers Survived by Sex

This visualization compares the number of male and female passengers who survived.

The analysis shows a significantly higher number of **female survivors compared with male survivors**, highlighting gender as an important factor in the survival pattern within the dataset.

---

### 2. Total Passengers by Title and Passenger Class

This visualization examines passenger titles across different passenger classes.

It provides insight into the composition of passengers and shows how titles such as **Mr., Miss., Mrs., and Master** were distributed across passenger classes.

---

### 3. Total Passengers by Embarkation

The analysis shows that **Southampton** was the primary embarkation location, followed by **Cherbourg** and **Queenstown**.

This provides an overview of where passengers boarded the Titanic.

---

### 4. Passenger Distribution by Family Size

Family size was analyzed to understand whether passengers were travelling alone or with family members.

The dashboard shows that **a family size of 1 represents the largest group**, indicating that travelling alone was common within the dataset.

---

### 5. Total Passengers by Sex

The gender distribution shows that:

- **Male passengers:** approximately **64.8%**
- **Female passengers:** approximately **35.2%**

This indicates that the dataset contained considerably more male passengers than female passengers.

---

### 6. Total Passengers by Passenger Class

The passenger class distribution shows that **Third Class** contained the largest number of passengers, followed by **First Class** and **Second Class**.

This provides an overview of the socioeconomic/class distribution represented in the dataset.

---

### 7. Passengers Died by Passenger Class

Passenger deaths were compared across the three passenger classes.

The visualization indicates that **Third Class had the highest number of passenger deaths**, followed by Second Class and First Class.

This highlights a strong relationship between passenger class and survival outcomes in the dataset.

---

### 8. Total Passengers by Cabin

Cabin information was also explored to understand the distribution of passengers across recorded cabin assignments.

Because cabin information contains many individual cabin values and missing entries, this visualization is primarily useful for understanding the distribution of recorded cabin assignments.

---

# 🔍 Key Insights

The analysis produced several important findings:

### 1. Overall Survival Was Low

Out of **891 passengers**, only **342 survived**, while **549 died**.

This represents:

- **38.4% survival rate**
- **61.6% death rate**

Therefore, the majority of passengers in the dataset did not survive.

---

### 2. Gender Had a Strong Relationship with Survival

Female passengers had a substantially higher survival count than male passengers.

This supports the well-known historical pattern that women had considerably better survival outcomes during the Titanic disaster.

---

### 3. Male Passengers Were the Majority

Approximately **64.8% of passengers were male**, compared with approximately **35.2% female**.

This means the passenger population was predominantly male.

---

### 4. Passenger Class Was Associated With Deaths

Third-class passengers accounted for the largest number of deaths.

This suggests that passenger class was an important factor associated with survival outcomes.

---

### 5. Southampton Was the Main Embarkation Point

The majority of passengers in the dataset embarked from **Southampton**, making it the largest embarkation location.

---

### 6. Travelling Alone Was Common

Passengers with a **family size of 1** represented the largest family-size category in the analysis.

This suggests that a substantial proportion of passengers were travelling without accompanying family members.

---

# 💡 Business/Data Analytics Perspective

Although the Titanic dataset is historical, the project demonstrates several transferable data analytics skills.

The same analytical approach can be applied to real-world business datasets to identify relationships between:

- Customer demographics and purchasing behavior
- Customer segments and retention
- Product categories and sales
- Customer characteristics and business outcomes
- Geographic locations and performance
- Customer groups and risk

The project demonstrates how raw data can be transformed into an interactive dashboard that communicates findings clearly to stakeholders.

---

# 📂 Repository Structure

```text
Titanic-Passenger-Analysis/
│
├── README.md
│
├── data/
│   └── titanic_cleaned.csv
│
├── powerbi/
│   └── Titanic_Passenger_Analysis.pbix
│
├── screenshots/
│   └── Titanic_Dashboard.png
│
└── documentation/
    └── Data_Cleaning.md
