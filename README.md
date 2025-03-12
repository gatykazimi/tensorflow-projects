# tensorflow-projects
 Tensorflow projects from freeCodeCamp

# Cat vs Dog
The fcc_cat_dog.ipynb file is a Jupyter notebook that contains an ML model using Tensorflow and Keras, whose goal it is differentiate between cats and dogs.

First, the  pictures were obtained from the following zip file:  
https://cdn.freecodecamp.org/project-data/cats-and-dogs/cats_and_dogs.zip  
Using ImageDataGenerator (and flow_from_directory), the images were converted into an array containing information on pixel location (x and y) and rbg values.
Then the model was built using the Keras Sequential model, with both Conv2D and MaxPooling2D layers
and ReLU activation. In the final dense layer, a sigmoid activation is used.
To increase accuracy, there were more layers and nodes in the model, and the training data was augmented to minimize overfitting.  
![image](https://github.com/user-attachments/assets/a6a31b3f-f920-4460-8a90-d422814f3b6c)

After training the model, the relationship between training and validation accuracy with epoch number and training and validation
loss with epoch number is shown on the plot below. This shows that the higher the epoch number, the accuracy is maximized and the loss is minimized.
However, sometimes the model would become less accurate with the higher epoch number, so the number of epochs had to be optimized (epochs=15 here).

![image](https://github.com/user-attachments/assets/46c449f1-0f29-40d6-89c2-3c046e4ca49f)  
After the model was trained, it showed **70%** accuracy with the test data.
