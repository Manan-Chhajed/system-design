- Virtual Functions
  - A member function in the base class that can be overridden by a derived class
  - It enables runtime polymorphism, where the function to be invoked is determined at runtime based on the actual object's type
  - Pure Virtual Function (Abstract Method)
    - A pure virtual function is a virtual function with no implementation in the base class. It is declared by assigning 0 to the function
    - The class containing at least one pure virtual function becomes an abstract class, meaning you cannot instantiate it directly
    - Derived classes must provide an implementation for pure virtual functions
  - Concrete Virtual Function
    - A concrete virtual function is a virtual function with an implementation in the base class
    - Derived classes can either use the base class's implementation or override it

- Abstract Class
  - A class that contains at least one pure virtual function is called an abstract class
  - It cannot be instantiated but can be used as a base class for other classes
  - Derived classes must provide implementations for all pure virtual functions

- Virtual Destructor
  -  Ensures that destructors of derived classes are called properly when an object is deleted via a pointer to the base class
  -  It is critical when dealing with polymorphism to avoid memory leaks.
 
- Polymorphism
  - Runtime Polymorphism
