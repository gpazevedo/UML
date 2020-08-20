# UML

The Unified Modeling Language (UML) is a general-purpose, standardized modeling language.

## Types of modeling

In UML, there are two main types of modeling: structural modeling and behavioral modeling. Structural modeling focuses on the static structure of the system, its parts, and how they are related to each other.

Main structure diagrams in UML:
* Class diagrams
* Component diagrams
* Package diagrams
* Deployment diagrams

Behavioral modeling shows the dynamic behavior of the components in a system.
Main behavior diagrams in UML:
* Use case diagrams
* Sequence diagrams
* Activity diagrams

## Structure Diagrams

This article approaches the Class Diagram and relationships among structural elements.

### Class Diagrams
Class diagrams show the structure of a software system presenting its classes and their relationships.
A class has methods and fields, each can be public, privated or protected.

![Class Diagram](./Class_Diagram.png "An isolated Class")

### Relationships

UML provides connections to specificate different relationships between its structural elements: classes, components and packages.

An association is a broad term that refers to a semantic relationship between classes.

![Association Relationship](./Class_Association.png "An association of 2 classes")

Aggregation is a relationship in which a child object can exist independently of the parent.

![Aggregation Relationship](./Class_Aggregation.png "An aggregation of 2 classes")

Composition is a relationship in which an object cannot exist independently of another object.

![Composition Relationship](./Class_Composition.png "An composition of 2 classes")

Multiplicity allows you to define the cardinality of a relationship between classes: *, 1, N

A dependency is a type of relationship between UML elements, such as classes, in which one element requires, needs, or depends on another element. The dependency is sometimes referred to as a supplier/client relationship because the supplier provides something to the client. The client is either semantically or structurally dependent on the supplier.

![Dependency Relationship](./Class_Dependency.png "The dependency between 2 classes")

Generalization is the process of abstracting common attributes and operations into a base class. The base class is sometimes referred to as the superclass, base type, or parent class. Generalization is also known as inheritance. The base class contains general attributes, operations, and associations that are shared with all of its subclasses.

![Generalization Relationship](./Class_Generalization.png "One generalized (base) class with 2 specialized (sub)classes")

Realization denotes a relationship in which one element realizes or implements the behavior that another element specifies. A common example of this is when a class implements an interface.

![Realzation Relationship](./Class_Realization.png "An Interface been realized by a class")
