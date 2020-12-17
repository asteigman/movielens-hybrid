# Personalization Final Project

The following project is the work of Amanda Steigman, Romane Goldmuntz, and Suman Tripathy.

## Repository Contents

**MovieLensFinal.ipynb**
Final report including all our business objectives, baseline and hybrid recommendation systems, as well as our takeaways and recommendations for the manager.

**Content-Based.ipynb**
Contains code and written explanations for the content-based recommender system based on movie tag and Wikipedia info. This model's predictions were incorporated into the hybrid models in MovieLensFinal.

**Wikipedia.ipynb**
Contains code and written explanations for how the content-based recommender system created movie vectors based on their tags and Wikipedia information. It shows how we scraped information from Wikipedia, combined it with the MovieLens tag data, and then narrowed down the tags to the most "important" ones. The outputted movie vectors are used directly in the content-based model. 

**Deep_Learning_Model_Autoencoders.ipynb**
Contains code and written explanations for the Autoencoder model. This model's predictions were incorporated into the hybrid models in MovieLensFinal.

**TrainTestSplitting.ipynb**
Splits our sample data into train, test, and val very carefully to ensure that users are represented within all the three datasets. The outputs from here are used directly to train all our models.

**requirements.txt**
Contains all required libraries with their respective versions. Install all these requirements prior to running the MovieLensFinal ipynb.

**inputs/**
Contains all input datasets required to train and test our models. 

**outputs/**
Contains all pickled model predictions for our Autoencoder, content-based model, and collaborative filtering model. These pickled dictionaries are used directly in our hybrid model.
