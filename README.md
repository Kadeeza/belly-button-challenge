# 🦠 Belly Button Biodiversity — Interactive Data Dashboard

![JavaScript](https://img.shields.io/badge/Tool-JavaScript-yellow) ![Plotly](https://img.shields.io/badge/Tool-Plotly-blue) ![D3.js](https://img.shields.io/badge/Tool-D3.js-orange) ![Data Visualization](https://img.shields.io/badge/Skill-Data%20Visualization-green) ![Interactive Dashboard](https://img.shields.io/badge/Skill-Dashboard%20Design-purple)

## 📌 Project Summary

This project builds a fully interactive web dashboard that explores a microbiology dataset cataloguing the bacteria cultures found in human belly buttons.

Users can select any individual from a dropdown menu to instantly update three visualizations and a demographic panel — demonstrating the kind of self-service, interactive data experience that business intelligence teams build for end users.

---

## 🎯 Business Objective

Interactive dashboards enable stakeholders to explore data independently without needing to run queries or scripts. This project demonstrates the ability to build a responsive, user-driven data application that:

- Loads and parses a structured JSON dataset
- Responds dynamically to user input
- Displays multiple views of the same underlying data simultaneously

---

## 🛠 Tools & Technologies

| Tool | Purpose |
|------|---------|
| JavaScript | Application logic and interactivity |
| D3.js | Data loading, DOM manipulation, dropdown events |
| Plotly.js | Interactive chart rendering |
| HTML | Dashboard layout and structure |
| JSON | Data source format |

---

## 📊 Dashboard Features

### Dropdown Menu
- Select any sample ID to update all charts and the metadata panel simultaneously

### Horizontal Bar Chart
- Displays the **top 10 OTUs (bacterial cultures)** found in the selected individual
- X-axis: sample values (count of bacteria)
- Y-axis: OTU ID labels
- Hover text: full OTU species label

### Bubble Chart
- Visualizes all OTUs for the selected individual
- X-axis: OTU ID
- Y-axis: Number of bacteria (sample values)
- Bubble size: scaled to sample values
- Bubble color: mapped to OTU ID

### Demographic Info Panel
- Displays individual metadata (age, ethnicity, location, etc.) for the selected sample

---

## 💼 Business Value Delivered

This project demonstrates the ability to:

✅ Build a dynamic, user-driven dashboard without a backend framework  
✅ Load and parse JSON data using D3.js  
✅ Create interactive Plotly charts that update in real time  
✅ Design a multi-panel dashboard layout for exploratory data analysis  

---

## 📁 Repository Structure

```
belly-button-challenge/
│── index.html          # Main dashboard page
│── samples.json        # Biodiversity dataset
│── static/
│   └── js/
│       └── app.js      # Dashboard logic and chart rendering
│── README.md
```
