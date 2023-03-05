# Signal Quality
<h3> Building a classifier to determine the signal quality(or strength) with given parameters.</h3>

Project Overview:<br>
<ul>
  <li>This is a project for determining the signal strength of an equipment.</li>
  <li>Any equipment manufacturing company can use this classifier to predict the signal strength of an equipment manufactured.</li>
  <li>The dataset used containes 1500+ records of various equipments.</li>
  <li>Steps performed:
    <ul>
      <li>Importing necessary libraries.</li>
      <li>Loading dataset.</li>
      <li>Exploratory data analysis</li>
      <li>Data cleansing</li>
      <li>Data preparation</li>
      <li>Creating a neural network</li>
      <li>Training of the neural network created</li>
      <li>Prediction and testing</li>
      <li>Plotting Training & Validation accuracy graph</li>
      <li>Plotting Training & Validation loss graph</li>
      <li>Classification report</li>
      <li>Resampling the data</li>
      <li>Data preparation of re-sampled data</li>
      <li>Creating a new neural network with updated features</li>
      <li>Training of the newly developed neural network</li>
      <li>Prediction and testing</li>
      <li>Plotting Training & Validation accuracy graph</li>
      <li>Plotting Training & Validation loss graph</li>
      <li>Classification report</li>
   </ul>
  </li>
<br>

![image](https://user-images.githubusercontent.com/72664379/194483126-3b79a1d8-2d4a-4b74-8553-c6d7fd7e93a8.png)
<br>Distribution of the signal strength(target class).
<br><br>

![image](https://user-images.githubusercontent.com/72664379/194483530-8a8685be-3126-4fc5-9739-c4bac531cce3.png)
<br>Frequency of each category of the signal strength(target class) in the dataset.
<br><br>

  ![image](https://user-images.githubusercontent.com/72664379/194741968-c29b1729-ca35-4721-a504-8409861ec74b.png)
<br>Graph showing the plot of Training & Validation accuracy of the neural network model created.
  <br><br>
  
  ![image](https://user-images.githubusercontent.com/72664379/194741982-3230875c-da49-4244-b547-742b3556c08b.png)
<br>Graph showing the plot of Training & Validation loss of the neural network model created.
  <br><br>
  
  ![image](https://user-images.githubusercontent.com/72664379/194742041-a89da275-6485-487a-a182-d17c6f6ecd62.png)
<br>Graph showing the plot of Training & Validation accuracy of the updated neural network model.
  <br><br>

![image](https://user-images.githubusercontent.com/72664379/194742069-70146fa1-27a9-4aeb-b18d-11fd356d6f60.png)
<br>Graph showing the plot of Training & Validation loss of the updated neural network model.
  <br><br>

<h3>Conclusions:</h3>
<ul>
  <li>Model 1:
  <ul>
    <li>Accuracy score: ~60%</li>
    <li>Loss score: ~93%</li>
  </ul>
  </li>
  
  <li>Model 2(updated model):
  <ul>
    <li>Accuracy score: ~74%</li>
    <li>Loss score: ~69%</li>
  </ul>
  </li>
  <li>Hence, improvisation is seen in the scores.</li>
  <li>A better dataset could be used for better results and predictions.</li>
</ul>
