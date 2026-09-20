
# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order



## 🧠 Algorithm
```
1.Start the program.
2.Create an empty dictionary and add key-value pairs.
3.Sort the dictionary items by their values using sorted() with a lambda function.
4.Store the sorted result in a variable.
5.Print a message and the sorted key-value pairs.
6.End the program.
```
## 🧪Program
```
def dictionairy():  
 key_value ={}   
 key_value[2] = 56      
 key_value[1] = 2
 key_value[5] = 12
 key_value[4] = 24
 key_value[6] = 18     
 key_value[3] = 323
 s=sorted(key_value.items(),key=lambda x:x[1])
 print ("Keys and Values sorted in alphabetical order by the value")
 print(s)
 
def main():
    dictionairy()
           
```
## Sample Output
![image](https://github.com/user-attachments/assets/f19f2bd9-a6f6-4aa4-a418-0d570459faa2)

## Result
The program successfully sorts the dictionary by its keys and values in alphabetical order and prints both sorted versions along with the original dictionary.
