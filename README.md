# ML-Project-Crop-Recommendation
# 🌾 Crop Recommendation System

This project is a machine learning-based web application that recommends the most suitable crop to cultivate based on various environmental and soil parameters.

## 🚀 Features

- Predicts the best crop using inputs like:
  - Nitrogen (N)
  - Phosphorus (P)
  - Potassium (K)
  - Temperature (°C)
  - Humidity (%)
  - pH
  - Rainfall (mm)
- Machine learning model trained on real agricultural data
- Web interface built using Flask
- Scalable and easily extendable for future improvements

## 📊 Dataset

The model is trained on a crop recommendation dataset with labeled data containing soil and weather features along with the recommended crop.

- Features:
  - `N`, `P`, `K`: soil nutrients
  - `temperature`: in Celsius
  - `humidity`: in percentage
  - `ph`: acidity/alkalinity of the soil
  - `rainfall`: in mm

## 🧠 Machine Learning

- Algorithms used: `RandomForestClassifier` (best-performing model)
- Preprocessing:
  - `MinMaxScaler` for normalization
  - `StandardScaler` for standardization
- Model Evaluation: Accuracy Score

## 🛠 Tech Stack

- Python
- Scikit-learn
- Flask (for web app)
- HTML(for frontend)

## 📦 How to Run

### 1. Clone the repository
```bash
git clone https://github.com/KaustukJaiswal/ML-Project-Crop-Recommendation
cd crop-recommendation
2. Install dependencies
bash
Copy code
3. Run the Flask app
bash
Copy code
python app.py
4. Open in Browser
Visit http://127.0.0.1:5000 to access the crop recommendation tool.

📁 Folder Structure
cpp
Copy code
├── app.py
├── model/
│   ├── crop_model.pkl
│   ├── scaler.pkl
│   └── stand_scalar.pkl
├── templates/
│   └── index.html
├── static/
│   └── style.css
├── dataset/
│   └── crop_data.csv
└── README.md
