# lambda-function-of-python
This notebook contains simple lambda function example. 

![ht](https://user-images.githubusercontent.com/23361656/135894655-d4d3828c-4c6e-4193-8f47-53bdb4add078.jpg)

Python is an object-oriented programming language. Like all other programming languages such as C, C++, Dart, and even Java has a lambda function in its syntax. 

Python lambda functions are anonymous in behavior and can take any number of arguments with a single expression. 

Python lambda functions are anonymous in behavior and can take any number of arguments with a single expression. In this article, we will learn about one fundamental python syntax. 

Lambda function 

Short Story of Lamda Function:

Before starting to learn a new concept it is wise to know its history like how it came to be in the first place, who, and how it was developed. 

Every tree has its root. Python and any other object-oriented programming language that supports lambda expressions have their root in lambda calculus. Basically, lambda calculus is a computational model developed by Alonzo Church. The inventor systematized the lambda function based on pure abstraction. 

Python is was not a functional language from the beginning. But later in 1994, it has adopted functions like reduce() , filter(), and lambda. 

Syntax:
The basic python function looks like below code snippet.

      >>> def test(x):
            return x
Here, a function 'test' is returning its argument 'x'. 

Lambda expression for this regular function will be,


    >>> lambda x: x

The expression is composed of,

Keyword: lambda

Argument: x

Body: x

Let me elaborate on this code with a bit for you. I am adding a number 5 to the x argument.

    >>> lambda x: x + 5
Here, I am adding 5 to an unknown value. We can surround the above lambda with parenthesis.

    >>> (lambda x: x + 5)(2)
    7
Here is the explanation of how the above line of code worked behind the scene, 

    (lambda x: x + 5)(2) = lambda 2: 2 + 5
                         = 2 + 5
                         = 7
This can seem a bit hard for the beginner. Some of you are thinking it would be nice to set a name for this function. So, what are you waiting for? Let's add an appropriate name to this lambda function. 

      >>> add = lambda x: x + 5
      >>> add(2)
      7
      
We can also write this lambda function in a regular syntax like below.

      >>> def add(x):
            return x + 2
  
This is all about lambda function fundamental. I hope this article helped you understand the basics of the lambda function. 
