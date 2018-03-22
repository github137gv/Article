# Article
Python
# 字符串的处理

将单词首字母全变为大写：

```python
name = "ni yu xi"
print(name.title())
```



结果：

```
Ni Yu Xi
```

将字符串改为全部大写或全部小写：

```python
name = "Boy Next dOOr"
print(name.upper())
print(name.lower())
```

结果：

```python
BOY NEXT DOOR
boy next door
```

删除空白：

Python能够找出字符串开头和末尾多余的空白。

```python
note = " boy next door "
print("后有空格"+ "|" + note + "|")
print("去除后空格" + "|" + note.rstrip() + "|")
print("去除前空格" + "|" + note.lstrip() + "|")
print("去除首尾空格" + "|" + note.strip() + "|")
```

结果：

```python
后有空格| boy next door |
去除后空格| boy next door|
去除前空格|boy next door |
去除首尾空格|boy next door|
```

