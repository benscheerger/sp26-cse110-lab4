1. Line 9 prints 20
2. Line 13 prints 20
3. Var should not be used as it can be accessed anywhere in the function, not just in the block where it is declared. This can lead to issues where the variable declared with var overwrites variables with the same name elsewhere in the function.
4. Line 9 prints 20
5. Line 13 results in an error, as using let means that the result variable is not accessible outside of the block where it was originally defined. 
6. Line 9 results in an error, as the consst declaration means that result is immutable, and trying to change it by adding num1 and num2 together would throw an error.
7. Line 13 results in an error, as similarly to let, the const variable is not accessible outside of the block where it was originally defined. 