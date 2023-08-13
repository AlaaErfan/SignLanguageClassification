# SignLanguageClassification
My 4th task as machine learning intern at Sync interns
## DataSet Link 
https://www.kaggle.com/datasets/datamunge/sign-language-mnist?datasetId=3258
### Convolutional Neural Network (CNN) Model
- The CNN_model function defines a CNN architecture for image classification.
- It consists of convolutional layers followed by max-pooling and dropout layers to prevent overfitting.
- The model is compiled using the Adam optimizer and sparse categorical cross-entropy loss for multi-class classification.
- The model is trained using the training dataset and validated using the validation dataset.
- Training history is stored in history for loss and accuracy evolution.
