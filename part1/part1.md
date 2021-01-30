# Part 1

1. Var i will be printed (using the argument from #4, line 11 prints 3) because variables declared with var are not block or loop-local, so it is still visible after the loop. 
2. discountedPrice will be printed (using the argument from #4, line 12 prints 150) because vairables declared with var is not local to the loop, so it functions as a global variable.
3. finalPrice will be printed (using the argument from #4, line 13 prints 150) because it is declared in the function (even if it's in the for loop it's okay because it's declared with var, so it will be global.)
4. The function will return the array discounted, which would be [ 50, 100, 150 ] because each price in the array prices will go through the for loop and gets reevaluated with the dicount amount and gets stored in the dicounted array. 
Also, it does not matter that the variables are declared inside the for loop because variables declared with var is global.
5. i will not print because declaring it with let means that it will be local to the for loop.
6. dicountedPrice will not print because declaring it with let means that it will be local to the for loop.
7. finalPricewill print because it was declared within scope of the dicountedPrices function and console.log is inside the function.
8. The function will return [ 50, 100, 150 ] because although the variables i and discountedPrice are only local to the for-loop, we only needed them inside the for
loop, and discounted variable is declared in scope of the function, so we changed its values correctly in the for-loop and stored the values in discountedPrice, then
we return the correct values in the end.
9. i will not print because declaring it with let means that it will be local to the for loop.
10. dicountedPrice will not print because declaring it with const means that it will be local to the for loop.
11. finalPrice will not print and there will be an error because we tried to modify finalPrice, which is a constant and shouldn't be modified.
12. The function will not return anything because there are errors in the function such as we're trying to modify constant vairables, which is not allowed and will raise errors.
13.
  A. student.name
  
  B. student["Grad Year"]
  
  C. student.greeting()
  
  D. student["Favorite Teacher"].name
  
  E. student.courseLoad[0]
  
 14.
  A. 32 because javascript treats the inputs as strings and put 3 and 2 together, so it's 32
  
  B. 1 because javascript treated the inputs as integers and subtracted them
  
  C. 3 because javascript converts null to 0 in this case
  
  D. 3null because javascript treated null as a string in this case
  
  E. 4 because javascript converts true to 1 in this case
  
  F. 0 because javascript is treating null and false as 0
  
  G. 3undefined becuase jevascript treats undefined as a string in this case
  
  H. NaN because undefined became NaN in this case so we can't subtract it with 3
 
15. 
  A. true because javascript treats 2 as an interger and 2 is greater than 1
  
  B. false because javascript is doing string comparison and two is lexographically greater than twelve
  
  C. true because the string "2" becomes integer 2
  
  D. false because === does the comparison without type conversion, so the string "2" is not equal to the integer 2
  
  E. false because true is equal to 1 not 2, so although == does not convert types, true is not equal to 1
  
  F. true because 2 is not null or undefined, so it evaluates as true.
  
 16. === compares without changing typed while ==, Javascipt may change the type and then do the comparison.
 
 17. "How are you" was printed because 2 got converted to true since it's not an intruitively "empty" value.
 
 19. [6,8, 10] is the result because the callback function, doSomething, was called and it will add 2 to all the numbers in the array then function x will multiply each number by 2.
 
 21. 
 1
 4
 3
 2
 
 
 
 
 
 
