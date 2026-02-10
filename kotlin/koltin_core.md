## KOTLIN CORE

1. Why Kotlin for Android?

- Concise, null-safe, interoperable with Java, officially supported by Google.

2. val vs var

- val – immutable
- var – mutable

3. Null Safety

- Safe Call (?), Elvis Oprator(?:), Not Null Assertion(!!)

4. lateinit vs lazy

- LateInit -> var only, non null ,runtime init
- lazy -> val only,Initialized on first use, Thread Safe
- eg -> lateinit var adapter: UserAdapter
- eg -> val repo by lazy { UserRepository() }

6.  Collection Syntax

- Array -> arrayOf()
- List -> listOf, mutableListOf
- Map -> mapOf,muteableMapOf
- Set -> setOf

7. suspend keyword

- Marks a function that can pause & resume without blocking thread.

8. Object vs companion object
9. what is higher-order functions

10. scope functions

- let: Executes the code block on the object and returns the result of the block. It’s commonly used for null checks.
- run : The run function is often used when you need to operate on an object and return a result. It can be used to initialize or transform an object.
- with : The with function is similar to run but is not called directly on the object; instead, the object is passed as an argument. This makes it ideal for configuring objects without directly calling them.
- apply :The apply function is used for configuring an object, as it returns the object itself after applying some configuration. It’s often used to initialize or modify objects.
- also : The also function is similar to apply but is used when you want to perform some additional operations on the object (like logging or debugging) and return the object itself.

11. What is a reified keyword in Kotlin

12. inline function
13. What are extension functions?
14. Sealed Class -

## OOPS in Kotlin

1. Primary Constructor

- Declared in the class header to define and initialize properties directly.
- Example : class User(val name: String, val age: Int)

2. Init Block

- A block of code that runs immediately after the primary constructor to handle setup logic or validation.
- Example: init { require(age > 0) { "Age must be positive" } }

3.  Secondary Constrctor

- An optional constructor in the class body used to provide alternative initialization paths, always delegating to the primary.
- Example: constructor(email: String) : this("Guest", 0) { println("Email set") }

4.
