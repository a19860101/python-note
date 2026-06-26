# Python基礎

## 第一支程式

### print()輸出文字

```python
print('Hello Python')
print('Welcome')
```

### 加引號

```python
print('單引號')
print("雙引號")
```

## 變數

### 變數命名規則

- 變數命名規則
- 變數名必須以字母或底線開頭。
- 變數名不能以數字開頭。
- 變數名稱只能包含字母數字字元和底線（Az、0-9 和 _）。
- 變數名稱區分大小寫（age、Age 和 AGE 是三個不同的變數）。
- 變數名不能是任何Python 關鍵字。

```python
name = 'Zac'
print(name)
```

## 資料型別

### 常見型別

| 型別      | 說明      | 範例              |
| ------- | ------- | --------------- |
| `str`   | 字串| `"小明"`          |
| `int`   | 整數      | `18`            |
| `float` | 浮點數      | `3.14`          |
| `bool`  | 布林值  | `True`, `False` |

```python
# 字串 str
text = 'hello'
print(test)

# 整數 int
i = 10
print(i)

# 浮點數 float
f = 3.14
print(f)

# 布林 bool
b = True
print(b)
```

### 檢查型別

可以使用`type()`檢查型別

```python
name = "小明"
age = 18
height = 170.5
is_student = True

print(type(name))
print(type(age))
print(type(height))
print(type(is_student))

```

輸出：

```bash
<class 'str'>
<class 'int'>
<class 'float'>
<class 'bool'>
```

### 型別轉換

- int()
- str()
- float()
- 

#### 字串轉整數

```python
age = "18"
print(type(age))

age = int(age)
print(type(age))

```

#### 整數轉字串

```python
age = 18
text = str(age)

print(text)
print(type(text))

```

#### 字串轉浮點數

```python
price = "99.5"
price = float(price)

print(price)
print(type(price))

```

### input() 輸入

```python
name = input("請輸入你的名字：")
print(name)
```

> `input()`出來的都是字串

