# Healthcare Cost Drivers Analysis

This project analyzes hospital billing data to identify patterns in healthcare costs across medical conditions, admission types, insurance providers, and hospital length of stay.

The goal is to explore potential cost drivers and demonstrate common healthcare analytics techniques such as data cleaning, aggregation, visualization, and derived metrics.

---

## Dataset

The dataset contains simulated hospital patient records including:

- Patient demographics
- Medical condition
- Admission type (Emergency, Urgent, Elective)
- Insurance provider
- Billing amount
- Date of admission and discharge

A derived metric, **Length of Stay**, was calculated using admission and discharge dates.

---

## Tools Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook (Google Colab)

---

## Analysis Steps

1. Loaded and inspected the dataset.
2. Cleaned and formatted date fields.
3. Calculated average billing amounts by:
   - Medical condition
   - Admission type
   - Insurance provider
4. Created a derived metric for **hospital length of stay**.
5. Visualized patterns in cost and hospitalization duration.

---

## Key Findings

- Average billing amounts are relatively consistent across medical conditions.
- Admission type shows only minor variation in average billing amounts.
- Insurance providers demonstrate similar billing averages within this dataset.
- Average hospital length of stay is approximately **15–16 days** across conditions.

These findings suggest that factors beyond the variables examined here—such as treatment procedures or patient severity—may play a larger role in determining hospital costs.

---

## Visualizations

The notebook includes the following visual analyses:

- Average billing by medical condition
- Average billing by admission type
- Average billing by insurance provider
- Average length of stay by medical condition

---

## Project Purpose

This project demonstrates exploratory data analysis and visualization techniques commonly used in healthcare analytics and financial analysis roles.
