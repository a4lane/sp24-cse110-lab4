1. Prints 3. 'i' is a var so it can be accessed after the for loop ends, and its value is three because prices.length = 3 so the loop runs 3 times. 
2. Prints 150. This is the value assigned to the var 'discountedPrice' during the last iteration of the for loop, and vars can be accessed outside of the scope they were defined in
3. Prints 150. Same as #2, this is the value assigned to 'finalPrice' in the last iteration of the for loop.
4. The function will return the array [50, 100, 150] because these are the results of discounting the original prices based on the discount 0.5
5. Error: 'i' was defined using let, so it can not be accesed outside of the for loop it was defined in
6. Error: 'discountedPrice' was also defined in the for loop using let, so it cannot be accessed outside of that block
7. Prints 150. 'finalPrice' was defined in the same scope as we are trying to access it, so we have access to its most recent value even though it was updated in the for loop
8. The function will still return the array [50, 100, 150] because 'discounted' was defined in the same scope as the return statement
9. Error: same as #5, 'i' is declared using let inside the for loop and can't be accessed outside
10. Prints 3. This is the length of the list 'prices', and we are accessing it in the same scope as it was defined
11. It will return the array [50, 100, 150] because even though 'discounted' was defined using const, its values can still be updated becuause the reference to the array is constant not the array itself  

12.  
    - (A) student.name
    - (B) student['Grad Year']
    - (C) student.greeting()
    - (D) student['Favorite Teacher'].name
    - (E) student.courseLoad[0]  
    <br>
  

13.
    - (A) '3' + 2 = '32': ints map to string representation w/ concatenation
    - (B) '3' - 2 = 1: subtratction is being applied to converts to int
    - (C) 3 + null = 3: null becomes 0 with numeric conversion
    - (D) '3' + null = '3null': '3' is a string, so performs string conversion and concatenation
    - (E) true + 3 = 4: true -> 1 with numeric conversion
    - (F) false + null = 0: false and null both map to 0 when performing a math operation
    - (G) '3' + undefined: '3' is a string so performs concatenation
    - (H) '3' - undefined = NaN: '3' -> 3 because we perform subtraction, 3 minus undefined number is NaN

<br>

14. 
    - (A) '2' > 1 = true: different types, '2' is converted to an integer
    - (B) '2' < '12': false, both strings so compares lexicographically
    - (C) 2 == '2' = true, different types so converts '2' to int and 2 == 2
    - (D) 2 === '2' = false: strict equality operator, so does not convert types 
    - (E) true == 2 = false: true -> 1 when converted to an integer, 1 ≠ 2
    - (F) true === Boolean(2) = true: Boolean(2) returns true because it is a constant, they are both boolean types and equal

<br>

15. == automatically converts types, === is strict equality operator and checks equality without type conversion

16. in part2-question16.js

17. The function returns [2, 4, 6]. The parameters passed to modifyArray are the array [1, 2, 3] and the function doSomething, which multiplies a number by two. modifyArray calls doSomething one each of the values in the original array, then returns a new array of the new values, each doubled by doSomething.

18. in part2-question18.js

19. 1 4 3 2
