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

1. Find the top 10 food items with the highest protein content.
2. Compute average fat content per `Food_Group`.
3. Identify the food item with the highest calcium content.
4. Check correlation between carbohydrate and energy.
5. Find top 5 fiber-rich foods in the "Pulses" subgroup.
6. Count number of food items per `Sub_Group`.
7. Compute average `Vitamin_A_mcg` for each `Food_Group`.
8. Filter foods with sodium < 100 mg and fat < 5g.
9. Group by `Sub_Group` and compute mean `Protein_g`.
10. Find top 5 foods with highest selenium content.

---

## 🚀 5 Complex-Level Pandas Analysis Questions

1. Rank all foods within each `Food_Group` by `Vitamin_B12_mcg`.
2. Use multi-index (`Food_Group`, `Sub_Group`) to calculate average of Ca, Mg, and P.
3. Perform PCA on nutritional columns to reduce dimensionality and cluster food types.
4. Apply KMeans clustering to group food items based on nutrients.
5. Create a composite “Nutri Score” using weighted sum of Protein, Fiber, and Vitamins.

---


