# OPTIMIZATION-MODEL

*COMPANY* :  CODETECH IT SOLUTIONS

*NAME* :  S.NIRANJANA

*INTERN ID* : CT04DH2216

*DOMAIN* :  DATA SCIENCE

*DURATION* :  4WEEKS

*MENTOR* :  NEELA SANTOSH KUMAR

---
## 🎯 Overview

This repository contains a complete implementation of a Linear Programming (LP) model to solve a **business optimization problem** using the **PuLP** library in Python. The goal is to **maximize profit** by determining the optimal number of units to produce for two products (Product A and Product B), considering limited resources such as machine time and labor time.

This project is developed as part of a **Data Science Internship Task at CodTech**, focused on applying **operations research techniques** to solve real-world business problems. A successful completion of this task demonstrates the ability to model, solve, and interpret LP problems using Python.

---

## 📚 Problem Statement

A company manufactures two products: **Product A** and **Product B**.  
Each product requires a specific amount of **machine time** and **labor hours**, both of which are available in limited supply. The objective is to determine the number of units of each product to produce in order to **maximize profit**.

### 🔧 Parameters:

- **Product A**
  - Machine Time: 4 hours/unit
  - Labor Time: 2 hours/unit
  - Profit: $20/unit
- **Product B**
  - Machine Time: 6 hours/unit
  - Labor Time: 4 hours/unit
  - Profit: $30/unit
- **Total Resources Available**
  - Machine Time: 240 hours
  - Labor Time: 160 hours

### 📈 Objective Function:

Maximize:  
`Profit = 20 * x + 30 * y`  
Where:
- `x` = units of Product A
- `y` = units of Product B


---

## 🧪 Solution Methodology

The model is solved using **Linear Programming (LP)** via the **PuLP** library in Python. PuLP is a powerful modeling tool that allows defining decision variables, constraints, and objective functions for LP problems.

The steps followed in the notebook are:

1. **Installing and Importing PuLP**
2. **Defining the LP Problem** (maximize or minimize)
3. **Creating Decision Variables**
4. **Writing the Objective Function**
5. **Adding Constraints**
6. **Solving the Model**
7. **Interpreting Results**

---

## 📂 Files in this Repository

| File Name               | Description                                           |
|-------------------------|-------------------------------------------------------|
| `optimization_model.ipynb` | Main Jupyter notebook demonstrating the full implementation |
| `README.md`             | Documentation and project overview                   |
| `requirements.txt`      | (Optional) Lists dependencies like PuLP              |

---


## 🧠 Insights & Business Impact

- This model helps businesses make **data-driven decisions** about resource allocation.
- By maximizing profit while adhering to production limits, companies can **optimize output** and **increase efficiency**.
- Such optimization models can be extended to multiple products, additional constraints (e.g., storage, raw materials), or even multi-objective problems.

---

## 🛠️ Dependencies

- Python 3.x
- PuLP

You can install PuLP using:

```bash
pip install pulp
**



---

### ✅ To Save as `.md` File:

If you're using Colab:
1. Create a new text file: `File > New > File`
2. Name it `README.md`
3. Paste the content above into it
4. Save and download it

If you're using GitHub, just paste this into the **README.md** section of your repository.

Would you also like a sample `requirements.txt` or a license file (`MIT`) to complete your repo setup?


