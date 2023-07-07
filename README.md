# Ml-models

## first-model : 
  We trained the artificial_neural_network_images model and the support vector machine on traffic sign classification dataset
  
  #### dataset details : 
  This data set contains 6358 manually labeled category labels. The labels include the following 10 categories: “GuideSign”, “M1”, “M4, “M5”, “M6”, “M7”, “P1”, “P10_50”, “P12”, “W1”, corresponding to ten Different traffic sign categories. All data has been manually divided into training set and test set according to the proportion, and the relevant training set annotation json file is provided.
  The data set contains two folders train and test, as well as a unified train.json file to save the annotations of all training data sets. The image tags save the dictionary serialized in json format, and all the annotations are saved in train.json Under the key named annotations in the file.
  
  You can download and get more details for dataset through the link :
  
   https://www.kaggle.com/datasets/wjybuqi/traffic-sign-classification-and-recognition

   # Results
<table>
<thead>
  <tr>
    <th>Operation Mode</th>
    <th colspan="1">accuracy</th>
    <th colspan="1">loss</th>
  </tr>
</thead>
<tbody>
  <tr>
  </tr>
  <tr>
    <td>Ann</td>
    <td>88.44%</td>
    <td>40.25%</td>
  </tr>
  <tr>
  </tr>
  <tr>
</tbody>
</table>

<br/>

## second-model : 
  We trained the artificial_neural_network_images model and the support vector machine on Students Performance in Exams dataset

  You can download and get more details for dataset through the link :
  
   https://www.kaggle.com/datasets/spscientist/students-performance-in-exams
   
   # Results
<table>
<thead>
  <tr>
    <th>Operation Mode</th>
    <th colspan="1">accuracy</th>
    <th colspan="1">loss</th>
  </tr>
</thead>
<tbody>
  <tr>
  </tr>
  <tr>
    <td>Ann</td>
    <td>89.38%</td>
    <td>23.21%</td>
  </tr>
  <tr>
  </tr>
  <tr>
</tbody>
</table>


## third-model : 
#### description
convolution neural network (CNN) plays an important role. However, the classical CNN has the problem of consuming too much computing resources. To solve this problem, first, this paper proposed a dilated CNN model which is built through replacing the convolution kernels of traditional CNN by the dilated convolution kernels, and then, the dilated CNN model is tested on the Mnist handwritten digital recognition data set. Second, to solve the detail loss problem in the dilated CNN model, the hybrid dilated CNN (HDC) is built by stacking dilated convolution kernels with different dilation rates.

With the help of the model in the paper https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8756165
, we improved the model and implemented on traffic sign dataset.

  #### dataset details : 
  using the same dataset in first model 

  
#### Implementation details:

Ratio used for training : 4062
Ratio used for Validation : 1270
Ratio used for testing : 1016

block diagram :         
1- CNN block diagram                           2- Dilated CNN block diagram                        3-  HDC block diagram

![image](https://github.com/mohamed-gasser/Ml-models/assets/102036714/dd8d13ba-0a6f-4a3c-9232-c74731ddbd56)       ![image](https://github.com/mohamed-gasser/Ml-models/assets/102036714/0d158ca6-d18a-4f2f-8cbe-86620c950873)     ![image](https://github.com/mohamed-gasser/Ml-models/assets/102036714/cfa9b7d2-0f2b-41df-b885-c1d676a7e874)
                                                           

##### hyperparameters used in your model : 
1- Adam (Learning rate =0.001

2- Droupout (0.25)

3- epochs :35

4- batchSize=32

5- Adding additional hidden layer

6- activation =relu

7- use validation .20 of dataset

8- increasing # of units in hidden layer to 128

#### accuracy curve

   <img src="https://github.com/mohamed-gasser/Ml-models/assets/102036714/b076f195-9494-456f-ba8c-c356b7af7962)" width="40%" height="20%">

#### loss curve
   
   <img src="https://github.com/mohamed-gasser/Ml-models/assets/102036714/6220717e-0d09-4515-b331-bb99d7b005dc" width="40%" height="20%">

# Results
   
   <img src="https://github.com/mohamed-gasser/Ml-models/assets/102036714/4f82d116-b5c7-4960-a9ae-4112ea8ded48" width="80%" height="30%">


## fourth-model : 
  We trained the artificial_neural_network_images model and the support vector machine on dataset.
  
  #### dataset details : 
IMDB movie review sentiment classification using CNN and keras/colab
tf.keras.datasets.imdb.load_data

#### description
Based on the feedback, classify the films on the basis that it is good or not good, using the RNN model for training on dataset iMDB movie review have positive and negative feedback.

   # Results
<table>
<thead>
  <tr>
    <th>Operation Mode</th>
    <th colspan="1">accuracy</th>
    <th colspan="1">loss</th>
  </tr>
</thead>
<tbody>
  <tr>
  </tr>
  <tr> 
    <td>Rnn</td>
    <td>87.34%</td>
    <td>37.41%</td>
  </tr>
  <tr>
  </tr>
  <tr>
</tbody>
</table>

<br/>

#### Contact
You can communicate by following e-mails If you have more questions about the project or to get the all src code :


o mohamedgasser230@gmail.com



