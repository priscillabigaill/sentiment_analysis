# Sentiment Analysis Algorithm Benchmarking  

[![Documentation](https://img.shields.io/badge/Report-Read-blue?logo=microsoft-word)](https://drive.google.com/file/d/1r7osbLJ7ZBkMASbXUtOhME_GEOy1cNjd/view?usp=sharing)

### Overview  
This repository explores the comparative performance of text processing algorithms, **TF-IDF** and **Word2Vec**, for sentiment analysis in e-commerce datasets. The project evaluates the efficiency and effectiveness of these algorithms across various metrics to provide insights into their use cases.  

### Features  
- **Implemented Algorithms**:  
  - TF-IDF  
  - Word2Vec (Skip-Gram model)  

- **Evaluation Metrics**:  
  - Word embedding creation time  
  - Model training time  
  - Memory and virtual memory usage  
  - Classification metrics: Accuracy, Precision, Recall, F1-Score  

- **Classification Models**:  
  - LinearSVC (Support Vector Classifier)  
  - Gaussian Naive Bayes  

### Requirements  
- Programming Languages: Python  
- Libraries/Modules Used:  
  - `pandas`, `numpy`, `re`, `psutil`, `time`  
  - Visualization: `matplotlib`, `seaborn`, `wordcloud`  
  - NLP: `nltk`, `sklearn`, `VaderSentiment`  

### How to Run  
1. Clone the repository:  
   ```bash
   git clone https://github.com/priscillabigaill/sentiment_analysis.git
   cd sentiment_analysis
   ```

2. Install Dependencies:   
   ```bash
   pip install -r requirements.txt
   ```  

3. Run the Script:  
   ```bash
   python main.py
   ```  
