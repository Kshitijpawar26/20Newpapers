This project performs topic modeling and clustering on the 20 Newsgroups dataset using NLP techniques. It extracts latent topics with Latent Dirichlet Allocation (LDA) and groups similar documents using K-Means clustering. The project also visualizes high-dimensional text embeddings using t-SNE.
In simple words: The project reads 20 categories of news articles, finds hidden topics, groups similar articles, and visualizes them.

Importing Libraries:-numpy, pandas → data handling.
  matplotlib, seaborn → visualization.
  sklearn → machine learning (clustering, topic modeling).
  nltk → natural language processing (stopwords, lemmatization).
  re → regex (cleaning text).



Step-by-step flow:

Load dataset from sklearn.datasets.fetch_20newsgroups.
Preprocess text: lowercase, remove stopwords, lemmatize.
Vectorize text using TfidfVectorizer.
Apply LDA to extract topics.
Cluster documents with KMeans.
Visualize using TSNE for 2D plotting.
