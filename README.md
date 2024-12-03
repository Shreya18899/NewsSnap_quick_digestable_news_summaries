**NewsSnap - Quick, digestable news summaries
**
Summarization app performing two kinds of summarization
  - Extractive Summarization
  - Abstractive Summarization

Models
1. Classification
  - Logistic Regression for classification with TF-IDF embeddings
  - BERT for classification
2. Summarization
  - TextRank for Extractive summarization
  - Text-to-Text Transformer for Abstractive summarization
  - BART for Abstractive summarization
  - LLaMA 3.2 for Abstractive summarization

Data Source
The dataset comprises 2,225 news articles sourced from the BBC website, categorized into five topics: Business, Entertainment, Politics, Sports, and Tech. This publicly available dataset, hosted at mlg.ucd.ie/datasets/bbc.html, serves as the foundation for our analysis. We also explored NewsAPI as an additional potential source for expanding the dataset.
The dataset is used for two primary purposes:
Text classification into the five predefined categories.
Generating concise summaries of the articles using advanced Large Language Models (LLMs).
