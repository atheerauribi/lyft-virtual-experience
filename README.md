# My attempt at the Lyft virtual experience program
The first step in this challenge is to refactor the architecture of the car/engine system that is used. The original data model uses OOP and has a parent class of Car, and and subclasses for each engine type that inherit Car. 

The task is to utelize a software architecture that allows for extendability in the future, such as the ability to take into consideration service for tires.
Here is the first attempt at a UML diagram that we created to re-organize the architecture of this system to be more extendable in the future. 

<iframe width="100%" height="800" src="./documentation/Model Answer - Diagram.pdf">
