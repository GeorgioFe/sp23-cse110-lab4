# JavaScript Part 2
__Question 1:__ At line 12, the code will print the value of "i" which is 3 since the length of the given array is 3 and we used "var" to delare i, hence it can be used outside of the for loop scope as well.

&nbsp;

__Question 2:__ At line 13, the code will print the value of discountedPrice which was at that point 150. That is because discountedPrice was declared with "var", so it can be used outside of the for loop scope. The last element of the given array was 300 and the discount is 0.5, hence the value 150.

&nbsp;

__Question 3:__ Similarly, at line 13, the code will print the value of finalPrice which was at that point 150.

&nbsp;

__Question 4:__ The function returns the array [50, 100, 150]. That's because we passed in the array [100, 200, 300] and a discount of 0.5, so all the prices will be cut in half, because what the function is doing is it's getting each element of the given array and removing a percentage of it (depending on the discount) and returning a new array with the updated prices.

&nbsp;

__Question 5:__ At line 12, the code causes a ReferenceError, because "i" is declared in the for loop scope using "let", so it wouldn't be accessible from outside of the for loop, which is where the code at line 12 is.

&nbsp;

__Question 6:__ At line 13, the code causes a ReferenceError, because "discountedPrice" is declared in the for loop scope using "let", so it wouldn't be accessible from outside of the for loop, which is where the code at line 13 is.

&nbsp;

__Question 7:__ At line 14, the code will print the value of "finalPrice" which is 150 at the final iteration. This works because even tho finalPrice is declared using the "let" keyword, it is in the same scope as the code at line 14.

&nbsp;

__Question 8:__ The function returns the array [50, 100, 150]. That's because we passed in the array [100, 200, 300] and a discount of 0.5, so all the prices will be cut in half, because what the function is doing is it's getting each element of the given array and removing a percentage of it (depending on the discount) and returning a new array with the updated prices.

&nbsp;

__Question 9:__ At line 11, the code causes a ReferenceError, because "i" is declared in the for loop scope using "let", so it wouldn't be accessible from outside of the for loop, which is where the code at line 11 is.

&nbsp;

__Question 10:__ At line 12, the code prints the value of "length", which is 3 in this case, because the given vector has 3 elements. This works because even tho "length" is declared using the "const" keyword, it is in the same scope as the code at line 12, and it is never changed/modified, so it wouldn't cause any errors.

&nbsp;

__Question 11:__ The function returns the array [50, 100, 150]. That's because we passed in the array [100, 200, 300] and a discount of 0.5, so all the prices will be cut in half, because what the function is doing is it's getting each element of the given array and removing a percentage of it (depending on the discount) and returning a new array with the updated prices.

&nbsp;

__Question 12:__

    A. student.name;
    B. student["Grad Year"];
    C. student.greeting();
    D. student["Favorite Teacher"].name;
    E. student.courseLoad[0];

&nbsp;

__Question 13:__ 

    A. '32', 2 was converted to a string so basically '3' and '2' got concatenated.

    B. 1, this time for the - operator, '3' was converted to the number 3 and the answer is 3 - 2.

    C. 3, null is converted to the number 0, so the answer is 3 + 0.

    D. '3null', null was converted to the string 'null', so basically '3' and 'null' got concatenated.

    E. 4, true is converted to the number 1 and the answer is 1 + 3.

    F. 0, both false and null are converted to the number 0 and the answer is 0 + 0.

    G. '3undefined', undefined was converted to the string 'undefined' so '3' and 'undefined' got concatenated.

    H. NaN, undefined was converted to a number which is NaN, and so the addition cannot give an answer which is a number.

&nbsp;

__Question 14:__

    A. true, '2' was converted to the number 2 and the output is 2 > 1.

    B. false, this was just a string comparison so it starts with the 1st character of each operand and the string '2' is larger than the string '1'.

    C. true, the string '2' is converted to the number 2 and the output is 2 == 2.

    D. false, because 2 and '2' are of different types.

    E. false, true was converted to the number 1, and the output is 1 == 2.

    F. true, Boolean(2) returns true because everything with a value is true, so the answer is true === true.

&nbsp;

__Question 15:__ The `==` operator compares the values of two operands, and returns true if they are equal, while the `===` operator compares not only the values but also the data types of the operands.

&nbsp;

[__Question 16:__](./part2-question16.js)
    
    Output:
    21
    45
    5
    2

&nbsp;

__Question 17:__ The code defines two functions, modifyArray and doSomething, and then calls modifyArray with an array [1, 2, 3] and the doSomething function as arguments.

The modifyArray function takes two arguments, an array and a callback function. It creates a new empty array newArr, then loops over each element of the input array, and applies the callback function to each element. The result of the callback function is then pushed into the newArr. Finally, the newArr array is returned.

The doSomething function is a simple function that takes a number as an argument and returns the doubled value of that number.

So, when we call modifyArray([1,2,3], doSomething), modifyArray creates a new array newArr and loops through each element of [1,2,3]. For each element, it applies the doSomething callback function to double the value, and pushes the result into newArr. After all the elements have been processed, newArr would contain [2, 4, 6], which is then returned by the modifyArray function.

Therefore, the final output of the code would be [2, 4, 6].

&nbsp;

[__Question 18:__](./part2-question18.js)

&nbsp;

__Question 19:__

    Output:
    1
    4
    3
    2