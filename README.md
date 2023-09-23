# Data-Augmentation
 Data Augmentation using Numpy, OpenCV, Matplotlib,...

According to Wikipedia, Data Augmentation are “Techniques used to increase the amount of data by adding slightly modified copies of already existing data or newly created synthetic data from existing data.” -> data augmentation is about making minimal changes to existing data to create new representative data. -> Why?: improve performance and outcomes of machine learning models by forming new and different examples to train datasets. If dataset in a machine learning model is rich and sufficient, the model performs better and more accurate.

The steps are:

1. Choose a few images, belonging to two different classes (tree, dog)
2. Define the following 10 transformation techniques (random rotating, vertical flipping, horizontal flipping, translation along x, translation along y, cropping, zooming, color modification, adding light gaussian noise, 
   adding illumination).
3. Apply each of the transformation to each image. We need to come out with 10 images resulting from each original image.
4. Visualize some images while comparing with the original image ( 10 visualizations)
5. Visualize the histograms of original and some resulting images
6. Apply a binary classifier on your data. Report the results.
The purpose is to not use built-in functions
