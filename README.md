## Hello World!

My name is __*Gregory!*__

- I am learning Git and GitHub.
- GitHub is very interesting.
- I also like the Python Language. 


### Fibonacci Sequence Generator
#### Generates Ten Numbers with a for-loop
```python

def fibonacci():
    current, previous = 0, 1
    while True:
        yield current
        current, previous = current + previous, current

fib = fibonacci()

for x in range(10):
    print(next(fib))
```
