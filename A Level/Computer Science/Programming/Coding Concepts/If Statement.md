In [[C Sharp|C#]], an `if` statement is a conditional statement that allows you to execute a block of code based on the evaluation of a condition. 

Here is the general syntax of an `if` statement:

```c#
if (condition)
{
    // code to execute if condition is met 
}
```

You can also specify something to happen if the condition is not met, with an `else` block:

```cs
if (condition)
{
    // code to execute if condition is met
}
else
{
    // code to execute if condition is not met
}
```

If there are additional conditions to be evaluated if the additional `if` condition is false, then a `else if` statement is used:

```cs
if (condition1)
{
    // code to execute if condition1 is true
}
else if (condition2)
{
	// code to execute if condition1 not met but condition2 is met
}
else
{
    // code to execute if neither condition is met
}
```
