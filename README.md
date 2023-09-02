# Fashion-Recommendation-System

The project is a fashion recommendations system which uses CNN to extract features from a dataset and create 2 pickle(.pkl) files one with the feature extraction data and the other with the information
about the location of each picture in the dataset. These (.pkl) files are then used to train a model which can take input of a new images (a product like a shirt, jacket etc) and find similar looking
products from the dataset.

We are using a pre-trained CNN model here based on ResNet-50 to get more accurate features from the dataset images.

The dataset used in our case can be found at:
https://drive.google.com/file/d/1iY-WXC4w1wCIl0GYYHk2larWzGvshkdl/view?usp=drive_link

The dataset can be downloaded and the feature_extraction.py code can be used to extract the features of the images (make sure to change the paths and folder names in the feature_extraction.py file) 
in the form of a .pkl file.

These .pkl files can be used with the streamlit based app which contains the model and the recommendations system.

# Use the command 'streamlit run app.py' to run the streamlit app from the directory of the project on your local machine.
