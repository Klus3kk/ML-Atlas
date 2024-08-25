# Term Frequency-Inverse Document Frequency (TF-IDF)

## Overview

Term Frequency-Inverse Document Frequency (TF-IDF) is a statistical measure used to evaluate the importance of a word in a document relative to a collection of documents (corpus). It adjusts for the frequency of the word and the number of documents containing the word.

## Where is it Used?

- **Text Mining:** Identifies important terms in documents for further analysis.
- **Search Engines:** Improves the relevance of search results.
- **Document Classification:** Enhances the accuracy of text classification models.

## How Does it Work?

TF-IDF combines two metrics:
- **Term Frequency (TF):** Measures how often a word appears in a document.
- **Inverse Document Frequency (IDF):** Measures how important a word is by considering its frequency across all documents.

The formula is:
\[ \text{TF-IDF}(t, d) = \text{TF}(t, d) \times \text{IDF}(t) \]

Where:
- \( \text{TF}(t, d) \) is the term frequency of term \( t \) in document \( d \).
- \( \text{IDF}(t) \) is the inverse document frequency of term \( t \).
