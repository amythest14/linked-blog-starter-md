In [[C Sharp|C#]], variables are used to store and manipulate data during the execution of a program. They have a specific type that determines the kind of data they can hold. 

In some languages, these [[Data Types]] must be explicitly declared in code. These are called statically typed languages, and include C# and [[C++]]. Other languages such as [[Python]] are dynamically typed which means their variable does not need to be specified in code and is determined in runtime.

Declaration:

To declare a variable, you specify its type, followed by its name.

Initialisation:

Initialisation is the process of assigning an initial value to a variable. This can be done at the same time as declaration as follows:

```cs
int age = 25;
```

Variable names are case-sensitive, meaning `age` and `Age` are different variables. Variables are generally named in camel case, so the first word starts with lower case and following words start with capital letters such as `ageYears`. Variables cannot contain spaces.

A new value can be assigned to an existing variable using the assignment operator (`=`).
For example:

```cs
age = 30;
```

Variables have a scope, which determines where they are accessible. In C#, variables can be defined at the level of [[Methods]] (local variables) or [[Classes]] (field or instance variables). The scope defines where the variable can be used within the program.

In C#, you can declare variables using implicit typing (`var`) in place of a data type, to make the compiler to infer the variable type based on the assigned value.

Related to variables are [[Constants]], which are very similar but are immutable (their value cannot be changed once it is assigned).

