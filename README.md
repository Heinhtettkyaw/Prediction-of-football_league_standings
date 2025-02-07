# ⚽ Football Match Outcome Prediction  

## 📌 Overview  
Predicting football match results isn't just guesswork—it’s data science! This project leverages the Poisson Distribution Model to forecast match outcomes (Win, Loss, Draw) based on historical match data. By analyzing past performance, we estimate goal probabilities and predict the most likely results.

✅ **Runs on Google Colab – No setup required!**  

## 🚀 Key Features  
- ✅ Predicts match outcomes using **Poisson distribution**  
- ✅ Evaluates performance based on **Win/Loss/Draw** (not exact scores)  
- ✅ Uses **Confusion Matrix, Accuracy, Precision, Recall, and mAP**  
- ✅ Trained on **17+ years of football match data**  

---

## 📊 How Poisson Distribution Works in This Project  
The **Poisson distribution** models the number of goals each team is likely to score, assuming:  
- Goals scored by a team follow a **Poisson process**.  
- The probability of a team scoring `x` goals depends on its attacking strength and the opponent’s defensive strength.  
- Using this, we predict match results and determine outcomes (Win, Loss, Draw).  

---

## 📂 Dataset Information  
- 📅 **Seasons Covered:** `2004` to `2024`  
- 📊 **Data Source:** `results.csv` ,`Matches_left.xlsx`,`Points_table_2025`

### **Example Dataset Format:**  
| Season  | Home Team | Away Team | Home Goals | Away Goals | Result |  
|---------|----------|----------|------------|------------|--------|  
| 2021-22 | Man City | Man Utd  | 2          | 1          | H      |  
| 2021-22 | Chelsea  | Arsenal  | 1          | 1          | D      |  

- `H` = Home Win  
- `A` = Away Win  
- `D` = Draw  

- **Training Data:** `2004-05 to 2023-24`  
- **Test Data:** `2024-2025 ` & League Standings  

---

## 🚀 How to Run in Google Colab  
No local setup required! Just open the notebook in Google Colab and run the cells.  

### 1️⃣ Open the Colab Notebook  
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/football-prediction/blob/main/football_prediction.ipynb)  

### 2️⃣ Upload the Dataset (`results.csv`,`Matches_left.xlsx`,`Points_table_2025`)  
Inside Colab, upload `results.csv`,`Matches_left.xlsx`,`Points_table_2025` by running:  
```python
from google.colab import files
uploaded = files.upload()
```
### 3️⃣ Run the Model
Simply run all cells in the notebook.

---
## 📈 Model Evaluation Metrics

### The model is evaluated using:

✅ Accuracy – Percentage of correct predictions.

📊 Confusion Matrix – Breakdown of Home Wins (H), Away Wins (A), and Draws (D).

🎯 Precision & Recall – Measures prediction quality.


📌 Mean Average Precision (mAP) – Overall model performance.

---

## 📜 License

This project is licensed under the MIT License.

---
## 👤 Author

**Hein Htet Kyaw**
