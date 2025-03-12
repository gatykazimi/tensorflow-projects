# tensorflow-projects
 Tensorflow projects from freeCodeCamp

# Cat vs Dog
The fcc_cat_dog.ipynb file is a Jupyter notebook that has an ML model using Tensorflow and Keras. 
First, the  pictures were generated using ImageDataGenerator, then the model was built using the Keras Sequential model, using Conv2D and MaxPooling2D layers
and ReLU activation. In the final dense layer, I used a sigmoid activation.
To increase accuracy, I used more layers and nodes in my model, and augmented my training data to minimize overfitting.  
![image](https://github.com/user-attachments/assets/a6a31b3f-f920-4460-8a90-d422814f3b6c)

After training my model, I plotted the relationship between training and validation accuracy with epoch number and training and validation
loss with epoch number. This shows that the higher the epoch number, the accuracy is maximized and the loss is minimized.  

![image](https://github.com/user-attachments/assets/46c449f1-0f29-40d6-89c2-3c046e4ca49f)  
After the model was trained, I compared it against the test batch, and it had a **70%** accuracy.
