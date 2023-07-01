# Object-Detection-using-BOW
Object Detection using Bag of Visual Words methodology

The general idea of bag of visual words (BOVW) is to represent an image as a set of features. Features consist of keypoints and descriptors. Keypoints are the “stand out” points in an image, so no matter whether the image is rotated, shrink, or expand, its key points will always be the same. And descriptor is the description of the key point. We use the key points and descriptors to construct vocabularies and represent each image as a frequency histogram of features that are in the image. From the frequency histogram, later, we can find another similar image or predict the category of the image.

The major steps in this project involves :-
1.Read train images
2. compute SIFT descriptors list for the images
3. clustering of the Descriptors using KNN
4. Feature extraction from the Descriptor list
5. Find the dictionary and plot the histogram
6. Train the SVM
7. Test the model
8. Checking Accuracy

For more details on the project please follow this 
[Image Classification uisng BoW report.pdf](https://github.com/RoyAnuska/Object-Detection-using-BOW/files/11924821/Image.Classification.uisng.BoW.report.pdf)

For Dataset please follow this link
https://drive.google.com/drive/folders/1imGf1Ov3HpqsqNmP4dMRzR9qWeMwKIkx?usp=sharing
