# Plant-Leaf-Disease-Classification-using-Neural-Network
The results and important lessons learned from the image classification study for plant disease detection are presented in this section. 

Preprocessing and Data Exploration:
•	Three plant diseases were used in the dataset: tomato bacterial spot, potato early blight, and corn common rust.
•	The three classes combined for a total of 900 photos, indicating a balanced dataset
•	For training and assessment, the script successfully executed train-test splits and transformed photos into NumPy arrays.
  ![image](https://github.com/HarshadVortex/Plant-Leaf-Disease-Classification-using-Neural-Network/assets/164507622/2b60408a-d0e8-4ea0-bfdf-788dfaaf7caa)

Training and Model Architecture: 

•	Multiple convolutional layers, max pooling layers, and thick layers were used to construct a convolutional neural network (CNN) architecture. If it is pertinent to the project's objectives, briefly describe the number of layers used. 
•	With a batch size of 128, the model was trained across 50 epochs. 
 ![image](https://github.com/HarshadVortex/Plant-Leaf-Disease-Classification-using-Neural-Network/assets/164507622/7518b27f-b4a3-4545-85dc-a308465900e0)

Training Results: 

•	After 50 epochs, the model attained a training accuracy of 0.9902 and a validation accuracy of 0.971
•	To track the learning process, visualizations of the training and validation loss and accuracy curves were created. (If any observations from the plots were made, mention them.

 ![image](https://github.com/HarshadVortex/Plant-Leaf-Disease-Classification-using-Neural-Network/assets/164507622/2f725b58-78f2-4de1-964a-558ae39e8691)
![image](https://github.com/HarshadVortex/Plant-Leaf-Disease-Classification-using-Neural-Network/assets/164507622/0dd6e65f-06c2-4f0f-bcb6-f5547dca1730)

          
Assessment: 

•	Test accuracy for the trained model was 98.88 % when it was assessed using the test data that had not yet been viewed. 
•	To show the capabilities of the model, a sample prediction was made and the projected disease class was compared to the actual class. 

Conclusions:

Convolutional neural networks (CNNs) were effectively used in this experiment to classify three plant diseases: tomato bacterial spot, potato early blight, and corn common rust. With a test accuracy of 98.88 %, the model proved to have practical applications in agriculture. Future work to improve the accuracy and generalizability of the model should consider exploring other network designs, utilizing data augmentation approaches, and expanding the dataset. All things considered, this effort opens the door for the further development of reliable and automated diagnostic tools and advances the rapidly expanding field of deep learning-based plant disease identification.

