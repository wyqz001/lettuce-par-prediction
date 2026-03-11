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
4. Model evaluation  
5. Growth simulation and harvest prediction  

---

## Key Idea

Lettuce growth depends mainly on two factors:

- available light (PAR)
- plant size (weight)

The regression model estimates daily growth using:

growth = a × PAR + b × weight + c

---

## Example Simulation

Starting from a plant weight of **200 g**, the model predicts how many days are needed to reach the harvest weight (**250 g**) under different PAR scenarios.

For example:

- continuous sunny days
- rainy days followed by sunshine
- multiple cloudy days

This allows simple harvest forecasting based on expected weather conditions.

---

## Tools Used

Python  
Pandas  
Matplotlib  
Scikit-learn
