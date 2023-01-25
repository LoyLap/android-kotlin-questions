# kotlin-questions

## How do I start?
- First of all make sure you are screen sharing via Google Chat link. We will try and record the session if you agree.

- You can work in any IDE (IntellJ based is recommended) or directly in the [Kotlin language playground](https://pl.kotl.in/jiZuiC58B). 

- Take up to ~50 mins in total on the following questions, attempt each one and let us know if you have any further questions.

- Questions should progress in difficulty. Feel free to use Google and Stack Overflow, and to embellish your answer if you have time. 

- When you are finished, paste your answers into the playground and share the snapshot with "Copy Link" button.

---
### Question 1 "countdown with steps":

Create a function which accepts two integers (a limit, and a step size) and returns a list of all the numbers counting down to the 1, taking the step size into consideration. If the countdown is not possible, return an empty list, e.g.
```
f(0, 1) // []
f(6, 1) // [6, 5, 4, 3, 2, 1]
f(6, 2) // [6, 4, 2] 
```

### Question 2 "has a duplicate character":

Create a function which accepts a string argument, and returns a boolean. If the string contains at least one repeated character return `true`, otherwise return `false`, e.g.
```
f("xyz") //false
f("loylap") //true 
```

### Question 3 "has duplicate arguments"

Create a function which accepts a variable number of string arguments, and returns a list of dupicate arguments. If there are no duplicates, return an empty list.  e.g.
```
f("a", "b", "c") //[]
f("l", "o", "y", "l", "a", "p") // [l]
```

### Question 4 "min sub-list sum length"
Create a function which accepts a list of integers and a "sum" integer. Return the minimum length of a sub-list which when each element is added together, is greater to or equal than the sum integer. e.g.

```
f(listOf(1, 3, 4), 6) // 2 (smallest sub-list [3, 4])
f(listOf(1, 2, 11, 5, 9, 4, 6), 22) // 3 (smallest sub-list [11, 5, 9])
f(listOf(1, 30, 12, 7, 2, 9, 8), 500) // 0 (none of the integers sums up to 500)
```
