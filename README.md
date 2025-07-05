# Computer-Vision-Assignment-1
Custom CNN , Fine Tuned For CFAR10 dataset

# Baseline Model:
* Test Loss: 0.654900312423706
* Test Accuracy: 0.7814000248908997

# Fine tuned Model:
* Test Loss: 0.44790834188461304
* Test Accuracy: 0.8476999998092651

# What architectural/ training changes led to improvements and why?

* The model was made deeper with more filters, helping it learn better features.

* Batch Normalization layers improved training stability and accuracy.

* Dropout reduced overfitting.

* The Adam optimizer made learning faster and smoother.

* A learning rate scheduler helped fine-tune the training process.

* Early stopping prevented the model from over-training.

* These changes improved accuracy from 78% to 85% and increased performance on all classes.
