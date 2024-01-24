# Face-Mask-Detection-Using-MobileNetV2-Architecture

The main aim of the project is to detect whether a person was wearing a face 
mask or not, which held great importance during the COVID-19 pandemic. For this 
purpose, we employed the MobileNetV2 architecture, a Convolution Neural 
Network (CNN), given that our data consisted of visual and image data. The 
dataset was divided into 80 percent for training data and 20 percent for testing 
data. The images, with dimensions of 224x224 pixels, were converted into array 
format. The MobileNetV2 architecture comprises three layers: an 
AveragePooling2D layer, a Dense layer, and a Flatten layer. The architecture 
utilized ReLU and softmax activation functions, and optimization was carried out 
using the Adam optimizer.
The model achieved an accuracy of 98 percent for individuals wearing masks, 
denoted by a green bounding box around the face, and an accuracy of 99 percent 
for individuals without masks. Additionally, we successfully deployed the model 
to our devices using TensorFlow Lite (TFLite).
