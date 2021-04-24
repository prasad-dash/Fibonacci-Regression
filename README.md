# Fibonacci-Regression
Fibonacci-numbers follow the rule :
Fn+1/Fn=1.618033...
I tried to model this relation using a linear regression in the form:
Fn+1=(1.618)Fn+0
Library used:
-Scikit Learn
-numpy
-matplotlib.pyplot
During the fit process I first tried with first 100 fibonacci numbers but got a bad result for first 10 numbers.
Then I tried to model it with first 1000 fibonacci numbers I managed to get the first number to 1.618 instead of 1.0.
But in doing so the model resulted in a maximum error of order 10^193.
Surprisingly the graph between log(error)  and number of entries was linear.
