# Module13Challenge
The task is to create a binary classification model using a deep neural network.

This challenge consists of three technical deliverables:

- Preprocess data for a neural network model.

- Use the model-fit-predict pattern to compile and evaluate a binary classification model.

- Optimize the model.
# Technologies
- python 3.9.13
- JupyterLab
- libraries: pandas, pathlib, Keras, TensorFlow, sklearn
- MacOs
# Installation
If you want to run the program yourself and/or enter different data, do the following:
1. To install the project files, go to the GitHub page for the workshop, click on the green Code button, then download the repository as a ZIP file. 
<img width="1040" alt="image" src="https://user-images.githubusercontent.com/111472420/206604132-dfc4bf83-2e00-4206-8d0c-3e0665d4c461.png">
2. Unpack a zip file into the directory you can operate from in JupyterLab. 
<img width="982" alt="image" src="https://user-images.githubusercontent.com/111472420/206604428-197ae718-5f3d-4e69-865a-e4226dca6cd7.png">

3. Install the required libraries via Terminal and Run the code! 
## Optimization
### Alternative model №1
For the first alternative model I decided to:
- add the third hidden layer
- increase number of epochs
- adjust number of nodes in each hidden layer </br>

<br>
<img width="635" alt="image" src="https://user-images.githubusercontent.com/111472420/206605255-acc7d144-d1d1-4219-894f-ef3d7a5013e4.png"> </br>
The results were practically the same, even a bit worse. Therefore it became obvious that it's not necessary to add the third hidden layer and/or increase number of epochs. </br>

### Alternative model №2
For the second model I decided to:
- change the activation function to <i>tanh</i>
- decrease number of epochs</br>

</br>
<img width="635" alt="image" src="https://user-images.githubusercontent.com/111472420/206605940-98354ff1-ab9c-406e-9141-87f67bd68fda.png"></br>
The accuracy went a bit higher, but the overall change is insignificant. Consequently, I believe that these results are as good as they can get. 








