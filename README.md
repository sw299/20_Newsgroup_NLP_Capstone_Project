# 20_Newsgroup_NLP_Capstone_Project

## Exploring and modelling the 20 Newsgroups data set
### Dataset description:
* the 20 Newsgroups data set is a collection of approximately 19K newsgroup documents
* The original form of this dataset is at this page: http://qwone.com/~jason/20Newsgroups/

### Inspiration:
* Classifying text documents into various news groups

### Sections:
* Preparing full, train and test data set
* Data cleaning: removing stopwords, filter out short words, stemming and lemmatization
* Vectorization: tf_idf
* Comparison Naive_Bayes performance between applying stemming and lemmatization
* Exploring different ngrams in the vectorizer step
* Exploring various ML algorithms: SVC, Logistic regression, Random forest, and Gradient boosting
* Inspecting the top words calcualted by Naive_bayes
* Text extraction: lsa, lda, and nnmf
* Unsupervised learning with LSA: KMeans and GaussianMixture
* Text summarization: tf_idf, calculate similarity, rank sentences based on scores
* Word2vec

### Conclusion:
* As applying stemming or lemmatization to the text did not alter the machine learning model accuracy significantly
* Model results did not changed much as using different ngrams in the vectorization step
* Various supervised machine learning models were studied and Naive_Bayes seems worked best interms of model accuracy and efficiency
* The top words calucated by Naive_Bayes model seems highly correlated with their corresponding news groups
* Text extraction were performed using LSA, LDA, and NNMF, and they showed clearly different performace for different topics
* Unsupervised learning: KMeans and GaussianMixtureModel were explorated in this project and both of them are not promising for identifying news groups
* Text summarization techniques were used and it seems works well for select the most representative sentence
* Word2vec has worked successfully for finding similar and dissimilar words

![Picture1](https://user-images.githubusercontent.com/46268295/71007515-bf0d3900-20ac-11ea-8d2f-9e9385b1a68f.png)
