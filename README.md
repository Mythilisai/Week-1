Plant Disease Detection using CNN

This project uses a Convolutional Neural Network (CNN) to detect plant diseases from leaf images. It helps farmers by identifying whether a plant is healthy or sick early.


 What is the Project?

- A deep learning model that looks at pictures of plant leaves.
- It tells if the leaf is healthy or has a disease.
- Works on crops like apple, cherry, grape, and corn.


 Pipeline

1. Collect Data  
   - Images of plant leaves (healthy and diseased).  
   - Dataset split into: `train`, `valid`, `test`.

2. Upload & Load Dataset  
   - ZIP the dataset.  
   - Upload it to Google Drive.  
   - Use Google Colab to load and unzip it.

3. Preprocessing Images  
   - Resize images.  
   - Normalize pixel values.

4. Image Augmentation  
   - Add variety using flip, rotate, zoom, etc.  
   - Helps the model learn better.

5. Model Design  
   - A simple CNN model is created using Keras/TensorFlow.  
   - Trained with training and validation datasets.

6. Model Testing  
   - Final model tested using the test dataset.  
   - Accuracy and performance checked.


 Tools Used

- Python  
- Google Colab  
- Google Drive  



