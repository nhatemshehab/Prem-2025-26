# Premier League 2025-2026: Attacking Analysis
> A descriptive analysis of tactical intent and efficiency in the English top flight. 

## ⚽ Project Overview
This project explores the "state of the attack" across the Premier League. Using Power BI, I visualized how teams translate tactical setups into goal-scoring opportunities, moving beyond basic scorelines to quantify the "eye test" with numerical evidence.

## 🧠 The Logic: Confirming Intuition
This dashboard focuses on four key pillars of modern football:
* **Field Tilt**: Calculated as passes in the opponent's final third as a percentage of total passes to measure sustained pressure.
* **Attacking Effectiveness**: Analyzes goals scored per 90 relative to the total goals in a team's games to highlight clinical efficiency.
* **Set Piece Meta**: Maps the volume of corners and free kicks against execution success.
* **Individual Output**: Compares high-volume shooters like **Erling Haaland** to the rest of the league to see how team style influences player stats.

## 🛠️ Data Engineering & ETL
To ensure a clean and joinable dataset, I performed the following transformations:
* **Standardization**: Unified team names (e.g., "Man City" → "Manchester City") to act as a primary key across all tables.
* **Data Cleaning**: Dropped null values in the pressing tables and renamed technical columns (e.g., "xG" → "Expected Goals") for clarity.
* **Feature Engineering**: Created custom metrics for **Passes in the Final Third %** and **Goals per 90**.

## 📊 Dashboard Features
* **Interactive Navigation**: A custom **Bookmark Bar** allows users to flip through grouped visualizations: Overall, Attacking Effectiveness, Set Pieces, and Attacking Players.
* **Visual Hierarchy**: High-level KPI cards for total goals and games played combined with detailed scatter plots for style-of-play clustering.

## 🎨 Design & Styling
* **Branding**: Used a deep purple and pink gradient theme to align with the Premier League’s official visual identity.
* **User Experience**: Integrated official club crests within charts for immediate recognition.

---
*Created by Noor Hatem Shehab* 
