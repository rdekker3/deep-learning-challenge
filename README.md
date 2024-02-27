# deep-learning-challenge
 All code by Ryan Dekker;
 
• IS_SUCCESSFUL is the target (dependent)variable 
• The feature variable includes the ASK_AMT, as how much was asked is a vital part for whther the fund was successful. 
• The EIN and name columns were both removed because they are non-numeric and have no effect on the dependent variable

This nueral network had had two hidden layers and an output layer. These nueral network was run using Rectified Linear Unit and the output layer used Sigmoid Activation. For best performance in validating the test data, the Epochs level was 100. 

These data were skewed with some that needed to be pruned for outliers - classification counts less than two, and application counts less than 500. After outlier removal, these data were much more representative of general trends. These data were able to be modeled well because the "is-successful" dependent variable had a close to even split of successful and unsuccessful, rather than only a tiny fraction being one or the other. Therefore, the binary cross entrophy method was well-suited. 
