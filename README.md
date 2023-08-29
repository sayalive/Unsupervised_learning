# Unsupervised_learning
##### Project name: Netflix Movies and Tv Shows Clustering
### Project summary:

The entertainment industry is highly competitive, and success depends on various factors such as genre, rating, production budget, cast, and more. A study was conducted to analyze the factors that impact the popularity of movies and TV shows on Netflix. The study utilized a dataset with approximately 12 variables to cluster movies and TV shows based on their popularity and audience preferences.

To begin the analysis, data wrangling was performed, which involved handling missing values and checking unique values. The study found that there were 2389 missing values for the 'director' column, 718 for the 'cast' column, 507 for the 'country' column, and 10 for the 'date_added' column. These missing values were eliminated by dropping the corresponding rows.

Next, exploratory data analysis (EDA) was conducted. The number of movies on Netflix exceeds the number of TV shows, with 5372 movies and 2398 TV shows currently available on the platform. The most common rating for TV shows is TV-MA, indicating a significant proportion of adult-oriented TV shows on Netflix. Moreover, TV-MA is also the most common rating for both movies and TV shows, suggesting that Netflix's content predominantly caters to an adult demographic, focusing on mature and potentially controversial themes.

The years 2017 and 2018 witnessed the highest number of movie releases, while 2020 had the highest number of TV show releases. The growth rate of movie releases on Netflix is significantly higher than that of TV shows. Since 2015, there has been a substantial increase in the number of movies and TV show episodes available on Netflix. However, there has been a noticeable decline in the production of movies and TV show episodes after 2020, indicating that Netflix has prioritized expanding its movie content over TV shows.

Based on the countplot, it can be observed that Netflix adds the highest number of movies and TV shows between October and January. This period seems to be the busiest time of the year for Netflix in terms of introducing new content to its platform. The United States has the highest number of content offerings on Netflix, followed by India, which boasts the highest number of movies.

To cluster the shows, the study focused on six key attributes: director, cast, country, genre, rating, and description. These attributes were transformed into a 10,000-feature TFIDF vectorization, and Principal Component Analysis (PCA) was utilized to reduce the components to 3000, capturing more than 80% of the variance.

Two clustering algorithms, namely K-Means and Agglomerative clustering, were employed to group the shows. K-Means identified 5 as the optimal number of clusters, while Agglomerative clustering suggested 7 clusters. These clusters were visualized using a dendrogram.

Finally, a content-based recommender system was developed using the similarity matrix obtained through cosine similarity. This system offers personalized recommendations based on the user's watched shows, providing them with 10 top-notch suggestions to explore.

In conclusion, the study highlighted significant trends in the Netflix dataset, including the contrasting growth rates of movies and TV shows, the busiest period for adding new content, and the content demographics. Through clustering and a content-based recommender system, personalized recommendations based on the user's viewing history were generated. This study provides valuable insights into the factors influencing the popularity of movies and TV shows on Netflix, establishing a basis for further research and analysis.

# Objective:
In this project, you are required to do

1.Exploratory Data Analysis.

2.Understanding what type content is available in different countries.

3.Is Netflix has increasingly focusing on TV rather than movies in recent years.

4.Clustering similar content by matching text-based features.
