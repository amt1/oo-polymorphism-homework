# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

Polymorphism means having many forms

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

In OO design, polymorphism means that a class's functionality can vary from how it is defined in its superclass.

Here is an example from the Employee Lab. The Employee class has a method to calculate a 1% pay bonus:
public double payBonus(){
return (salary / 100);
}

In the Director class this is overridden to pay a 2% bonus:
public double payBonus(){
return (salary / 50);
}

3. What can we use to implement polymorphism in Java?

Inheriting from a superclass and overriding or overloading methods.
Adding behaviour based groupings using interfaces.


4. How many 'forms' can an object take when using polymorphism?

More than one

5. Give an example of when you could use polymorphism.

Weekdays



# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?

Composition assigns an object to be part of another object. 

7. When would you use composition? Provide a simple example in Java.

The component objects provide the containing object with the functionality it needs.

8. What is/are the advantage(s) of using composition?

We should favour composition over inheritance because it keeps the hierarchy less complicated

9. When an object is destroyed, what happens to all the objects it is composed of?
When the containing object is destroyed its component objects are also destroyed.
