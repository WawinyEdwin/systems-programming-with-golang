Methods

method declarations
- a method is declared with avariant of the ordinary function declaration in which an extra parameter appears before the function name
- the parameter attaches the function to the type of that parameter

methods with a pointer reciever
- because calling afunction makes copy of each argument value, if afunction needs to update a variable, or if an  argument is so large that we wish to avoid copying it, we must pass the address of the variable using a pointer. 

nil is a valid reciever value
- 

composing types by struct embedding
- 

bit vector type
- a set rep by a map is  very flexibe but, for certain problems, a specialized rep may outperform it.
- a bit vector uses a slice of unsigned integer values or "words" each bit of which rep a possible element of the set. the set contains i if the i-th bit is a set.


encapsulation
- a variable or methos of an object is said to be encapsulated if it inaccessible to clients of the object. 
- Go has only one mechanism to control visibility of names: capitalized identifiers are exportes from the package in which they are defined, and uncapitalized identifiers are not.