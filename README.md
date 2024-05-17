# Blocky
Concept for the language


```Scala
x = 5 // var
Person = [name::String age::Int] // type
person = Person[name: "Alice" age: 25] // object


// method for Person
// fields of first arg are always in scope
birthday = [ self::Person -> Person[name: name age: age + 1] 

olderPerson = person birthday // UFCS


add = [x::Int y::Int -> x + y]
// short syntax
add = [x::Int + y::Int]

1 add: 2
add[x: 1 y: 2]
```
