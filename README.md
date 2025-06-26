# 🛍️ Bike-Sales - Customer Purchase Analytics

This project analyzes customer behavior and purchasing patterns using Excel tools like PivotTables, PivotCharts, and formulas. The goal is to gain insights from customer gender, income, age group, and product preferences.

---

## 📊 Dataset Summary

- **Total Rows**: 100+ customer records
- **Fields Include**: Name, Gender, Age, Income, Product, Purchase Status, Liked/Disliked
- **Age Grouping**: Adolescents, Middle Age, Old Age
- **Purchase Decision**: Yes / No
- **Liked Product**: Yes / No

---

## 🧠 Key Analysis

### 🎯 Objective:
To understand how gender, age group, and preferences impact purchase behavior and income levels.

### 📌 Pivot Table:
- **Rows**: Gender
- **Columns**: Purchase Status, Liked
- **Values**: Sum of Income

### 📈 Pivot Chart:
- **Chart Type**: Column Chart
- **Title**: `Income vs Purchase: by Genders`

---

## 💡 Insights

- Males had slightly higher income contributions in 'Purchase = Yes'.
- Females showed more consistency across 'Liked' and 'Purchased' status.
- Adolescents mostly belonged to the non-purchasing segment.
- Old Age group had lower frequency but higher average income.

---

## 🛠️ Tools Used

- **Microsoft Excel / Google Sheets**
- PivotTables & Charts
- Custom Excel Formulas:
```excel
=IF(A2<=30,"Adolescents",IF(A2<=55,"Middle Age","Old Age"))
