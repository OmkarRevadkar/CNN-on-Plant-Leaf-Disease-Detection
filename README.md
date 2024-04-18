-CNN stands for Convolutional Neural Network. It is used to classify images in the target variable. It is to be used when the input is an image data. 
-CNN comprises of 3 layers:
   1) Convolutional Layer
   2) Pooling Layer
   3) Fully Connected Layer

CNN's involve data compression. In Pooling layer, the insignificant features of an image are removed retaining only its significant features which are then passed to the next layer which is Pooling Layer. Same process is followed in this layer as well. The most important is the slider or filter which slides over the image in this process. In  Convolutional layer, dot product which is the convolution is found with the help of the slider. In Pooling layers, there are 2 options: MaxPooling or AvgPooling. The compressed data is then flattened to a series before passing to the fully connected layer. The fully connected layer is a layer is a layer in which all neurons in each layer are interconnected with each other.

In this project, I have worked on the CNN model to predict if the plant leaf has a disease or not classifying into 3 labels as Healthy/Powdery/Rust. 
The steps involved are as follows:

1) Import the necessary libraries as required. Get the main paths and associated categories.
2) Join the paths involved so as to be able to read the images.
3) Resize and visualize images wherever required.
4) Assign labels to the images while collecting them in an empty array.
5) Take value counts for all 3 classes present in the dataset to check if the data is balanced or not.
6) Carry 'data augmentation' i.e creating duplicates from the original images and then adding them to the original if the dataset is insufficient to build an appropriate model.
7) Do sampling if desired, then initialize and build the model on CNN using train data.
8) Plot the train and validation accuracies on a graph to check the model performance.
9) Save the model for future purpose and easy accessibility.
10) Check for the predictions on test data and validate the model.
