Sentiment Analysis with spaCy

Overview
:This project focuses on sentiment analysis using spaCy, a popular natural language processing library in Python. The dataset used for analysis consists of 28,332 records of various Amazon products, with a primary focus on product reviews. The project aims to analyze and classify the sentiment of product reviews using spaCy's en_core_web_sm model.

Preprocessing
To prepare the data for sentiment analysis, the dataset was cleaned by retaining only the relevant column containing product reviews ('review.text'). A preprocessing function was created to tokenize and lemmatize the reviews, enhancing the quality of the input for sentiment analysis.

Sentiment Analysis Function
A sentiment analysis function was implemented to predict the sentiment of a product review. The analysis uses spaCy's en_core_web_sm model to assign a polarity score, with 1 indicating a very positive sentiment, -1 indicating a very negative sentiment, and 0 indicating a neutral sentiment. The results, including polarity scores and sentiments, were added to respective columns in the dataset.

Similarity Analysis
The project also includes a similarity analysis using spaCy's similarity function. Vectors for the processed reviews were obtained, and cosine similarity was used to compare the similarity of two chosen product reviews. A similarity score of 1 indicates high similarity, while a score of 0 suggests low similarity.

Observations and Improvements
Observations from the analysis include the need for a larger dataset to provide more diverse reviews for accurate sentiment analysis. Additionally, adjustments to the polarity score range and indicating the degree of positivity or negativity could enhance the analysis. Some inaccuracies may be resolved by using a larger spaCy model exposed to more data.
