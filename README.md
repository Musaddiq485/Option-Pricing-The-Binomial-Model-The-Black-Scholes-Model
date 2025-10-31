# Option Pricing: Black-Scholes & Cox-Ross-Rubinstein (CRR) Model

> This project implements and compares two fundamental models in quantitative finance for pricing European call options: the **Black-Scholes formula** and the **Cox-Ross-Rubinstein (CRR) binomial tree model**.

---

## 📌 Overview
In this project, I:  
- Compute European call option prices using the Black-Scholes formula  
- Compute the same prices using the CRR binomial tree model  
- Analyze convergence of CRR prices to the Black-Scholes price  
- Explore absolute/relative errors and visualize odd-even oscillations in CRR  

This project demonstrates my skills in **Python, numerical methods, financial modeling, and data visualization**.

---

## 🛠 Tools & Skills
- **Programming:** Python, NumPy, SciPy, Matplotlib  
- **Finance:** European option pricing, Black-Scholes model, Binomial tree method  
- **Analytics:** Convergence analysis, absolute/relative errors, numerical visualization  
- **Data Visualization:** Line plots, log-log plots, error convergence charts  

---

## 🔍 Workflow
1. **Import Required Libraries**  
   NumPy, Matplotlib, and SciPy for computations and visualization  

2. **Black-Scholes Model**  
   - Analytical solution for European call options  
   - Python function implemented to calculate option price  

3. **Cox-Ross-Rubinstein (CRR) Binomial Model**  
   - Compute option prices using stepwise binomial tree  
   - Perform backward induction to calculate present value  

4. **Convergence Analysis**  
   - Compare CRR prices with Black-Scholes price for N = 10 to 500 steps  
   - Calculate absolute and relative errors  
   - Visualize convergence rate using log-log plots  

5. **Odd-Even Oscillation Analysis**  
   - Visualize CRR prices for small N to show oscillations based on parity  
   - Analyze how oscillations diminish with increasing steps  

---

## 📊 Results / Visualizations

### CRR vs Black-Scholes Convergence
![CRR vs Black-Scholes](https://github.com/Musaddiq485/Option-Pricing-The-Binomial-Model-The-Black-Scholes-Model/blob/6d970f3281a11089d32eb6bd947c0aa409894f5d/Screenshot%202025-10-31%20170322.png)
*CRR prices converge to the Black-Scholes price as number of steps increases.*

### Absolute & Relative Errors
![Errors](https://github.com/Musaddiq485/Option-Pricing-The-Binomial-Model-The-Black-Scholes-Model/blob/ad50ab6ef178a24d583903b7f22e03a86469b50f/Screenshot%202025-10-31%20170345.png)
![Errors](https://github.com/Musaddiq485/Option-Pricing-The-Binomial-Model-The-Black-Scholes-Model/blob/8bc540e0cfb41e67cca42006bc84db79f955ed7e/Screenshot%202025-10-31%20170408.png)
*Absolute and relative errors decrease with increasing steps, demonstrating convergence.*

### Log-Log Convergence
![Log-Log Plot](https://github.com/Musaddiq485/Option-Pricing-The-Binomial-Model-The-Black-Scholes-Model/blob/8b27fdb979844d8b90150e5b0e34c856cfbee074/Screenshot%202025-10-31%20170422.png)
*Log-log plot shows approximate slope -1 for convergence rate.*

### Odd-Even Oscillation Effect
![Odd-Even Oscillation](https://github.com/Musaddiq485/Option-Pricing-The-Binomial-Model-The-Black-Scholes-Model/blob/3b8fda8dc8b74675cfffc7bf94447248b19ff17a/Screenshot%202025-10-31%20172043.png)
*Small N shows oscillation depending on step parity; stabilizes as N increases.*

---

## ✨ Key Insights
- CRR prices **converge quickly** to Black-Scholes values as N increases  
- Absolute and relative errors decrease roughly proportional to 1/N  
- Odd-even oscillation is observed for small N and diminishes with larger steps  
- Demonstrates ability to implement numerical finance models and perform convergence analysis  

---

## ⚠️ Notes
- This project is part of my **learning and skill-building** in quantitative finance and Python programming  
- Screenshots are placeholders — update them with your actual figures from Jupyter Notebook  
