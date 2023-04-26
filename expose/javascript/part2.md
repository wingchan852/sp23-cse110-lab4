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
