1. The length of prices will be logged to the console. This is because i was initialized using "var", so it exists outside of the for loop and i will stop increasing when it is equal to prices.length.

2. The final value of discountedPrice from the last iteration of the for loop will be logged to the console. discountedPrice was initialized in the for loop, but since it was initialized using "var", it is accessible outside of the for loop.

3. The last value of finalPrice will be logged to the console. finalPrice was initialized outside of the loop using a "var" declaration so it will be accessible both inside the loop and throughout the entire function.

4. The function will return [50, 100, 150]. The discounted array is declared using "var", so it is accessible throughout the entire function. finalPrice is calculated in the for loop and pushed to the discounted array in each iteration and after discounted is modified, it is returned.

5. We will get an error since i was declared with "let" so it is not accessible outside of the for loop.

6. Similarly, we will get an error since discountedPrice is initialized with "let" inside the for loop and is not accessible once the loop has ended.

7. The last value of finalPrice will be logged to the console. This succeeds since finalPrice was declared outside of the for loop using "let" and any modifications done in the loop will persist afterwards.

8. The function will return [50, 100, 300] since the array discounted was declared with "let" outside of the for loop and will continue to exist after the loop ends along with any prices pushed into the array.

9. You would get an error since i was declared with let in the for loop and does not exist outside of the loop.

10. You would get an error since discountedPrice is declared using "const" inside the for loop and does not persist once the loop is finished.

11. The for loop attempts to change finalPrice which was declared using "const", so we would have gotten an error.

12. The function would successfully return [50, 100, 150]. Even though discounted is declared using "const", the for loop is still able to push elements into the array. We just cannot change the value of the array object itself.

13a. student.name

13b. student["Grad Year"]

13c. student.greeting()

13d. student["Favorite Teacher"].name

13e. student.courseLoad[0]

14a. '3' + 2 outputs '32'. The 2 is implicitly converted to a string '2' and is concatenated to '3', giving us '32'.

14b. '3' - 2 outputs 1. The output is an integer this time because we cannot subtract two strings, so the '3' is converted to the integer 3 and subtracts 2.

14c. 3 + null outputs 3. Null is treated as 0 for mathematic operations, so 3 + 0 = 3.

14d. '3' + null outputs '3null' since null is converted to a string and appended to '3'.

14e. true + 3 outputs 4. The boolean value true is converted to 1 then added to 3.

14f. false + null outputs 0. Numeric conversion occurs since we have addition without any strings. False and null are both represented as 0, so 0 + 0 = 0.

14g. "3" + undefined outputs "3undefined". undefined is converted to a string and concatenated to "3".

14h. "3" - undefined outputs NaN. Since we are subtracting values, we will be outputting a numeric value. "3" can be converted to 3, but undefined converts to NaN which will cause the entire output to be NaN.

15a. "2" > 1 outputs true since "2" is converted to a number and 2 is greater than 1.

15b. '2' < '12' outputs false since both '2' and '12' are converted to numbers and then compared.

15c. 2 == '2' outputs true since '2' is converted to a number and 2 is equal to 2.

15d. 2 === '2' outputs false since 2 is a number and '2' is a string, so a strict equality gives false.

15e. true == 2 outputs false since true is converted to 1 and 1 is not equal to 2.

15f. true === Boolean(2) outputs true since 2 is non-empty and Boolean(2) will output true which is the exact same as the left side.

16. The == operator will attempt to convert different type values to the same type so true will be equal to 1, but a strict equality operator === will check equality without any type conversion so true will not be equal to 1 using ===.

17. How are you? gets printed since the comparison 2 == true is false since true is converted to 1 and 2 is not equal to 1. In the next else if statement, 2 is non-empty and is treated as true, so that statement executes.

18. If modifyArray([1, 2, 3], doSomething) is called, a return array called newArr is made. Each element of the parameter array [1, 2, 3] is then passed to the callback function doSomething along with function(x) which multiplies x by 2. The callback function doSomething will add 2 to the number then call function(x) to multiply it by 2. The result is then pushed to newArr. The final newArr contains the elements of the original array after they have been increased by 2 then multiplied by 2.

19. The console will print 1 first. Then the console will print 3 followed by 2. This occurs since console.log(2) is set to have a delay of 1 second, so 3 will print first. Finally, the console prints 4.
