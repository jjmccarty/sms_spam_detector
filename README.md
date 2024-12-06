# sms_spam_detector
SMU AI Challenge - Module 21

The following module refactors code designed to predict if a text message is ham or spam from an existing notebook into a second file that organizes the original logic into a set of functions.  These functions include:

1. ```sms_classification``` which takes a dataframe as the input and creates a pipeline with a Support Vector Classification (SVC) model for the fitted model to be returned. 

2. ```sms_prediction``` which takes text as an input and uses the model created by ```sms_classification``` to predict if the message is ham or spam. The resulting prediction is returned from the function. 

In order to stream line the availability of the model this is used to create a small Gradio application that allows a user to input in the text for a message and the application will output the prediction for the message.  

The following messages were used to test the output of the application:


1. You are a lucky winner of $5000!
2. You won 2 free tickets to the Super Bowl.
3. You won 2 free tickets to the Super Bowl. Text us to claim your prize.
4. Thanks for registering. Text 4343 to receive free updates on medicare.

> Note that screenshot files were added to this repository to verify the execution of each message in the application.  These are provided in the Resources folder. 

