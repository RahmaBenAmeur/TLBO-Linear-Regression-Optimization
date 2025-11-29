#  TLBO Optimization for Linear Regression  
### Teaching–Learning Based Optimization implemented in Python (Google Colab)

This repository contains a full implementation of the **Teaching–Learning Based Optimization (TLBO)** algorithm applied to a **linear regression problem**.  
The goal is to estimate the parameters *(w, b)* of a linear model by minimizing the **Mean Squared Error (MSE)** using a population-based metaheuristic inspired by a classroom learning process.

This project was created as part of an academic presentation and integrates multiple AI-powered tools for code, visuals, video narration, and presentation enhancement.

---

##  Overview

The notebook includes:

- Synthetic dataset generation  
- Definition of the MSE objective function  
- Full implementation of the **TLBO algorithm**  
- Teacher Phase & Learner Phase mechanisms  
- Optimization of model parameters *(w, b)*  
- Convergence curve visualization  
- Plot of the fitted regression line  
- Final results and interpretation  

The project demonstrates how TLBO can successfully solve **continuous optimization problems**.

---

##  Project Structure

TLBO-Linear-Regression/
│
├── TLBO_LinearRegression.ipynb # Main Google Colab notebook
└── README.md # Documentation


---

## 🧠 Teaching–Learning Based Optimization (TLBO)

TLBO is a population-based optimization algorithm inspired by the interaction between:

- **Teacher Phase**: learners improve by moving toward the best solution  
- **Learner Phase**: learners improve by interacting with each other  

Key advantages:

- No algorithm-specific parameters  
- Simple to implement  
- Efficient for low/medium-dimensional problems  
- Works well in continuous optimization  

---

## 📈 Results

The algorithm converges to estimated parameters close to the real model:

Best parameters (w, b): 2.62 , 6.55
Best MSE: 2.18


The notebook also plots: 

- TLBO convergence curve  
- The optimized regression line  

---

## 🛠️ Tools Used (AI-Powered)

This project was enhanced using several intelligent tools:

- **GitHub Copilot** — Smart assistance for writing and improving code  
- **ChatGPT** — Code generation, explanation, optimization, TLBO logic  
- **Gamma.app** — Automatic generation of the PowerPoint presentation  
- **Google Gemini** — AI image generation for conceptual visuals  
- **Whisk AI** — Video generation for TLBO teaching & learning phases  
- **TTS.aiKTP** — Text-to-speech for generating narration  
- **CupCat** — Video assembly and editing  







