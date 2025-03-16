# 🚗 EV Range Predictor - Using Machine Learning

## 📌 Overview

This project is an **EV Range Predictor** that estimates the driving range of an electric vehicle (EV) based on key parameters such as acceleration, top speed, battery capacity, and drive type. The model is trained using **machine learning** techniques to provide accurate range predictions.

## 📊 Dataset

The dataset used for training the model contains information on various electric vehicles, including:

- **Acceleration (0-100 km/h)**
- **Top Speed**
- **Battery Capacity (kWh)**
- **Seats**
- **Drive Type (FWD, RWD, AWD)**
- **Range (km) - Target Variable**

## 🏗 Tech Stack

- **Python** 🐍
- **Flask** 🌐 (for web deployment)
- **Machine Learning (Sklearn, Pandas, NumPy)** 🤖
- **Matplotlib & Seaborn** 📊 (for visualization)
- **HTML, CSS, JavaScript** 🎨 (for UI)

## 🚀 Features

✅ Predicts EV range based on input parameters
✅ User-friendly web interface
✅ Data visualization for insights
✅ Model trained using real-world EV data

## 📷 Screenshots

### App Interface
## 📸 Visualizations
![Visualization 1](https://github.com/anshuman-kar/EV-Range-Predictor---Using-Machine-Learning/blob/main/Screenshot%202025-03-16%20223606.png)
![Visualization 2](https://github.com/anshuman-kar/EV-Range-Predictor---Using-Machine-Learning/blob/main/Screenshot%202025-03-16%20223630.png)



### Prediction Result



## ⚙️ How to Run

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/yourusername/EV-Range-Predictor.git
   cd EV-Range-Predictor
   ```
2. **Install Dependencies:**
   ```sh
   pip install -r requirements.txt
   ```
3. **Run the Application:**
   ```sh
   python app.py
   ```
4. **Open in Browser:**
   ```
   http://127.0.0.1:5000/
   ```

## 🔥 Model Training

The machine learning model is trained using regression techniques on the EV dataset. The trained model is saved as `model.pkl` and is used for predictions in the Flask application.

## 📁 Project Structure

```
📂 EV-Range-Predictor
│── 📁 static        # CSS, JS, Images
│── 📁 templates     # HTML files
│── 📄 app.py        # Flask application
│── 📄 model.ipynb   # Jupyter notebook for model training
│── 📄 model.pkl     # Trained machine learning model
│── 📄 evdataset.csv  # Dataset used for training
│── 📄 requirements.txt  # Dependencies
│── 📄 README.md      # Project documentation
```

## 📌 Future Improvements

- Improve model accuracy with more features
- Deploy on a cloud platform
- Enhance UI/UX
