# 📱 Samsung Mobile Recommendation System

An AI/ML project that helps users find suitable Samsung smartphones based on their budget, intended use, and personal preferences.

## 📌 About the Project

Choosing a smartphone can be difficult because different models offer different features and prices. This project explores a Python-based recommendation system that matches user preferences with Samsung smartphone data.

The current notebook uses a content-based scoring approach to rank affordable models according to camera, battery, and performance preferences.

## 🎯 Project Objectives

- Recommend suitable Samsung smartphones based on user requirements.
- Consider the user's maximum budget in Indian Rupees (INR).
- Analyze camera, battery, and performance preferences.
- Practice data processing and machine learning techniques.

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn

## ✨ Features

- User-defined smartphone budget.
- Primary-use selection, such as gaming, photography, study, or battery life.
- Camera, battery, and performance importance ratings from 1 to 5.
- Feature scaling using `MinMaxScaler`.
- Weighted preference scoring using NumPy.
- Filtering of models that exceed the user's budget.

## ⚙️ How It Works

1. Load the smartphone dataset.
2. Validate the required dataset columns.
3. Group smartphone records by model.
4. Normalize camera, battery, and performance features.
5. Collect user preferences.
6. Calculate weighted content-based scores.
7. Filter models according to the user's budget.
8. Rank affordable models for recommendation.

*Note: The recommendation output and ranking steps must be completed in the notebook before the full workflow is functional.*

## 📂 Repository Contents

- `samsung.ipynb` — Google Colab notebook containing the Python code.
- `README.md` — Project documentation.
- `.gitignore` — Files and folders excluded from Git tracking.

## 📊 Dataset Requirements

The notebook expects a CSV file named:

`samsung_mobile_recommendation_50_samples.csv`

The dataset should contain these columns:

- `User_ID`
- `Samsung_Model`
- `Approx_Budget_INR`
- `Primary_Use`
- `Camera_Preference_Score`
- `Battery_Preference_Score`
- `Performance_Preference_Score`
- `User_Rating_1_to_5`

The dataset is not included in this repository yet. Add it if you have permission to share it.

## 🚀 How to Run the Project

1. Open `samsung.ipynb` in this repository.
2. Open the notebook in Google Colab.
3. Upload the required CSV dataset.
4. Install any missing dependencies.
5. Run the notebook cells in order.

## 🔮 Future Improvements

- Complete the recommendation output and display the top-ranked smartphones.
- Implement and evaluate collaborative filtering if user-rating data supports it.
- Add a Streamlit web interface.
- Include more smartphone specifications and reliable price data.
- Evaluate recommendation quality using appropriate metrics.

## 👨‍💻 Author

GitHub: [akshukla2789-source](https://github.com/akshukla2789-source)

---

⭐ If you find this project useful, consider starring the repository.
