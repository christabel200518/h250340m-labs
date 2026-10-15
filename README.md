Christabel Shaba 
H250340M 
Software Engineering 

Object-Oriented Programming in Java: Lab Summaries

Lab 1: Classes & Objects
Covers class blueprints, creating objects with new, accessing fields and methods with the dot operator, and reference aliasing. Always check for null before calling methods on a variable to avoid a NullPointerException.

Lab 2: Constructors, this, and static Members
Covers constructor overloading, constructor chaining with this(...), and the difference between static and instance members. The this(...) call must be on the first line of a constructor. Use static methods only for logic that does not depend on instance state.

Lab 3: Encapsulation & Access Modifiers
Covers access levels (private, protected, default, public), validation inside setters, and defensive copying. Never return direct references to internal mutable objects like List or Date. Return unmodifiable views or copies instead.

Lab 4: Inheritance & Hierarchy
Covers extending classes with extends, calling super(...), overriding methods with @Override, and composition. Call super(...) explicitly when the superclass has no default constructor. Use final to prevent unwanted subclassing.

Lab 5: Polymorphism & Method Dispatch
Covers compile-time overloading versus runtime overriding, dynamic method dispatch, upcasting and downcasting, and type checking. Always verify the type with instanceof before downcasting to avoid a ClassCastException.

Lab 6: Abstraction, Abstract Classes & Interfaces
Covers abstract classes, implementing interfaces, default and static methods in interfaces, and Comparable. Concrete subclasses must implement all abstract or interface methods before objects can be created.

Lab 7: Exception Handling & Resource Management
Covers the exception hierarchy, try-catch-finally, checked versus unchecked exceptions, custom exceptions, and AutoCloseable resources. Order catch blocks from most specific to most general, and use try-with-resources for automatic cleanup.

Lab 8: Generics & Collections Framework
Covers generic type parameters, type erasure, wrapper classes, List, Set, Map, and Comparator. Avoid raw types and always specify the generic type for compile-time safety.

Lab 9: Nested Types, Enums, Records & Object Contracts
Covers inner classes, enums, records, and implementing equals(), hashCode() and toString(). Keep equals() and hashCode() consistent so maps and sets work correctly.

Lab 10: File I/O, Lambdas & Streams
Covers file handling with java.nio.file, CSV persistence, functional interfaces, lambda expressions, and Stream pipelines. Streams can only be used once, so do not reuse a stream after a terminal operation like collect() or forEach().

Lab 11: Design Patterns & Architecture
Covers Singleton, Factory, Strategy and Observer patterns, combined into a full system application. Use a pattern only when it fits the problem, for example Singleton for a single configuration and Factory for decoupled object creation
