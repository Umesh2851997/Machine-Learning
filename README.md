# Netflix TV & Movies show Clustering 

## **Project Summary -**

This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine. In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset. Innitially we start with understanding the data set, then we clean the data to make analysis ready. I then prepare the data for creating clusters by various parameters wherein we remove stop words, white spaces numbers etc so that we can get important words and based on that we shall form clusters.later I have used the silhoute method and kmeans elbow method to find optimal number of clusters and built recommender system by cosine similarity and recommended top 5 movies.


## **Problem Statement**

Netflix, as of 2022-Q2, stands as the foremost global provider of online streaming services, boasting a subscriber base exceeding 220 million. It is imperative for the platform to adeptly categorize its hosted shows to heighten user satisfaction and mitigate subscriber attrition.This project aims to discern similarities and differences among Netflix shows by creating clusters. These clusters can then be utilized to furnish users with personalized show recommendations aligned with their preferences. The primary objective is to categorize Netflix shows into distinct clusters, ensuring that shows within a cluster share similarities while those in separate clusters exhibit dissimilarity.

## **Conclusion**

Our aim was to cluster shows for a content-based recommender system recommending 5 shows to users based on viewing history. Starting with 7787 records and 11 attributes, we focused on Netflix's content. Analysis revealed more movies than TV shows, with a growing U.S. collection. We selected six attributes for clustering, transformed into a 9000-feature TFIDF vector, and reduced dimensions to 2500 using PCA. K-Means and Agglomerative clustering resulted in 7 and 5 optimal clusters, respectively. We built a content-based recommender system using cosine similarity, offering personalized suggestions by analyzing the user's watched shows, presenting 5 top-notch recommendations to explore.
