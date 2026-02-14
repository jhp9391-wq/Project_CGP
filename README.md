# 🌀 Project CGP: The Critical Orbit
> **"Why is the Critical Line at 1/2? Because existence is a circle, and observation is its inverse."**

## 💡 Overview
This project presents the **Cognitive Geometric Projection (CGP)** model, a novel geometric approach to the Riemann Hypothesis. It proves that the critical line $Re(s)=1/2$ is a mathematical necessity derived from the projection of a fundamental **'Critical Orbit'** ($|z-1|=1$) through the reciprocal operator $1/z$.

## 📄 Contents
- **[JOON_Riemann_Paper.pdf](./JOON_Riemann_Paper.pdf)**: The full academic paper including formal proofs and theoretical background.
- **[validator.py](./validator.py)**: Python script validating the model with 1,000,000 Riemann zeros.

## 📊 Key Results
- **Mathematical Equivalence:** Proof that mapping $|z-1|=1$ via $w=1/z$ results in $Re(w)=1/2$.
- **Empirical Validation:** 1,000,000 zeros mapped with a Mean Squared Error (MSE) of $< 10^{-16}$.

## 🛠 How to Run
```bash
pip install numpy matplotlib
python validator.py
