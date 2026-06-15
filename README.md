# 🏠 Housing Price Prediction

A Machine Learning project that predicts housing prices based on various housing features such as median income, house age, total rooms, population, and ocean proximity.

## 📌 Project Overview

This project uses a supervised machine learning model to estimate house prices from housing-related data. The model is trained on historical housing data and deployed using Python and Flask.

## 🚀 Features

- Data preprocessing and cleaning
- Feature engineering
- Categorical data encoding
- Machine Learning model training
- Pipeline creation for preprocessing and prediction
- House price prediction using trained model
- CSV input and output support

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Flask
- Google Collab

## 📂 Project Structure

```
housing_pricing_prediction/
│
├── main.py
├── main_new.py
├── input.csv
├── output.csv
├── housing1.csv
├── model.pkl
├── pipeline.pkl
├── README.md
└── requirements.txt
```

## 📊 Dataset Features

The dataset contains the following attributes:

- longitude
- latitude
- housing_median_age
- total_rooms
- total_bedrooms
- population
- households
- median_income
- ocean_proximity

### Target Variable

- median_house_value

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/vashush01/housing_pricing_prediction.git
```

Move into the project directory:

```bash
cd housing_pricing_prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## ▶️ Running the Project

Run the application:

```bash
python main.py
```

or

```bash
python main_new.py
```

## 📈 Model Training

The machine learning model is trained using Scikit-Learn pipelines that handle:

- Missing value treatment
- Feature scaling
- Categorical encoding
- Model fitting

The trained model is saved as:

```text
model.pkl
pipeline.pkl
```

## 📋 Example Input

```csv
longitude,latitude,housing_median_age,total_rooms,total_bedrooms,population,households,median_income,ocean_proximity
-122.23,37.88,41,880,129,322,126,8.3252,NEAR BAY
```

## 📋 Example Output

```csv
Predicted House Value
452600
```

## 🎯 Future Improvements

- Hyperparameter tuning
- Model deployment on cloud
- Interactive web interface
- Real-time predictions using API
- Advanced ensemble models

## 👨‍💻 Author

**Vashu Sharma**

- B.sc CS (Data Science)
- Machine Learning Enthusiast
- Python Developer

## 📜 License

This project is open source and available under the MIT License.
