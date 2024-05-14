# Baigiamasis-darbas-JackDaniels
Fake or Orignial Bottle checking tool with CNN model

Here’s a high-level overview of the steps you would need to follow:

Image Preprocessing: You would need to preprocess your images before feeding them into the model. This could involve resizing the images to a fixed size, normalizing the pixel values, etc. Keras provides the ImageDataGenerator class that can help with this.
Model Training: You would train your model on your preprocessed datasets. Make sure to divide your data into a training set and a validation set to evaluate your model’s performance.
Prediction Function: After training your model, you can use it to predict the class of new images. You would need to preprocess these new images in the same way as your training and validation images.
In this code, the predict_image function takes the path to an image file, preprocesses the image, and uses the trained model to predict whether the image is of an original or fake Jack Daniels bottle. You can call this function with the path to a new image to make a prediction.

Please replace 'dataset/training_set' and 'dataset/test_set' with the paths to your actual datasets. The fit_generator function trains the model for a fixed number of epochs (iterations on a dataset). You can adjust the steps_per_epoch, epochs, and validation_steps parameters based on your dataset size and computational resources.

Remember, this is a basic model and might not give high accuracy. For complex datasets, you might need a more complex model, data augmentation, or pre-trained models. Also, always remember to preprocess your images and labels correctly before feeding them into the model.


Link For datasets : https://drive.google.com/drive/folders/1y2GL-MFbC50CxzdXBGjia416RsU3FOp-?usp=sharing
