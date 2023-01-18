# Melanoma Detection Assignment

To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
# Table of Contents

* [General Info](*general-info)
* [Technologies Used](*technologies-used)
* [Conclusions](*conclusions)
* [Acknowledgements](*acknowledgements)

Data Reading/Data Understanding → Defining the path for train and test images Dataset Creation→ Create train & validation dataset from the train directory with a batch size of 32. Also, make sure you resize your images to 180*180. Dataset visualisation → Create a code to visualize one instance of all the nine classes present in the dataset Model Building & training : Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model, rescale images to normalize pixel values between (0,1). Choose an appropriate optimiser and loss function for model training Train the model for ~20 epochs Write your findings after the model fit. You must check if there is any evidence of model overfit or underfit. Chose an appropriate data augmentation strategy to resolve underfitting/overfitting Model Building & training on the augmented data : Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1). Choose an appropriate optimiser and loss function for model training Train the model for ~20 epochs Write your findings after the model fit, see if the earlier issue is resolved or not? Class distribution: Examine the current class distribution in the training dataset

### Which class has the least number of samples?
Which classes dominate the data in terms of the proportionate number of samples? Handling class imbalances: Rectify class imbalances present in the training dataset with Augmentor library. Model Building & training on the rectified class imbalance data : Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model, rescale images to normalize pixel values between (0,1). Choose an appropriate optimiser and loss function for model training Train the model for ~30 epochs Write your findings after the model fit, see if the issues are resolved or not?
# Technologies Used

- Python
- Tensorflow - keras
- Matplotlib

# Conclusions

Conclusion 1 from the model 1
The accuracy of the model for the Training data set is 88.23%. But the Validation accuracy between 54.14% only.

The validation loss as observed is very high. For training the loss is less than 0.3265 where are for validation the loss is 2.1436.

This shows that the model is overfitting.

Conclusion 2 from the model 2
We see that both training and validation accuracy and loss is almost similary i.e., 58.26% and 55.26% and 1.16 to 1.37 respectively. We dont see high accuracy of the model. They are underfitting as they are not able to perform well on the given dataset.
We need to relook at the data and then train the model.

Conclusion 3 from the model 3
So we can conclude that class imbalance helped in improving the model performance with 3 convolution layers, pooling layers, flatten and dense layers.

# Acknowledgements

## Contact
Created by [biswasamanta@gmail.com] !


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
