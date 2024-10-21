ADS509-FinalProject 
# Literary Analysis: Comparing Nonfiction and Fiction through Topic Modeling and Sentiment Analysis

### Team 3: Claire Bentzen, Tara Dehdari, Logan Van Dine

## Overview

This project explores thematic and linguistic differences between fiction and nonfiction texts, focusing on works that address significant societal issues such as gender roles and individual rights. Using text mining techniques such as topic modeling and sentiment analysis, we aim to uncover how each genre approaches similar themes differently. The team also looks to train multiple classification models to recognize when verbiage of a text belongs to either the fiction or nonfiction genre.

The dataset includes eight books: four fiction and four nonfiction works. The books were scraped from Project Gutenberg and processed for analysis. Our analysis involves text preprocessing, feature extraction, sentiment analysis, and topic modeling, with the goal of distinguishing between the styles and themes of fiction versus nonfiction.

### Fiction Books:
- *Pride and Prejudice* by Jane Austen
- *The Awakening* by Kate Chopin
- *North and South* by Elizabeth Gaskell
- *Wuthering Heights* by Emily Brontë

### Nonfiction Books:
- *A Vindication of the Rights of Woman* by Mary Wollstonecraft
- *Enfranchisement of Women* by Harriet Hardy Taylor Mill
- *On Liberty* by John Stuart Mill
- *The Subjection of Women* by John Stuart Mill

## Project Structure

The project contains the following key components:

- **Data Scraping**: Extracting full text from Project Gutenberg for the selected fiction and nonfiction books.
- **Data Cleaning and Tokenization**: Processing the raw text data by removing punctuation, converting to lowercase, and tokenizing into words.
- **Exploratory Data Analysis (EDA)**: Initial analysis of the texts, including calculating descriptive statistics (e.g., lexical diversity) and generating word clouds.
- **Text Classification**: Implementing machine learning models (Logistic Regression, Naive Bayes, and SVM) to classify the texts as fiction or nonfiction.
- **Topic Modeling**: Applying Non-Negative Matrix Factorization (NMF), Latent Semantic Analysis (LSA), and Latent Dirichlet Allocation (LDA) to uncover themes across the texts.
- **Sentiment Analysis**: Analyzing the sentiment of the texts by measuring positive, negative, and neutral tones using the VADER sentiment analyzer.

## Key Features
- **Text Classification**: Logistic Regression, Naive Bayes, and SVM models were applied, with Naive Bayes achieving the highest accuracy of 94.8%.
- **Topic Modeling**: Techniques like NMF, LSA, and LDA were used to uncover themes, with fiction focusing on dialogue and characters, while nonfiction centered on societal concepts.
- **Sentiment Analysis**: Fiction showed more emotional diversity, while nonfiction maintained a neutral tone.


## How to Use

### 1. Setup
Clone this repository and navigate to the project directory:

```bash
git clone https://github.com/lvandine44/ADS509-FinalProject.git
```

### 2. Install Dependencies

### 3. Run Repository

## Conclusion

The results demonstrate that fiction tends to focus more on dialogue and characters, while nonfiction addresses broader societal and philosophical issues. The models successfully classified the texts, and sentiment analysis revealed that fiction has a more diverse emotional tone than nonfiction. However, the team would like to further train the modeling prior to deployment in order to find a larger margin of successful predictions.

