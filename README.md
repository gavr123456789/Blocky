# Blocky
Concept for the language


```Clojure
x = 5 -- var
Person = [name: String age: Int]
person = Person[name: "Alice" age: 25]


-- method for Person
birthday = [ self: Person -> Person[name: name age: age + 1] -- fields of first arg are always in scope

olderPerson = person birthday -- UFCS



```
