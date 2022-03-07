# Data-scienence-Handwrittendigit-detection

The handwritten digit recognition is the ability of computers to recognize human
handwritten digits. It is a hard task for the machine because handwritten digits are
not perfect and can be made with many different flavours. The handwritten digit
recognition is the solution to this problem which uses the image of a digit and
recognizes the digit present in the image.

# Installation requirements:
- Jupyter notebook
- Google colab

# The MNIST dataset: 
This is probably one of the most popular datasets among machine learning
and deep learning enthusiasts. The MNIST dataset contains 60,000
training images of handwritten digits from zero to nine and 10,000 images
for testing. So, the MNIST dataset has 10 different classes. The handwritten
digits images are represented as a 28×28 matrix where each cell contains
grayscale pixel value

# Convolutation neural network: 
![image](https://user-images.githubusercontent.com/73145010/157036483-25d72f95-43fe-41a9-a099-26ad34e4a367.png)

# model performance:
## Model accuracy:
![image](https://user-images.githubusercontent.com/73145010/157037023-4a88b97a-cb8a-4144-bbca-d588c5223db7.png)

## Model loss:
![image](https://user-images.githubusercontent.com/73145010/157037075-c2a11476-c04d-47b4-9ebd-4c25b9ac830f.png)

## Model true lavel visualization:
![image](https://user-images.githubusercontent.com/73145010/157037192-bc5aefee-1411-48a5-95d3-4ca9c132b1a5.png)


## Conclusion :
- Loaded image is extracted from the MNIST test dataset, save it in my current working directory with the filename "sample_image.png". Running the example first loads and prepares  the image, loads the model, and then correctly predicts that the loaded image represents the digit ‘7‘.
- The classification accuracy for the model on the test dataset is calculated, we can see that the model achieved an accuracy of 99.24%.
