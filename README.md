# 🧮 Statistics Assignments  
*Author: Mahsa Dorri*  

This repository contains two assignments from the Statistics module.  
Each project explores fundamental probability and data analysis concepts using Python.

---

## 🦟 Assignment 1 — Beer vs Water: Mosquito Attraction Study

> **Goal:**  
> Analyze whether beer consumption increases attractiveness to mosquitoes.  

📁 **File:**  
`MahsaDorri - Assignment1 - Statistics.ipynb`

---

### 📊 Project Overview
- Compare mosquito response between **Beer** and **Water** groups.  
- Use boxplots and descriptive statistics to summarize findings.  
- Provide interpretation of results about beer consumption and mosquito attraction.  

---

### ⚙️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

### 🔎 Key Steps
1. **Data Loading**  
   - Imported `mosquitos_data.csv` into a Pandas DataFrame.  

2. **Visualization**  
   - Created side-by-side boxplots to compare mosquito attraction across groups.  

3. **Statistics**  
   - Calculated mean, median, standard deviation, and count.  

4. **Findings**  
   - The *Beer group* shows higher mosquito response on average.  
   - Evidence suggests beer consumption may increase mosquito attractiveness.  

---

### 📌 How to Run
1. Clone this repository  
2. Open the notebook in **Jupyter** or **Google Colab**  
3. Run all cells to reproduce the analysis  

---

## 🚪 Assignment 2 — The Monty Hall Problem Simulation

> **Goal:**  
> Simulate the Monty Hall game show to understand conditional probability and decision-making under uncertainty.  

📁 **File:**  
`MahsaDorri - Statistic - Assignment2`

---

### 🎯 Project Overview
- Simulate **10,000 rounds** of the Monty Hall game.  
- Compare two strategies:  
  1. Staying with the original door  
  2. Switching to the other unopened door  
- Compute and compare the probability of winning for both strategies.  

---

### ⚙️ Technologies Used
- Python  
- Random module  
- Matplotlib *(optional for visualization)*  

---

### 🔎 Key Steps
1. **Setup**  
   - Randomly assign one car 🚗 and two goats 🐐 behind three doors.  

2. **Simulation**  
   - Repeat the game 10,000 times for both “stay” and “switch” strategies.  

3. **Computation**  
   - Count wins for each strategy and calculate corresponding probabilities.  

4. **Visualization (Optional)**  
   - Plot a bar chart comparing the win rates of both strategies.  

---

### 📈 Findings
- Staying with the original door wins **≈ 33%** of the time.  
- Switching to the other door wins **≈ 67%** of the time.  

✅ **Conclusion:** It is statistically advantageous to switch doors.  

---

### 📌 How to Run
1. Run the Jupyter Notebook or Python script:  
   ```bash
   python monty_hall_simulation.py
