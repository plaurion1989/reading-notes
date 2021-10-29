# Hashtables

## How Hashtables work

Hash maps do this to store values:

- accept a key
- calculate the hash of the key
- use modulus to convert the hash into an array index
- store the key with the value by appending both to the end of a linked list

Hash maps do this to read value:

- accept a key
- calculate the hash of the key
- use modulus to convert the hash into an array index
- use the array index to access the short LinkedList representing a bucket
- search through the bucket looking for a node with a key/value pair that matches the key you were given

## Collisions

A collision happens when more than one key hashes to the same index in an array.  essentially forcing the hash map to handle two keys resolving to the same index.  when this happens, the keys will over-write eachother.  Resolving these collisions requires changing the inital state of the buckets.  instead of null, we could initialize them as a linked list. Each index in the array is a ***"bucket"*** that can now store multiple key value pairs based on the change of its internal state.

## Internal Methods
**Add()**

When adding a new key/value pair to a hashtable:

send the key to the GetHash method.
Once you determine the index of where it should be placed, go to that index
Check if something exists at that index already, if it doesn’t, add it with the key/value pair.
If something does exist, add the new key/value pair to the data structure within that bucket.

**Find()**

The Find takes in a key, gets the Hash, and goes to the index location specified. Once at the index location is found in the array, it is then the responsibility of the algorithm the iterate through the bucket and see if the key exists and return the value.

**Contains()**

The Contains method will accept a key, and return a bool on if that key exists inside the hashtable. The best way to do this is to have the contains call the GetHash and check the hashtable if the key exists in the table given the index returned.

**GetHash()**

The GetHash will accept a key as a string, conduct the hash, and then return the index of the array where the key/value should be placed.


[Back to Main Page](../README.md)
