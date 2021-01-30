1. i will print prices.length because i is visible after the loop due to the fact that it's global variable and that vars cannot be block or loop local
2. discountedPrice will print prices[i] * (1-discount) because the var is visible after the loop due to the fact that its global variable
3. finalPrice will printMath.round(discountedPrice*100)/100 because its a variable defined in the function discountPrices. finalPrice is scoped to the current function and gets processsed at the end.
4. will return [50,100,150] because all the vars in the function gets its value updated, due to the fact that they are all declared in the same scope of the discountPrices function.
5. i will not print anything because it's inside the scope of the for loop and line 11 is outside of the for loop
6. discountedPrice will not print anything because the var was declared inside of the for loop and the console.log is called outside of the for loop
7. finalPrice will print Math.round(discountedPrice*100)/100. An answer gets printed because finalPrice was declared in the scope of the discountedPrices function and the console log was in the same scope of the function.
8. [50,100,150] will get returned. even though finalPrice isnt console logged, the value of finalPrice gets pushed into the discount array. The numbers in discount gets saved and returned at the end because discount is declared in the scope of the discountPrices block and the return line is also in the same scope.
9. i will not be printed and will throw an error because its declared with let, which means that i only exists in the scope of the for loop. 
10. discountedPrice will throw an error becuase it's a constant and it cannot get changed
11. finalPrice will throw and error because it's a constant and it cannot get changed
12. will return an error because discounted is a const and it cannot get changed, which it does in line 8.
13. 
    1.  a) student.name 
    2.  b) student["Grad Year"] 
    3.  c) student.greeting, d)   
    4.  student.greeting.name  
    5.  e) student.courseLoad[0]
14.  
     1.  a) '32'- the plus sign can also be interpreted as a concatenation so 2 got concatenated to 3
     2.  b) 1- the 3 is interpreted as an integer and so 3 minus 2 is 1
     3.  c) 3- adding 3 and null is the same as adding 3 with 0
     4.  d) '3null'- 2 gets concatenated with null since the + sign can also be interpeted as concatenation
     5.  e) 4- true represents 1, so i'm able to add 1 and 3
     6.  f) 0- false represents 0 and null also represents 0 so the sum is 0
     7.  g) 3undefined- 3 is concatenated with undefined. both are viewed as strings
     8.  h) NaN- 3 subtrated by something that's not a number is not a number.

15. GOT TO DO DIS TOOOO
    1.  true because '2' is interpreted as a number and 2 is greater than 1
    2.  false becuase when we compare two strings, the 1 from the 12 is less than the single 2
    3.  true because '2' gets interpreted as a number and 2 is equal to 2
    4.  false because 2 and '2' are different types. the === is more strict on the types of the values
    5.  false because true is also known as 1 and 1 is not equal to 2
    6.  true because Boolean(2) is also known as true. anything greater than 1 as a bool is true. so true and true is true.
16. == tests equality of values of the same type while == is a strict equality operator which also checks equality without the type conversion
17. How are you? gets printed because the first if statement is false. True is also known as 1. 1 is not equal to 2. Then we move onto the second condition. Since 2 is a number greater than 0, it represents the boolean true. Therefore How are you? gets printed
18. find file
19. [6 , 8, 10] after calling modifyArray, we will go inside of the for loop. in line 4, we call the call back function, which is doSomething. We pass in the element in the array's index and another function that returns x*2. Inside of doSoemthing we will call the other function with the element + 2 as its parameter. For the first element 1, we will call the other function with 3. In the other function we will multiply 3 by 2 which is 6. This return value then gets pushed in newArray. The for loops iterate like this for the elements 2 and 3 too and the final returned answer is [6 , 8, 10].
20. find file
21. 1 4 3 2

