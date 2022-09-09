# Week 2 Assignment 1

Loops can be useful to compute a series expansion of a function. The Taylor series of the inverse tangent function is given by
https://latex.codecogs.com/gif.image?\dpi{110}\arctan(x)=1-\frac{1}{3}x^3&plus;\frac{1}{5}x^5-\frac{1}{7}x^7&plus;\frac{1}{9}x^9&plus;\cdots

We can use the above expression to compute the value of , using the fact that
https://latex.codecogs.com/gif.image?\dpi{110}\frac{\pi}{4}=\arctan(1)=1-\frac{1}{3}&plus;\frac{1}{5}-\frac{1}{7}&plus;\frac{1}{9}&plus;\cdots

TASK: Write a loop to compute the value of pi using the first 1000 terms of the above series. This called the Leibniz formula.


EXPECTED OUTCOME: a value close to pi.