# Semantic-segmentation-model-with-U-Net-TF-
Semantic segmentation model with U-Net &amp; TF  for https://www.kaggle.com/c/data-science-bowl-2018
Challenge: create an algorithm to automate nucleus detection
Plan
1. Import necessary libraries
2. Importing TensorFlow - an open source library for numerical computation and large-scale machine learning
2.1. Import support libraries
2.2 Import matplotlib for visualization
3. Input files: Unzipping the train files
3.1 Input files: Unzipping the test files
4. Preprocessing phase: 
1) load the data,
2) get data ready for model
5. Tunning png image parameters: almost all pictures are in 256 * 256 resolution, we will leave this resolution to save more information
6. Obtain from train and test input data images and masks
7. Visualizing training images and the segmented images related to it
8. Building semantic segmentation model with UNet architecture using Keras. UNET paper https://arxiv.org/abs/1505.04597
9. Training the model
10. Apply the semantic segmentation algorighm on the train and test images using our trained model
11. Visualizing model results on train data
12. Visualizing model results on test data
13. Create list of unsampled test masks
14. Implement Run-length encoding for each separate mask identified by skimage (from https://www.kaggle.com/rakhlin/fast-run-length-encoding-python )
15. Obtain our semantic segmentation model results (encoded pixels) and create submission
Thanks for ideas: Kjetil Åmdal-Sævik, Rakhlin
