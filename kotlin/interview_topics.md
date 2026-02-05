## KOTLIN CORE

1. Why Kotlin for Android?

- Concise, null-safe, interoperable with Java, officially supported by Google.

2. val vs var

- val – immutable
- var – mutable

3. Null Safety

- Safe Call (?), Elvis Oprator(?:), Not Null Assertion(!!)

4. Collection Syntax

- Array -> arrayOf()
- List -> listOf, mutableListOf
- Map -> mapOf,muteableMapOf
- Set -> setOf,

---

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
