# Lab Report 5
## Different Test Results  
<img src='Comparing Code/unnamed.png' title='vimDiff.PNG' width='' alt='vimDiff.PNG' />  
To compare the codes, we used `vim diff` after a bash loop to see what results were different from our implementation to their implementation.  
The highlighted parts made it easy to identify which files were producing the different outputs.  
The highlights made it easy to manually check which files were having issues.  

[One of the tests that both code differed](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/194.md)  

According to Common Mark, this should be the correct output  
<img src='Comparing Code/commonJS.PNG' title='common.PNG' width='' alt='common.PNG' />  
So, in this case, both implementations got the result incorrect. Our results showed `[]` while the provided implementation gave `[url]` rather 
than `Foo*bar]`.  
In order to fix our implementation, we need to check if there are closing `]` after the url so it includes it in the link.  
<img src='Comparing Code/codeToBeChanged.PNG' title='codeToBeChanged.PNG' width='' alt='codeToBeChanged.PNG' />  
Moreover, we need to have the code recognize that there are other formats that can be considered as a link and we would have to add a new method or implementation
to check other variations of links.  
