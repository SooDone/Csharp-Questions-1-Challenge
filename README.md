# Csharp-Questions-1-Challenge
You are preparing for a software engineering job interview where you will be asked questions about C# development using Visual Studio and .NET. The following questions are ones that might be asked in an interview. To support your preparation, you are to create a markdown document that is hosted on GitHub that lists the questions, your answers, and supporting documentation/links.

**Q: What is a namespace?** They are used to give  the compiler context for names that define information.

**Q: What are value types?** Value types are variables that can be directly assigned a variable and directly have data.

**Q: What are reference types?** Instead of storing the data itself, the reference types store the address of where the data is being stored.

**Q: What is an automatic property and how is it useful?** Makes property declaration more precise and are used when there's no need for added property accessors. 

**Q: What is the purpose of using statement?** The using statement gives the syntax to target a specific scope of the use of a resource object.

**Q: What are dynamic type variables?** A type that tells the compiler that the variable's type can change (unlike static type variables) until it runs the program.

**Q: What is the purpose of the is operator?** It understands if a type change is compatible and determines if an object can be converted to a specific type. 

**Q: What are generics and how is using them useful?** Generics let you define a class with placeholders for whatever type of fields, methods, parameters, etc, it has. Generics replace these placeholders with a certain type when compiling.

**Q: What is the scope of a public member of a class?** The scope is an encloses the context of a public member that specifies where a name is allowed without being qualified.

**Q: Can you create a function that can accept a varying number of arguments?**
Yes.

**Q: How do you sort an array?** Using this code:
int[] Array = new int [1] { 1, 2, 3};
Array.Sort(Array);

**Q: What is a nullable type and what purpose does it serve?**
A type that you can assign normal and null values to.

**Q: What is an enumeration?**
A group constant integers with names

**Q: What is inheritance?**
When a subclass inherits the properties of a class

**Q: Is multiple inheritance supported?**
No.

**Q: What is the purpose of the as operator?** 
You use it to do certain types of of conversions between reference or nullable types that are compatable.

**Q: What is an object?**
An object or "instance" is data/memory that can be stored in arrays, collections and variables. 

**Q: What is the difference between a struct and a class?**
A structure is of type value so it's stored on the stack, whereas a class is a reference type and is stored on the heap. A class supports inheritance and polymorphism, but a structure does not.

**Q: What is the difference between continue and break statements?** 
The difference between break statements and continue statements in C# is that using the break statement, you can skip the loop, but by using the continue statement, you only jump over one iteration and continue with the loop.

**Q: What is this and how is it used?**
The "this" keyword describes the most recent iteration of a class. It's also used to modify the first parameter of an extension method.

**Q: What is try and catch and when are they used?**
Try and catch is made of a try function block followed by one or more catch/s, which describe the handlers when there are different exceptions.

**Q: How is exception handling done?**
First the "catch" keyword finds the exception, then the "finally" block determines whether the exception is "thrown" or "not thrown". Finally, the "throw" keyword throws and exception when an issue is detected.

**Q: What is finally and what is its purpose?**
To determine if an exception should be thrown or not.

**Q: List the differences between Array and ArrayList.**
An Array has a static size while an ArrayList has a dynamic size. Also, an Array is multi-dimensional while an ArrayList is a single demension. 

**Q: What is an object?**
Same question as 17. "An object or "instance" is data/memory that can be stored in arrays, collections and variables."

**Q: Define constructor.**
 A constructor is a certain method of a class that will be triggered automattically when a part of the class is made.

**Q: When can var be used to declare a variable and how is the type for the variable determined?**
It can only be used when a local variable is initialized and declared in the the same statement. The var will take on the type name given.

**Q: What is an abstract class?**
Abstract classes are classes that include class members which aren't complete and have to be inserted into a derived class.

**Q: What is an interface?**
An interface is similar to a base of an abstract class. Any class or structure that has an interface has to also have all of it's members.

**Q: What is a method?**
A block of code that has a number of statements within it.

**Q: What is a property?**
A member with a dynamic/flexible way to read, write, and/or compute the value of a private field.

**Q: What is an access specifier?**
It describes how accessible an object and its members are.

**Q: What access specifiers are supported and what do they mean?**
Private: The extent of the accessibility has a limit inside the classes or structure that they are created/declared. The private members cannot be used outside the class and it has the most limited access. 

Protected: The extent of accessibility has a limit inside the class or structure and the class inherited from the class.

Internal: Can access inside the program that have its declarations, and can access in the same assembly level, but not from a seperate assembly.

Protected internal: Has the same access levels as internal and protected (it's a combination). It can access anywhere in the same assembly and class. The classes are also inherited from it's own class.

**Q: What is a collection?**
Special classes that are used in data storage and retrival.

**Q: What is a Hash Table?**
A class that represents a group of key/value pairs that are grouped together on the hash code key.
