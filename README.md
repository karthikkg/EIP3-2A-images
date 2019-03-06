# EIP3 Assignment
#### NAME : Gajula Karthik Kumar
#### EMAIL : karthikg.myb@gmail.com
#### BATCH : 3
## 1. Convolution

In deep learning convolutions are nothing but the dot product of matrices.Convolutions in CNNs works on the principle of loosely connected layers as opposed to fully connected layers in multi-layer perceptrons. Convolution is performed on input data using a number of predefined size and number of filters whose values are randomly assigned which later learn through multiple forward and backpropagaton and to produce feature maps.The very first few layers detects minor features. Later layers detect complex features which are fed to activation funcion usually softmax which gives a probability of classification of the input data.

## 2. Filters/Kernels
Filters are matrices that are used to convovle on input data matrix. Filters convolved on input matrix produces important feature maps. These feature maps are further convoled by another set of filters in further layers to produce complex features. A activation function is later applied to these feature maps to produce the probability in classification or a continuous value in regression.

## 3. Epochs
Epoch is one of the important Hyperparameters.The one forwrad and one back propagation in CNNs is called Epoch. The choice of number of epochs plays an important role in generalisation of the model. Too many Epochs during training leads to overfitting of the model. We can decide number of epochs by plotting the training and validation data error rate versuses number of epochs during training of model. Validation data error rate decreases along with training error rate as number of epochs increases. But after a specific number of epochs valdation error rate increase even when training error rate decreases. At this specific number of epochs it is recomended to stop training. This early stoping method should be wisely used to choose the number of epochs.

## 4. Feature maps

Feature maps are the byproducts i.e the summed product of filters and input data. Feature maps contains the essential information of the input data. Early feature maps contains minor properties like edges, shapes etc. later featur maps consists of complex features. Gradient descent algorithm(mostly used) in back propagaton plays a important role in learning of the features or development of the feature maps. The last layer feature maps are fed to activation function to obtain a prediction of the model.

## 5. 3x3 Filter:

3x3 size has gained popularity in CNNs. 3x3 is effective odd filter which is efficient for edge detection. We normally use 3x3 filters in convolution layers along with single stride. The application of 3x3 results in a loss of 2x2 values when padding not applied. It detects an important feature each time applied.Hence 3x3 filters gained importance in industrial application
