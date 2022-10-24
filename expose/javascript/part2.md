   1. 3 will be printed. Because i is declared by var that has a function scope of visibility and accessibility. At the end of the for loop, i is updated to the length of the prices array, which is 3.
   2. 150 will be printed. Because discountedPrices is declared by var that has a function scope of visibility and accessibility. At the end of the for loop, discountedPrices is calculated as 150.
   3. 150 will be printed. Because finalPrices is declared by var that has a function scope of visibility and accessibility. At the end of the for loop, finalPrices is calculated as 150.
   4. The function will return the discounted price array that was calculated by the function.
   5. The code causes an error. Because i is in the for loop and declared by let that has a block scope, it is only visible to the block of code inside the for loop. Trying to access it outside the loop will cause an error for accessing undefined variable.
   6. The code causes an error. Because discountedPrices is in the for loop and declared by let that has a block scope, it is only visible to the block of code inside the for loop. Trying to access it outside the loop will cause an error for accessing undefined variable.
   7. 150 will be printed. Because finalPrices is on the top of the function and declared by let that has a block scope, it is visible to the codes throughout the function.
   8. The function will return the discounted price array that was calculated by the function.
   9. The code causes an error. Because i is in the for loop and declared by let that has a block scope, it is only visible to the block of code inside the for loop. Trying to access it outside the loop will cause an error for accessing undefined variable.
   10. 3 will be printed. Because length is declared by const that has a block scope of visibility and accessibility. At line 4, length is assigned to the length of the prices array, which is 3.
   11. The function will return the discounted price array that was calculated by the function.
   12. a. student.name;
   b. student["Grad Year"];
   c. student.greeting();
   d. student["Favorite Teacher"].name;
   e. student.courseLoad[0];
   13. a. '32'. Number 2 coverted to string and concatenate with '3'.
   b. 1. String '3' coverted to number.
   c. 3. null converted to number 0.
   d. '3null'. null converted to string then concatenate with '3'.
   e. 4. true converted to number 1.
   f. 0. false and null both converted to number 0.
   g. '3undefined'. undefined converted to string then concatenate with '3'.
   h. NaN. undefined converted to NaN, making the result of minus operation also becomes NaN.
   14. a. true. '2' converted to number 2 and is greater.
   b. false. Comparison of strings is in dictionary order
   c. true. '2' converted to number 2 and is equal.
   d. false. Strict equality operator checks the equality without type conversion.
   e. false. true converted number 1 and is not equal.
   f. true. Boolean converted number 2 into boolean value true.
   15.  == will do type conversion, while === will not.
   17.  result would be a new array with elements 2, 4, and 6. The original Array was passed in as a parameter, and doSomething was passed in as callbacks. In the for loop of function modifyArray, the code calls function doSomething on every array element. In the function doSomething, the code will return the doubled value of the input argument, thus making evey element in the original array doubled. Finally, the code will return the new array with doubled elements of 2, 4, and 6.
   19. 1 4 3 2