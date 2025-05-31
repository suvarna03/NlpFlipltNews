# NlpFlipltNews

**Context:**
The Gurugram-based company ‘FlipItNews’ aims to revolutionize the way Indians perceive finance, business, and capital market investment, by giving it a boost through artificial intelligence (AI) and machine learning (ML). They’re on a mission to reinvent financial literacy for Indians, where financial awareness is driven by smart information discovery and engagement with peers. Through their smart content discovery and contextual engagement, the company is simplifying business, finance, and investment for millennials and first-time investors

**Objective:**
The goal of this project is to use a bunch of news articles extracted from the companies’ internal database and categorize them into several categories like politics, technology, sports, business and entertainment based on their content. Use natural language processing and create & compare at least three different models.

**Concepts Tested:**
 * 1: Natural Language Processing
 * 2:Text Processing
 * 3:Stopwords, Tokenization, Lemmatization
 4:Bag of Words, TF-IDF
 5: Multi-class Classification

 **Implementation:**
   1. Importing the libraries & Reading the data file.
   2. Exploring the dataset.
    a: Shape of the dataset
    b: News articles per category
  3. Processing the Textual Data i.e. the news articles.
    a: Removing the non-letters
    b: Tokenizing the text
    c: Removing stopwords
    d: Lemmatization
  4. Encoding and Transforming the data.
    a: Encoding the target variable
    b: Bag of Words
    c: TF-IDF
    d: Train-Test Split
  5. Model Training & Evaluation (30 points)
    1: Simple Approach
      a: Naive Bayes
    2: Functionalized Code
      a: Decision Tree
      b: Nearest Neighbors
      c: Random Forest
     
**Insights**
  * Naive Bayes performs excellently with high ROC AUC (0.999) and generalizes well (small gap between train and test accuracy), indicating robustness and less overfitting.
  * KNN performs slightly lower on all metrics, and could be sensitive to data scaling and neighborhood choice. Still a solid performer.
  * Random Forest has the highest overall performance, perfect train accuracy (possible overfitting), and best general test scores (accuracy, precision, recall, F1).

**Recommendation**
* Random Forest is the top performer overall in terms of predictive power.
* Naive Bayes is a close second, simpler and faster, suitable if interpretability and speed matter.
* KNN is decent but not optimal here; may benefit from tuning k or scaling
