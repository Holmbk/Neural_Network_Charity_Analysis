# Neural_Network_Charity_Analysis
## Purpose
Using Alphabet Soup's CSV to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup
## Results
### Data Preprocessing
- What variables are considered the targets for your model? APPLICATION_TYPE, CLASSIFICATION, and ASK_AMT
- What variables are considered to be the features for your model? APPLICATION_TYPE, and CLASSIFICATION
- What variables are neither targets nor features, and should be removed from the input data? EIN and NAME
### Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why?
  Layer1 was 80 hidden nodes, and Layer2 was 30 hidden nodes Activation was sigmoid
- Were you able to achieve the target model performance? No it only reached 74%
- What steps did you take to try and increase model performance? Went to optimize the solution.  This time kept NAME as one of the variables.
The lookd at NAME value counts for binning. Looked at how many NAMEs value counts were less than 6. If any have a value less that 6 were replaced by "other". Then replaced APPLICATION_TYPE counts less than 600 as "other". Looked at CLASSIFACTION for binning.  Any classifactions less that 1000 replaced by "other". Used 3 layers this time (100), (30), and (10). Activation was sigmoid.  This time performance 78.7%
## Summary
The variables may look obvious to remove or use.  However when running the evaluation you may see that a different variable should be used or not removed.
