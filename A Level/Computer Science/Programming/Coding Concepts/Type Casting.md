In [[C Sharp|C#]], type casting is when the value of one data type is assigned to a [[Variables|variable]] of a different data type.


To convert one data type to another, the `Convert` class of methods is used:

| Data Type | Method               |
| --------- | -------------------- |
| Integer   | `Convert.ToInt()`    |
| Double    | `Convert.ToDouble()` |
| String    | `Convert.ToString()` |
| Char      | `Convert.ToChar()`   |
| Boolean   | `Convert.ToBoolean()`                     |


For example, to convert a double to an integer, you would do:

```cs
double variable1 = 1.23;
int variable2 = Convert.ToInt32(variable1);
```

