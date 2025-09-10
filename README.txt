Damage Model Code
the damage_model jupyter notebook contains code to do cost estimation on the files in the prediction directory. Running all cells will give you the results.

Segmentation Model Code
The segementation_model jupyter notebook contains source code for training the DeepLabV3 model.
The code needs the RescueNet dataset to be added to the RescueNet directory with orginal directory names. 
Training was performed on a v2-8 TPU so running the model on a CPU maybe computationaly expensive. 
The weights for model 1 and model 2 are saved in the model_weights directory. 
There is a cell with in the notebook that will load the model weights to allow for model inference.
To easily review results use the SingleImage_evaluate() function to display the image, prediction, label, and IoU score.
There are other functions in the "Help Function" section that will help you view the results of the model.