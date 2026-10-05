# AI-Disaster-Early-Warning-System
AI Disaster Early Warning System is a Flask-based Machine Learning web application that analyzes rainfall, water level, and wind speed to predict disaster risk. Using a Decision Tree Classifier, it categorizes conditions into Low, Medium, and High risk and provides warning messages and safety instructions.
# AI Disaster Early Warning System

📌 About the Project

The **AI Disaster Early Warning System** is a Flask-based Machine Learning web application designed to predict environmental disaster risk based on parameters such as **rainfall, water level, and wind speed**.

The system uses a **Decision Tree Classifier** to classify the given environmental conditions into **Low, Medium, or High Risk** and provides appropriate warning messages and safety instructions.

---

## 🎯 Objectives

* To analyze environmental conditions using Machine Learning.
* To use rainfall, water level, and wind speed as input parameters.
* To train a Decision Tree classification model.
* To predict the level of disaster risk.
* To provide warning messages and safety instructions through a web interface.

---

## 🛠️ Technologies Used

* **Python**
* **Flask**
* **Pandas**
* **Scikit-learn**
* **HTML**
* **CSS**

---

## 🤖 Machine Learning Algorithm

### Decision Tree Classifier

A **Decision Tree Classifier** is used to classify environmental conditions into different risk categories.

The model uses:

**Input Features:**

* Rainfall
* Water Level
* Wind Speed

**Output:**

* Low Risk
* Medium Risk
* High Risk

---

## 📊 Dataset

The project uses a **sample disaster dataset created within the project**.

### Dataset Features

| Feature     | Description             |
| ----------- | ----------------------- |
| Rainfall    | Rainfall measurement    |
| Water Level | Water level measurement |
| Wind Speed  | Wind speed measurement  |
| Risk        | Disaster risk category  |

The dataset contains **15 sample records**, divided into Low, Medium, and High risk categories.

---

## ⚙️ How the System Works

```text
User enters environmental data
            ↓
      Flask Web Application
            ↓
      Input Data Processing
            ↓
     Decision Tree Classifier
            ↓
       Risk Prediction
            ↓
   Low / Medium / High Risk
            ↓
 Warning Message & Safety Instructions
```

---

## 📁 Project Structure

```text
AI-Disaster-Early-Warning-System/
│
├── app.py
├── model.py
├── requirements.txt
│
├── templates/
│   └── index.html
│
└── static/
    └── style.css
```

---

## 💻 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/AI-Disaster-Early-Warning-System.git
```

### 2. Open the Project Folder

```bash
cd AI-Disaster-Early-Warning-System
```

### 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

The project requires:

```text
Flask
Pandas
Scikit-learn
```

---

## ▶️ Run the Application

Run the following command:

```bash
python app.py
```

After starting the Flask server, open the application in your web browser using the local address shown by Flask.

---

## 🖥️ Features

* 🌧️ Rainfall input
* 🌊 Water-level input
* 💨 Wind-speed input
* 🤖 Machine Learning prediction
* ⚠️ Low, Medium, and High risk classification
* 📢 Warning messages
* 🛡️ Safety instructions
* 🌐 Flask-based web interface

---

## 📈 Results

The system accepts environmental parameters and predicts the corresponding disaster risk.

### Example

**Input:**

```text
Rainfall: 100
Water Level: 55
Wind Speed: 30
```

**Output:**

```text
HIGH RISK
```

The system then displays an appropriate warning and safety instructions.

> **Note:** The current project uses a small sample dataset and does not include a separate accuracy/performance evaluation.

---

## ⚠️ Limitations

* The dataset contains only a small number of sample records.
* The dataset is created within the project and is not real-time data.
* Real-time weather and environmental sensors are not currently connected.
* The current implementation does not calculate model accuracy.

---

## 🚀 Future Scope

The project can be further improved by:

* Integrating real-time weather APIs.
* Using a larger real-world disaster dataset.
* Connecting IoT sensors for automatic data collection.
* Adding a database for historical environmental data.
* Adding model performance evaluation.
* Comparing multiple Machine Learning algorithms.
* Adding SMS/email emergency notifications.
* Developing a mobile application.
* Adding real-time location-based disaster monitoring.

---

## 📚 References

* Python Documentation
* Flask Documentation
* Pandas Documentation
* Scikit-learn Documentation
* Decision Tree Classification – Scikit-learn

---

## 👩‍💻 Author

**Asmitha Mohan Raj**

B.Sc. Information Technology
MVLU
Academic Year: 2026–2027

---

## 📄 License

This project is created for **educational and academic purposes**.
