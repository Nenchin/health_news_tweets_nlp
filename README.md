# health_news_tweets_nlp

This project aims to cluster health headline tweets and then classify the clusters using natural language processing (NLP) techniques. The project is implemented in Python and uses the following libraries:

NLTK: for text preprocessing and natural language processing tasks
- Scikit-learn: for machine learning algorithms
- Pandas and Glob: for data manipulation and analysis
- Matplotlib and Plotly: for data visualization
- Imblearn: to handle data imbalance

Steps involved in the project:

 ![Project Pipeline](https://github.com/Nenchin/health_news_tweets_nlp/assets/99443495/94854d70-5241-4266-b0b9-6381ab0e4030)
   
Collect the data:
- The data sets are in the Health-Tweets folder

Data preprocessing:
- Clean and preprocess the tweets by removing stop words, punctuation, and other irrelevant characters.
    
Feature engineering:
- Extract features from the tweets using the TF-IDF vectorizer.

Cluster the data:
- Cluster the tweets using a clustering algorithm to cluster the data into groups.

Create the target variables for classification:
- For each tweet, assign it to the cluster that it belongs to.

Train a classifier:
- Train a classification model to predict the cluster labels of new tweets.

Evaluate the classifier:
- Evaluate the classifier on a held-out test set.
    
To run the project:

- Clone this repository to your local machine.
- Install the required Python libraries.
- Open the Jupyter Notebook health_news_tweets_clustering_classification.ipynb file and follow the instructions.
- Once you have finished running the notebook, you will have a trained classification model that can be used to predict the cluster labels of new tweets.

Example use case:

The trained classification model can be used to identify tweets that are discussing specific health topics, such as cancer, heart disease, or diabetes. This information can be used to track public sentiment about these topics, detect misinformation, identify emerging health trends, or target users with relevant health information.

Additional notes:

The number of clusters used in the clustering step can be tuned to achieve better results.
Different classification algorithms can be evaluated to find the one that performs best on the given dataset.
The trained classification model can be deployed in a production environment to make predictions on new tweets in real time.

Contributions:

Contributions to this project are welcome. Please feel free to fork the repository and submit a pull request with your changes.
