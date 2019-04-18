# C-Interview-Questions-2
1. What is C#? It is a computer programming language that is used in the .NET platform and is an object-oriented programming language.

2. What is a class, what is an object, and how are they related? A class defines the kinds of data and the functionality of objects. An object is how you access the data. So the class is the blueprint for an object. 

3. What is the difference between a class and a struct? Structs are value types and classes are reference types.

4. What is an enum and when should it be used? Enums are lists of constants. When you need a predefined list of values which do not represent some kind of numeric or textual data, you should use an enum.

5. What is the difference between break and continue? The major difference between break and continue statements in C language is that a break causes the innermost enclosing loop or switch to be exited immediately.

6. Can "this be used with a static method? No it cannot.

7. What is the difference between string and StringBuilder in C#? String is immutable, which means that when you create a string you can never change it. Rather it will create a new string to store the new value, and this can be inefficient if you need to change the value of a string variable a lot. StringBuilder can be used to simulate a mutable string, so it is good for when you need to change a string a lot.

8. What are properties? A property is a member that provides a flexible mechanism to read, write, or compute the value of a private field. Properties can be used as if they are public data members, but they are actually special methods called accessors.

9. What are value types in C#? Provide one example value type in C#. The value types directly contain data. Some examples are int, char, and float, which stores numbers, alphabets, and floating point numbers, respectively. myInt = 0;

10. What are reference types in C#? Provide one example of a reference type in C#. You can imagine a reference type similar to a pointer that is implicitly dereferenced when you access them. The built-in reference types supported by C# include: object, string, and dynamic. String a = "hello";

11. What is encapsulation? Encapsulation describes the idea of bundling data and methods that work on that data within one unit.

12. What are nullable types? nullables allow you to assign normal range of values as well as null values.

13. What is a namespace? A namespace is a set of symbols that are used to organize objects of various kinds, so that these objects may be referred to by name.

14. What is the purpose of the "using" statement? The using statement is mostly used when you need to one or more resources in a segment.

15. What is a constructor?  When is it called? A constructor is a special method of a class or structure in object-oriented programming that initializes an object of that type. You call a constructor when you want to create a new object instance.

16. Does C# support the functional programming paradigm? Provide some details in addition to yes/no. Yes it does because it has a lot of features that can be used with functional programming techniques.

17. Explain the static keyword. The statoc keyword means that the variable or function is shared between all instances of that class as it belongs to the type, not the actual objects themselves.

18. How is exception handling done in C#? It is built on 4 key words. Try, catch, finally and throw.

19. What is LINQ and how/when is it used? It is a query syntax that is used to retrieve data from LINQ-enabled data source. Implicitly typed variables: A variable var, which enables the compiler to infer the type of the variable.

20. What is the difference between “as” and “is” operators in C#? The is operator returns true if the given object is of the same type whereas as operator returns the object when they are compatible with the given type.
