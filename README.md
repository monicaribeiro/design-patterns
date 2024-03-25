This project has an educational purpose. 

I decided to, after almost 10 years, review all design patterns and create a material that could help people who want quick access to refresh their minds about it.
Through these years, I worked with many of these design patterns and they helped me to create solutions:
- easier to maintain;
- reusable;
- reliable;
- flexible;
- and adaptable.

To do these review, I'm reading again the design patterns bible written by Gang of Four. In addition, I will also use other references that will be cited at the end of these notes.

*Happy studies* :)

# Design Patterns

#### “Each pattern describes a problem which occurs over and over again in our environment, and then describes the core of the solution to that problem, in such a way that you can use this solution a million times over, without ever doing it the same way twice”, Christopher Alexander.

>Even though Alexander was talking about patterns in buildings and towns, what he says is true about object-oriented design patterns. Our solutions are expressed in terms of objects and interfaces instead of walls and doors, but at the core of both kinds of patterns is a solution to a problem in a context.
Gamma, Erich. (pp. 27-28).

Each pattern has:
- **name**: it will increase your vocabulary when discussing solutions.
- **problem**: a description of when you should use it.
- **solution**
- **consequences**: trade-offs of applying the pattern. This is importanttt!! There is no silver bullet.

### Design Principles vs Design Patterns

**Design Principles**, such as SOLID, are high-level guidelines to design reusable software applications.
They are pure abstraction, because they can be applied in any programming languages.


**Design Patterns** are low-level solutions of frequent object-oriented programing related problems.
They are concrete implementations and state-of-the-art problem specific solutions.


Some **design principles** can be implemented by **design patterns**.

### Designing for Change 

>"The key to maximizing reuse lies in anticipating new requirements and changes to existing requirements, and in designing your systems so that they can evolve accordingly."  (p. 62). Kindle Edition


## 3 types of design patterns

### #1 CREATIONAL PATTERNS

These patterns are designed for class instantiation (class and object creational patterns).

>"In software engineering creational patterns provide various object creation mechanisms which increase flexibility and reuse of existing code"

- Abstract Factory
- Builder
- Singleton
- Factory Method
- Prototype

### References

- Book - [Padrões de Projetos: Soluções Reutilizáveis de Software Orientados a Objetos](https://amzn.to/3ULQvaE)