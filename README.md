[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/t5_8rvXi)
# Experiment 53: Custom Exception (Age Validation)

## Problem Statement

Create a custom exception class named `InvalidAgeException`.
Write a program to read an age.
* If the age is **less than 18**, throw the custom exception with the message "Not eligible to vote".
* Otherwise (age >= 18), print "Eligible to vote".

**Important:** If the exception is caught, you must print "Exception: " followed by the exception message.

## Input Format

* An integer representing age.

## Output Format

* `Eligible to vote` OR `Exception: Not eligible to vote`.

### Example 1

**Input:**

```text
15
```

**Output:**

```text
Exception: Not eligible to vote
```

### Example 2

**Input:**

```text
20
```

**Output:**

```text
Eligible to vote
```
