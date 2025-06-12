# 🚗 Car Price Predictor

A web application built using **Flask**, **HTML/CSS**, and **Machine Learning** that predicts the resale price of a car based on details like company, model, year, fuel type, and kilometers driven.

---

## 📌 Features

- Predicts car resale price using a trained **Linear Regression** model
- Clean and interactive user interface
- Responsive form with input validation
- Animated card UI and hover ripple background effect

---

## 🧠 Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript  
- **Backend**: Python, Flask  
- **ML Model**: Linear Regression (`scikit-learn`)  
- **Dataset**: Cleaned Car Dataset (CSV)

---

## 📁 Project Structure

```
car-price-predictor/
├── static/
│   └── style.css              # Custom styles for UI
├── templates/
│   └── index.html             # HTML frontend
├── LinearRegressionModel.pkl  # Trained ML model
├── Cleaned_Car_data.csv       # Cleaned dataset
├── app.py                     # Flask backend app
└── README.md                  # Project readme
```

---

## 🚀 How to Run the Project

### ✅ Step 1: Clone the Repository

```bash
git clone https://github.com/yourusername/car-price-predictor.git
cd car-price-predictor
```

### ✅ Step 2: Set Up a Virtual Environment

```bash
python -m venv venv
# Activate the virtual environment
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate
```

### ✅ Step 3: Install Dependencies

If you have a `requirements.txt` file:

```bash
pip install -r requirements.txt
```

If not, manually install:

```bash
pip install flask pandas numpy scikit-learn
```

### ✅ Step 4: Run the Application

```bash
python app.py
```

Open your browser and go to:

```
http://127.0.0.1:5000/
```

---

## 🧪 Model Details

- **Model Type**: Linear Regression
- **Trained On**: Cleaned car resale dataset
- **Features Used**:
  - Company
  - Car Name
  - Year
  - Fuel Type
  - Kilometers Driven
- **Target Variable**: Selling Price

---

## 📸 Screenshots

![demo](https://github.com/user-attachments/assets/5aa61900-cea4-4e11-8c44-ed5682f16f38)

![sample-prediction](https://github.com/user-attachments/assets/917ad49b-98cd-41c4-bd66-e95a3bb374f6)

## 🛠 Improvements to Consider

- [ ] Add dropdown auto-filters by company
- [ ] Display model accuracy metrics
- [ ] Upload dataset feature for bulk predictions
- [ ] Save prediction logs for user reference
- [ ] Deploy on platforms like Render or Heroku

---

## 📃 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

---

## 🙌 Acknowledgments

- Flask documentation: https://flask.palletsprojects.com/
- scikit-learn documentation: https://scikit-learn.org/
- UI Gradient Inspiration: [UI Gradients](https://uigradients.com/)
