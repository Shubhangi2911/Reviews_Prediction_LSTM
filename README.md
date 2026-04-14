# 🍽️ Restaurant Review Analysis System

---

## 🖥️ GUI APP

A Python-based desktop application that uses **Natural Language Processing (NLP)** to analyze customer feedback.
The system classifies reviews as **Positive or Negative** using a **BERT/LSTM model** and provides real-time statistical visualization for restaurant owners.

---

### 🚀 Features

* **Customer Review Portal:** Interactive GUI for customers to select food items and submit text reviews
* **Sentiment Analysis:** Uses BERT (Transformers) or LSTM to predict sentiment
* **Owner Dashboard:** Secure login system (**abc / 12345**)
* **Real-time Analytics:** Displays review counts and Pie Charts using Matplotlib
* **Database Integration:** Stores food-wise ratings (Good/Bad/Total) in MySQL

---

### 🛠️ Tech Stack

* GUI: Tkinter
* NLP Models: Hugging Face Transformers (BERT), TensorFlow/Keras (LSTM)
* Database: MySQL (PyMySQL)
* Visualization: Matplotlib
* Language: Python 3.x

---

### 📋 Prerequisites

* MySQL Server
* Python Libraries:

```
pip install torch transformers tensorflow keras pymysql matplotlib
```

---

### ⚙️ Database Configuration

Create database:

```
CREATE DATABASE rest_review_db;
```

Create table:

```
CREATE TABLE reviews_table (
    food VARCHAR(100) PRIMARY KEY,
    good_review INT DEFAULT 0,
    bad_review INT DEFAULT 0,
    customer INT DEFAULT 0
);
```

---

## 🌐 FLASK APP

A dual-interface sentiment analysis platform that utilizes **BERT and LSTM deep learning models** to predict customer satisfaction.
This project includes a **Flask Web App** and a **Tkinter Desktop App**.

---

### 🌟 Key Features

* **Hybrid NLP Engine:** BERT + LSTM support
* **Web Interface (Flask):** Quick sentiment prediction
* **Admin Desktop Portal (Tkinter):**

  * Secure login (**abc / 12345**)
  * Menu-based tracking (Idly, Biryani, etc.)
  * Pie chart analytics
* **Database Integration:** Real-time MySQL data storage

---

### 🛠️ Tech Stack

| Component     | Technology                       |
| ------------- | -------------------------------- |
| Language      | Python 3.8+                      |
| Deep Learning | PyTorch (BERT), TensorFlow/Keras |
| Web Framework | Flask                            |
| GUI Framework | Tkinter                          |
| Database      | MySQL (PyMySQL)                  |
| Visualization | Matplotlib                       |

---

## 📦 requirements.txt

```
pandas
tensorflow
matplotlib
seaborn
scikit-learn
flask
nltk
pymysql
cryptography
torch
transformers
torchvision
```

---
