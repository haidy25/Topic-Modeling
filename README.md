# Topic-Modeling Clustering with KMeans
This repository contains a Python script for clustering articles using the KMeans algorithm. 
The script preprocesses textual data, applies TF-IDF vectorization, performs KMeans clustering, and visualizes the clusters using PCA.

Dependencies

Python 3.x
nltk
pandas
numpy
scikit-learn
matplotlib


Usage
Clone the repository to your local machine.


Install the required dependencies using pip install -r requirements.txt.


Place your dataset (e.g., CSV file containing articles) in the root directory with the name articles1.csv.


Run the article_clustering.py script using Python.


After execution, the script will generate visualizations of the clusters and print the optimal number of clusters based on the squared-sum-error.


# Customization
Adjust the SAMPLE_SIZE variable to specify the number of samples to be used for clustering.

Modify the max_K variable to set the maximum number of clusters to consider during optimization.

You can customize the preprocessing steps, such as adding or removing stopwords, punctuation, or adjusting the lemmatization process.

# Output
The script will produce a plot showing the squared-sum-error against the number of clusters, aiding in determining the optimal K value.
Additionally, it generates a PCA plot visualizing the clusters formed by KMeans.

# Dataset
Ensure your dataset (e.g., articles1.csv) contains a column named content containing the text data to be clustered.

# License
This project is licensed under the MIT License - see the LICENSE file for details.

# Acknowledgments
This script was inspired by various tutorials and documentation from the NLTK and scikit-learn libraries.
