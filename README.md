# 🌍 Disaster Tweet Classification using Machine Learning

## 📌 Project Overview
This project is a machine learning-based classification system that determines whether a given tweet is related to a disaster or not. It leverages Natural Language Processing (NLP) techniques and Logistic Regression to classify tweets. The project follows a structured approach, including data preprocessing, feature extraction, model training, and evaluation.

## ✨ Features
- **Text Cleaning**: Removes URLs, special characters, and converts text to lowercase.
- **TF-IDF Vectorization**: Converts text into numerical representations.
- **Logistic Regression Model**: Classifies tweets as disaster-related or not.
- **Performance Metrics**: Evaluates precision, recall, F1-score, and accuracy.
- **Feature Importance Visualization**: Identifies key words influencing predictions.
- **Tweet Prediction**: Classifies new tweets in real-time.
- **Submission File Creation**: Generates a CSV file for model predictions.

---

## 🚀 Steps to Clone and Run the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/sidharth0909/Disaster-Tweet-Classification.git
cd Disaster-Tweet-Classification
```

### 2️⃣ Create a Virtual Environment
```bash
python -m venv venv
```

### 3️⃣ Activate the Virtual Environment
#### On Windows:
```bash
venv\Scripts\activate
```
#### On macOS/Linux:
```bash
source venv/bin/activate
```

### 4️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 5️⃣ Run the Application
To preprocess the data and train the model:
```bash
python train.py
```
To classify new tweets:
```bash
python predict.py
```

---

## 📊 Model Training & Evaluation
The Logistic Regression model is trained using TF-IDF vectorized text features. The dataset is split into training and validation sets to optimize performance. The model achieves:

| Metric         | Score  |
|---------------|--------|
| Precision     | 80%    |
| Recall        | 78%    |
| F1-Score      | 79%    |
| Accuracy      | 80%    |

---

## 📈 Feature Importance Visualization
The project visualizes the most influential words in determining disaster-related tweets:
- **Top 10 Words Indicating Disaster Tweets** (e.g., earthquake, fire, flood)
- **Top 10 Words Indicating Non-Disaster Tweets** (e.g., happy, fun, sale)

---

## 📝 Sample Predictions
The model can classify new tweets as disaster-related or not:

```bash
Tweet: "There's a fire in the building!" --> Prediction: Disaster
Tweet: "I just got a new phone, and it's awesome!" --> Prediction: Not a Disaster
Tweet: "Earthquake near Los Angeles, stay safe everyone!" --> Prediction: Disaster
```
---

## 📜 License
This project is licensed under the MIT License.

## 📧 Contact
For questions or collaborations, reach out to **Sidharth Saholiya** at [your-email@example.com](mailto:your-email@example.com).

