# The-Spam-Filter

In this project, I used a SMS dataset to create a spam filter. In this dataset, there are 5572 SMS messages which are filtered as spam or ham 
by people. The dataset was collected by Tiago A. Almeida and José María Gómez Hidalgo. 
After I opened the data, I split it into two parts to train and test.
I started my process with data cleaning. I cleaned punctuations and translated letters as lower case. I created new columns for each word. 
After the cleaning step, I started my train and test step. I used naive bayes method to classify my data for two options (Spam| Ham). For this method, I 
calculated possibilities and parameters. I used these parameters to classify my data and I created a function for it. After that, I created another 
function to use on my test data set. To see my function's success, I calculated the accuracy.

## Conclusion

I calculated the rate between correct classification and total to see accuracy. I obtained the accuracy as 98.7%. My algorithm classified 1100 SMS 
messages
truly from 1114 SMS messages. As a conclusion, I used Naive Bayes algorithm to classify the SMS message dataset and was successful with a highly accurate score. 

