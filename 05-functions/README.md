Functions lets us wrap a sequence of statements as a unit that can be called frm elsewhere in a program, perhaps multiple times.

the type of a function | signature.

function with not body - implemented in a language other than Go.


Recursion
- functions may call themselves, either directly or indirectly.

Multiple Return Values
- a function can return more than one result.
- the result of calling a multi-valued function is atuple of values.

Function Values
- functions are first-class values in Go: like other values, function values have types, and they may be assigned to variables or passed to or returned from functions.

Anon Functions
- named functions are declared at the package level, but we can use a functions literal to denote a function value within an expression. A function literal is written like a function declaration but without a name following the func keyword.

Variadic functions
- is one that can be called with varying numbers of arguments.
- To declare a variadic function, the type of the final parameter is preceded by an ellipsis, which indicates that the function may be called with any number of arguments with this type.

Defered Function calls
 - 

Panic
- when go runtime detects mistakes it panics

Recover
- 
