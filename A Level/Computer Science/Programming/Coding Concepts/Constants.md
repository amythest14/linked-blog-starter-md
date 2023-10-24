In [[C Sharp|C#]], constants are immutable values which are known at compile time and do not change for the life of the program. They function very similarly to [[Variables]], except their value can never change in run time.

For example instead of having a variable to represent pi like this:

```cs
double pi = 3.1415
```

you should instead have:

```cs
const double pi = 3.1415
```

as the value of pi will never change. Leaving as a variable could be a security concern as someone could change the value of the variable, so setting this as a constant eliminates this.