# EVA-4-Session-5
File 1: Basic Model
1.	Targets: 98.5 (Wanted to test the input on the lighter model and verify with less number of parameters)
2.	Results: Train Accuracy: 98.91 and Test Accuracy: 98.73. Parameters: 9996
3.	Analysis: Lighter Model which has 7 Convolution Layers
4.	File Link: https://github.com/gudaykiran/EVA-4-Session-5/blob/master/File1_Lighter_Model.ipynb



File 2: Batch Normalization
1.	Targets: 99.3 (Wanted to Stabilize the accuracy)
2.	Results: Train Accuracy: 99.63 and Test Accuracy: 99.27. Parameters: 8996
3.	Analysis: BatchNormalization Added to all layers except Output layer, BatchNormalization Stabilises the learning process. Hence, reduced the number of parameters. Consistency in test accuracy is visible
4.	File Link: https://github.com/gudaykiran/EVA-4-Session-5/blob/master/File2_BatchNorm.ipynb
File 3: Regularization
1.	Targets: 99.3  (wanted to avoid Overfitting)
2.	Results: Train Accuracy: 98.95 and Test Accuracy: 99.22. Parameters: 8996
3.	Analysis: Dropout is added to all layers to reduce the overfitting.
4.	File Link: https://github.com/gudaykiran/EVA-4-Session-5/blob/master/File3_Regularization.ipynb
File 4: Image Augmentation
1.	Targets: 99.3 (Wanted to improve performance and ability of training model by applying transformations from 5-7, such that the model would be able to generalize better on the test data) 
2.	Results: Train Accuracy: 98.75 and Test Accuracy: 99.37. Parameters: 6952
3.	Analysis: Image augmentation has improved the test accuracy.
4.	File Link: https://github.com/gudaykiran/EVA-4-Session-5/blob/master/File4_ImageAugmentation.ipynb
File 5: OverKill
1.	Targets: 99.4 (Wanted to improve performance by adding the LR Scheduler) 
2.	Results: Train Accuracy: 98.84 and Test Accuracy: 99.46. Parameters: 9576
3.	Analysis: LR Scheduler is added with learning rate to be 0.05, step size =4 and gamma=0.5. The test accuracy is stable and the best accuracy is 99.46
4.	File Link: https://colab.research.google.com/drive/1ZTqZyQYqubeoM7OC4E8qyF31E8g6V4z8#scrollTo=nmgSe3TDdE7l
