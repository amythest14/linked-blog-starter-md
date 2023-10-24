In [[C Sharp|C#]], an array is a data structure that allows you to store a fixed size collection of elements of the same type. It provides a way to organise and access multiple related values under a single variable name.

Arrays are used to work with collections of data, such as a list of numbers, names, or any other type of object. The elements in an array are accessed using an index, which represents the position of the element within the array. 

Here is the general syntax for declaring and initialising an array:

```cs
datatype[] arrayname = new datatype[size] {data to be stored};
```

For example:
```cs
int[] numbers = new int[5] { 1, 2, 3, 4, 5 };
```

Arrays are zero-based, meaning the index of the first element is 0, the second element is 1, and so on. You can access individual elements of an array using this syntax:

```cs
numbers[x]; // Accessing the (x + 1) element
```

You can also modify the value of an array element using the same syntax:

```cs
numbers[1] = 10; // Modifying the value of the second element
```

