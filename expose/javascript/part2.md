1. 
Output: 3
* The output is 3 since the loop variable "i" is declared with var, so it exists outside of the loop scope. There are 3 elements in the input and the loop runs for each of them, so it terminates when i = prices.length (3 in this case), leaving "i" as 3.

2. 
Output: 150
* The output is 150 since discountedPrice is declared as var, meaning it exists outside the loop scope. The last time discountedPrice is set is to be 0.5 of the last element (300), leading to the output of 150.

3.
Output: 150
* The output is 150 since finalPrice is declared as var, meaning it exists at function scope; it is accessed within the function so it remains defined. The last time finalPrice is set is to be the last discountedPrice rounded, leading to the output of 150.

4. 
* The function will return an array with the discounted values. discounted (defined as var) points to the beginning of the array, which then gets elements pushed by the function, leading the array of discounts to be returned.

5.
Output: Error: i is not defined
* Since "i" is defined with let, it doesn't exist outside the loop, causing an error when called outside the loop.

6.
Output: discountedPrice is not defined
* Since discountedPrice is defined with let, it doesn't exist outside the loop, causing an error when called outside the loop.

7.
Output: 150
* The output is 150 since finalPrice is declared as let, meaning it exists at function scope; it is accessed within the function so it remains defined. The last time finalPrice is set is to be the last discountedPrice rounded, leading to the output of 150.

8.
The function will return an array with the discounted values. discounted (defined as let) points to the beginning of the array, which then gets elements pushed by the function, leading the array of discounts to be returned.

9.
Output: Error: i is not defined
* Since "i" is defined with let, it doesn't exist outside the loop, causing an error when called outside the loop.

10.
Output: 3
* Since length is defined as a const at function level, and called at function level. It is defined as the input array length, which is 3 in this case, leading to an output of 3.

11.
The function will return an array with the discounted values. discounted (defined as const) points to the beginning of the array, which then gets elements pushed by the function, leading the array of discounts to be returned. Even though discounted is const, it just points to the start of the array, and the pointer itself isn't changed.

12.
a) student.name;
b) student["Grad Year"];
c) student.greeting();
d) student["Favorite Teacher"].name;
e) student.courseLoad[0];



13.
a) '32' (2 is converted to a string and concatenated)
b) 1 ('3' is automatically converted to an int for computation)
c) 3 (null = 0)
d) '3null' (null just converts to string)
e) 4 (true =1)
f) 0 (both null and false = 0)
g) '3undefined' (undefined just converts to string)
h) NaN (undefined as int converts to NaN)


14.
a) true (different types, '2' converted to 2)
b) false (both strings, 12 is lexicographically before 2)
c) true (non-strict equality converts both to numbers)
d) false (strict equality checks without type conversion)
e) false (true = 1, 1 doesn't equal 2)
f) true (Boolean(2) takes boolean of nonzero/special string, which is true)

15.
== represents non-strict equality, meaning that the types can both be converted to ints if needed. By contrast, === is strict and requires types to be the same, and equal within that type, to return true. 

16.


17.


18.

