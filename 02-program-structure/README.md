The structure of Go programs.

1. Names- of Go functions, variables, constants, types, statement labels and packages.

2. Declations - names a program entitity and specifies some or all of its properties.

3. Variables - A variable is a piece of storage containing a value
    - Pointers - A pointer value is the address of a variable. A pointer is thus the location at which a value is stored.
    - `new` Function - the expression `new(T)` creates an unnamed variable of type T, initialize it to zero value of T, and returns its address, which is a value of type *T.
    - lifetime of variables - is the interval of time during which it exists as the program executes

4. Assignments - the value held by a variable is updated by an assignment statement. = 
    - Tuple Assignment - allows several variables to be assigned at once e.g `x, y = y, x`
    - Assignability - 

5. Type Declarations - the type of a variable or expression defines the characteristics of the values it may take on, such as their size, how they are represented internally, the intrinsic operations that can be performed on them and the methods associated with them.

6. Packages and Files - Support modularity, encapsulation, separate compilation, and re-use
    - imports - every package is identified by a unique string called its import path.
    - package initialization - begins by initializing package-level variables in the order in which they are declared, except that dependencies are resolved first.

7. Scope - the scope of a declaration is the part of the source code where a use of the declared name refers to that declaration. It is a complile-time property.
