go types fall into 4 types
1. basic types: numbers, strings, booleans
2. aggregate types: arrays and structs
3. refernce types: pointers, slices, maps, functions, channels
4. interface types: 

Integers
-4 distinct sizes of signed ints - 8, 16, 32, 64bits
- rune is a synonym for int32
- byte is a synonym fot uint8
Runes are printed with %c or with %q if quoting is desired

Floating Point numbers
-go provides two sizes, float32(6 decinal digit presision) , float64(15 decimal digit precision)
Printf with %g verb
complex numbers

Booleans
has only two values true and false

Strings
- is an immutable sequence of bytes.
- built in len() returns the number of bytes in a string.
- string literal- a seq of bytes enclosed in a double quotes.
- packages for manipulating strings: bytes, strings, strconv, unicode

Constants
- expressions whose value is known to the compiler and whose evaluation is guaranteed to occur at compile time, not at run time.