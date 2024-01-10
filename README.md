# HashMap

This project is part of the Odin Project's Javascript Course.
It has JavaScript implementations of `HashMap` and `HashSet` classes.

### Description

The `HashMap` class is an implementation of a hash map, allowing you to store key-value pairs.
The `HashSet` class behaves similarly to a HashMap but does not store associated values.
They each have methods for adding, retrieving, checking the existence, and removing key-value pairs. They also include functions to get keys, the number of keys or key-value pairs, and to clear the map.

### Usage

```javascript
// Example usage of the HashMap class
const myHashMap = new HashMap();

myHashMap.set("name", "John");
myHashMap.set("age", 25);

console.log("Get:", myHashMap.get(name)); // Output: ['John', 25]
console.log("Entries:", myHashMap.entries()); // Output: [['name', 'John'], ['age', 25]]

// Example usage of the HashSet class
const myHashSet = new HashSet();

myHashSet.set("apple");
myHashSet.set("orange");

console.log("Keys:", myHashSet.keys()); // Output: ['apple', 'orange']
console.log("Length:", myHashSet.length); // Output: 2
```
