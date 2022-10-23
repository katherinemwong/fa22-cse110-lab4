1. It prints the value 3, because in the last iteration of the for loop, i = 2 and is post incremented to 3. This works because i is within the function scope. 

2. It prints the value 150, which is the discounted price of the last element in the price array. This works because discountedPrice is within the scope of the function. 

3. It prints the value 150, which is the final price of the last element in the price array. This works because finalPrice is within the scope of the function. 

4. The function returns discounted array, which equals [50, 100, 150], which is an array of the discounted prices without printing anything. This works because discounted is a var that is defined within the scope of the function. 

5. We get an error that i is not defined. This ias because i is declared using let and since it was declared in the for loop, i can only be accessible within the for loop. 

6. There is an error and discountedPrice is not defined. This is because discountedPrice is declared using let, which means that the scope of discountedPrice only exists within the for loop.

7. It will print 150. This is because finalPrice is declared using let, which means that its scope extends until the end of the block, which is esssentially the end of the function. 

8. It returns discounted, which is an array of the discounted prices [50, 100, 150]. This works because it is defined using let, which means discounted's scope is within the block and thus within the function.

9. It returns a reference error and i is not defined. This is because i is declared using let, so the scope of i only exists within the for loop.

10. It prints 3. This is because length is declared using const and it exists within the block, which is essentially the whole function.

11. This function will return the discounted array [50, 100, 150]. Even though discounted is declared using const, this prevents us from reassigning the variable but not pushing new values into it. 

12. Write notation
    1.  student.name

    2.  student['Grad Year']

    3.  student.greeting()

    4.  student['Favorite Teacher'].name

    5.  student.courseLoad[0]

13. Arithmetic
    1.  ‘3’ + 2 = '32' since 2 becomes a string
    2.  ‘3’ - 2 = 1 since 3 becomes an int
    3.  3 + null = 3 null maps to 0
    4.  ‘3’ + null = '3null' since null becomes a string
    5.  true + 3 = 4 since true maps to 1
    6.  false + null = 0 since false and null both map to 0
    7.  '3' + undefined = '3undefined' since undefined becomes a string
    8.  '3' - undefined = NaN since undefined maps to NaN

14. Comparison
    1.  ‘2’ > 1 = true because 2 becomes an int
    2.  ‘2’ < ‘12’ = false since strings are compared in lexicographical ordering 
    3.  2 == ‘2’ true since '2' becomes an int
    4.  2 === ‘2’ false since they are different types 
    5.  true == 2 false since true equals 1 
    6.  true === Boolean(2) true since since converting 2 to a boolean equals to true

15. == cannot differentiate 0 or an empty string from false. === checks equality without converting the type. If a and b are different types, then a === b will return false without trying to convert any of the elements.

16. In part2-question16.js

17. The result will be [2, 4, 6]. The function modifyArray creates a newArr, iterates over the array passed in as a parameter, and multiplies each element of the array by 2 and inputs this into the new array, which is returned. 

18. In part2-question18.js

19. The function prints 1 4 3 2 separated by newlines. This is because 1 and 4 is printed first, while 2 and 3 are printed with, even though 3 should not print with delays.