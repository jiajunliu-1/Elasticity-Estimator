

# 📊 git
## 👨‍💻 Author

**Jiajun Liu**  
_Data Analyst · Revenue Optimization · Python Enthusiast_  

🔗 [GitHub Profile](https://github.com/jiajunliu-1)  
📫 Email: jiajunliu111@gmail.com  

This project estimates the **price elasticity of demand** using historical price and quantity data. It helps analysts and pricing teams understand how changes in price impact customer demand and overall revenue — a key concept in **revenue optimization**.

---

## 🧠 Overview

**Price Elasticity of Demand** measures how sensitive demand is to changes in price. This project uses a **log-log regression model** to estimate elasticity, classify whether a product is elastic or inelastic, and visualize key metrics such as:

- Demand curve
- Revenue curve
- Elasticity zones

---

## 🔧 Features

- 🧮 Log-log linear regression model for elasticity estimation
- 📈 Demand vs. Price and Revenue vs. Price visualizations
- ✅ Elastic vs. Inelastic zone detection
- 📊 Jupyter notebook walkthrough
- 🗃️ Easy-to-read mock dataset included

---

## 📂 Project Structure
    elasticity-estimator/
    ├── data/
    │   └── mock_pricing_data.csv        # Synthetic price & quantity data
    ├── notebooks/
    │   └── elasticity_analysis.ipynb    # Main analysis walkthrough
    ├── src/
    │   ├── elasticity_model.py          # Elasticity calculation functions
    │   └── visualization.py             # Plotting utilities
    ├── README.md
    ├── requirements.txt


## 📥 How to Use

1. Clone the repo:
   ```bash
   git clone git@github.com:jiajunliu-1/Elasticity-Estimator.git
   cd Elasticity-Estimator

2. Install the requirements
    ```bash
    pip install -r requirements.txt
3. Run the notebook
    ```bash
    jupyter notebook notebooks/elasticity_analysis.ipynb


   