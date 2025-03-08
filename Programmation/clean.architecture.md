SOLID - CLEAN ARCHTECTURE

SOLID :

- S : Single Responsability Principle
	+ on method or class should do one specific thing only
	+ More maintenable because you know exactly where to go to fix what
	+ concept of splitting functionality into block
	DRY : principle
		+ Less Code Repedition
		+ On implementation point for code in your application
		+ Open/closed Principle onlu works when DRY is followed
- O : Open-closed Principle
	+ object/entities/class should be closed for modification but open for extension
- L : Liskov principle
	+ class or derived should be substitutable to the parent class
- I : Interface Segragation principle
	+ class should never be forced to implement method or functionality that it doesn't need
- D : Dependency Inversion principle
	+ Entities must depend on abstraction, and not implementation
	+ Promote Loose-Coupling in application
	+ Allow for easier code sharing between dependent classes

Undertanding Clean Architecture

Automapper
 - converts complex data types with ease
 - can be used in several parts of the application
 - Saves time spent on writing manual mapping code
 - Might lead to performance and debugging issues

CQRS : Command Query Responsability Segragation
Mediator : has to do with handling the relationships between requests and handlers without needing