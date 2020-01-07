**SOLID** is an acronym of a few basic principles to build a well-architectured object oriented software. By using them the software
can benefit from reusability, easy maintenance, scalability and easy testability.

**S** stands for single responsibility. One way to express it is that every class shall do one thing and do it well. Solution for it is to
create small concentrated classes. 

**O** stands for the open/closed principle. Software Entitites shall be open for extension but closed for modification. The solution is the 
good usage of interfaces, abstract classes, polymorphism to implement the good separation of interface and implementation. 

**L** Liskov substitution: the subclass or an implementation class shall be able to completely substitute the paren class 
by implementing its methods rather than relying on the base implementation.

**I** Interface segregation principle: no class shall be forced to implement methods it does not need. To solve this, instead of adding methods
to an interface one should prefer to create a new interface and let the classes implement multiple interfaces. 

**D** Dependency inversion (solved by the popular pattern dependency injection) : High level components should not depend on low-level components.
Instead both shall depend on abstractions. Abstractions should not depend on details, instead details shall depend on abstractions. 
