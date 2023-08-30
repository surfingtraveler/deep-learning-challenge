# deep-learning-challenge


OVERVIEW OF ANALYSIS:
To assist the nonprofit Foundation Alphabet Soup with creating a binary classifer in the provided dataset that can predict whether applicants will be successful if funded by Alphabet Soup.

RESULTS:

  * Data Preprocessing
    1.  _What variable(s) are the target(s) for your model?_

        The target variable for my model is _IS_SUCCESSFUL_ in order to find the applicants with the best chance for success as this target variable indicates whether the money was used effectively.
        
    3.  _What variable(s) are the features for your model?_

         APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT.
        
    4.   _What variable(s) should be removed from the input data because they are neither targets nor features?_

         Both EIN AND NAME as these are neither targets nor features.

  * Compiling, Training, and Evaluating the Model
    1. _How many neurons, layers, and activation functions did you select for your neural network model, and why?_
       For the neural network model, I used 4 hidden layers and 150, 130, 90, and 50 neuron nodes.  For the activation functions I used ReLU and Sigmoid since the model is a binary classification mode.


    2. _Were you able to achieve the target model performance?_

       Unfortunately, I was unable to achieve the target model performance of 75%.  The closest I was able to obtain was .7418.

    3. _What steps did you take in your attempts to increase model performance?_
   
       I tried various combinations of increase the epochs from 100 to 200 in my first Optimization and from 100 to 150 and 4 hidden layers in my third Optimization.  I also increased the number of neuron nodes.

SUMMARY:
I was disappointed as none of my optimization attempts changed the accuracy by very much at all.  The highest I was able to achieve with the model was 74.18% - below the 75% target.  In researching it appears the Random forest algorithm might be a good possibility to try this analysis.  Random forest is popular for classification problems and might be better suited for this dataset analysis.


