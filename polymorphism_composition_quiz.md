# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?
A. Literally, many forms

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.
A. We can access objects of different types using a single interface.
In Java we could have an Animal Interface which promises a speak() function.
Child classes (e.g dog, cat, duck) which implement this Interface can then override the speak() method to perform a speaking action that is appropriate for the type (eg bark, meow, quack) 

3. What can we use to implement polymorphism in Java?
Base and abstract classes which child classes inherit from using the 'extends' keyword

4. How many 'forms' can an object take when using polymorphism?

A. As many as are defined in the parent/child class hierarchy

5. Give an example of when you could use polymorphism.

A. When you wish to provide methods whose behaviour can be overridden depending on the type of input


# Composition and Aggregation

6. What do we mean by 'composition' in reference to object-oriented programming?
When an object is made up of other object types

7. When would you use composition? Provide a simple example in Java.
A. If you want to have an object made of other objects which only exist as part of the parent. eg. a model of a human would be composed of different body part objects (limbs head, organs etc) but these would not exist outside of the human object.

8. Give a difference between composition and aggregation?
In composition, the component object cannot exist without first instantiating the containing object, whereas in aggregation, the component object can exist separately and be passed in to build (construct) the containing object.

9. What is/are the advantage(s) of using composition/aggregation?
A. Using either allows us to define HAS-A relationships between objects rather than IS-A like when using inheritance. This allows for potentially stronger encapsulation as you can restrict access to component objects if required and only allow them to be modified internally within the containing object.

10. When using composition, when an object is destroyed, what happens to all the objects it is composed of?
A. They are destroyed also

11. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?
A. They are retained.