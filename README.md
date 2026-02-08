# Banking Intent Classification using NLP

This project is a simple Natural Language Processing (NLP) application that classifies banking-related customer queries into predefined categories using machine learning.

The system predicts the intent of a user’s request based on text input, making it suitable for basic banking chatbot or customer support automation scenarios.

---

##  Project Description

- Loads banking queries from a CSV dataset
- Cleans text data by removing Turkish stopwords
- Converts text into numerical features using **CountVectorizer**
- Trains a **Random Forest Classifier**
- Predicts the intent of a new user-entered query

---

##  Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- CountVectorizer  
- Random Forest Classifier  

---

##  Dataset Structure

The dataset file (`banka.csv`) contains the following columns:

| Column Name | Description |
|------------|------------|
| `sorgu` | Customer banking request text |
| `label` | Numerical label representing the request category |

---

##  How the System Works

1. The dataset is loaded and required columns are selected.
2. Turkish stopwords are removed from customer queries.
3. Text data is vectorized using **CountVectorizer**.
4. The dataset is split into training and testing sets.
5. A **Random Forest Classifier** is trained on the data.
6. The model predicts the category of a new user query entered at runtime.

---

##  Usage

Run the script and enter a banking request when prompted:

```text
Yapmak İstediniz İşlemi Giriniz.
