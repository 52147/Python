# Python

## lambda function

- Lambda comes from the Lambda Calculus and refers to anonymous functions in programming.
- It allows you to write quick throw away functions without naming them. 
- It also provides a nice way to write closures. With that power you can do things like this.

```
def adder(x):
    return lambda y: x + y
add5 = adder(5)
add5(1)
6
```
- As you can see from the snippet of Python, the function adder takes in an argument x, and returns an anonymous function, or lambda, that takes another argument y. 
- That anonymous function allows you to create functions from functions. 
- This is a simple example, but it should convey the power lambdas and closures have.
