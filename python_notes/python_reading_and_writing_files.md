### Automating files and the filesytem with Python
- Python enables you to create, read and change files and text in the code that you can use repeatedly.
- You can use `open` functions to create a file object that can read and write files 
- It takes two arguments: the path of the file and the mode 
- You can open a textfile using the `r` mode to read its content
- The file object has a `read` method that returns the content of the file as a string.

```python
file_path = '/Users/iAllali/Desktop/SpartaTraining/spartarepo/python_notes/test.py'
open_file = open(file_path, 'r')
text = open_file.read()
print(len(text))
```
