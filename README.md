# Fundamentals-of-AI-ML

## 🚀 What This Project Does
---

This project:

* Loads a real-world SMS dataset
* Preprocesses text data
* Converts text into numerical features using TF-IDF
* Trains a Naive Bayes model
* Evaluates model performance
* Saves the trained model
* Predicts whether a message is spam or not
## 🧠 How It Works
---
* Text messages are cleaned and processed
* TF-IDF converts text → numerical vectors
* Model learns patterns from spam vs normal messages
* New messages are classified based on learned patterns
## 🛠️ Tech Stack
---
* Python
* Pandas
* Scikit-learn
* NumPy
* Pickle (for model saving)
## 📦 Setup Instructions
---
Follow these steps to run the project locally:

* 1. Clone the Repository
git clone https://github.com/Vallabh-Singhal/Fundamentals-of-AI-ML.git
cd Fundamentals-of-AI-ML
* 2. Install Dependencies
pip install pandas scikit-learn numpy
* 3. Run the Script
1. Save your code in a file, for example:
   
spam_classifier.py

2. Then run:

python spam_classifier.py

## ▶️ Output
---
The program will:
* Print model accuracy
* Show classification report
* Pick a random SMS from dataset
* Predict whether it is spam or not

Example:

Accuracy: 0.97

Random Message: Congratulations! You've won a prize...

Prediction: Spam
## 📂 Project Structure
---

Fundamentals-of-AI-ML

│── spam_classifier.py                 # Main ML script

│── spam_model.pkl                     # Saved trained model

│── vectorizer.pkl                     # Saved TF-IDF vectorizer

│── README.md                          # Project documentation

## 💡 How to Use for Custom Input
---

* You can modify the script to test your own message:

print(predict_spam("Free entry in a contest! Win now!"))

## 📊 Evaluation Metrics
---
* Accuracy Score
* Precision
* Recall
* F1-score

## 🔮 Future Improvements
---
* Add GUI (Tkinter / Web App)
* Deploy using Flask or Streamlit
* Use advanced models (SVM, Deep Learning)
* Improve preprocessing (stemming, lemmatization)
