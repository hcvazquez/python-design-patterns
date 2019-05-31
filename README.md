# python-design-patterns

A repository of design patterns implemented in python.

## What Is a Design Pattern?

Each pattern describes a problem which occurs over and
over again in our environment, and then describes the core of the solution to that
problem, in such a way that you can use this solution a million times over, without ever
doing it the same way twice". Even though Alexander was talking
about patterns in buildings and towns, what he says is true about object-oriented design
patterns. Our solutions are expressed in terms of objects and interfaces instead of walls
and doors, but at the core of both kinds of patterns is a solution to a problem in a
context.

In general, a pattern has four essential elements:
1. The pattern name is a handle we can use to describe a design problem, its solutions,
and consequences in a word or two. Naming a pattern immediately
increases our design vocabulary. It lets us design at a higher level of abstraction.
Having a vocabulary for patterns lets us talk about them with our colleagues,
in our documentation, and even to ourselves. It makes it easier to think about
designs and to communicate them and their trade-offs to others. Finding good
names has been one of the hardest parts of developing our catalog.

2. The problem describes when to apply the pattern.It explains the problem and its
context. It might describe specific design problems such as how to represent algorithms as objects.
It might describe class or object structures that are symptomatic
of an inflexible design. Sometimes the problem will include a list of conditions
that must be met before it makes sense to apply the pattern.

3. The solution describes the elements that make up the design, their relationships,
responsibilities, and collaborations. The solution does'nt describe a particular
concrete design or implementation, because a pattern is like a template that can
be applied in many different situations. Instead, the pattern provides an abstract
description of a design problem and how a general arrangement of elements
(classes and objects in our case) solves it.

4. The consequences are the results and trade-offs of applying the pattern.Though
consequences are often unvoiced when we describe design decisions, they are
critical for evaluating design alternatives and for understanding the costs and
benefits of applying the pattern.
The consequences for software often concern space and time trade-offs. They
may address language and implementation issues as well. Since reuse is often a
factor in object-oriented design, the consequences of a pattern include its impact
on a system's flexibility, extensibility, or portability. Listing these consequences
explicitly helps you understand and evaluate them.

Point of view affects one's interpretation of what is and isn't a pattern. One person's
pattern can be another person's primitive building block. Here I have concentrated 
on patterns at a certain level of abstraction as the described in Gamma's design patterns book. 
Design patterns are not about designs
such as linked lists and hash tables that can be encoded in classes and reused as is. Nor
are they complex, domain-specific designs for an entire application or subsystem. The
design patterns in this book are descriptions of communicating objects and classes that are
customized to solve a general design problem in a particular context.
A design pattern names, abstracts, and identifies the key aspects of a common design
structure that make it useful for creating a reusable object-oriented design. The design
pattern identifies the participating classes and instances, their roles and collaborations,
and the distribution of responsibilities. Each design pattern focuses on a particular
object-oriented design problem or issue. It describes when it applies, whether it can be
applied in view of other design constraints, and the consequences and trade-offs of its
use.

## Classifying Patterns
According to Gamma design patterns can be classified under three purposes. The three purposes are:

### Creational
How an object can be created. This often involves isolating the details of object creation so your code isn’t dependent on what types of objects there are and thus doesn’t have to be changed when you add a new type of object. The aforementioned Singleton is classified as a creational pattern, and later in this book you’ll see examples of Factory Method and Prototype.

### Structural
Designing objects to satisfy particular project constraints. These work with the way objects are connected with other objects to ensure that changes in the system don’t require changes to those connections.

### Behavioral
Objects that handle particular types of actions within a program. These encapsulate processes that you want to perform, such as interpreting a language, fulfilling a request, moving through a sequence (as in an iterator), or implementing an algorithm. This book contains examples of the Observer and the Visitor patterns.