1. prints 3
2. prints 150
3. prints 150
4. returns an array of [50, 100, 150]. This functions takes in an array of prices and apply a percentage discount to them then returns these discounted prices.
5. error, outside of block scope of `i`
6. error, outside of block scope of `discountedPrice`
7. prints 150
8. Similar to question 4, it returns an array of [50, 100, 150]. This functions takes in an array of prices and apply a percentage discount to them then returns these discounted prices.
9. error, can't reassign the constant variable `i`
10. prints 3
11. Similar to question 4, it returns an array of [50, 100, 150]. This functions takes in an array of prices and apply a percentage discount to them then returns these discounted prices.
12. | A | student.name |
    |---|---|
    | B | student["Grad Year"] |
    | C | student.greeting() | 
    | D | student["Favorite Teacher"].name |
    | E | student.courseLoad[0] |
13. | | output | explanation |
    |---|---|---|
    | A | '32' | 2 is converted into '2' and string concatenation is performed |
    | B | 1 | '3' is converted to a Number and 3 - 2 is calculated |
    | C | 3 | null is converted to 0 and 3 + 0 is calculated |
    | D | '3null' | null is converted to 'null' and string concatenation is performed |
    | E | 4 | true is converted to 1 and 1 + 3 is calculated |
    | F | 0 | false and null are converted to 0 and 0 + 0 is calculated |
    | G | '3undefined' | undefined is converted to 'undefined' and string concatenation is performed |
    | H | NaN | '3' is converted to 3 and undefined is converted to NaN and 3 + NaN is calculated |
14. | | output | explanation |
    |---|---|---|
    | A | true | '2' is converted to 2 and 2 > 1 is true |
    | B | false | string comparison is performed and the first characters is compared and '2' > '1' |
    | C | true | '2' is converted to 2 and 2 == 2 |
    | D | false | 2 and '2' are different types so 2 === '2' returns false |
    | E | false | true is converted to 1 and 1 != 2 |
    | F | true | Boolean(2) returns true and true === true |
15. If `==` is performed on different types, JS auto converts them to numbers and compares. `===` checks comparison without type conversion.
16. [Code here](part2-question16.js)
17. The result from the function call would be an array of [2, 4, 6]. The function modifyArray takes the array [1, 2, 3] and loop through each element and using it as an argument of the doSomething function that returns the input * 2. Then it uses these outputs from doSomething and creates a new array that is returned. 
18. [Code here](part2-question18.js)
19. 1
    
    4
    
    3
    
    2
