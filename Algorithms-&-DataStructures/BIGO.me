# Big O Notation

## What is Big O Notation?

In mathematics, Big O Notation is a way to represent the complexity of a function. It is a way to represent the number of operations that a function will take to complete.

To break it down into layman's terms, it refers to the cost of your program via space and run-time requirements.

## Why is Big O Notation Important?

We do not have the privilege of all owning the same computer. An application that may take 0.01 seconds on my 4k game-ready rig to run will not be able to run in 0.1 seconds on my 2014 Macbook pro.

Due to this fact, we need to be able to estimate the time it will take to run our program. It is key to gauging the scalability of an application to have some sort of universal metric to gauge the performance of our application.

Big O notation is the tool we use to make these measurements.

## Measuring Performance With Big O

### Space Complexity

The number of memory locations that your program will use.

### Run Time Complexity

The number of operations that your program will take to complete.

### The Actual Measurements

As the number of elements in the array grows, the number of operations that your program will take to complete grows. This is called [algorithmic efficiency](https://en.wikipedia.org/wiki/Algorithmic_efficiency). The chart below is a visual representation of this. The more operations that must be completed, the less efficient the program is.

![Towards Data Science Big O Complexity Chart](https://miro.medium.com/max/1400/1*5ZLci3SuR0zM_QlZOADv8Q.jpeg)

So, as we can see measurements by time in a world where we don't all use the same system are irrelevant. It also helps that Big O is language agnostic.

We can look at two examples in Javascript and in python.

## O(1)

```python
#Python
numA = 2
numB = 4
print(numA + numB)
```

```javascript
//Javascript
const numA = 2,
    numB = 4;
console.log(numA + numB);
```

OutPut

```
6
```

The above can be referred to for simplicity as a constant time operation. While more than 1 operation occurs, assigning both variables, looking for the values of both variables, and adding the values together. None of these operations have the potential to change the time it takes to run all systems equally.

We would refer to this as O(1).

While an operation involving 5000 preset variables might take much longer than the one above with just 2, the amount of time it takes is still constant and would still be O(1).

## O(n) and O(log n)

```python
#Python
rangeN = 5;
for num in range(rangeN):
    print(num)
```

```javascript
//Javascript
const rangeN = 5;
for (var i = 0; i < rangeN; i++) {
    console.log(i);
}
```

Output

```
0
1
2
3
4
```

The above operations are similar to O(1) in that it has the potential to remain constant as long as **n** remains constant. However, it also has the potential to be of variable length, theoretically, n is the number of elements in the array, and n could be any number. While in the above case it is 5, it could be 10, 20, 30, 1000, or 1000000.

We can represent this linear variability with the letter n and attach it to O (our growth rate) to get O(n).

### O(log n)

Let's quickly talk about O(log n). This is a time operation that is proportional to the logarithm of the number of elements in the array. While time increases linearly n goes up exponentially. There's no better explanation than this [stack overflow](https://stackoverflow.com/a/2307330) answer](https://stackoverflow.com/a/2307330). An example of log base 2 would be.

```javascript
//Javascript
const rangeN = 10;
for (var i = 1; i < rangeN; i = i * 2) {
    console.log(i);
}
```

```
1
2
4
8
```

## O(n log n)

An exceedingly rare algorithm type to run into n log n can be described as having log-linear complexity.

What this essentially means is that a log n algorithm as seen above will have an assurance rate of N times.

An example is unnecessary here because you can just think of the above example in O(log n) being nested inside of a loop that is executed n times.

## O(n^2)

```javascript
function example(array1, array2) {
    for (var i = 0; i < array1.length; i++) {
        for (var j = 0; j < array2.length; j++) {
            console.log(array1[i]);
            console.log(array2[j]);
        }
    }
}
```

## O(2^n)

An example of an algorithm that has an exponential growth rate is the Fibonacci sequence.

If you are unfamiliar with it, it looks something like this.

    0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 144

You may be able to see what it is already. You can see that each number in the sequence is the sum of the two previous numbers.

The growth rate doubles with each iteration and we have N iterations.

It's exceedingly easy for this type of notation to get out of hand. You can see iteration 13 is 144 however we only have to travel to iteration 30 to already be at 514229.

## O(n!)

I don't know a scenario in which an individual would run into this. For a quick example think of something we do up to 3 times repeating.

3 _ 2 _ 1 = 6, we have done that task a total of 6 times. Not bad right?

Let's do it 5 times.

5 _ 4 _ 3 _ 2 _ 1 = 120, we have done that task a total of 120 times. With just 2 more interactions we have done it 20 times more. Still, we have modern computers who cares?

Let's do it 20 times.

20 _ 19 _ 18 _ 17 _ 16 _ 15 _ 14 _ 13 _ 12 _ 11 _ 10 _ 9 _ 8 _ 7 _ 6 _ 5 _ 4 _ 3 _ 2 \* 1 = 2.432902e+18, we have done that task a total of 2.432902e+18 times.

Which is 2.0274183e+16 times more than our SECOND example of 120 times.

So it's safe to say if you find yourself running into this, you should probably look into a better algorithm.

# The Rules

## Constant Removal

Say the result of our application is line by line:

```
O(1)
O(n)
O(n)
O(n)

O(1)
O(1)
O(1)
O(1)
```

The total of our applications running is:

O(1) + O(n) + O(n) + O(n) + O(1) + O(1) + O(1) + O(1)

or

O(5 + 3n)

When computing O notation we do not care about things that will always happen the same way. So we can remove the constant-time operations.

This allows us to simplify our notation. Giving us;

O(n) for the entire application.

## Worst Case

This is a referral to the upper bound of the time it takes to run the algorithm. The worst case is the case where the algorithm is the most time-consuming.

## Best Case

This is a referral to the lower bound of the time it takes to run the algorithm. The best case is the case where the algorithm is the least time-consuming.

### Quick Example

```javascript
// Array of 33 names
const names = ['Adam', 'Alex', ...'Victor', 'Walter'];

for (var i = 0; i < names.length; i++) {
    if (names[i] === 'Alex') {
        console.log('Alex found at index ' + i);
        break;
    }
}
```

```
Alex found at index 1
```

```javascript
// Array of 33 names
const names = ['Adam', 'Aaron', ...'Victor', 'Walter', 'Alex'];

for (var i = 0; i < names.length; i++) {
    if (names[i] === 'Alex') {
        console.log('Alex found at index ' + i);
        break;
    }
}
```

```
Alex found at index 32
```

For the above 2 examples. In example 1, n = 2, and in example 2, n = 33.

The worst-case as long as our array is always 33 names is O(33). While the best case is O(1).

### What does that mean?

When using Big O notation, we need to always assume that the time it takes to run the algorithm is the worst case. So regardless of where Alex is in the array, it is always assumed he will be last every time.

## Parameters and Dropping Nondominant

So far we've needed examples that only take 1 n parameter. But we can also have examples that take multiple n parameters.

```javascript
function example(array1, array2) {
    for (var i = 0; i < array1.length; i++) {
        console.log(array1[i]);
    }

    for (var i = 0; i < array2.length; i++) {
        console.log(array2[i]);
    }
}
```

The above would have an O notation of O(n + m). This is because we notate both inputs into a function separately. The only way we are allowed to eliminate an input parameter is if it is constant.

However the above is only true if there is a nondominant input operation.

We can see where it isn't true below.

```javascript
function example(array1, array2) {
    for (var i = 0; i < array2.length; i++) {
        console.log(array2[i]);
    }

    for (var i = 0; i < array1.length; i++) {
        for (var j = 0; j < array2.length; j++) {
            console.log(array1[i]);
            console.log(array2[j]);
        }
    }
}
```

Here we have our O(n^2) example with an extra loop inside but not nested. So you'd think given 2 inputs that our O notation would be. O(n + n^2). However, in a case such as this, we only care about the dominant or more performance-intensive notation. So we can drop the nondominant input. Giving us O(n^2).
