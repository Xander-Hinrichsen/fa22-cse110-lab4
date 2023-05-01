1. 3 will be printed (logged by console?) because the variable i was declared with 'var', so it stays viable even outside of the for loop it was declared in, since we are still inside the function it was declared in
2. 150 will be printed because at the end of the for loop, discountedPrice takes on the value of the last element of the prices list times 0.5 (300*0.5), and this value is accessable outside of the for loop because the variable discountedPrice is declared with 'var'
3. 150 will be printed because final price is declared with 'var' and viable everywhere in the function, and it takes on the same value of 'discountedPrice' in part two, rounded to 2 decimal points.
4. This function will return a list that is the same as the prices list with every element /= 2 and rounded to 2 decimal places. This is because the for loop of the function divides each element in 2, rounds it, and then pushes it onto the end of the list to be returned.
5. Error - befcause the variable i is declared as a 'let' and at line 12, it is being accessed outside of the block that it was defined in; i does not exist at line 12.
6. Error - similar to q5, 'dicountedPrice' is declared as a 'let' and attempting to access outside of block scope
7. 150 will be printed - even though 'finalPrice' was declared with 'let', the console.log is in the same block as the 'finalPrice' variable declaration
8. This function will return the input 'prices' list with each element divided by two and rounded to the second decimal place for the same reasons as stated in question #4 and because there are no scope violations
9. Error - attempting to access i, but i is out of scope because declared in a different block with 'let'
10. 3 will be printed because it is the lenght of the 'prices' array, and because there are no variable scope/assignment violations
11. the function will return the input 'prices' array with each of the elements divided by 2
12. 
a.student.name
b.student["Grad Year"]
c.student.greeting()
d.student['Favorite Teacher'].name
e.student.courseLoad[0]
13. Arithmetic
a. ‘3’ + 2: '32', string-int addition overloaded to string output
b. ‘3’ - 2: 1, string-int subtraction overloaded to int output
c. 3 + null: 3, int-null addition overloaded to int output
d. ‘3’ + null: '3null', who knows why, this seems dumb
e. true + 3: 4, true has a value of 1 in integer form, so it makes sense
f. false + null: 0, in integer form, false=0, null=0?
g. '3' + undefined: '3undefined', they just decided to overload this way? it's dumb
h. '3' - undefined: NaN, because neither of them are numbers? sure.
14. Comparison
a.'2' > 1: true, in int-string comparison (not '==='), strings are converted to ints
b.'2' < '12': false, for some reason it only considers the first digit for string number comparisons
c. 2 == '2': true - it convers the string to an int for comparison
d. 2 === '2': false - different datatypes being compared
e. true == 2: false - true is converted to int value of 1
f. true === Boolean(2): true, same datatypes, Boolean function returns true for nonzero int input
15. === checks for both datatype equality and value equality, == is overloaded to handle comparisons across different datatypes
16. in file 'part2-question16.js'
17. [2,4,6] - modifyArray takes in the array [1,2,3] and a 'doSomething' function that returns 2 * input value. modifyArray then applies this 'doSomething' function to every element in the input array [1,2,3] using a for loop, resulting in [2,4,6]
18. in file 'part2-question18.js'
19. answer:
    1
    4
    3
    2
  