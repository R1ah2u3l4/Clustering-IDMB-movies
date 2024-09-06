# IMDb Movies Reviews Clustering
### Overview
Welcome to the IMDb Movies Reviews Clustering project! In this project, we utilize Natural Language Processing (NLP) techniques to cluster IMDb movie reviews. By analyzing and grouping reviews, we aim to discover patterns and insights within the dataset. We've employed various Python libraries and techniques, including NLTK, WordCloud, Flatten, FreqDist, CountVectorizer, Standard Scaling, and the K-Means clustering algorithm.

### Introduction
In today's age of data abundance, understanding and making sense of textual data is crucial. IMDb movie reviews provide a valuable dataset for analyzing and clustering opinions on movies. By implementing NLP techniques and clustering algorithms, we can group similar reviews together, aiding in various applications such as recommendation systems and sentiment analysis.

### Dependencies
To run this project, you will need the following Python libraries:

- NLTK
- WordCloud
- NumPy
- Pandas
- Scikit-Learn
- Matplotlib
- Seaborn

### Project Overview
- **Data Collection:** We start by collecting IMDb movie reviews data.
- **Data Preprocessing:** The raw text data goes through preprocessing steps, including tokenization, stemming/lemmatization, and stop-word removal.
- **Feature Extraction:** We utilize the CountVectorizer to convert text data into numerical features.
- **Scaling:** Standard scaling is applied to ensure all features have the same scale.
- **Clustering:** We employ the K-Means clustering algorithm to group similar reviews.
- **Evaluation:** The Elbow plot and Silhouette score help determine the optimal number of clusters.
- **Visualization:** We visualize the results with a dendrogram to better understand the hierarchical structure of the clusters.

### Data Preprocessing
**The preprocessing of IMDb movie reviews involves:**

- **Tokenization:** Splitting reviews into words or tokens.
- **Stop-word Removal:** Removing common words that don't provide significant meaning.
- **Stemming/Lemmatization:** Reducing words to their root form for consistency.
- **Flatten and Frequency Distribution:** Flattening token lists and computing term frequencies.
**Clustering**
We apply the **K-Means clustering** algorithm to group similar reviews together. The **Elbow plot** helps determine the optimal number of clusters, and the **Silhouette score** assesses the quality of clustering.

### Results and Visualization
The final results are visualized using a dendrogram, providing insights into the hierarchical structure of the clusters. This visualization aids in understanding how reviews are grouped together based on their content.

### Conclusion
By implementing NLP techniques and K-Means clustering, we've successfully clustered IMDb movie reviews, revealing hidden patterns and insights within the dataset. This project serves as a foundation for more advanced applications, such as movie recommendation systems or sentiment analysis.

### Contributing
Contributions to this project are welcome. If you would like to contribute, please follow these steps:

Fork the repository on GitHub
- 1) Create a new branch from the `main` branch to work on your changes.
- 2) Make your modifications and commit your changes.
- 3) Push your branch to your forked repository.
- 4) Open a pull request to the original repository, describing the changes you made.

**License**
This project is licensed under the GPU License.

**Contact**
If you have any questions or suggestions regarding this project, please feel free to contact me at [Email](132anaskhan@gmail.com)
