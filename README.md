# 📝 Automatic Answer Checker  

This project is an **AI-based answer evaluation system** that compares student responses with predefined answers and generates **automated scoring and feedback**. It uses **fuzzy string matching (FuzzyWuzzy), keyword extraction, and grammar analysis** to determine similarity and accuracy.  

---

## 📌 Table of Contents  
- [Introduction](#introduction)  
- [Problem Statement](#problem-statement)  
- [Importance of This Project](#importance-of-this-project)  
- [Methodology](#methodology)  
- [Evaluation Criteria](#evaluation-criteria)  
- [Results and Performance](#results-and-performance)  
- [Conclusion](#conclusion)  

---

## 📖 Introduction  
Manual answer checking is **time-consuming, inconsistent, and prone to human bias**. This project automates the process using **text analysis, similarity measurement, and keyword extraction** to evaluate written answers effectively.  

---

## ❌ Problem Statement  
- **Manual checking is slow & inconsistent**  
- **Bias in human evaluation**  
- **Lack of instant feedback for students**  

This system provides **fast, unbiased, and automated answer evaluation** using **AI-based text similarity techniques**.  

---

## 🌍 Importance of This Project  
✅ **Automated Grading**: Reduces **manual efforts**  
✅ **Instant Feedback**: Provides **real-time scoring**  
✅ **Reduces Human Bias**: Ensures **consistent evaluation**  

---

## ⚙️ Methodology  
1️⃣ **Input Handling**:  
   - Users **select a subject** and **enter their answer**  
   - Predefined answers are **loaded from an Excel sheet**  

2️⃣ **Text Processing & Similarity Matching**:  
   - **Tokenization & Cleaning**: Removes stopwords and punctuation  
   - **Keyword Extraction**: Identifies important terms from model answers  
   - **Fuzzy Matching**: Uses `FuzzyWuzzy` for **text similarity comparison**  

3️⃣ **Grammar & Keyword Analysis**:  
   - Grammar checked against **English word dictionary**  
   - **Keyword order and relevance** are assessed  

4️⃣ **Score Calculation**:  
   - Based on **similarity factor, grammar, keyword presence, and order accuracy**  

---

## 📊 Evaluation Criteria  
| Metric                    | Description |  
|---------------------------|-------------|  
| **Similarity Factor (FR)** | Measures **text similarity** with model answers |  
| **Grammar Accuracy (GM)** | Checks **correctness of sentence structure** |  
| **Keyword Presence (KT)** | Evaluates if **important terms are used** |  
| **Keyword Order (CM)**    | Ensures **logical flow of key terms** |  

🔢 **Final Score Calculation**:  
\[
Score = \frac{FR}{(FR_{max} \times 100)} + (KTF \times KT) + (CMF \times CM) + (GMF \times GM)
\]  

---

## 📈 Results and Performance  
✅ **Fast & Accurate**: Provides **real-time grading**  
✅ **Keyword-Based Evaluation**: Detects **important concepts**  
✅ **Grammar Checking**: Ensures **language correctness**  

---

## 🏁 Conclusion  
This **Automatic Answer Checker** provides an **efficient, unbiased, and instant grading system** using **AI and text similarity techniques**. It can be integrated into **educational platforms for online exams and assignments**.  
