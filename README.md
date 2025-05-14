# MLS Salary Analysis ⚽

**Author:** [@miles-alexander](https://github.com/miles-alexander)

---

## Project Overview

This project analyzes the relationship between player performance metrics and salaries in Major League Soccer (MLS) during the 2021 season, focusing on evaluating compensation levels for the 2022 season. The goal is to determine whether players' performances correlate with changes in their guaranteed compensation and identify potential instances of players being overpaid or underpaid relative to their on-field contributions.

---

## Research Questions

* Are MLS player salaries proportionate to their performance metrics?
* Which performance metrics most significantly correlate with salary changes?
* How do different positions (forwards, goalkeepers, midfielders, defenders) compare in terms of performance-to-salary correlation?
* Are salary increases consistent across similar performance levels?

---

## Data Sources

### **MLS Player Salary Data (2021-2022)**: Publicly available data containing player names, positions, performance metrics, and compensation.

   **Source:** Kaggle

   **URL:** - https://www.kaggle.com/datasets/viv6369/mls-season-2021-players-stats-and-their-salaries


---

## Data Preparation & Transformation

* **Data Cleaning**: Standardized column names and handled missing values.
* **Feature Engineering**: Created metrics such as Body Mass Index (BMI) to enhance analysis.
* **Feature Selection**: Focused on metrics that exhibited significant correlations with salary changes.
* **Correlation Analysis**: Examined relationships between performance metrics and salary data.
* **Modeling Techniques**: Applied regression models (Linear, Decision Tree, Random Forest, Lasso) to predict salaries based on player statistics.
* **Model Evaluation**: Compared model performance using Mean Squared Error (MSE) and R² scores to assess accuracy and potential overfitting.

---

## Key Insights

* **Forwards**: Higher goal tallies generally corresponded to salary increases, though some exceptions were noted for internationally recognized players.
* **Goalkeepers**: Saves did not consistently correlate with salary increases. Some top-performing goalkeepers experienced stagnant or reduced salaries.
* **Midfielders**: Assists were a major factor, though salary adjustments varied, with some high-assist players facing pay cuts.
* **Defenders**: Goals conceded in the box was used as a metric, but it showed weak correlation with salary changes.

---

## Key Visualizations

* Distribution of player salaries by position
* Correlation between performance metrics and salary changes
* Salary comparisons between top-performing players and average performers
* Analysis of salary trends among top 10 players per position

---

## Ethical Considerations

* No personal or sensitive information was used.
* Data transformations prioritized accuracy and transparency.
* Analysis acknowledges that salary determinants may include factors beyond performance, such as player marketability and fan engagement.

---

## Tools Used

* **Python (Pandas, Matplotlib, Seaborn)**: Data manipulation and visualization
* **Jupyter Notebook**: Analysis and data exploration
* **HTML Export**: Report presentation

---

## View the Report

To view the analysis and visualizations:

    1. Download the raw HTML file:

        - Visit the project repository on GitHub.

        - Locate the HTML file.

        - Click on the file and select Download or Save As to your computer.

    2. Open the HTML file in your web browser:

        - Right-click the file and select Open with → Your Browser (e.g., Chrome, Firefox).

---

## License

This project is intended for educational and analytical purposes. The data utilized is publicly available, and no personally identifiable information (PII) was used. All data sources are cited in compliance with relevant terms of service.

---
