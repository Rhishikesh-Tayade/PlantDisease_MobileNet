# PlantDisease_MobileNet
This project leverages a pretrained model with ImageNet weights through transfer learning. By applying fine-tuning, the model has been adapted into an effective and accurate plant disease classifier.

This project utilizes a MobileNet convolutional neural network to classify plant diseases from images. The model is trained on a dataset likely sourced from Kaggle, and the code is provided in a Jupyter notebook format.

The following libraries are required to run this project:
opendatasets, tensorflow, matplotlib, numpy
You can install these dependencies using the requirements.txt file generated previously.

The best weight of the fine-tuned model is attached as (best_weights_plant_diseae.weights.h5). 
It got good results:
    loss     --> 0.0519
    acc      --> 0.9834
    val_loss --> 0.0498
    val_acc  --> 0.9839

ReduceLROnPlateau, EarlyStopping, ModelCheckpoint were also used from tensorflow.keras.callbacks in order to reduce LR, save the best weights of model for further neccesary training ...
