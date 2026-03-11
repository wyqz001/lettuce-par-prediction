# Lettuce PAR Prediction

This project analyzes lettuce growth using environmental light data (PAR) and plant weight.

The goal is to explore how light conditions influence daily lettuce growth and to simulate harvest timing under different weather scenarios.

---

## Dataset

The dataset contains daily observations of lettuce plants.

Variables include:

- **daily_PAR** – daily photosynthetically active radiation
- **weight_g** – plant weight (grams)
- **daily_growth** – daily increase in weight
- **days_after_transplant** – growth stage indicator

---

## Analysis Workflow

1. Data loading and inspection  
2. Data visualization  
3. Linear regression modeling  
4. Growth simulation  
5. Harvest timing prediction  

---

## Example Insight

The regression model estimates daily lettuce growth using:

growth = a × PAR + b × weight + c

This allows simulation of harvest timing under different light conditions.

---

## Tools Used

Python  
Pandas  
Matplotlib  
Scikit-learn
