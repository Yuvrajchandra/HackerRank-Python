# HackerRank-Python
This repository contains solutions of Python problems from HackerRank and some tips &amp; tricks to solve python programs.  

---

+ **strip()**  
  The strip() method removes characters from both left and right based on the argument (a string specifying the set of characters to be removed).
  
---

+ **Python Division**  
  /  : It is used for integer division  
  // : It is used for float division  
  For eg-  
  4 / 3 = 1  
  4 // 3 = 1.33333333333  
  
---

+ **To convert a space separated input into list**  
  arr = list(map(int, input().split()))  
  
---

+ **To iterate key, values of dictionary**  
  dict_obj = {}  
  for key,values in dict_obj.items():  
  
---

+ **To get dictionary keys as list**  
  key_list = dict_obj.keys()
  
---

+ **To get dictionary values as list**  
  values_list = dict_obj.values()
  
---

+ **To print float numbers upto specified decimal places**  
  print("{:.4f}".format(22/7))  
  **->** 3.1429   
  
---

+ **Some common operations of List in Python**  
  1.) append(x) - Adds a single element x to the end of a list.  
  2.) extend(L) - Merges another list L to the end.  
  3.) insert(i,x) - Inserts element x at position i.  
  4.) remove(x) - Removes the first occurrence of element x.  
  5.) pop() - Removes the last element of a list. If an argument is passed, that index item is popped out.  
  6.) index(x) - Returns the first index of a value in the list. Throws an error if it's not found.  
  7.) count(x) - Counts the number of occurrences of an element x.  
  8.) sort() - Sorts the list.  
  9.) reverse() - Reverses the list.  
  
 ---
 
+ **Python hash()**  
  The hash() method returns the hash value of an object if it has one.  

---

+ **To input a complex number**  
  complex_num = complex(input())
  
---

+ **To get ASCII Code from a character**  
  ord() is used  
  
---

+ **To get character from ASCII Code**  
  chr() is used  
  [Complete mapping of ASCII Table](https://www.rapidtables.com/code/text/ascii-table.html)  
  
---

+ **Python Strings**  
  1. swapcase() - The string swapcase() method converts all uppercase characters to lowercase and vice versa of the given string, and returns it.  
  string = "gEEksFORgeeks"  
  print(string.swapcase())   
  GeeKSforGEEKS  
  
  2. isupper() - The isupper() methods returns “True” if all characters in the string are uppercase, Otherwise, It returns “False”.  
  3. islower() - The islower() methods returns “True” if all characters in the string are lowercase, Otherwise, It returns “False”.  
  4. lower() - The lower() methods returns the lowercased string from the given string.  
  5. upper() - The upper() methods returns the uppercased string from the given string.   
  
---



