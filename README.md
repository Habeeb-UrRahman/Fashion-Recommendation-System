# Fashion-Recommendation-System

The project is a fashion recommendations system which uses CNN to extract features from a dataset and create 2 pickle(.pkl) files one with the feature extraction data and the other with the information
about the location of each picture in the dataset. These (.pkl) files are then used to train a model which can take input of a new images (a product like a shirt, jacket etc) and find similar looking
products from the dataset.

We are using a pre-trained CNN model here based on ResNet-50 to get more accurate features from the dataset images.
![cnn_banner](https://github.com/Habeeb-UrRahman/Fashion-Recommendation-System/assets/89064840/66afe31c-3fd6-4b79-9863-ae20bc36e680)

![394nf](https://github.com/Habeeb-UrRahman/Fashion-Recommendation-System/assets/89064840/0d763b17-216f-4039-97f1-a85d8a3f1621)

- The dataset used in our case can be found at:
https://drive.google.com/file/d/1iY-WXC4w1wCIl0GYYHk2larWzGvshkdl/view?usp=drive_link

-  Image Embeddings (.pkl) file for the dataset used in our case:
https://drive.google.com/file/d/1eU-EFqG8arVSXr9iUMwwpwQ_BmM0KWB-/view?usp=sharing

- Image file embeddings (.pkl) file for the dataset used in our case:
https://drive.google.com/file/d/14NwuwccZ0rLC-Bn4h7h90js0829jKOwz/view?usp=sharing

- The dataset can be downloaded and the feature_extraction.py code can be used to extract the features of the images (make sure to change the paths and folder names in the feature_extraction.py file) 
in the form of a .pkl file.

- These .pkl files can be used with the streamlit based app which contains the model and the recommendations system.

Use the command 'streamlit run app.py' to run the streamlit app from the directory of the project on your local machine.

#Sample

![Screenshot 2023-08-14 123255](https://github.com/Habeeb-UrRahman/Fashion-Recommendation-System/assets/89064840/ad255b7a-f6ec-451f-aba0-8c57ef076c7f)






