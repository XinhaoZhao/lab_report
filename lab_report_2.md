Case 1.  
   1.![Image](https://i.imgur.com/doN73bm.png)  
   2. [Link](https://github.com/XinhaoZhao/markdown-parser/blob/f2f386353a7b0eb201faf2a606d0cbc7e37735bd/test-file2.md)  
   3.![Image](https://i.imgur.com/PLVfUz2.png)  
   4. The symptom is that an exception was thrown when running the code on the new test file,  
      and this is because in the new file, we used a different way of adding links using Markdown,  
      which the code could not handle.  
      
Case 2.
1. ![Image](https://i.imgur.com/r37BzEk.png)  
2. [Link](https://github.com/FatCaToops/markdown-parser/commit/5080c2e203752b28f1656ac11112f4ed3db26272)
3. ![image](https://i.imgur.com/F71q8Zs.png)
4. The symptom is that an exception was thrown when running the code. The reason is the code fails to detect  
   a link because of syntax. 

Case 3.
1. ![Image](https://i.imgur.com/r37BzEk.png)  
2. [Link](https://github.com/FatCaToops/markdown-parser/blob/main/test-file2.md)
3. ![image](https://i.imgur.com/F71q8Zs.png)
4. The symptom is that an exception was thrown. The reason is there are other texts at the end of the test
   file that interferes with the detection links. 
