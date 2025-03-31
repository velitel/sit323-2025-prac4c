With this project the process was almost the exact same as the process for 4.1P
I grabbed the code that was already done for the addition calculation, and copied it the amount of times there were different calculations that needed to be made, I then changed the constants for each to be the corresponding calculation, subtract, divide, multiply, exponentiate, square and modulo.

I then replaced the addition plus (+) symbol for minus (-), multiply (*), divide (/), exponentiate (**) and modulo (%)

Square rooting was slightly different, I had to change the return from n1 + n2; to Mat.sqrt(n1 * n2 + n1 * n2);

Running the code seemed easy enough, opened Brave browser and ran http://localhost:3040/divide?n1=5&n2=5 to get answer for 5 divide 5 and so on and so forth for each of the various different calculations.

After making sure the code ran effectively, it was time to upload to Github found a quicker way through terminal to create a .gitignore file I ran the command

“echo node_modules > .gitignore” which made the .gitignore file and added node_modules straight away, that is a little nice to know!

Ran through the motions of uploading to Github

"git init"
"git add ."
"git commit -m "Task 4.2C Completed”"
"git branch -M master"
"git remote add origin https://github.com/velitel/sit323-2025-prac4c"
"git push -u origin master"


