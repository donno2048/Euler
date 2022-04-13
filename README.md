# Project Euler

This is a solution to the first 50 problems of Project Euler.

I got bored after 50 problems but if I'll have some spare time I'll maybe try to solve more in the future.

Almost all of the solutions are one second or less, except in a few cases, if the solution is more than 10 seconds it's noted as a comment, not even one of them is a minute or more.

I didn't really try to optimize the solutions unless it was obvious to me to find the optimized solution.

In some cases the solutions use the form:

```py
for i in range(RANGE):
    ...
    if condition:
        ...
        break
    ...
```

Instead of:

```py
i = 0
while True:
    ...
    if condition:
        ...
        break
    ...
    i += 1
```

In most cases this is because there is an upper bound, but sometimes it's just because I want to stop at a certain threshold.
