Game of Thrones Text Processing and Word2Vec Analysis:
This project demonstrates text processing and word embedding techniques using the Gensim Word2Vec model, along with dimensionality reduction using PCA and visualization using Plotly. 
The text data is extracted from the Game of Thrones (GOT) series files
Features--->
Text Preprocessing:
The text from GOT files is split into sentences using NLTK's sent_tokenize.
Each sentence is further tokenized and cleaned using Gensim's simple_preprocess, which:
Converts text to lowercase.
Removes punctuation and stopwords.
Keeps words with a minimum length of 2 characters.
Word2Vec Model:
A Word2Vec model is trained using the preprocessed sentences to generate numerical vector representations of words.
These word embeddings capture the semantic relationships between words.
Dimensionality Reduction:
Principal Component Analysis (PCA) is applied to reduce the high-dimensional Word2Vec embeddings into 2D space for visualization.
Visualization:
The reduced embeddings are plotted in a 2D scatter plot using Plotly, an interactive visualization library.
Future Improvements--->
Experiment with different Word2Vec parameters (e.g., vector_size, window, min_count) to improve embeddings.
Explore advanced dimensionality reduction techniques like t-SNE or UMAP for better visualization.
Extend the project to perform tasks like text classification or sentiment analysis
