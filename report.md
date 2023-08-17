# Model Analysis

### Data Preprocessing

  - What variable(s) are the target(s) for your model?

        The target variables are in the "IS_SUCCESSFUL" column.
  
  - What variable(s) are the features for your model?

        The features are in every column besides the "IS_SUCCESSFUL" column.
  
  - What variable(s) should be removed from the input data because they are neither targets nor features?

        The "EIN" and "NAME" columns were removed becasue they were not targets or features.

### Compiling, Training, and Evaluating the Model

 - How many neurons, layers, and activation functions did you select for your neural network model, and why?

        I used two layers, the first layer using 9 neurons and the second layer using 5 neurons. I chose these based on the amount of feature data.
 
 - Were you able to achieve the target model performance?

        I was only able to reach an accuracy of about 73%.
 
 - What steps did you take in your attempts to increase model performance?

        I ran the model multiple times, changed the number of layers, chaged the number of neurons, and changed the activation arguments.

Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.

        Overall, the model had an accuracy of approximately 73% in predicting the classification problem. Using a model with greater correlation between input and output would likely result in higher prediction accuracy. This may be accomplished by cleaning the data differently/better, as well as using different activation functions and more iterations.