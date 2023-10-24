In [[C Sharp]] and other languages using the [[Object-Oriented Programming]] paradigm, a class is a blueprint for creating [[Objects]] of a given type. It specifies the [[Properties]] and [[Methods]] that an object will have. 

Here is a simple example of a class:

```cs
public class Person
{
    // Attributes/Fields
    public string FirstName;
    public string LastName;
    public int Age;

    // Methods
    public void SayHello()
    {
        Console.WriteLine($"Hello, my name is {FirstName} {LastName} and I am {Age} years old.");
    }
}
```

To create objects from this class you do:

```cs
Person person1 = new Person();
person1.FirstName = "John";
person1.LastName = "Doe";
person1.Age = 30;

person1.SayHello(); // This will print "Hello, my name is John Doe and I am 30 years old."
```
