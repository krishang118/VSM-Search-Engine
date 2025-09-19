# VSM Search Engine: A NLP and Vector Space Model-based System

This system is a Vector Space Model (VSM) based search engine over a small document corpus. Each document and query is represented as a vector of TF-IDF weights, and results are ranked using cosine similarity.

The system supports advanced NLP preprocessing techniques to improve retrieval quality.

## Features

### Core Functionalities
- Vector Space Model (VSM): Documents and queries are converted into vectors using TF-IDF, enabling relevance-based ranking.
- Cosine Similarity: Measures the similarity between the query vector and document vectors for ranking.
 
### Additional Modifications
These enhancements improve the search quality and query handling:

- Stopword Removal: Common English stopwords are removed during preprocessing.
- Lemmatization: Words are lemmatized using NLTK’s WordNetLemmatizer for normalized forms.
- Synonym Expansion: Query terms are expanded using WordNet synonyms to increase recall.
- Spell Correction: Misspelled query terms are corrected using string similarity.
- Highlighting Results: Matching terms in document snippets are highlighted in the output.
 
## How to Run

1. Make sure Python 3.8+ is installed.
2. Clone this repository on your local machine.
3. Unzip the Corpus ZIP file, and make sure the extracted `Corpus` folder lies in the main project directory.
4. Install the required dependencies: 
```bash
pip install nltk
```
5. Open and run the cells of the `VSM Search Engine.ipynb` Jupyter Notebook file.

## Contributing

Contributions are welcome!

## License

Distributed under the MIT License.
