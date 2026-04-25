# 👥 Workforce Restructuring using Prediction & Optimization

Making workforce decisions is complex — this project combines machine learning and optimization to design a data-driven, fair, and cost-efficient strategy for employee attrition and restructuring.

---

## 🚨 The Problem

Organizations undergoing restructuring face a difficult challenge: reducing workforce size while maintaining fairness, legal compliance, and operational stability.

Traditional approaches rely heavily on subjective decisions, which can lead to:
- inefficient cost outcomes  
- potential legal risks  
- unfair or inconsistent employee targeting  

In regulated environments, such as France, decisions must be made at a **group level** rather than targeting individuals, adding another layer of complexity.

---

## 💡 The Solution

This project builds a two-stage analytical framework that integrates prediction with optimization.

First, a machine learning model estimates each employee’s likelihood of accepting voluntary exit (RCC). Then, these probabilities are used within an optimization model to determine which employee groups should be offered exit packages, ensuring cost efficiency while respecting business and legal constraints.

The approach transforms restructuring from a subjective process into a structured, data-driven decision system.

---

## 📊 Business Impact

This framework enables organizations to make smarter, more defensible workforce decisions.

It allows:
- minimization of severance costs  
- achievement of workforce reduction targets  
- fair and legally compliant restructuring  
- scalable and repeatable decision-making  

By aligning analytics with real-world constraints, the solution balances efficiency with responsibility.

---

## 🛠️ How it was done

The project began by analyzing historical attrition data to identify key drivers of employee exit, such as overtime, job mobility, tenure, and satisfaction. A logistic regression model was selected for its strong performance and interpretability, with techniques like SMOTE applied to address class imbalance.

Predicted probabilities were then used to form **objectively defined employee groups**, ensuring compliance with labour regulations that prohibit individual targeting. These groups were constructed using business-relevant and legally neutral features such as department, role, and workload.

An optimization model was developed in Excel using Solver to minimize total severance cost while satisfying key constraints, including workforce reduction targets, cost savings requirements, and department-level retention thresholds.

The final solution identifies the most efficient groups to target, balancing predictive accuracy, operational feasibility, and legal compliance.

---

## 📄 Full Case Study

👉 [View Report](./report.pdf)
