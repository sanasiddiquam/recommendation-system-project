# 🎬 Bollywood Movie Recommendation System

A **content-based movie recommendation system** that suggests Bollywood movies similar to a user-selected movie using Natural Language Processing (NLP) techniques.

---

## 📌 Project Overview

With the rapid growth of online streaming platforms, users often struggle to discover movies that match their interests. This project addresses that challenge by building a **content-based recommendation system** that recommends Bollywood movies based on movie metadata such as genre, overview, director, and cast.

The system does **not require user ratings** and relies purely on movie content similarity.

---

## 🎯 Objectives

- Build a content-based recommendation system for Bollywood movies  
- Suggest movies similar to a selected movie  
- Use NLP techniques for text representation and similarity computation  
- Provide an explainable and scalable recommendation approach  

---

## 🧠 Approach

### 🔹 Recommendation Technique
- **Content-Based Filtering**

### 🔹 Text Representation
- **TF-IDF (Term Frequency–Inverse Document Frequency)**

### 🔹 Similarity Metric
- **Cosine Similarity**

---

## 📊 Dataset Details

- **Format:** CSV  
- **Total Movies:** 2199  
- **Features Used:**
  - Genre
  - Overview
  - Director
  - Cast

The `year` column was excluded as it does not contribute to content similarity.

---

## 🛠️ Technologies & Tools

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Jupyter Notebook  
- ipywidgets  

---

## ⚙️ How It Works

1. Load the Bollywood movie dataset  
2. Clean and preprocess the data  
3. Combine important text features into a single column  
4. Convert text into numerical vectors using TF-IDF  
5. Compute cosine similarity between movies  
6. Recommend top similar movies based on user input  

---

## 💡 Example Usage

- User inputs a movie name (e.g., *Jawan*)
- The system returns a list of similar Bollywood movies
- Recommendations are based on textual similarity of movie content

---

## ✅ Key Features

- No user ratings required  
- Simple and explainable recommendations  
- Efficient and scalable  
- Interactive movie input using widgets  

---

## ⚠️ Limitations

- No personalization based on user preferences  
- Dependent on the quality of movie metadata  
- Cannot adapt to changing user interests  

---

## 🚀 Future Improvements

- Hybrid recommendation system  
- User rating and feedback integration  
- Web application deployment  
- Use of advanced embeddings (Word2Vec, BERT, etc.)

---

## 📜 Ethical Considerations

- No personal or sensitive user data is used  
- Recommendations are assistive, not prescriptive  
- Dataset bias may influence recommendations  

---

## 📂 Project Structure

