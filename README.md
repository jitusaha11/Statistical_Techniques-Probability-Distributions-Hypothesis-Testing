# 📊 Statistical Techniques: Probability Distributions & Hypothesis Testing

> **A Python-based Statistical Analysis Project using Jupyter Notebook**  
> 🧠 Explores Binomial, Poisson, Chi-Square distributions & applies Hypothesis Testing (ANOVA, Chi-Square Test) on real-world used car sales data.

---

## 📌 Project Overview

This project demonstrates **statistical techniques** applied to real-world industrial problems using **Python**.  
It combines **simulation of probability distributions** and **hypothesis testing** to extract actionable insights from data, with applications in **automotive resale, marketing analysis, and quality control**.

The dataset analyzed: `car_sales_cleaned.csv` – containing details on used car sales including make, price, color, body type, and transmission.

---

## 🎯 Objectives

- Simulate and visualize **Binomial**, **Poisson**, and **Chi-Square** distributions.
- Apply **One-Way ANOVA**, **Two-Way ANOVA**, and **Chi-Square Test** to real-world sales data.
- Compare simulated results with theoretical probability distributions.
- Draw statistically significant business conclusions from the results.

---

## 🧩 Project Tasks

### **Part 1 – Probability Distributions**
1. **Binomial Distribution**  
   - Simulate a 5-coin toss experiment  
   - Compare simulation with theoretical binomial distribution for 10, 100, and 1000 runs
2. **Poisson Distribution**  
   - Simulate website sign-ups (avg 3/hour)  
   - Compare simulation with theoretical Poisson distribution (λ = 3)
3. **Chi-Square Distribution**  
   - Simulate squared measurement errors with 2 degrees of freedom  
   - Compare simulation with theoretical Chi-Square PDF

---

### **Part 2 – Hypothesis Testing**
1. **One-Way ANOVA**  
   - Test belief: *Toyota cars resell for ₹12,400 on average*  
   - Use sample data and significance level **α = 0.05**
2. **Two-Way ANOVA**  
   - Analyze effect of:
     - **Body Type** (SUV, Sedan, Coupe, etc.)
     - **Transmission Type** (Automatic, Manual)  
     - Interaction between both factors  
   - Sample size: 5000 black-colored cars
3. **Chi-Square Test**  
   - Compare distribution of Toyota car colors vs. overall market  
   - Test for statistical significance (**α = 0.05**)

---

## 🛠️ Tools & Libraries Used

| Tool/Library      | Purpose |
|-------------------|---------|
| **Python 3**      | Programming & analysis |
| **Jupyter Notebook** | Interactive development environment |
| **NumPy**         | Random sampling, numerical operations |
| **Pandas**        | Data cleaning, manipulation |
| **Matplotlib / Seaborn** | Visualization |
| **SciPy.stats**   | Statistical tests (ANOVA, Chi-Square) |

---


