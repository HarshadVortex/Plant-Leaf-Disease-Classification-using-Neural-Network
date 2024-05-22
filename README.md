# Plant-Leaf-Disease-Classification-using-Neural-Network
The results and important lessons learned from the image classification study for plant disease detection are presented in this section. 

Preprocessing and Data Exploration:
•	Three plant diseases were used in the dataset: tomato bacterial spot, potato early blight, and corn common rust.
•	The three classes combined for a total of 900 photos, indicating a balanced dataset
•	For training and assessment, the script successfully executed train-test splits and transformed photos into NumPy arrays.
  
Training and Model Architecture: 

•	Multiple convolutional layers, max pooling layers, and thick layers were used to construct a convolutional neural network (CNN) architecture. If it is pertinent to the project's objectives, briefly describe the number of layers used. 
•	With a batch size of 128, the model was trained across 50 epochs. 
 
Training Results: 

•	After 50 epochs, the model attained a training accuracy of 0.9902 and a validation accuracy of 0.971
•	To track the learning process, visualizations of the training and validation loss and accuracy curves were created. (If any observations from the plots were made, mention them.

 
          
Assessment: 

•	Test accuracy for the trained model was 98.88 % when it was assessed using the test data that had not yet been viewed. 
•	To show the capabilities of the model, a sample prediction was made and the projected disease class was compared to the actual class. 
