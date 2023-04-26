1. It prints the number "3" because the length of the array is 3 so i got update to 3 then exist the loop. Since we declare with var, i becomes a global variable where it can be used outside the for loop.
2. It prints "150". discountedPrice got updated to 300 * 0.5 = 150 at the last loop. Since we declare with var, it becomes a global variable and it can be visited outside the for loop.
3. It prints "150". finalPrice got updated to (300 * 100) / 100 = 150 at the last loop. Since we declare with var, it becomes a global variable and can be visited outside the for loop.
4. It will return ['50', '100', 150']. The function calculates the discounted price each loop and then push it to an array. Since we set the discount as 0.5 so each price in prices will cut half. Thus, we get an array of ['50', '100', 150'].
5. It returns error because we are trying to access i outside the scope. Since i is declare with let, it only belongs to the for loop scope.
6. It returns error. Same reason as above. discountedPrice only be visitable inside the for loop as it's declare with let.
7. It prints "150" as we declare finalPrice inside the function scope so we are able to access it inside the function. 
8. It returns ['50', '100', 150']. The for loop is going to update each price in prices with 0.5 discount then add it to the discounted array. 
9. It returns error because we are trying to access i outside the for loop scope. Since i is declare with let and inside the for loop, it only be visible inside the for loop.
10. It prints "3" as we initialize length to prices.length, which is 3 in this case, at the beginning of the function.
11. It returns ['50', '100', 150']. The for loop is going to update all price in prices with discount 0.5 then push to discounted. Then, discounted got updated even though we declare with const because we only change the value of what it's pointing to. In other words, discounted is storing a memory address of what it's pointing to and we only chnage the values of what it's pointing to but not the actual address. 
12.
  -  student.name
  -  student["Grad Year"]
  -  student.greeting()
  -  student["Favorite Teacher"].name
  -  student.courseLoad[0]

13.
  - 32. 2 maps to its string representation and do the string concatenation.
  - 1. Since we cannot subtract string so 3 convert to its number representation and do the subtraction.
  - 3. null convert to 0 so we have 3 + 0 = 3
  - 3null. It convert null to string and peform string concatenation.
  - 4. true convert to number 1 then perform the addition.
  - 0. convert both null and false to 0 so we have 0 + 0 = 0
  - 3undefined. convert undefined to string and perform string concatenation.
  - NaN. convert undefined to its number value NaN so we have 3 - NaN = NaN.

14.
  - true. '2' become number and 2 > 1.
  - false. compare the first character in both string so we have 2 < 1 which is false.
  - true. convert string '2' to number 2 so we have 2 == 2 which is true.
  - false. using strict comparison and we are comparing two data type so it return false.
  - false. true become 1 so we have 1 == 2 which is false.
  - true. convert 2 to true.
  - true. convert 2 to true manually.

15. == allow the system to do the convert for you then do the comparison. === return false if we compare two different data types. 
