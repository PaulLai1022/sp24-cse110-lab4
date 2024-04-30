question1:
3, discountPrices function calculates the discounted prices for each item in the array [100, 200, 300] with a discount of 0.5 (50% discount) and it round the prices into two decimal places by round method, which return 3 at the end. 

question2:
150, discountPrices function is called with arguments [100, 200, 300] and 0.5.
Inside the function, the for loop iterates over each price in the prices array.
for each price,the discounted prices will be calculated in store in discounted array.
300 will be the last item in the prices array in this case, 300*0.5 = 150

question3:
the statement will print the final rounded discounted price of the last item in the prices array. it's 300 in this case, 300*0.5 = 150

question4:
the funtion will return a array containing the discounted prices items in prices array. In this case [50, 100, 150]

question5:
Since i is declared using let inside the for loop, it is not accessible outside the loop. If you try to log i outside the loop, it will result in a ReferenceError.

question6: 
The variable discountedPrice is defined inside the for loop, so it's not accessible outside of the loop, which will result in ReferenceError when return

question7:
finalPrice is defined inside the for loop, so it's not accessible outside of the loop, which will result in ReferenceError when return


question8:
[ 50, 100, 150 ], The function discountedPrices will return an array [50, 100, 150], which are the discounted prices for each item in the input array [100, 200, 300] with a discount rate of 0.5.

question9:
console.log(i) will cause an error because i is declared using let inside the for loop, making it block-scoped to the loop. which result in reference error

question10:
In this code, console.log(length) will print the length of the prices array, which is 3 in this case becasue of ([100, 200, 300]). Because we have stored the length of the prices array in a constant length length. 

quetsion11:
[ 50, 100, 150 ],  the funtion will return an array containing the discounted prices of the items in the prices array.

Question12:
A: console.log(student.name); 
B: console.log(student.Grad);
C: student.greeting(); 
D: console.log(student.Teacher.name);
E: console.log(student.courseLoad[0]); 

Question13:

A: Output: '32'
Explanation: When you use the + operator with a string and a number, JavaScript converts the number to a string and concatenates the two values.

B: Output: 1
Explanation: When you use the - operator with a string and a number, JavaScript tries to convert the string to a number. In this case, '3' is converted to the number 3, and then the subtraction is performed.

C: Output: 3
Explanation: When you use the + operator with a number and null, JavaScript treats null as 0 in numeric contexts, so the result is 3.

D: Output: '3null'
Explanation: Similar to the first case, null is converted to a string and concatenated with '3'.

E: Output: 4
Explanation: When you use the + operator with true and a number, true is converted to 1, and then the addition is used.


F: Output: 0
Explanation: When you use the + operator with false and null, both values are converted to numbers (false = 0 and null = 0), and then the addition is performed.

G: Output: '3undefined'
Explanation: undefined is converted to a string and concatenated with '3'.

H: Output: NaN
Explanation:  use the - operator with a string and undefined, then undefined is converted to NaN, any calculatio follow with NaN return NaN

Question 14:

A: Output: true
Explanation: When comparing a string and number using the > operator, JavaScript converts the string to a number. In this case, '2' is converted to 2, and 2 > 1 is true.

B: Output: false
Explanation: When comparing two strings using the < operator, JavaScript compares them lexicographically instead of the value. Since '2' is greater than '1' (in terms of Unicode values), '2' is also greater than '12'.

C: Output: true
Explanation: When using the == operator, JavaScript performs type coercion. The string '2' is converted to a number before the comparison, so 2 == 2 is true.

D: Output: false
Explanation: The === operator performs strict equality comparison without type coercion. Since 2 and '2' are of different types, the result is false.

E: Output: true
Explanation: The true boolean is coerced to 1 before comparison, so 1 == 2 is true.

F: Output: false
Explanation: The Boolean(2) expression returns true, but the === operator checks for strict equality without type coercion. Since true and Boolean(2) are of different types, the result is false.

Question 15: 
The == operator is known as the equality operator that do type coersion when compairing value and  === operator is known as the strict equality operator which doesn't perform coersion and compairing value. 





