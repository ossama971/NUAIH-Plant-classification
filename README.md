# NUAIH-Plant-classification
Plant disease image classification using ResNet50

Used Keras' ImageDataGenerator' to perform data augmentation and create a balanced dataset by oversampling the minority class
and then loads the pre-trained ResNet50 model and creates a new model by adding a classification layer on top of it and compiles the model with Adam optimizer, categorical cross-entropy loss function, and accuracy as the evaluation metric.
