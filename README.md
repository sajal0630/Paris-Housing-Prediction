# 🏠 Paris Housing Price Prediction

This project analyzes housing data from Paris to uncover what factors most influence property prices and builds a Multiple Linear Regression model to predict them. The goal was to provide data-driven recommendations to a real estate development company, guiding their investment and marketing strategies.

## 🔍 Objective

To identify and quantify how features like square meters, neighborhood exclusivity, amenities (e.g., pool, yard, garage), and property history influence housing prices in Paris.

## 📂 Project Structure

- `paris_housing_regression.csv` – The dataset used for modeling  
- `ALY_6020_Assignment_2.ipynb` – Complete Python notebook (data cleaning, EDA, modeling)  
- `ALY_6020_Mod_2_Gangrade.pdf` – Final APA-style report  

## 🛠️ What’s Inside

- **Data Cleaning & Imputation**: Addressed missing values with thoughtful techniques (e.g., median imputation) and removed high-missing columns  
- **EDA & Hypothesis Testing**: Explored visual and statistical relationships between price and features like `hasPool`, `cityPartRange`, etc.  
- **Model Development**: Built an initial Multiple Linear Regression model using all variables, evaluated with R² and AIC  
- **Stepwise Feature Selection**: Refined model using forward selection based on AIC  
- **Bonus**: Also experimented with a **log-transformed model** to reduce skewness and improve interpretability  

## 📈 Key Findings

- **Square Meters** had the most significant and consistent positive influence on price  
- **Neighborhood exclusivity** and features like `hasPool` showed some influence, but not always statistically significant  
- The **stepwise model** yielded the same set of predictors as the initial model, confirming stability  

## 💡 Business Takeaways

- Focus on developing properties with **larger square footage**  
- Prioritize projects in **more exclusive neighborhoods**, even if marginally significant  
- Log transformation can offer an additional lens for smoother interpretation of pricing trends  

## 🧰 Tools & Libraries

- Python (Pandas, NumPy, Seaborn, Matplotlib)  
- Statsmodels  
- scikit-learn  
- MLxtend  

## 📝 Report

For detailed analysis, interpretations, and business recommendations, [read the full report here](ALY_6020_Mod_2_Gangrade.pdf).
