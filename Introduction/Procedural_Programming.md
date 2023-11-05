Procedural programming is a paradigm in computer programming that is derived from structured programming, based upon the concept of the procedure call. Procedures, also known as routines, subroutines, or functions (not to be confused with mathematical functions, but similar to those used in functional programming), simply contain a series of computational steps to be carried out.

In procedural programming, a program is typically structured into procedures or functions that are meant to perform specific tasks. This programming paradigm is characterized by data being passed through procedures that operate on it, often transforming it along the way. It contrasts with object-oriented programming (OOP), where data and methods are bundled into objects.

Here is an outline of procedural programming concepts in Python:

1. **Functions**:
   Functions are the fundamental building blocks of procedural programming. In Python, you define a function using the `def` keyword.

   Example of a simple function:

   ```python
   def greet(name):
       return f"Hello, {name}!"

   print(greet("Alice"))  # Output: Hello, Alice!
   ```

2. **Global and Local Variables**:
   Procedural programming often makes use of both global and local variables. Local variables exist within a function and cannot be accessed outside of it, while global variables can be accessed throughout the entire program.

   ```python
   x = "global"

   def function():
       y = "local"
       return y

   print(function())  # Output: local
   print(x)           # Output: global
   ```

3. **Procedure Calls**:
   Functions can be called from other functions, allowing for modularity and code reuse.

   ```python
   def add(a, b):
       return a + b