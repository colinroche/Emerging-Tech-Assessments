# Emerging-Tech-Assessments
Repository related to Assessments in Emerging Technologies Module

# Task [1] Square-Root to 100 decimal places

## Research

### The Mathamatics of Calculating the Square Root of Numbers
I decided to start my research on the the mathamatical aspect on calculating root numbers, what equations people have used in solving these and how this might help me better understand the optimal way to approach problem.

I thought it would be attentional to look at this problem form mutiple aspects including ideas that date back centuries to get a firm grasp on its fundentimentals which might show  how to code this in the most efficient way.

These include the likes of the Babylonian method, dating back the Babylonian period and others mathimations take on the subject.


### Conclusion
In most cases when trying the calculate the square root of a number with reference to this research most ideas are too simple of convoluted for use in computing.
The less complex of these method are not accurate enough to calculate the square root to a correct 100 decimal places.

The more convoluted do not seem to be an efficient way of doing this either, requiring the checking a number of different variable and to be exponential in every iteration of the method. This might work for computation of lower decimal answer but has potentional problem when it comes to 100 decimal places.

### The Babylonian Method
![](images/babylonian.png)

This way of finding square roots was discoverd by the Babylonian Civilation(1500BC) and is still widely used today.

It seems to be a very accurate way of calculating square roots, the question is how accurate and if its a feasible way of doing it.

## Documentation
### Simple Square Root
A quick and simple way of calculating the square root of a number in python is using the ** - expontentiation operator.  They way to do the is by having the exponent number set to .5.  The reason this works is that in maths, the square root of a number is the number multiplied the expontent of .5.

The problem with this method of getting the square root of number is that in python, the calculation doesn't seem to be stored with extreme accurrency.  If fact python seems to only store this number accurrently to 12 decimals places which is insufficent for us.  The storing of the absolute of the calculation is necessary to get the number to an accurate 100 decimals.

### The Babylonian Method
I decided to test this method be firstly trying to output the square root of 2, using it, to 100 decimal places.  After successfully doing this i thought it was the right method to go with.  The problem the arose though was similar to the simple operators method, storing the value of the output in its absolute value allowing the output to be accurate it to 100 decimal places.

## References

### Task [1] - Square-Root of 2 outputted to 100 decimal places
The Written Method
* [Pencil and Paper Method](https://mathlesstraveled.com/2009/06/11/square-roots-with-pencil-and-paper-method-2/)
* [Quick way of getting square roots](https://www.youtube.com/watch?v=PJHtqMjrStk)
* [Calculating square roots without a calculator](https://www.youtube.com/watch?v=uIrjN2Onn8M)
* [Babylonian Method](https://mathlesstraveled.com/2009/05/18/square-roots-with-pencil-and-paper-the-babylonian-method/)
