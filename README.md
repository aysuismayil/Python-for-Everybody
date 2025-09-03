# Python-for-Everybody
````markdown
# 📘 Python for Everybody — Notes (University of Michigan)
````
## 📑 Table of Contents / Оглавление  
- Chapters / Главы  
  - [Chapter 1 — Why Program? / Зачем программировать?](https://github.com/aysuismayil/Python-for-Everybody/blob/main/README.md#chapter14:~:text=%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85%20%D0%B8%20%D0%B2%D0%B8%D0%B7%D1%83%D0%B0%D0%BB%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F.-,Chapter%201%20%E2%80%94%20Why%20Program%3F%20/%20%D0%97%D0%B0%D1%87%D0%B5%D0%BC%20%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D1%82%D1%8C%3F,-English%3A%20Programming)  
  - [Chapter 2 — Variables & Expressions / Переменные и выражения](https://tinyurl.com/2nhcacuy)
  - [Chapter 3 — Conditional Execution / Условные операторы](https://github.com/aysuismayil/Python-for-Everybody/blob/main/README.md#chapter14:~:text=(result)-,Chapter%203%20%E2%80%94%20Conditional%20Execution%20/%20%D0%A3%D1%81%D0%BB%D0%BE%D0%B2%D0%BD%D1%8B%D0%B5%20%D0%BE%D0%BF%D0%B5%D1%80%D0%B0%D1%82%D0%BE%D1%80%D1%8B,-English%3A%20Use)  
  - [Chapter 4 — Functions / Функции](https://tinyurl.com/bdzh7wr8)  
  - [Chapter 5 — Loops & Iterations / Циклы и итерации](https://tinyurl.com/bdhuwcub)  
  - [Chapter 6 — Strings / Строки](https://tinyurl.com/8at8uwt6)  
  - [Chapter 7 — Files / Файлы](https://tinyurl.com/bdfth32h)  
  - [Chapter 8 — Lists / Списки](https://tinyurl.com/59zkueea)  
  - [Chapter 9 — Dictionaries / Словари](https://github.com/aysuismayil/Python-for-Everybody/blob/main/README.md#:~:text=(nums)-,Chapter%209%20%E2%80%94%20Dictionaries%20/%20%D0%A1%D0%BB%D0%BE%D0%B2%D0%B0%D1%80%D0%B8,-English%3A%20Dictionaries)  
  - [Chapter 10 — Tuples / Кортежи](https://tinyurl.com/tc9c5c5c)  
  - [Chapter 11 — Regular Expressions / Регулярные выражения](https://tinyurl.com/2yz2bpy3)  
  - [Chapter 12 — Network Programming / Работа с сетью](https://tinyurl.com/4jhm3bry)  
  - [Chapter 13 — Using Web Services / Веб-сервисы](https://tinyurl.com/3jjsvzes)  
  - [Chapter 14 — Object-Oriented Programming / Объектно-ориентированное программирование](https://tinyurl.com/ympemy8y)  
  - [Chapter 15 — Databases / Базы данных](https://tinyurl.com/yte97atz)  
  - [Chapter 16 — Data Visualization / Визуализация данных](https://tinyurl.com/4tts8fhj)  
- [Resources / Ресурсы](https://tinyurl.com/ymb68fja)  

---

## 🔹 Overview / Обзор  

**Course:** Python for Everybody, University of Michigan (Charles Severance)  
**Source:** [py4e.com](https://www.py4e.com/lessons) and [Coursera](https://www.coursera.org/learn/python)

This course introduces Python basics: variables, expressions, conditionals, functions, strings, files, lists, dictionaries, tuples, regular expressions, web, databases, and visualization.  

Курс знакомит с основами Python: переменные, выражения, условия, функции, строки, файлы, списки, словари, кортежи, регулярные выражения, веб, базы данных и визуализация.  

---

# Chapter 1 — Why Program? / Зачем программировать?  
**English:** Programming allows us to automate tasks and solve problems.  
**Русский:** Программирование помогает автоматизировать задачи и решать проблемы.  
```python
print("Hello, world!")
```

# Chapter 2 — Variables & Expressions / Переменные и выражения

**English:** Variables store data, constants are fixed values, and expressions combine them.
**Русский:** Переменные хранят данные, константы — фиксированные значения, выражения их объединяют.

```python
PI = 3.14
x = 10
result = x * PI
print(result)
```

# Chapter 3 — Conditional Execution / Условные операторы

**English:** Use `if`, `elif`, `else` to make decisions.
**Русский:** Используем `if`, `elif`, `else` для принятия решений.

```python
age = 18
if age >= 18:
    print("Adult")
else:
    print("Underage")
```

# Chapter 4 — Functions / Функции

**English:** Functions group reusable code.
**Русский:** Функции объединяют код для повторного использования.

```python
def greet(name):
    return f"Hello, {name}!"

print(greet("Alice"))
```

# Chapter 5 — Loops & Iterations / Циклы и итерации

**English:** Loops repeat tasks.
**Русский:** Циклы повторяют действия.

```python
for i in range(5):
    print(i)
```

# Chapter 6 — Strings / Строки

**English:** Strings are sequences of characters.
**Русский:** Строки — это последовательности символов.

```python
text = "Python"
print(text.lower())
print(text.upper())
```

# Chapter 7 — Files / Файлы

**English:** Python can read and write files.
**Русский:** Python может читать и записывать файлы.

```python
with open("test.txt", "r") as f:
    print(f.read())
```

# Chapter 8 — Lists / Списки

**English:** Lists store ordered collections.
**Русский:** Списки хранят упорядоченные коллекции.

```python
nums = [1, 2, 3]
nums.append(4)
print(nums)
```

# Chapter 9 — Dictionaries / Словари

**English:** Dictionaries store key-value pairs.
**Русский:** Словари хранят пары ключ-значение.

```python
person = {"name": "Alice", "age": 25}
print(person["name"])
```

# Chapter 10 — Tuples / Кортежи

**English:** Tuples are immutable sequences.
**Русский:** Кортежи — это неизменяемые последовательности.

```python
coords = (10, 20)
print(coords[0])
```

# Chapter 11 — Regular Expressions / Регулярные выражения

**English:** Regex helps find patterns in text.
**Русский:** Регулярные выражения помогают находить шаблоны в тексте.

```python
import re
text = "My number is 1234"
print(re.findall(r'\d+', text))
```

# Chapter 12 — Network Programming / Работа с сетью

**English:** Python can connect to the web.
**Русский:** Python может подключаться к интернету.

```python
import socket
mysock = socket.socket(socket.AF_INET, socket.SOCK_STREAM)
mysock.connect(("data.pr4e.org", 80))
```

# Chapter 13 — Using Web Services / Веб-сервисы

**English:** Python can fetch data from the web.
**Русский:** Python может получать данные из интернета.

```python
import urllib.request
fhand = urllib.request.urlopen("http://data.pr4e.org/romeo.txt")
for line in fhand:
    print(line.decode().strip())
```

# Chapter 14 — Object-Oriented Programming / Объектно-ориентированное программирование

**English:** OOP organizes code into classes.
**Русский:** ООП организует код в классы.

```python
class Dog:
    def __init__(self, name):
        self.name = name

    def bark(self):
        print("Woof!")

mydog = Dog("Buddy")
mydog.bark()
```

# Chapter 15 — Databases / Базы данных

**English:** Python can store data in databases.
**Русский:** Python может хранить данные в базах данных.

```python
import sqlite3
conn = sqlite3.connect('test.db')
cursor = conn.cursor()
cursor.execute('CREATE TABLE IF NOT EXISTS users (id INTEGER, name TEXT)')
```

# Chapter 16 — Data Visualization / Визуализация данных

**English:** Python can visualize data with libraries.
**Русский:** Python может визуализировать данные с помощью библиотек.

```python
import matplotlib.pyplot as plt
x = [1,2,3]
y = [2,4,6]
plt.plot(x, y)
plt.show()
```

## 🔗 Resources / Ресурсы

* 📖 [Full lessons — py4e.com](https://www.py4e.com/lessons)
* 🎥 [Coursera course](https://www.coursera.org/learn/python)

