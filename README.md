# Analyzing-Sentiment-in-Reviews-TF-IDF-Matrix-and-UMAP-Visualization

Generate a labelled 1000-row text dataset using OpenAI’s ChatGPT. This dataset should
contain positive and negative reviews of something (e.g, you could ask ChatGPT to generate
positive/ negative movie reviews, or positive/ negative smartphone reviews, etc) You might
have to run your prompt multiple times to compile a 1000-row dataset as ChatGPT won’t give
you 1000 reviews in one go. Name this dataset Reviews.csv

Using Python, convert Reviews.csv to a TF-IDF matrix and visualize that matrix using UMAP
dimensionality reduction technique.
How does tuning TF-IDF hyperparameters ‘ngram_range’ and ‘min_df’ affect the TF-IDF matrix
and the subsequent visualization? 
How does tuning UMAP hyperparameters ‘n_neighbors’ and ‘min_dist’ affect the
visualization? 
Can you identify two clusters of reviews based on positive and negative sentiments? If yes,
can you identify any sub-clusters within these two clusters? If yes, what do the sub-clusters
tell us? 
