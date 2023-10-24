In [[C Sharp|C#]], a switch statement is a control flow statement that allows you to choose one of several code blocks to execute based on the value of a variable of expression. It is more concise than multiple if-else statements when there are multiple cases to evaluate.

```c#
switch (expression)
{
    case val1:
        // code to execute if exp = val1
        break;
    case val2:
        // Code to run if exp = val2
        break;
    // etc
    default:
        // Code to run if exp matches no cases
        break;
}

```

It is like an [[If Statement]] in that *if* the expression given is equal to a value, then some outcome will happen. However it specifies multiple outcomes for different values of the expression. The `default` is akin to the `else` in an if statement.
