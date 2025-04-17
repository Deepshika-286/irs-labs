# NLP mini projects
This repository contains a collection of simple NLP and Machine Learning mini-projects done over the span of 5 weeks. Each week focuses on a different core concept ranging from classification to clustering, similarity measures, and text preprocessing techniques.

## Week 1 – Naive Bayes for Sentiment Classification
A basic sentiment classifier was created using the Naive Bayes algorithm.

The dataset includes simple text reviews labeled as positive or negative.

The text was vectorized using CountVectorizer, and the model was trained and tested using MultinomialNB.

Example prediction:
"worst movie" → negative

## Week 2 – Support Vector Machine (SVM)
Demonstrated binary classification using Support Vector Machine with a linear kernel.

Synthetic 2D data points were used to classify two classes.

Visualized the SVM decision boundary using matplotlib.

Explored how SVM separates classes with a maximum margin.

## Week 3 – Dendrogram and Clustering
Applied Hierarchical Clustering using scipy's linkage and dendrogram.

Used sample 2D coordinates and visualized cluster formation using a dendrogram.

The ward method was used to calculate the linkage matrix.

## Week 4 – Jaccard Distance for Text Similarity
Implemented a custom function to calculate Jaccard similarity between two strings.

Jaccard similarity = size of intersection ÷ size of union.

Example:
"sis" and "sas" → Jaccard Score: 0.33

## Week 5 – Text Preprocessing (Stemming & Stop Words)
🔹 Stemming
Used PorterStemmer from nltk to stem words to their root form.

Example:

programmer → programm

programming → program

🔹 Stop Word Removal
Used spaCy to tokenize and filter out stop words from a sentence.

Example input:
"ram is a student in anurag university..."

Output:
['ram', 'student', 'anurag', 'university', 'gets', 'explore', 'laboratories', 'free', 'times']

## Technologies & Libraries Used
- Python 3

- pandas, numpy

- scikit-learn

- matplotlib, scipy

- nltk, spacy

## Notes
All code snippets are beginner-friendly and can be run in Jupyter Notebook or any Python environment.

These are ideal for educational or practice purposes in NLP and ML basics.
### Hope this helps! Happy Learning!!
