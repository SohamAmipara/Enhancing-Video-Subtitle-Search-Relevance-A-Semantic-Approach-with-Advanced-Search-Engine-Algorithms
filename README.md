# Enhancing Video Subtitle Search Relevance: A Semantic Approach with Advanced Search Engine Algorithms

## Overview

In the fast-evolving landscape of digital content, effective search engines play a pivotal role in connecting users with relevant information. For platforms like Google, providing a seamless and accurate search experience is paramount. This project focuses on improving the search relevance for video subtitles, enhancing the accessibility of video content.

## Objective

The primary objective of this project is to develop an advanced search engine algorithm that efficiently retrieves subtitles based on user queries, with a specific emphasis on subtitle content. By leveraging natural language processing (NLP) and machine learning (ML) techniques, the aim is to enhance the relevance and accuracy of search results.

## Core Features

- **Ingesting Documents**: Read and preprocess subtitle documents, including decoding and cleaning steps.
- **Text Vectorization**: Experiment with Bag-of-Words (BOW), TF-IDF, and BERT-based SentenceTransformers for text vectorization.
- **Document Chunking**: Divide large documents into smaller, more manageable chunks to handle information loss effectively.
- **Embedding Storage**: Store embeddings in a ChromaDB database for efficient retrieval.
- **Document Retrieval**: Calculate similarity scores between document embeddings and user search query embeddings using cosine similarity.
- **User Interface**: Use Streamlit to create a user-friendly interface for querying subtitles.

## Installation

To clone this project, run the following command:

```
git clone https://github.com/SohamAmipara/Enhancing-Video-Subtitle-Search-Relevance-A-Semantic-Approach-with-Advanced-Search-Engine-Algorithms.git
```

### Requirements

- Python (version 3.x)
- Libraries:
  - pandas
  - numpy
  - scikit-learn
  - joblib
  - nltk
  - BeautifulSoup
  - sqlite3
  - streamlit

You can install the required Python libraries using pip:

```
pip install pandas numpy scikit-learn joblib nltk BeautifulSoup4 streamlit
```

Additionally, you might need to download NLTK data:

```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')
```

## Usage

1. **Ingesting Documents**: Execute the necessary scripts to ingest and preprocess subtitle documents.
2. **Text Vectorization**: Experiment with different text vectorization techniques as described in the project statement.
3. **Document Chunking**: Implement document chunking to handle large documents effectively.
4. **Embedding Storage**: Store embeddings in a ChromaDB database for efficient retrieval.
5. **Document Retrieval**: Develop a user interface using Streamlit for querying subtitles based on user input.


## Connect with Me
Let's connect and continue the conversation! Feel free to reach out if you have any questions or suggestions. Happy exploring! 🌟🚀
- [LinkedIn](https://www.linkedin.com/in/soham-amipara/)
- [Twitter](https://twitter.com/SB_Amipara/)
- [Medium](https://medium.com/@soham.amipara91/)

🚀 Happy Learning! 📊

Thank You!!
