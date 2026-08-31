# Polymorphism:

# Definition: Polymorphism means "one thing having many forms." In programming, it means the same method or operation can behave differently depending on the object or situation.

# Example:

# class Dog:
#   def sound(self):
#       print("Bark")

# class Cat:
#   def sound(self):
#       print("Meow")

# Same method → different behavior = Polymorphism.

# Types of polymorphism: 

# Polymorphism can be achieved in python in two ways well if we talk about compile time languages there are 3 ways but python does not support Method overloading.

# Method overloading means having same name methods inside a class but parameters will be different but in python the latest definition will overwrite the previous one.

# Method Overriding: This is where a child class overrides a method of the parent class, and Python decides at run time which method to call based on the object type. 

# Example: 

# class Animal:
#   def sound(self):
#       print("Animal makes a sound")

# class Dog (Animal):
#   def sound(self):
#       print("Dog barks")

# Duck Typing:

# Python follows the philosophy: "If it walks like a duck and quacks like a duck, it must be a duck."

# Example: 

# class Duck:
#   def talk(self):
#       print("Quack!")

# class Human:
#   def talk(self):
#       print("Hello!")

# In the speak() function, we don't care if it's a Duck or a Human -- we only care that the object has a talk() method.


