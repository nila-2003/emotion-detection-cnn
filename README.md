# emotion-detection-cnn
The project recognises emotions based on facial expressions.

Dataset Used : https://www.kaggle.com/datasets/jonathanoheix/face-expression-recognition-dataset

Emotions detected : angry, disgust, happy, fear, sad, neutral, surprise

Model used : CNN ( i.e, sequential model ). The following layers were included:- 
Dense, Input, Dropout, GlobalAveragePooling2D, Flatten, Conv2D, BatchNormalization, Activation, MaxPooling2D.

Epochs used : 1 (48 recommended for better results and it may vary based on GPU/CPU).
