# Longest-Compounded-Word

# Steps to Execute this code
1. open the cpp file (ex:'code.cpp') on any c++ ide
2. Use any of the input file ('input_01.txt' or 'input_02.txt') in place of 'input.txt' in given code.
3. Now compile and run the code
4. The needed output will get printed in 'output.txt'
5. You will find the 'Output.txt' file in the same folder.

# Overview

n: no. of strings 
<br>
k: max(length of string)
<br>
<br>
Time complexity:
<br>
<br>
Best case-> O($k^2$)
<br>
Average Case-> O(nk)
<br>
Worst Case-> O(n $k^2$)  
<br>
Space complexity: O(k)
<br>
<br>

* To solve this problem "Dynamic programming" data structure is used.
* Now starting from the end of list of strings i try to find if current string can be made by smaller words or not
* if yes then store the string in ans1 and same goes with second largest compounded word
* if we get both the strings then we stop and print the output strings