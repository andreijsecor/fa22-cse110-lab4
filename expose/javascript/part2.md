1. The console will print `3` because this is the final value of `i` at that moment.
2. The console will print `150` because this is the final value of `discountedPrice` at that moment (given by prices[2] * (1 - 0.5))
3. The console will print `150` because this is the final value of `finalPrice` at that moment (given by round(150*100)/100)
4. This code will return the array `[50,100,150]`. This is because this code, effectively, iterates through each element of the array (lines 6-10), applies the discount (line 7), rounds the price to the nearest cent (line 8), and stores the discounted price in an array (line 9), which is returned (line 16).
5. The console will throw an error because `i` is not defined in that scope.
6. The console will throw an error because `discountedPrice` is not defined in that scope.
7. The console will print `150` because this is the final value of `finalPrice` at that moment.
8. The code will return the same thing as the previous function; that is, `[50,100,150]`. This is because the changed scope of the variables, in this case, does not affect the functionality of the function.
9. The code will throw an error because `i` is not defined in that scope.
10. The console will print `3` because this is the value of `length`, as it was initially assigned to the length of `prices`.
11. This code will return the same array, `[50,100,150]`. Functionally, the only difference between this function and the others is that it does not round the discounted prices to the nearest cent; however, this does not matter in this case.
12. Let us assume we have a `student` object called `student`.
    a. `student.name`
    b. `student['Grad Year']`
    c. `student.greeting()`
    d. `student['favorite teacher'].name`
    e. `student.courseLoad[0]`
13. 
    a. `'32'`: adding a string and an int concatenates the int as a string
    b. `'1'`: subtracting an int attempts to parse the string, returning `NaN` if it can't
    c. `3`: integer arithmetic treats `null` as `0`
    d. `'3null'`: attempts to concatenate `null` as a string, which is `'null'`
    e. `4`: integer arithmetic treats `true` as `1` and `false` as `0`
    f. `0`: attempts to perform integer arithmetic, resulting in the addition of their associated integers, giving us the equivalent of `0 + 0`
    g. `3undefined`: concatenates `undefined` as a string
    h. `NaN`: attempts to parse the string as an int, then subtracts `undefined`, which always results in `NaN`.
14. 
    a. `true`: parses the string as an int, resulting in `2 > 1`
    b. `true`: performs a string comparison, which compares them alphabetically
    c. `true`: parses the string as an int, resulting in `2 == 2`
    d. `false`: strict equality always considers different types to be different
    e. `false`: converts the boolean to an int, resulting in `1 == 2`
    f. `true`: the boolean form of `2` is `true`
15. `==` will compare two variables, and will attempt to perform type conversions to compare two different types. Meanwhile, `===` will never perform type conversions when comparing, and will always consider two different types to be different.
16. JS file
17. This function iterates through every element in the array, calls `callback()` on it as a callback function, then stores the result in an array which will be returned. In this case, the callback function multiplies the input by 2. In effect, this call of the function will return an array identical to the input, but whose values are doubled, returning the array `[2,4,6]`.
18. JS file
19. The output is: `1 4 3 2`, with newlines instead of spaces.