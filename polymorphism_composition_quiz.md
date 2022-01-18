# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

poly - many
morph - shape or type
so, many shapes or types. as in, many types of things can be passed into the same function. 

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

it means we can have different types of things passed into the same method and the overriding class method will 
be implemented. for example, if you had multiple Shape classes for Circle, Square, Triangle, you could use one method to calculate the area of a shape called getArea(), and a getArea() class override in each of the classes that would calculate the area appropriately for each different shape. 

3. What can we use to implement polymorphism in Java?

interfaces and abstract classes


4. How many 'forms' can an object take when using polymorphism?

as many as you deem appropriate

5. Give an example of when you could use polymorphism.

the example in my answer to question 2, or an interface for devices. different types of device could implement the interface and then they would be forced to have class methods relating to the interface


# Composition and Aggregation

6. What do we mean by 'composition' in reference to object-oriented programming?

Objects can be composed of other objects

7. When would you use composition? Provide a simple example in Java.

If you were creating a Cake object from Flour, Eggs, and Sugar objects, the Cake could not exist independantly, it would be composed of all the other ingredients.

8. Give a difference between composition and aggregation?

Composition is when an object is made up of other objects, and aggregation is when the object is made up of it's own properties but also includes porperties that are independant objects.

9. What is/are the advantage(s) of using composition/aggregation?

a class can use behaviour from a group of other classes, and that behaviour can change at runtime.

10. When using composition, when an object is destroyed, what happens to all the objects it is composed of?

they are also destroyed

11. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?

they can still exist independantly