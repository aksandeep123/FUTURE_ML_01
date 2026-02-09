# Project Report: Support Ticket Classification

## 1. Problem Statement
Customer support teams often receive a high volume of tickets. Manually categorization is time-consuming and error-prone. The goal of this project is to automate the classification of support tickets based on their text content using Machine Learning.

## 2. Methodology
1.  **Data Collection**: Created a synthetic dataset representing common customer issues (Billing, Technical, etc.).
2.  **Preprocessing**:
    -   Lowercasing
    -   Removing punctuation and special characters
    -   Tokenization
    -   Stopword removal
3.  **Feature Engineering**: Used **TF-IDF (Term Frequency-Inverse Document Frequency)** to convert text into numerical vectors.
4.  **Model Selection**: Chose **Multinomial Naive Bayes**, which is effective for text classification tasks.
5.  **Evaluation**: Split data into training (80%) and testing (20%) sets and evaluated using Accuracy, Precision, Recall, and F1-score.

## 3. Tools & Technologies
-   **Language**: Python
-   **Libraries**: Pandas, Scikit-learn, NLTK, Matplotlib, Seaborn
-   **Environment**: Jupyter Notebook

## 4. Results
-   The model successfully classified sample tickets into correct categories.
-   Confusion matrix visualization showed distinct diagonal dominance, indicating good performance on the synthetic set.

## 5. Conclusion
This project demonstrates how NLP techniques can be applied to solve real-world business problems. The automated classification system can significantly reduce the workload on support agents.
