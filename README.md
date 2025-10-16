🍎 Nutrition Prediction using Machine Learning

This project predicts nutritional values such as calories, protein, carbohydrates, and fat based on given food data using various machine learning models.

📘 Project Overview

The goal is to develop and compare multiple machine learning pipelines — including Random Forest, Gradient Boosting, and Neural Networks — to predict multiple nutrition outputs simultaneously.

This can be used in **diet recommendation systems, health tracking apps, and fitness platforms**.

🧠 Technologies Used

* **Python**
* **Scikit-learn**
* **Keras / TensorFlow**
* **Pandas, NumPy**
* **Matplotlib / Seaborn**
* **Jupyter Notebook**


📂 Folder Structure

```
Nutrition_Prediction/
│
├── notebooks/               # Jupyter notebooks for model training
├── data/                    # Dataset used for training
├── models/                  # Saved ML and DL model files
├── README.md                # Project documentation
├── requirements.txt         # Python dependencies
└── .gitignore               # Files ignored by Git
```

---

📊 Model Summary

* **Random Forest Model**
* **Gradient Boosting MultiOutput Model**
* **Deep Learning Keras Model**

Each model was trained and evaluated using multi-output regression to predict calories, fat, protein, and carbs.

🚀 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/AarzooPatil/Nutrition_Prediction.git
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Open the main notebook:

   ```bash
   jupyter notebook notebooks/Code1.ipynb
   ```

---
📈 Dataset

The dataset (`Nutrition Ai Dataset.xlsx`) contains various food items with their nutritional compositions such as **calories, fat, protein, carbs, and fiber**.

---
🏁 Results

✅ Achieved accurate multi-output regression for nutritional prediction.
✅ Best-performing model: **Gradient Boosting Pipeline**
✅ Model stored as `.joblib` and `.keras` files for reuse.

---
✨ Author

👩‍💻 **Aarzoo Patil**
📂 *Final Year B.Tech (Artificial Intelligence)*
🔗 [GitHub Profile](https://github.com/AarzooPatil)

---

### 🔗 Project Link

👉 [https://github.com/AarzooPatil/Nutrition_Prediction]
