# Spotify_ML_Project-DSCI303

This is our final project for DSCI 303 - Machine Learning for Data Science. 

## Abstract
Music forms an integral part of our everyday lives. From 20th century jazz and rock beats, to modern hip-hop and rap, people listen to and create all types of music. In this paper, we analyze a publicly available dataset of ~160k songs to predict their popularity and classify them into the era in which they were released. We use inherent features of those songs, such as energy, acousticness, etc to train several supervised and unsupervised learning methods. 
Supervised models such as Support Vector Machines, K-Nearest Neighbors and Random Forest are used for “era” and popularity classification. Unsupervised models such as KMeans and Gaussian Mixture Models were used to cluster the data and we then compared the predicted clusters to actual era and popularity clusters to test whether inherent nature of songs can reveal information about their popularity or age.
We find that KNN worked best when predicting non-quantiled popularity classes, while Random Forest worked best when predicting eras. Upon careful inspection, these results are more promising than they intuitively appear which we discuss further.

