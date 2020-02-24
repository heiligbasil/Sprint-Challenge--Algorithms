#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n) -> grows linearly


b) O(n^c) -> polynomial; as the input increases the time taken increases faster


c) O(n) -> it is recursive but only grows linearly because a single call is being made

## Exercise II


I would start at floor 0 (ground level) and try to throw an egg. If it didn't break I would move up to the next floor and see if it got broken when thrown off. I would repeat this until I reached a floor where the egg broke. I would say that I could do this in a `for` loop and as soon as an egg broke, I would store the value of the `current floor - 1` and break out of the loop. The runtime complexity is O(n) because it would scale linearly no matter the height of the building. 