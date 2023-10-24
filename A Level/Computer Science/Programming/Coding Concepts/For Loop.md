In [[C Sharp|C#]], the `for` loop is a control flow statement that allows you to execute a block of code a specific number of time. It is a way to iterate over a sequence of values or perform a set of operations with a known iteration count.

Here is the general syntax of a `for` loop:

```cs
for (initialization; condition; iteration)
{
    // Code block to execute repeatedly
}
```

The initialisation part is used to set up initial values and initialise the loop control variables. For example `int i = 0`. This essentially establishes the starting value of the variable that increments (or decrements) every execution of the loop.

The condition part of the code is evaluated before each iteration of the loop. If true, the code inside of the loop is executed. If false, the loop terminated, and the program continues with the next statement after the loop. For example `i < 5`. In this case the iteration will continue whilst `i` is less than 5.

The iteration part of the loop is executed after each iteration of the loop. It updates the loop control variables. Typically this will be `i++`, which increments `i` by one. Alternatively it could be `i--` to decrement `i`, or `i += x` where `x` is an integer to increment `i` by some other number or variable.

So this example all together:

```cs
for (int i = 0; i < 5; i++)
{
    // Code to be executed repeatedly
}
```

Additionally, you can break out of the loop prematurely using the `break` statement or skip the current iteration and move to the next iteration using the `continue` statement if certain conditions are met.

```cs
    if (i == skippable)
    {
        continue; // Skip the current iteration and move to the next iteration
    }
    
    if (i == breakable)
    {
        break; // Terminate the loop
    }
}

```
