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
