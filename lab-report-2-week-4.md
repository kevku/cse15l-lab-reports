# Lab Report 2 
---
1) Having an empty line at the end of .md 
   The code infinitely runs to look for the next symbol that it can locate.
   Since the next line is empty, it infinitely runs forever and we need a break 
   <img src='Fixing Bugs/Bug 1.PNG' title='Bug 1.PNG' width='' alt='Bug 1.PNG' />  
   <img src='Fixing Bugs/FixedBug 1.PNG' title='FixedBug - 1.PNG' width='' alt='FixedBug - 1.PNG' />  
   <img src='Fixing Bugs/Result 1.PNG' title='Result 1.PNG' width='' alt='Result 1.PNG' />  
   
2) Having no closing parenthesis after the link  
   No closing parenthesis causes the code to spit a -1 from the indexOf sign.  
   This causes the code to run infinitely due to the while loop.  
   To fix this issue, if the closing or opening parenthesis gives a -1 it stops the loop.  
   <img src='Fixing Bugs/Bug 2.PNG' title='Bug 2.PNG' width='' alt='Bug 2.PNG' />  
   <img src='Fixing Bugs/FixedBug - 2.PNG' title='FixedBug - 2.PNG' width='' alt='FixedBug - 2.PNG' />  
   <img src='Fixing Bugs/Result 2.PNG' title='Result 2.PNG' width='' alt='Result 2.PNG' />  
   
3) Not having Open or Close Bracket  
   This bug was also similar to the first bug where it can't find the symbol.  
   Not being able to find the symbol will also spit -1 and we also added breaks for those cases.  
   <img src='Fixing Bugs/Bug 3.PNG' title='Bug 3.PNG' width='' alt='Bug 3.PNG' />  
   <img src='Fixing Bugs/FixedBug - 3.PNG' title='FixedBug - 3.PNG' width='' alt='FixedBug - 3.PNG' />  
   <img src='Fixing Bugs/Result 3.PNG' title='Result 3.PNG' width='' alt='Result 3.PNG' />  
