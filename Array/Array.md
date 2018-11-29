# Array
An array is a set of contiguous memory that stores a set number of values.

## Depiction in Memory

![array in memory](Array.png)

An array is a contiguous data structure, meaning it is next to eachother in memory, and that things are accessible by simply adding the size multiplied by the size of a cell. The data inside each of the cells has to be the same data type and the same size, but this is often circumvented by having pointers inside.

## Operations

### Access/Read:O(1)
It takes only O(1) time to access data in an array because to access the nth index of the array, it simply has to multiply the size of the cells by the memory each requires and then add the memory address of the beginning of the array to find the data.

## Use Cases
An array is good to use with a constant amount of data that can be changed.

An array is terrible when data needs to be sorted, inserted, deleted, or have a different data type.

## Example
examplearray = ["red", "blue", "green"]

second = examplearray[1]


examplearray[2] = "yellow"
print(examplearray)
