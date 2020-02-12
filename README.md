# IBM Recommendation Engine
 
 ## Purpose
 Generate recommendations for new articles for users engaging on IBM's platform.
 
 ## File Descriptions
 -data folder: contains .csv files used in scripts
 -Recommendations_with_IBM_Final.ipynb: Jupyter notebook used for running analysis and making predictions
 -Recommendations_with_IBM_Final.html: visual of the Jupyter notebook
 
 ## Summary
 Four methods were utilized to make recommendations:
 1.  Knowledge Based Recommender - Recommends most popular overall items.  Often used to remedy the cold start problem when no information is available for a new user.
 2.  Collaborative Filtering Based Recommender - Recommends items to a user based on what other users with similar behaviors also do.
 3.  Content Based Recommendations - Not employed in this notebook, but the article titles can be processed using NLP techniques to identify article similarity based on content.
 4.  SVD Recommendations - Predicts if a user will interaction with a title or not using matrix operations
 
 ## Results 
Recommendation strength was not great because of the low level of user overlap between training and test set.

## Acknowledgements
This project was completed in conjunction with Udacity's Data Science Nanodegree Program in partnership with IBM Watson.
