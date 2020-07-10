# OneVsAll-classification
using OneVsAll classification algorithm to predict handwritten digits

working of one vs all classification

to understand the working of one-vs-all classification we need to understand logistic regression


what is logistic regression ?

it is a learning algorithm used to predict values between 0 and 1 i.e logical output hence the name logistic regression.

example : predicting whether a person has a particular disease or not 
          predicting whether a car sales value will cross a particular value or not
          
logistic regression can also be used to predict something that has multi-class output
example : classification of digits using its images as input 
          finding out what company a person gets placed to given his skills and qualification etc.
          
          
 working of logisitic regression .
 
 before understanding logistic regression we need to understand something called sigmoid function.
 
 ![alt text](https://www.google.com/imgres?imgurl=https%3A%2F%2Fupload.wikimedia.org%2Fwikipedia%2Fcommons%2Fthumb%2F8%2F88%2FLogistic-curve.svg%2F320px-Logistic-curve.svg.png&imgrefurl=https%3A%2F%2Fen.wikipedia.org%2Fwiki%2FSigmoid_function&tbnid=VjglH3kRCVECZM&vet=12ahUKEwiVv8rKhcLqAhXc-jgGHfwsDUUQMygAegUIARC0AQ..i&docid=avewwmVOe63F1M&w=320&h=213&q=sigmoid%20function%20graph&ved=2ahUKEwiVv8rKhcLqAhXc-jgGHfwsDUUQMygAegUIARC0AQ)

 the image shown here is a sigmoid function . basically it converts any number between (0,1) , this function is necesary as the output we predict should be logical
 so anything >= 0.5 will be predicted as 1 else 0.
 
 for more detailed explanation of logistic regression follow the link -> https://towardsdatascience.com/logistic-regression-detailed-overview-46c4da4303bc
 
 OneVsAll
 
 one-vs-all is the same as logistic regression except that we repeat the algorithm multiple times
 
 the number of times we repeat the algorithm depends on no of multi-classes present 
 
 
 ![alt text](https://www.google.com/imgres?imgurl=https%3A%2F%2Fmiro.medium.com%2Fmax%2F1400%2F1*RElrybCZ4WPsUfRwDl7fqA.png&imgrefurl=https%3A%2F%2Ftowardsdatascience.com%2Fmulti-class-classification-one-vs-all-one-vs-one-94daed32a87b&tbnid=rGntKT8qYAwfZM&vet=12ahUKEwjVk9SaiMLqAhVV7jgGHZHBBpkQMygBegUIARCnAQ..i&docid=pWq4eSSQh0a_xM&w=700&h=438&q=one%20vs%20all%20classification&ved=2ahUKEwjVk9SaiMLqAhVV7jgGHZHBBpkQMygBegUIARCnAQ)

 
