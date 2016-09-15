# Evaluater
A program that computes the precision and recall after receiving the datapoints and the predictions


I wrote this project when I was working with an ML library called Vowpal Wabbit because it doesn’t have built-in functions to get 
precision/recall/accuracy.
This project is written in C#, and it gets all the previously mentioned values after passing the predictions file and the test instances. 

Currently it doesn’t have support except for multi class (one against all –oaa) classification, 
and soon to add the binary/multilabel(CSOAA) classification. 

You can use the functions written in the evaluate class, and an example of how to use it is mentioned in the program class. 

		I hope this is useful  

