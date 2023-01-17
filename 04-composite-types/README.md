Arrays and structs are aggregate types; their values are concatenations of other values in memory.

arrays
- fixed-length sequence of zero or more elements of a particular type.

slices 
- represent variable-length sequences whose elements all have the same type
- a slice type is written []T, where the elements have type T; it looks like an array type without a size.

`append` function
- appends items to slices.

maps
- the hash table is one of the most ingenius and versatile of all data structures.it is an unordered collection of key/value pairs in which all the keys are distinct, and the value associated with a given key can be retrieved, updated, or removed using a constant numner of key comparisons on the average, no matter how large the hash table.

- a map is a reference to a hash table, and a map type is written map[k]V


structs
- is an aggregate data type that groups together zero or more named values of arbitrary types as a single entity.

struct literals - a value of a struct type can be writte using a struct literal that specifies values for its fields

JSON

Text and HTML templates
