# Hash Table

### What is Hash Table ?

It is an implementation of an associative array, a list of key-value pairs that allow you to retrieve a value via a key. 

### Why to use it?
because Hash tables have fast **search**, **insertion** and **delete** operations.

### There are two main ways to implement a hash table/associative array in JavaScript.
1. Using the Object Data Type
2. Using a Map Object

### The Hash table data structure stores elements in key-value pairs where

**Key**- unique integer that is used for indexing the values

**Value** - data that are associated with keys.

## Hashing (Hash Function)
**Hashing:** is the process of transforming any given key or a string of characters into another value ( fixed-length value or key that represents and makes it easier to find or employ the original string)

### When does a hash collision happen?
When the hash function generates the same index for multiple keys, there will be a conflict (what value to be stored in that index)

### We can resolve the hash collision using one of the following techniques.
1. Collision resolution by chaining
2. Open Addressing: Linear/Quadratic Probing and Double Hashing

### Applications of Hash Table
Hash tables are implemented where

1. constant time lookup and insertion is required
2. cryptographic applications
3. indexing data is required
