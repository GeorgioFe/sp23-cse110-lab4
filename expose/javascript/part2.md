__Question 1:__ At line 12, the code will print the value of "i" which is 3 since the length of the given array is 3 and we used "var" to delare i, hence it can be used outside of the for loop scope as well.

__Question 2:__ At line 13, the code will print the value of discountedPrice which was at that point 150. That is because discountedPrice was declared with "var", so it can be used outside of the for loop scope. The last element of the given array was 300 and the discount is 0.5, hence the value 150.

__Question 3:__ Similarly, at line 13, the code will print the value of finalPrice which was at that point 150.

__Question 4:__ The function returns the array [50, 100, 150]. That's because we passed in the array [100, 200, 300] and a discount of 0.5, so all the prices will be cut in half, because what the function is doing is it's getting each element of the given array and removing a percentage of it (depending on the discount) and returning a new array with the updated prices.

__Question 5:__ At line 12, the code causes a ReferenceError, because "i" is declared in the for loop scope using "let", so it wouldn't be accessible from outside of the for loop, which is where the code at line 12 is.

__Question 6:__ At line 13, the code causes a ReferenceError, because "discountedPrice" is declared in the for loop scope using "let", so it wouldn't be accessible from outside of the for loop, which is where the code at line 13 is.

__Question 7:__ At line 14, the code will print the value of "finalPrice" which is 150 at the final iteration. This works because even tho finalPrice is declared using the "let" keyword, it is in the same scope as the code at line 14.

__Question 8:__ The function returns the array [50, 100, 150]. That's because we passed in the array [100, 200, 300] and a discount of 0.5, so all the prices will be cut in half, because what the function is doing is it's getting each element of the given array and removing a percentage of it (depending on the discount) and returning a new array with the updated prices.

__Question 9:__ At line 11, the code causes a ReferenceError, because "i" is declared in the for loop scope using "let", so it wouldn't be accessible from outside of the for loop, which is where the code at line 11 is.

__Question 10:__ At line 12, the code prints the value of "length", which is 3 in this case, because the given vector has 3 elements. This works because even tho "length" is declared using the "const" keyword, it is in the same scope as the code at line 12, and it is never changed/modified, so it wouldn't cause any errors.

__Question 11:__ The function returns the array [50, 100, 150]. That's because we passed in the array [100, 200, 300] and a discount of 0.5, so all the prices will be cut in half, because what the function is doing is it's getting each element of the given array and removing a percentage of it (depending on the discount) and returning a new array with the updated prices.