# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean? **A: Something occurring in many different forms.**

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example. **A: Using a superclass to guide a subclass inheriting from it.**

3. What can we use to implement polymorphism in Java? **A: Classes (Abstract or not) Inheriting/extending**

4. How many 'forms' can an object take when using polymorphism? **An object instance can take the form of its own class, or superclass(es) by default upcasting, or downcast manually to subclasses if that makes sense (not always).**

5. Give an example of when you could use polymorphism. A: **A shape as an abstract superclass, and itsdefined shapes as subclasses with their own area calculations.**

# Composition and Aggregation

6. What do we mean by 'composition' in reference to object-oriented programming? **A: Composition means a Class made up of or included one or more other Classes.**

7. When would you use composition? Provide a simple example in Java. **A: A Circle Class will have a CentrePoint Class that cannot exist without the Circle.***

8. Give a difference between composition and aggregation? **A: Aggregation is where each Class/object can exist independantly. Composition is where the child Class relies on the Parent Class.**

9. What is/are the advantage(s) of using composition/aggregation? **A: One allows for creation and flexibility of objects without reliance on each other, the other forces behavior that is neccessary to some relationships, some things cannot exist without another, thus are Composited.**

10. When using composition, when an object is destroyed, what happens to all the objects it is composed of? **A: They go with it.**

11. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of? **A: The pointer is severed, but the object remains to be called and acted upon.**