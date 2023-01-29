# Surveillance-Alert-System-based-on-Image-Captioning-using-Deep-Learning-Approaches
This was a Group Project done as part of Coursework for Advanced Machine Learning during Fall Semester 2022 for UT Austin's MS Business Analytics Program.

In this project, our goal was to develop a surveillance alert system that could accurately identify and describe suspicious activities captured by security cameras. The existing semantic segmentation technology could only determine the objects in the image, but lacked the ability to explain the relationship between those objects using verbs or contextual information. To address this challenge, we proposed using an Image Captioning system that would view the images and generate captions to describe the events happening in them.

Our solution was based on the use of a Convolutional Neural Network (CNN) and Long Short-Term Memory (LSTM) architecture for image caption generation, and used the Vader algorithm to analyze the generated captions and trigger alerts if they contained red-flag words. To train the model, we used the Flickr-8k Images with Captions dataset from Kaggle and augmented it with an additional 568 surveillance images and captions that were manually generated.

The results of our project showed that our CNN-LSTM model performed well, achieving a BLEU score of 0.8 on the test dataset for the surveillance images. Compared to the state-of-the-art GPT2-generated captions, our model proved to be a flexible and effective tool for addressing the business need for an efficient and reliable surveillance system.

A detailed Medium article explaining the project: https://medium.com/@rgarg_98817/surveillance-alert-system-a394f28480c6
