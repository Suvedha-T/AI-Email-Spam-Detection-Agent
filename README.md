# AI Email Spam Detection Agent

## Overview

This project implements an **AI-based spam detection system** that classifies messages as **Spam** or **Ham (Not Spam)** using Natural Language Processing (NLP) and Machine Learning.

The system processes text messages, converts them into numerical features using **TF-IDF vectorization**, and applies a **Logistic Regression classifier** to detect spam messages.

This project demonstrates the complete **machine learning pipeline**, including preprocessing, model training, evaluation, and deployment of a prediction agent.

---

## Features

* Text preprocessing using NLP techniques
* Stopword removal and text cleaning
* TF-IDF feature extraction
* Logistic Regression classifier
* Spam detection agent function
* Performance evaluation metrics
* Visualization of results (graphs and heatmaps)

---

## Dataset

The project uses the **SMS Spam Collection Dataset**, which contains labeled messages categorized as spam or ham.

Dataset characteristics:

* Total messages: **5572**
* Classes:

  * **Ham** (legitimate message)
  * **Spam** (unwanted message)

---

## Machine Learning Pipeline

The workflow of the project follows these steps:

1. **Load Dataset**
2. **Text Preprocessing**

   * Lowercasing
   * Removing numbers
   * Removing punctuation
   * Removing stopwords
3. **Feature Extraction**

   * TF-IDF Vectorization
4. **Model Training**

   * Logistic Regression classifier
5. **Model Evaluation**

   * Accuracy
   * Precision
   * Recall
   * F1 Score
   * ROC-AUC
6. **Prediction Agent**

   * Classifies new messages as Spam or Ham

---

## Model Performance

Typical performance metrics for the trained model:

| Metric    | Score |
| --------- | ----- |
| Accuracy  | ~0.97 |
| Precision | High  |
| Recall    | High  |
| F1 Score  | High  |

---

## Visualizations

The project generates the following visualizations:

* Performance metrics bar chart
* Confusion matrix heatmap
* ROC curve

These help evaluate the effectiveness of the spam detection model.

---

## Project Structure

```
AI-Email-Spam-Detection-Agent
│
├── data
│
├── notebooks
│   └── spam_detection_ai_agent.ipynb
│
├── src
│
├── models
│
├── outputs
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

## Installation

Clone the repository:

```
git clone https://github.com/yourusername/AI-Email-Spam-Detection-Agent.git
```

Navigate to the project folder:

```
cd AI-Email-Spam-Detection-Agent
```

Install dependencies:

```
pip install -r requirements.txt
```

---

## Example Prediction

Input message:

```
Congratulations! You have won a free gift. Click here!
```

Output:

```
Prediction: SPAM
Confidence Score: 0.98
```

---

## Technologies Used

* Python
* Scikit-learn
* Pandas
* NumPy
* NLTK
* Matplotlib
* Seaborn

---

## Future Improvements

Possible extensions of the project:

* Deep learning models (LSTM / Transformers)
* Web interface for real-time prediction
* Email server integration
* API deployment for spam filtering systems

---

## Author

**Suvedha T**

B.E. Computer Science and Engineering
Specialization: Artificial Intelligence and Machine Learning

---

## License

This project is licensed under the **MIT License**.
