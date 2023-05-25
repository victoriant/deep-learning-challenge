# deep-learning-challenge

## Overview:
The nonprofit foundation Alphabet Soup wants to create a tool that can help it select the applicants for funding with the best chance of success in their ventures. It’ll require specific features to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup. 

## Results:

o	What variable(s) are the target(s) for your model?
The “IS_SUCCESSFUL” column was used as the target for our model. 

![Capture](https://github.com/victoriant/deep-learning-challenge/assets/119895467/fff5cba6-3ffe-44b7-97bc-9b3b226bd305)

o	What variable(s) are the features for your model?
The features for our model would include: Application_type, Affiliation, Classification, Use_Case, Organization, Status, Income_AMT, Special_Considerations and Ask_AMT. 

![Capture](https://github.com/victoriant/deep-learning-challenge/assets/119895467/b5e3d08e-3b97-46f3-8457-744c7233cb0e)

o	What variable(s) should be removed from the input data because they are neither targets nor features?
The Name and EIN columns should be removed. 

![Capture2](https://github.com/victoriant/deep-learning-challenge/assets/119895467/5a19976f-5097-4dd0-b5a2-86439ec3b155)

o	How many neurons, layers, and activation functions did you select for your neural network model, and why?
I went with the random approach, trying a variety of neurons, layers and activation functions. 
Test 1: 2 layers, 90/120 Neurons and LeakyReLU activation.
Test 2: 3 layers, 7/14/21 Neurons and relu activation.
Test 3: 4 layers, 10/20/30/40 Neurons and relu activation.
![Test 1](https://github.com/victoriant/deep-learning-challenge/assets/119895467/dde0176b-d4c3-414d-bbee-bf061d3af41d)
![Test 2](https://github.com/victoriant/deep-learning-challenge/assets/119895467/2d007466-d010-4b64-a6dc-70d45bcff037)
![Test 3](https://github.com/victoriant/deep-learning-challenge/assets/119895467/708334c9-dfbc-4af1-8070-e7bf447a6100)

o	Were you able to achieve the target model performance?
Unfortunately no, the highest I was able to achieve was 72.9%
 
o	What steps did you take in your attempts to increase model performance?
My steps involved adding more layers while keeping the neurons relatively close. 

## Summary:
Overall, there was not a big change when adding in additional Layers and Neurons. The three models that I ran all came back at around 73%. With further testing and adding additional features, I believe we would be able to reach a higher accuracy within our models. Allowing us to pass the 75% accuracy and being a valuable tool for Alphabet Soup to use. 
