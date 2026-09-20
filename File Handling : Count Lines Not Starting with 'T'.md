# File Handling in Python: Count Lines Not Starting with 'T'
## 🎯 Aim
To write a Python program that counts the number of words in a text file .

## 🧠 Algorithm
```
1.Start the program.
2.Define a function create_file(file_path, file_content) that:
   Opens a file at file_path in write mode
    Writes file_content to the file
3.Define another function count_words_in_file(file_path) that:
    Opens the file at file_path in read mode
     Reads the content and splits it into words
     Returns the number of words
4.Call create_file() with desired file path and content to create/write the file.
5.Call count_words_in_file() to get the total word count from the file.
6.End the program.
```
## 🧾 Program
```
def create_file(file_path,file_content):
    with open(file_path,'w')as file:
        file.write(file_content)
def count_words_in_file(file_path):
    with open(file_path,'r')as file:
         content=file.read()
         words=content.split()
         return len(words)
```

## Output
![image](https://github.com/user-attachments/assets/6ad88cd2-e8cf-46d7-a6fb-38f02403077e)


## Result
Thus,the program  that counts the number of words in a text file has been executed successfully.
