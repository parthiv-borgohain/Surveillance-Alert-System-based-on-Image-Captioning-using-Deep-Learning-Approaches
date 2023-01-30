# Surveillance-Alert-System-based-on-Image-Captioning-using-Deep-Learning-Approaches

This project was a group project as part of the Advanced Machine Learning coursework for the UT Austin MS Business Analytics Program in the Fall Semester of 2022.

Our aim was to create a surveillance alert system that could accurately detect and describe any suspicious activities recorded by security cameras. The current semantic segmentation technology could only identify the objects in the image, but lacked the ability to explain their relationship using verbs or contextual information. To overcome this challenge, we proposed using an Image Captioning system that could analyze the images and produce captions to describe the events taking place.

Our solution was based on the use of a Convolutional Neural Network (CNN) and Long Short-Term Memory (LSTM) architecture to generate captions, and the Vader algorithm to evaluate the captions and trigger alerts if they contained any warning words. The model was trained using the Flickr-8k Images with Captions dataset from Kaggle, augmented by an additional 568 surveillance images and captions that were generated manually.

The results of our project were impressive, with our CNN-LSTM model achieving a BLEU score of 0.8 on the test dataset for the surveillance images. Our solution proved to be a flexible and effective tool for addressing the business need for a reliable and efficient surveillance system.

For a detailed explanation of the project, please refer to the Medium article: https://medium.com/@rgarg_98817/surveillance-alert-system-a394f28480c6
