## Define closure?

<details>
    <summary>Answer here</summary>
     A closure means an inner function has access to the outer (enclosing) function’s variables—scope chain (even when outer function finishes execution). The closure has three scope chains: it has access to its own scope (variables defined between its curly brackets), it has access to the outer function’s variables, and it has access to the global variables.

     ```
      function buildFunctions() {

          var arr = [];

          for (var i = 0; i < 3; i++) {

              arr.push(
                  function () {
                      console.log(i);
                  }
              )
          }
          return arr;
      }

      var fs = buildFunctions();

      fs[0]();
      fs[1]();
      fs[2]();
     ```
</details>
<br>

## Define Polymorphism (OOP)?
<details>
  <summary>Answer here</summary>
  It is the practice of designing objects to share behaviors and to be able to override shared behaviors with specific ones. Polymorphism takes advantage of inheritance in order to make this happen.
</details>

## Define Encapsulation (OOP)?
<details>
  <summary>Answer here </summary>
  <p>Another important Object Oriented Programming principle is encapsulation.</p>
  
  <p>Encapsulation is defined by two concepts:</p>

	- Restricting access to instance variables and methods that do not need to be exposed.
  - Constructing methods to allow access to those instance variables and methods.
</details>

## Define inheritance (OOP)?
<details>
  <summary>Answer here</summary>

  - This allows the ability for a class to use instance variables and methods from another class. It is usually described as a child class inheriting instance variables and methods from a parent class. Alternatively, it can be described as a subclass inheriting instance variables and methods from a super class.

  - The extends keyword where the subclass extends from the superclass. Doing so provides all of the constructor functionality as well as the instance variables
</details>

## How to use the super keyword in subclass(OOP)?
<details>
  <summary>Answer here</summary>

  - When inheriting a class, the subclass will have access to a new keyword, super. This references the superclass it is inheriting from. It can be used in two ways:

		* Invoking super() calls the constructor on the superclass. This ensures the initial values are set from a super class (See the constructors on OfficeBuilding and ResidentialBuilding)
    * Calling super() in the constructor is required in order to use this in the constructor
  - Calling super.methodName() allows the ability to call a method from the superclass specifically. This allows the ability to override methods while still being able to include the functionality from the superclass (See the addFloor() method of the OfficeBuilding).
</details>

## Define abstraction
<details>
  <summary>Answer here</summary>
Its main goal is to handle complexity by hiding unnecessary details from the user.
</details>