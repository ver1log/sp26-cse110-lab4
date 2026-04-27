1. 20
2. 20
3. We should not use var beacuse it is function scoped, meaning it can be modified in unexpected places and can be harder to debug
4. 20
5. We get an error here due to how let is block scoped and not function scoped, and we try to access it to print the value
6. The code errors out before we even get to the print line by trying to modify the result variable
7. The same error that occurs in question 6 occurs here


