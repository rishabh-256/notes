How data is stored? (Int Examples)
> Int are basically stored as binary bits, First, Each int is stored in 4 bytes cap, 1 byte has 8bits, these bytes are stored in memory location, so 4 bytes for each number


When we call a value based on its index (array has a index operator), it calls the memory's starting block (adding the first block) + i (index) * 4 (bcoz of the 4bytes)


- lookup by index = O(1)
- lookup by value = O(n)
- print all values (Array traversal) = O(n)
- inserting new value by index = O(n)
- delete element by index  = O(n)

Theory: There are two types of Array.
1. Static
2. Dynamic 

In python we use dynamic array as list

In static array you have fixed size and you have to specify the length/bounds of the array and the data type - as compared to dynamic array where its not required

In dynamic array while doing the memory allocation, data gets stored in blocks in ram, in a case where u store data in data allocation of 10 blocks, next blocks might already being used/allocated by some other data, and u try to add a new location, in that case you get a new location of oldlocation(10) + oldlocation(10) * 2 = 30, in a entirely new block and copy all that data from previous block which will add time overhead too


one_d_array = [1,2,3,4]
two_d_array = [ [1,2,3,4] , [5,6,7,8,9] [10,11,12,13,] ]
