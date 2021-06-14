Data Reading/Data Understanding → Defining the path for train and test images 

Dataset Creation→ Create train & validation dataset from the train directory with a batch size of 32. Also, make sure you resize your images to 180*180.

Dataset visualisation → Create a code to visualize one instance of all the nine classes present in the dataset 

Model Building & training : 

Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).

Choose an appropriate optimiser and loss function for model training

Train the model for ~20 epochs

Write your findings after the model fit, see if there is evidence of model overfit or underfit

Choose an appropriate data augmentation strategy to resolve underfitting/overfitting 

Model Building & training on the augmented data :

Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).

Choose an appropriate optimiser and loss function for model training

Train the model for ~20 epochs

Write your findings after the model fit, see if the earlier issue is resolved or not?

Class distribution: Examine the current class distribution in the training dataset 

- Which class has the least number of samples?
- Which classes dominate the data in terms of the proportionate number of samples?

Handling class imbalances: Rectify class imbalances present in the training dataset with Augmentor library.

Model Building & training on the rectified class imbalance data :

Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).

Choose an appropriate optimiser and loss function for model training

Train the model for ~30 epochs

Write your findings after the model fit, see if the issues are resolved or not?
