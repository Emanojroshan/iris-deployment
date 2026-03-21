# 🌸 Iris Flower Classification Web Application

A production-ready Machine Learning web application that predicts the species of an Iris flower based on user-provided morphological features. This project demonstrates end-to-end ML workflow including model training, serialization, and deployment using a Flask-based web interface.

---

## 🚀 Overview

This application allows users to input key flower measurements:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

Based on these inputs, the system predicts the Iris species:
**Setosa, Versicolor, or Virginica** in real-time.

---

## ✨ Key Features

* 🔍 Real-time prediction using trained ML model
* 🌐 Web-based interface built with Flask
* ⚡ Lightweight and fast response system
* 🧠 Pre-trained and serialized model (`.pkl`)
* 📦 Ready for deployment (includes Procfile)

---

## 🛠️ Technology Stack

| Category         | Technology Used  |
| ---------------- | ---------------- |
| Programming      | Python           |
| Backend          | Flask            |
| Machine Learning | Scikit-learn     |
| Frontend         | HTML, CSS        |
| Deployment       | Render / Railway |

---

## 📊 Machine Learning Model

* **Algorithm Used:** Logistic Regression *(update if different)*
* **Dataset:** Iris Dataset (UCI Machine Learning Repository)
* **Model Accuracy:** ~95%
* **Model Serialization:** Pickle (`iris_model.pkl`)

---

## 📂 Project Structure

```
iris-deployment/
│
├── app.py                  # Main Flask application
├── iris_model.pkl          # Trained ML model
├── requirements.txt        # Project dependencies
├── Procfile                # Deployment configuration
│
├── templates/              # HTML templates
│   ├── home.html
│   └── result.html
│
└── static/                 # Static assets (CSS)
    └── style.css
```

---

## ▶️ Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Emanojroshan/iris-deployment.git
cd iris-deployment
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Application

```bash
python app.py
```

### 4️⃣ Access the App

Open your browser and navigate to:

```
http://127.0.0.1:5000/
```

---

## 🌐 Live Demo

🚀 *Deployed Application:*
(Add your live deployment link here)

---

## 📸 Application Preview

https://github.com/Emanojroshan/iris-deployment/blob/b17d23ca7b7d1203b083a86489c772adde7f1a35/screenshots/output.mp4

---

## 🔒 Input Handling

* Accepts numerical inputs for all features
* Designed for structured user input
* Can be extended with validation and error handling

---

## 📈 Future Enhancements

* Add prediction confidence scores
* Improve UI/UX with modern frontend frameworks
* Integrate REST API endpoints
* Dockerize the application
* Deploy using CI/CD pipelines

---

## 👨‍💻 Author

**Manoj Roshan**
🔗 GitHub: https://github.com/Emanojroshan

---

## ⭐ Acknowledgements

* UCI Machine Learning Repository (Iris Dataset)
* Scikit-learn Documentation
