# Hash Tables

[Home](/README.md) | [Back](/401-main/401TableofContents.md)

What is a Hash Table?

A Hash table is a data structure used to store information. There are 2 main components: A key and a value. This is a great way to create a associative array. 

To use a hash table you will need to create a hash function.  This function will look at a key and evaluate it. Then it will return  an index number where this this key should be stored on the hash table.

    hashFunction(Key) -> index


In the case where a new key is passed but the index has a value, the new hash will chain that key to the one already present effectively making a linked list to that index space.

![University of Michigan CS](https://www.eecs.umich.edu/courses/eecs380/ALG/niemann/s_fig31.gif)
<br>
*PC: University of Michigan CS*
___


Vocab:

**Hash** - A hash is used to determine the index of the array for a hash table.

**Buckets** - Each index is a bucket. An index could potentially contain multiple key/value pairs if a collision occurs. Think of a bucket like a node

**Collisions** - A collision is what happens when more than one key gets hashed to the same location of the hash table.

___
<br>

Built in methods:

    Add()
    Find()
    Contains()
    GetHash()
