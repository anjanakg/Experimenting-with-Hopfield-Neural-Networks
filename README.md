# Experimenting with Hopfield Neural Networks

<p align="justify"> Hopfield is a Recurrent Neural Network. The Hopfield model has two stages as storage and retrieval. The weights are calculated based on the stored states and the weights are not updated during iterations. Hopfield networks store states with minimum energy. One of their applications is image recognition.
</p>

Here I added 3 notebooks. 

[here](Classification_of_UDSculptures_ResNet50.ipynb) 
.


<p align="center">
  <img src="https://github.com/anjanakg/Visualizing-Hidden-Stories-Using-Deep-Learning/blob/main/images/Picture2.jpg" width="1200" >
</p>

<br>



<p align="justify"> 
    We tried several pre-trained models to select the best model. 
    We trained each model on the training set and evaluated each trained model’s performance on the validation set. And finally, choose the model with the best             validation set performance for testing on test data set.
</p>

<p align="justify"> 
    We faced lots of pitfalls during our process. The ResNet50 with Transfer Learning model performed very well in our data. However, we could not convert it to tflite     format. We converted it to ONNX format with ONNX opset version 11. But the file size was 150MB and also Unity was not supporting it.  
</p>

  The complete notebook of ResNet50 model implementation, training, and evaluation is
  [here](Classification_of_UDSculptures_ResNet50.ipynb) 
  .
