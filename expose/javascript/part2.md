# Part 1 Answers

1. Output: **3** Reason: we get 3 because in the for loop, i is the loop variable, and it increments after each loop until it is equal to the length of array prices.
2. Output: **150** Reason: discountedPrice is last updated in the for loop, and it was set equal to the last element of the array (300) times half, so it is 150.
3. Output: **150** Reason: finalPrice is last updated in the for loop, it was set equal a rounded discountedPrice, so since the last discountedPrice was 150, it is rounded to 150.
4. Return: **[ 50, 100, 150 ]** Reason: the returned value is the array of prices after they have been processed
5. An error is outputted saying i is not defined. This is caused because i is declared for the for-loop using let, it has a more local scope, therefore it can only be used in the loop.
6. An error is outputted saying discountedPrice is not defined. This is caused because discountedPrice is declared within the for-loop using let, it has a more local scope, therefore it can only be used in the loop.
7. Output: **150** Reason: while finalPrice is declared using let, it was not declared in the for loop, so as long as the console.log is within the same box, it can be accessed.
8. Output: **[ 50, 100, 150 ]** Reason: the array discounted is also declared outside the for loop and within the same box as the return function, so the data inside can be accessed when returning.
9. An error is outputted (i is not defined) because i is only declared for the for loop, so it cannot be accessed outside the for loop.
10. Output: **3** Reason: the length is a constant that was set as the length of the input array, and it is declared in the same block as the console.log.
11. Output: **[ 50, 100, 150 ]** Reason: the output array was initialized using cosnt, so it cannot be reassigned, however you can push items into it.
12. 
    1. student.name
    2. student['Grad Year']
    3. student.greeting()
    4. student['Favorite Teacher'].name
    5. student.courseLoad[0]
13. 
    1. 32 - reason: 3 is a string, so it concatenated with 2.
    2. 1 - reason: the string 3 is converted to int to perform the subtraction operation.
    3. 3 - reason: 3 is int so when it is added with null, null acts as 0.
    4. 3null - reason: 3 as a string will concatenated the null.
    5. 4 - reason: true is equivalent to 1, so adding that to int 3 become 4.
    6. 0 - reason: false is equivalent to 0, so adding it to null is also int 0.
    7. 3undefined - reason: string 3 will concatenate the undefined.
    8. NaN - reason: string 3 will turn into int for subtraction, but we cannot minus undefined type so it is not a number.
14.  
    1. true - reason: 2 is converted to number 2, and it is compared with 1.
    2. false - reason: 2 is compared with 1, since the 2 is greater than 1, it returns false and the second digit of 12 is no longer checked. 
    3. true - reason: string 2 is converted to 2 number before comparison, so they are equivalent.
    4. false - reason: === is a strict equality operator, so the type of both sides are not converted before comparison.
    5. false - reason: true is converted to 1, so 1 is not equal to 2.
    6. true - reason: any non-zero number is true, so it converts to 1. true is converted to 1, so it is true that they equal to each other.
15. == is the equality operator and it will perform type coersion if the two elements are different types. === is a strict equality operator so no type coersion is made before comparison.
16.  21 45 5 2
17. [ 2, 4, 6 ]
18. See expose/javascript/part2-question18.js
19. 1 4 3 2

