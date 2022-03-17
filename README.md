# flower-recognization
Flower recognization using CNN 

Data source: [Link to Dataset](https://www.tensorflow.org/datasets/catalog/tf_flowers)

Total flowers image count in dataset:  3670

Flowers names:  ['dandelion', 'tulips', 'sunflowers', 'roses', 'daisy']

- dandelion total count: 898
- tulips total count: 799
- sunflowers total count: 699
- roses total count: 641
- daisy total count: 633

I have trained a Convolutional Neural Network (CNN) to predit the 5 types of flowers using the flower recognization dataset mentioned in the above. 
The flower images were first preprocessed and resize into a fixed image size to train the machine learning model. After the model training there was training accuracy about 68% and validation accuracy was about 66%. These accuracy can be further improved by adding more datasets and enhancing CNN layers along with working on following options, such as:
-image enhancement and feature extraction
-fine-tune on data augmention
-transfer learning on VGG model, etc.
