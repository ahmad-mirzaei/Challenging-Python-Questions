***`1.`*** <p>Python was created by [Guido van Rossum](https://en.wikipedia.org/wiki/Guido_van_Rossum) in **1989**. 
He began developing it as a successor to the ABC programming language, aiming to create a language that was easy to read and write, with a focus on simplicity and readability. Python's first public release, **Python 0.9.0**, was made in **1991**.</p>

---
***`2.`*** <p>Uses of Python: Big Data, Mobile Apps, Data Science, Web Scripting, Web Development, Machine Learning, Game Development, Image Processing, Desktop Programming, Hacking and Security, Artificial Intelligence, and ...</p>

---
***`3.`*** output :<br />
- python
- programmer
### Explanation :
<p>When we put a semicolon at the end of a command and then write the next command, although it is in one line, Python calculates it as two separate commands, and we do not encounter a syntax error.</p>

---
***`4.`*** Multiplication --> *<br />
***`5.`*** --> 43<br />
***`6.`*** --> Parentheses ( )

<p>Here is the table of operator precedence in Python, listed from the highest to the lowest precedence:</p>

| Precedence | Operator               | Description                                         |
|------------|------------------------|-----------------------------------------------------|
| 1          | `()` (Parentheses)      | Parentheses always have the highest precedence.     |
| 2          | `**`                    | Exponentiation (Power)                             |
| 3          | `+x`, `-x`, `~x`           | Unary plus, Unary minus, Bitwise NOT                |
| 4          | `*`, `/`, `//`, `%`     | Multiplication, Division, Floor Division, Modulus  |
| 5          | `+`, `-`                | Addition and Subtraction                           |
| 6          | `<<`, `>>`              | Bitwise left shift, Bitwise right shift            |
| 7          | `&`                     | Bitwise AND                                        |
| 8          | `^`                    | Bitwise XOR                                     |
| 9         | `==`, `!=`, `>`, `<`, `>=`, `<=` | Comparison operators (equal to, not equal to, greater than, less than, greater than or equal to, less than or equal to) |
| 10         | `not`                   | Logical NOT                                         |
| 11         | `and`                   | Logical AND                                         |
| 12         | `or`                    | Logical OR                                          |
| 13         | `=`, `+=`, `-=`, `*=`, `/=`, `%=`, `**=`, `//=` | Assignment operators                             |
| 14         | `is`, `is not`, `in`, `not in` | Identity and membership operators                |

<p>This table shows the operator precedence in Python, with the highest precedence at the top. Operators with higher precedence are evaluated first, unless parentheses are used to alter the order of evaluation.</p>

---

***`7.`*** int, str, list, dict

### Explanation of :
In Python, the main data types include:
- `int`: Integer
- `float`: Floating-point number
- `str`: String (text)
- `list`: List
- `tuple`: Tuple
- `dict`: Dictionary
- `set`: Set
- `bool`: Boolean (True or False)

There are no data types called `char`, `double`, `array`, or `numeric` in Python.

---
***`8.`*** b) a is equal to 0.5, and b is equal to 0..<br />
### Explanation :<br />
1 / 2 (regular division) results in a float, which is 0.5.<br />
1 // 2 (floor division) results in an integer, which is 0.

***`9.`*** y = 3 <br />
### Explanation :
<p>The int() function in Python truncates the decimal part of a float, keeping only the integer part. Therefore, 3.14159 becomes 3.</p>

***`10.`*** b) 112

### Explanation :
x ** 2: The square of 10, which equals 100.<br />
y * 5: The product of 3 and 5, which equals 15.<br />
x // y: The integer division of 10 by 3, which equals 3 (since the fractional part is discarded).

---

## `String` :

***`11.`*** 
```python
text = "Python Programming"
character = text[5]
print(character)
```
***`12.`*** 
```python
text = "programming"
reversed_text = text[::-1]
print(reversed_text)
```
***`13.`*** 
```python
text = "python programming language"
result = "lang" in text 
print(result)  
```
***`14.`***
```python
text = "python,php,javascript,django, laravel,react"
split_text = text.split(",")
print(split_text) 
``` 
***`15.`***
```python
text = "I love nothing"
modified_text = text.replace("nothing", "python")
print(modified_text)
```
***`16.`*** 
```python
words = ["Python", "is", "very", "lovely"] 
join_words = " ".join(words) 
print(join_words)
```
***`17.`***
```python
text = "challenging python questions together"
uppercase_text = text.upper()
print(uppercase_text)
```
***`18.`***
```python
text = "banana applebanana apple apple banana apple banana bananaapple"
text_count = text.count("banana")
print(text_count)
```
***`19.`***
```python
ascii_code = ord('P')
print(ascii_code)
```
***`20.`*** 
```python
ch = chr(89)
print(ch)
```

| **Character** | **ASCII Code** |
|---------------|----------------|
| A             | 65             |
| B             | 66             |
| C             | 67             |
| D             | 68             |
| E             | 69             |
| F             | 70             |
| G             | 71             |
| H             | 72             |
| I             | 73             |
| J             | 74             |
| K             | 75             |
| L             | 76             |
| M             | 77             |
| N             | 78             |
| O             | 79             |
| P             | 80             |
| Q             | 81             |
| R             | 82             |
| S             | 83             |
| T             | 84             |
| U             | 85             |
| V             | 86             |
| W             | 87             |
| X             | 88             |
| Y             | 89             |
| Z             | 90             |
| a             | 97             |
| b             | 98             |
| c             | 99             |
| d             | 100            |
| e             | 101            |
| f             | 102            |
| g             | 103            |
| h             | 104            |
| i             | 105            |
| j             | 106            |
| k             | 107            |
| l             | 108            |
| m             | 109            |
| n             | 110            |
| o             | 111            |
| p             | 112            |
| q             | 113            |
| r             | 114            |
| s             | 115            |
| t             | 116            |
| u             | 117            |
| v             | 118            |
| w             | 119            |
| x             | 120            |
| y             | 121            |
| z             | 122            |
| 0             | 48             |
| 1             | 49             |
| 2             | 50             |
| 3             | 51             |
| 4             | 52             |
| 5             | 53             |
| 6             | 54             |
| 7             | 55             |
| 8             | 56             |
| 9             | 57             |
| Space         | 32             |
| !             | 33             |
| "             | 34             |
| #             | 35             |
| $             | 36             |
| %             | 37             |
| &             | 38             |
| '             | 39             |
| (             | 40             |
| )             | 41             |
| *             | 42             |
| +             | 43             |
| ,             | 44             |
| -             | 45             |
| .             | 46             |
| /             | 47             |

***`21.`***
```python
name = "Ahmad"
age = 36
print(f"My name is {name} and I am {age} years old.")
```
***`22.`***
```python
number = 1234567890
print(f"number : {number:,}")
```
---

## `List` : 

***`23.`*** 
```python
my_list = [10, 20, 30, 40, 50]

first_item = my_list[0]
last_item = my_list[-1]

print(f"First item: {first_item}")
print(f"Last item: {last_item}")
```
***`24.`***
```python
num_list = [10, 20, 30, 40, 50]
str_list_1 = ["python programming language is the best"]
str_list_2 = ["python", "programming", "language", "is", "the best"]

print(len(num_list))
print(len(str_list_1))
print(len(str_list_2))
```
***`25.`***
```python
nested_list = [[1, 2, 3], ["python", "django", "django rest"], [True, False]]

second_item_first_list = nested_list[0][1]

first_item_second_list = nested_list[1][0]

last_item_third_list = nested_list[2][-1]

print(f"Second item from the first list: {second_item_first_list}")
print(f"First item from the second list: {first_item_second_list}")
print(f"Last item from the third list: {last_item_third_list}")
```
***`26.`*** 
```python
numbers = [2, 4, 6]
numbers.append(8)
print(numbers)
```
***`27.`*** 
```python
names = ["Ali", "Sara", "Reza"]
names.append("Ahmad")
print(names)
```
***`28.`***
```python
numbers = [1, 2, 3, 4, 5]
numbers.remove(5)
print(numbers)
```
***`29.`***
```python
a = [10, 20, 30, 40, 50, 60]
b = []
# step 1
popped_element = a.pop()  
b.append(popped_element)
# step 2
# b.append(a.pop())
print(a)
print(b)
```
***`30.`***
```python
words = ['a', 'b', 'd']
words.insert(2, 'c')
print(words)
```
***`31.`***
```python
numbers = [5, 10, 15, 25]

numbers.insert(3, 20) 
numbers.insert(len(numbers), 30)
numbers.append(35)
print(numbers)
```
***`32.`***
```python
a = [0, 1, 2, 3, 4]
b = [5, 6, 7, 8, 9]

c = a + b
print(c)
```
***`33.`***
```python
a = [0, 1, 2, 3]
b = [4, 5, 6, 7, 8]
c = [9, 10, 11, 12, 13, 14]

d = a + b + c
sum_d = sum(d)
print(sum_d)
```
---

## `Dictionary` :
***`34.`*** 
```python
dict1 = {"name": "Ali", "age": 25}
dict2 = {"city": "Tehran", "age": 26}

dict1.update(dict2)
print(dict1)
```
***`35.`***
```python

person = {
    "name": "Ali",
    "contact": {
        "email": "ali@example.com",
        "phone": "123456789"
    },
    "address": {
        "city": "Tehran",
        "postal_code": "12345"
    }
}

email = person["contact"]["email"]
city = person["address"]["city"]

print(f"email : {email}")
print(f"city : {city}")
```
***`36.`***
```python
my_dict = {"name": "Ahmad", "age": 36, "city": "Shiraz"}
my_dict.clear()
print(my_dict) # output -> {} 
```
***`37.`***
```python
my_dict = {"name": "Ahmad", "age": 36, "city": "Shiraz"}
last_item = my_dict.popitem()

print(last_item) # output -> ('city', 'Shiraz')
```
***`38.`***
```python
my_dict = {"name": "Ahmad", "age": 36}
my_dict.setdefault("city", "Shiraz")

print(my_dict)
```
***`39.`***
```python
my_dict = {"name": "Ahmad", "age": 36, "city": "Shiraz"}
keys = my_dict.keys()

print(keys)
```