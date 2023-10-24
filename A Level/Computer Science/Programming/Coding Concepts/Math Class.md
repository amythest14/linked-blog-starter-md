
The `Math` [[Classes|Class]] in [[C Sharp|C#]] provides various [[Methods]] to do mathematical functions. Here are the most commonly used methods in the `Math` class:

 
 `Math.Abs`: Returns the absolute value of a number.
 
 ```cs
 int result = Math.Abs(-5); // result = 5
```

`Math.Round`: Rounds a decimal value to the nearest integer or a specified number of decimal places.

```cs
double roundedValue = Math.Round(3.14159, 2); // roundedValue = 3.14
```
 
`Math.Max` and `Math.Min`: Returns the maximum or minimum value among two or more numbers.

```cs
int max = Math.Max(10, 5); // max = 10
int min = Math.Min(10, 5); // min = 5
```

`Math.Sqrt`: Returns the square root of a number.

```cs
double squareRoot = Math.Sqrt(25); // squareRoot = 5.0
```

`Math.Pow`: Returns a specified number raised to the power of another number.

```cs
double powerResult = Math.Pow(2, 3); // powerResult = 8.0`
```

`Math.Floor`: Always rounds a number down

`Math.Ceiling`: Always rounds a number up

```cs
double floorValue = Math.Floor(3.7); // floorValue = 3.0
double ceilingValue = Math.Ceiling(3.2); // ceilingValue = 4.0
```

