# IML_CNN

This Directory contains the various methods to train Convolution Neural Network models and their weights stored in their respective files.
This Directory is structured to hold 3 different folders for the models trained to target specific attributes of Gender, Emotions and Age

## Models

### [cnnGender](https://drive.google.com/drive/folders/1NNoNN2kkXtEvrYv0Pf8gWdBw6Ej_EjoN)
Contains 10 various CNN models trained on different parameters and differernt Architecutre implemented in the file [Gender_Analysis](https://colab.research.google.com/drive/12K91YeH0N7NYk4sFxdVfOS1IzjAhjO12), it also contains 20 different model weights as a result of extensive training of 10 different models on 2 folds of data.


The Weights are stored in the following format:

model _i__j_.hdf5

where _i_ represents the model number of the 10 various ones
where _j_ represents the number number of the _i_ th model.  _j_ ranges from 1-2 

[PostTrainingAnalysis_Gender](https://colab.research.google.com/drive/16mPeYAQxAdWRzUX2I_XGARxPMnQzPz7_) contains an automated code to fetch a specified model, then proceed to load that particular model's weight for every fold and presents a complete Post Training Analysis of the model ranging from Training Loss, Accuracy, Precision, Recall, F1 Score, Confusion Matrix, ROC curve and Average Precision for both Testing and Training Data.

### [cnnEmo](https://drive.google.com/drive/folders/1qBXOaSn4MG-fUJRXoFj1JRx7ydlhH5Vg)
Contains 10 various CNN models trained on different parameters and differernt Architecutre implemented in the file [ClassifyEmo](https://colab.research.google.com/drive/1FAjjuVOQQ0nMAADh2JxzIQhHkufhXgs2), it also contains 50 different model weights as a result of extensive training of 10 different models on 5 folds of data.

The Weights are stored in the following format:

model _i__j_.hdf5 

where _i_ represents the model number of the 10 various ones
where _j_ represents the fold number of the _i_ th model. _j_ ranges from 1-5 

[PostTrainingAnalysis_Emo](https://colab.research.google.com/drive/1xm8nlxiFpwccshg6TiZoc-W8eFQMmzpL) contains an automated code to fetch a specified model, then proceed to load that particular model's weight for every fold and presents a complete Post Training Analysis of the model ranging from Training Loss, Accuracy, Precision, Recall, F1 Score, Confusion Matrix, ROC curve and Average Precision for both Testing and Training Data.

### [cnnAge](https://drive.google.com/drive/folders/1Ih5R9pCIPm26U1ZmoJ9MVU4Xf2sZV3fu)
Contains 10 various CNN models trained on different parameters and differernt Architecutre implemented in the file [AgeMain](https://colab.research.google.com/drive/1JtJzP8_UeJtT6EOMmqePHmgguFzzf5Fo), it also contains 10 different model weights as a result of extensive training of 10 different models.

The Weights are stored in the following format:

ModelAge _i_.h5

where _i_ represents the model number of the 10 various ones

[PostTrainingAnalysis_Age](https://colab.research.google.com/drive/1jlcT34X_fcjrDAjs8ORHD-Yx2mk4iYr2) contains an automated code to fetch a specified model, then proceed to load that particular model's weight for every fold and presents a complete Post Training Analysis of the model ranging from Mean Sqaured Error, Root Mean Squared Error and Mean Absolute Error for both Testing and Training Data.
