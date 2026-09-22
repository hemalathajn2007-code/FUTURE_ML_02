# Support Ticket Classification & Prioritization

## 📌 Project Overview

The **Support Ticket Classification & Prioritization System** is a Machine Learning and Natural Language Processing (NLP) project that automatically analyzes customer support tickets.

The system processes customer support ticket descriptions and predicts the appropriate ticket category. This helps organize customer requests and reduce the amount of manual work required by support teams.

This project was developed as part of **Future Interns – Machine Learning Task 2 (2026)**.

---

## 🎯 Objectives

* Clean and preprocess customer support ticket data
* Apply Natural Language Processing techniques
* Convert text into numerical features using TF-IDF
* Classify support tickets into different categories
* Train a Machine Learning classification model
* Evaluate model performance
* Predict the category of new support tickets

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* NLTK
* Scikit-learn
* Matplotlib
* Seaborn
* Google Colab
* Jupyter Notebook

---

## 📊 Dataset

The project uses a **Customer Support Ticket Dataset** containing **8,469 records and 17 columns**.

Important columns include:

* Ticket ID
* Customer Name
* Customer Email
* Customer Age
* Product Purchased
* Ticket Type
* Ticket Subject
* Ticket Description
* Ticket Status
* Ticket Priority
* Ticket Channel
* Customer Satisfaction Rating

The main text fields are used for Natural Language Processing and ticket classification.

---

## 🔄 Project Workflow

```text
Customer Support Dataset
          ↓
     Data Loading
          ↓
   Data Preprocessing
          ↓
      Text Cleaning
          ↓
    TF-IDF Vectorization
          ↓
 Machine Learning Model
          ↓
    Model Evaluation
          ↓
   New Ticket Prediction
```

---

## 🧹 Data Preprocessing

The support ticket text is prepared before training the model.

The preprocessing process includes:

1. Converting text to lowercase
2. Removing unnecessary characters
3. Removing extra spaces
4. Cleaning the ticket text
5. Preparing the text for TF-IDF vectorization

---

## 🔤 TF-IDF Vectorization

TF-IDF stands for **Term Frequency–Inverse Document Frequency**.

It converts text into numerical values so that Machine Learning algorithms can process customer support messages.

For example:

```text
My laptop is not turning on
```

is converted into numerical features using TF-IDF.

---

## 🤖 Machine Learning Model

A Machine Learning classification model is trained using the processed ticket data.

The model learns patterns from previously classified tickets and predicts the category of a new customer support ticket.

The ticket categories in the dataset include:

* Billing inquiry
* Cancellation request
* Product inquiry
* Refund request
* Technical issue

---

## 📈 Model Evaluation

The model is evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Classification Report

The classification report provides performance information for each ticket category.

---

## 🔮 New Ticket Prediction

After training the model, a new customer support message can be tested.

### Input

```text
My laptop is not turning on and I need immediate help
```

### Output

```text
Predicted Ticket Type: Product inquiry
```

This demonstrates how the trained model can classify a previously unseen support message.

---

## 💡 Benefits

* Automates support ticket classification
* Reduces manual ticket sorting
* Helps organize customer requests
* Saves support team time
* Demonstrates practical NLP application
* Provides a foundation for automated customer support systems

---

## 📂 Project Structure

```text
Support-Ticket-Classification/
│
├── Support_Ticket_Classification.ipynb
├── requirements.txt
├── README.md
└── screenshots/
    ├── dataset.png
    ├── evaluation.png
    └── prediction.png
```

---

## ▶️ How to Run

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/Support-Ticket-Classification.git
```

### Step 2: Open the Notebook

Open:

```text
Support_Ticket_Classification.ipynb
```

The notebook can be opened using **Google Colab** or **Jupyter Notebook**.

### Step 3: Install Required Libraries

```bash
pip install -r requirements.txt
```

### Step 4: Add the Dataset

Upload the dataset to your Google Colab environment or place it in the project folder.

### Step 5: Run the Notebook

Run the notebook cells from top to bottom to reproduce the analysis and predictions.

---

## 🔮 Future Improvements

The project can be further improved by adding:

* Automatic priority prediction
* High / Medium / Low priority classification
* Advanced NLP models
* BERT-based classification
* Real-time ticket classification
* Web-based support dashboard
* Automatic ticket routing
* Chatbot integration
* Email integration

---

## 👩‍💻 Project Information

**Project:** Support Ticket Classification & Prioritization
**Program:** Future Interns – Machine Learning Task 2
**Year:** 2026
**Domain:** Machine Learning & Natural Language Processing

---

## ⭐ Conclusion

The **Support Ticket Classification & Prioritization System** demonstrates how Machine Learning and Natural Language Processing can be applied to customer support automation.

The system preprocesses customer ticket text, converts it into numerical features using TF-IDF, trains a Machine Learning classification model, evaluates its performance, and predicts the category of new suppor

