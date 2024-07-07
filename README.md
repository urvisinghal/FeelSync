The scope of this project includes data collection and labeling, model training and evaluation, and integration into a user interface.

To train the machine learning model, data representing a range of emotions and corresponding music needs to be collected and labeled. Publicly available datasets such as the Spotify Dataset and the FER 2013 Dataset will be used.

The dataset has been preprocessed to make it suitable for training. This involves cleaning and normalizing the data, removing any duplicates or irrelevant information, and splitting it into training and testing datasets.

Two models have been built for this project. The first one analyzes an image and detects the emotion the person in it is feeling. The second one takes the detected mood as input and generates suitable songs based on the user's playlist. Convolutional neural networks (CNNs) are utilized by both models to make predictions. For the music recommender model, users also have the option to submit their own playlists using the Spotify API to receive personalized recommendations.
