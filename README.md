# Data-Mining-Final-Projet

This project builds and evaluates a machine learning model to classify whether a news headline is clickbait or not. Using an SVC (Support Vector Classifier), the model learns patterns from a labeled dataset of over 30,000 headlines to distinguish between sensational and standard titles. It then uses this model to analyze the prevalence of clickbait in New York Times articles from 1998-2004.

**Project Structure**
.

├── README.md

├── model.ipynb                       # Jupyter notebook with full preprocessing, training, and evaluation

├── clickbait_data.csv                # Main labeled dataset of headlines (clickbait vs. not)

├── 1998.csv                          # NYT article data from 1998

├── 1999.csv

├── 2000.csv

├── 2001.csv

├── 2002.csv

├── 2003.csv

└── 2004.csv


**Dataset**

The clickbait_data.csv file contains:

headline: The original headline text.
label: 1 for clickbait, 0 for non-clickbait.
Headlines come from a range of sources and time periods (1998–2004), ensuring a broad mix of writing styles.

**Model Performance**

The trained SVC model achieves an accuracy of ~95%.
