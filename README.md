# Neural_Network_Charity_Analysis

## Overview of the project
Using our understanding of machine learning, we tried to predict whether or not the applicants will be successful using alphabet soup.The dataset contain many organizations that have been funded by alphabet soup and have number of columns that captures the metadata of each organization like organization type and the use of funding amongst others. This project has 3 steps: Preprocessing the data for the neural network, Compile,train and evaluate the model & finally optimizing the model.
For this project, I create a neural network by using Data Manipulation, creating training and testing sets, and analyzed models that I have created.

## Results
### Data Processing
1. To clean the data EIN and NAME columns were removed since they have little to do with the model.
2. The variable we targeted in this module is the IS_SUCCESSFUL column.
3. The varibales considered are : 'STATUS', 'ASK_AMT', 'IS_SUCCESSFUL', 'APPLICATION_TYPE', 'CLASSIFICATION', 'USE_CASE', 'ORGANIZATION', 'INCOME_AMT'.

### Compiling, Training, and Evaluating the Model
1. Attempt 1
2 Hidden Layers
80 neurons (Layer1), 30 neurons(Layer2)
Used Relu and Sigmoid Activations Functions and removed "USE_CASE_Other","AFFILIATION_Other" columns.
![Capture](https://user-images.githubusercontent.com/76858662/117715969-fe0ec380-b1a6-11eb-8d51-aefe5149801e.PNG)

2. Attempt 2
3 Hidden Layers
80 neurons (Layer1), 30 neurons(Layer2), 15 neurons(Layer3)
Used Relu and Sigmoid Activations Functions and removed "USE_CASE_Other","AFFILIATION_Other" columns.
![Capture](https://user-images.githubusercontent.com/76858662/117716145-3dd5ab00-b1a7-11eb-89d3-476a921c1440.PNG)

3. Attempt 3
3 Hidden Layers
80 neurons(Layer1), 35 neurons(Layer2), 10 neurons (Layer3)
Used Relu and Sigmoid Activations Functions.
![Capture](https://user-images.githubusercontent.com/76858662/117716457-9dcc5180-b1a7-11eb-9f7c-093f1ba9437a.PNG)

4. Attempt 4
3 Hidden Layers
80 neurons (Layer1), 30 neurons(Layer2), 15 neurons (Layer3)
![Capture](https://user-images.githubusercontent.com/76858662/117716612-cf451d00-b1a7-11eb-8c3b-1e258ede8b42.PNG)

## Results
The models accuracy ended up being 72.8% which was quite okay as it was improving. Although I did not get to the accuracy of 75% , it is possible the reason for this is we have to drop more features which may have affected the neural network. The best way to increase the accuracy of your model is to have more data. If we have solid data added to this model, the accuracy of this model will be much better.





