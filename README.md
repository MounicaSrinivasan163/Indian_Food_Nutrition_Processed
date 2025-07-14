# Indian Food Nutrition Analysis

This project uses the `Indian_Food_Nutrition_Processed.csv` dataset to analyze the nutritional composition of Indian food items, grouped by food category, subcategory, and macro-/micro-nutrient values.

---

## 📁 Dataset Overview

The dataset includes nutrient information (energy, protein, fat, vitamins, and minerals) for various Indian foods. It’s structured for nutrition planning, health-based analysis, and clustering based on food types.

---

## 📊 Column Description Table

| Column Name         | Description                                               | Type        |
|---------------------|-----------------------------------------------------------|-------------|
| Dish Name           | Name of the Indian dish                                   | Categorical |
| Calories (kcal)     | Energy provided by the dish in kilocalories               | Continuous  |
| Carbohydrates (g)   | Amount of carbohydrates in grams                          | Continuous  |
| Protein (g)         | Amount of protein in grams                                | Continuous  |
| Fats (g)            | Total fat content in grams                                | Continuous  |
| Free Sugar (g)      | Amount of free/added sugars in grams                      | Continuous  |
| Fibre (g)           | Dietary fiber content in grams                            | Continuous  |
| Sodium (mg)         | Sodium content in milligrams                              | Continuous  |
| Calcium (mg)        | Calcium content in milligrams                             | Continuous  |
| Iron (mg)           | Iron content in milligrams                                | Continuous  |
| Vitamin C (mg)      | Vitamin C content in milligrams                           | Continuous  |
| Folate (µg)         | Folate (Vitamin B9) content in micrograms                 | Continuous  |


---

## 💡 Use Cases

- Identify top foods for **high protein** or **low fat** diets
- Recommend **calcium- and iron-rich** Indian meals
- Build **nutritional scoring systems** for food ranking
- Group foods by **macronutrient profiles** using clustering
- Detect **vitamin-rich foods** for immunity or eye health
- Filter **low-sodium options** for hypertension-friendly diets
- Create **interactive dashboards** for meal planning apps
- Analyze **nutritional gaps** in specific food categories
- Apply **PCA or feature selection** for dimensionality reduction
- Generate **meal suggestions** based on dietary restrictions

---

## 📌 10 Medium-Level Pandas Analysis Questions

1. List the top 10 dishes with the highest protein content.
2. Find the average calories per dish.
3. Which dish has the highest calcium content?
4. Count how many dishes have more than 20g of carbohydrates.
5. What is the average sodium content across all dishes?
6. Group the dishes by high (>10g) vs low (≤10g) fat content and calculate the average protein.
7. Find dishes with both low sugar (<5g) and high fibre (>5g).
8. Calculate the correlation between calories and fats.
9. Identify dishes that are high in iron (>10mg) and vitamin C (>20mg).
10. Create a new column `calorie_density = Calories / (Protein + Carbohydrates + Fats)` and sort the top 5 dishes.


---

## 🚀 5 Complex-Level Pandas Analysis Questions

1. Normalize all continuous nutrient columns and perform KMeans clustering to group similar dishes nutritionally.
2. Apply PCA (Principal Component Analysis) to reduce dimensions and visualize nutritional profiles in 2D.
3. Create a custom “Health Score” using a weighted formula:  
   `score = 0.4*Fibre + 0.3*Protein - 0.2*Free Sugar - 0.1*Sodium`
   and rank dishes.
4. Group dishes by calorie range (e.g., <200, 200–400, >400) and compute average values of all other nutrients.
5. Build a pairplot using seaborn to visualize relationships between all nutrients and identify outliers.

---


