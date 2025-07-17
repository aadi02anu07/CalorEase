# CalorEase 🔥

**CalorEase** is a machine learning-powered calorie predictor that estimates the number of calories burned during an exercise session based on personalized inputs such as heart rate, age, body temperature, and more. Built with Streamlit for interactivity and XGBoost for powerful predictions, CalorEase offers a lightweight, intuitive, and insightful fitness companion.

---

## 🚀 Features

- 🔢 **User Inputs**: Age, height, weight, duration of exercise, heart rate, and body temperature.
- 🤖 **Machine Learning Model**: Uses `XGBRegressor` for precise calorie burn predictions.
- 📊 **Standardization**: Data is preprocessed with `StandardScaler` for optimal performance.
- 🖼️ **Visualization**: Includes a UI illustration to enhance user experience.
- ✅ **Real-time Predictions**: Instant feedback on estimated calorie expenditure.

---

## 🧠 How It Works

1. **Data Processing**:
   - Loads data from `exercise.csv` (features) and `calories.csv` (target).
   - Scales the features using `StandardScaler`.

2. **Model Training**:
   - Trains an `XGBRegressor` model on the dataset.

3. **Prediction**:
   - Takes real-time user inputs and predicts the calories burned.

4. **Results Display**:
   - Streamlit displays the predicted calories with a clean UI.

---

## 📂 Dataset

- `exercise.csv` – Contains feature values like duration, heart rate, temperature, etc.
- `calories.csv` – Contains the actual calories burned for each record.

---

## 🛠️ Tech Stack

- **Frontend**: [Streamlit](https://streamlit.io/)
- **Machine Learning**: [XGBoost](https://xgboost.readthedocs.io/en/stable/), scikit-learn
- **Data Processing**: pandas, numpy
- **Visualization**: PIL for image rendering

---

## 📦 Installation

1. Clone the repository:

```bash
git clone https://github.com/aadi02anu07/CalorEase.git
cd CalorEase
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

> If `requirements.txt` is not present, install manually:

```bash
pip install streamlit pandas numpy scikit-learn xgboost pillow
```

3. Run the app:

```bash
streamlit run app.py
```

---

## 🖼️ Screenshot

![CalorEase Interface](./assets/example.png)  
*Clean and intuitive UI for accurate calorie estimation.*

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repo, open issues, or submit pull requests.

---


## 💡 Acknowledgements

- Data inspired from real-world fitness tracking datasets.
- Model implementation using [XGBoost](https://xgboost.ai/).

---

## 📬 Contact

For feedback or questions, reach out via [GitHub Issues](https://github.com/aadi02anu07/CalorEase/issues).
