1. Line 12 would print 3
2. Line 13 would print 150
3. Line 14 would print 150
4. The function would return [50, 100, 150]
5. Line 12 would throw an error, as i is declared in the scope of the for loop, which is not accessible at line 12.
6. Line 13 would throw an error, as the var is declared in the scope of the for loop, which is not accessible at line 13.
7. Line 14 would print 150
8. The function would return [50, 100, 150]
9. Line 11 would throw an error, as i is declared in the scope of the for loop, which is not accessible at line 11.
10. Line 12 would print 3
11. This function would return [50, 100, 150]
12. 
- a: student.name
- b: student['Grad Year']
- c: student.greeting()
- d: student['Favorite Teacher'].name
- e: student.courseLoad[0]
13.  
 - a: The output is 32, as '3' is a string, so JS concatenates with +
 - b: The output is 1, because even though '3' is a string, - only works with numbers
 - c: The output is 3, as null is treated as a 0 when used in addition
 - d: The output is 3null, as '3' is a string, so js concatenates
 - e: The output is 4, as true is treated as a 1 in addition
 - f: The output is 0, as both false and null are treated as 0 in addition
 - g: The output is 3undefined, as '3' is a string, so js concatenates
 - h: The output would be null, as undefined cannot be used in integer subtraction
14. 
- a: The output is true, as js converts '2' to an integer
- b: The output is false, as js compares strings by lexicographical order, and 1 is greater than 2
- c: The output is true, as js converts '2' to an integer
- d: The output is false, as === only allows for strict comparisons, meaning type conversion is not allowed
- e: The output is false, as true is converted to 1
- f: The output is true, as Boolean(2) equates to true.
15. The == operater is less strict, and allows for type conversion when making comparisons, while the === is stricter, and does not allow for type conversion
17. The result would be [2,4,6]. This occurs because the for loop iterates through the array [1,2,3], and for each iteration the callback function is called, which doubles the number at hand. This results in an array where each of the original values is doubled.
19. The printout is as follows
1
4
3
2