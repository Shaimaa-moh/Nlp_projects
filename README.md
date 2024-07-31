# Natural Language Processing  ✍️🌐
NLP is a field of artificial intelligence that focuses on the interaction between computers and humans through natural language. 
It involves various tasks such as text analysis, language translation, sentiment analysis, and information retrieval.
# Preprocessing steps
- Translate the english words and franko to arabic
- Remove arabic noise like diacritics and punctuation
- Remove elongation and numbers , meaningless emojis 
- Replace the meaningful emojis to their text meaning in arabic
- Apply ar-corrector to check the mispelling of the word 
- Tokenize the text
- Remove the stop words
- Check all characters are arabic
- Do the stemming and lemitization
# TF-IDF Transformation
Term Frequency-Inverse Document Frequency (TF-IDF) is a statistical measure used to evaluate the importance of a word in a document relative to a collection of documents (corpus).
The TF-IDF value increases proportionally to the number of times a word appears in a document but is offset by the frequency of the word in the corpus, helping to filter out common terms.
# Similarity Detection
Using TF-IDF vectors, we can measure the similarity between documents by computing the cosine similarity between their vectors.
Cosine similarity is a metric used to measure how similar two documents are, irrespective of their size.
By converting text descriptions to TF-IDF vectors and computing similarities, we can match text queries to relevant information.
# Sentiment Analysis 😊😢
Sentiment analysis involves determining the sentiment or emotional tone of a piece of text. 
This can be done by training models on labeled data where the sentiment (positive, negative, neutral) is known. TF-IDF vectors are used to represent the text for model training and prediction.

