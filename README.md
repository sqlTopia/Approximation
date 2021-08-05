This source code will help you get best matching fraction for any decimal number.
It takes two parameters; the number itself and maximum value for the denominator. If you pass NULL, the code will search until perfect match is found.

The code will also remember the best matching fraction even if it is not the largest denominator.
For example, if you pass 3.14159265358979 and 33 as parameter values, the code will return {22, 7, 10} (10 is the number of total iterations).
If you pass 3.14159265358979 and 333 as parameter values, the code will return {355, 113, 24}.
If you pass 3.14159265358979 and 3,333 as parameter values, the code will return {355, 113, 50} (as 355/113 is the best approximation).
