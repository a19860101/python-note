# 字串

## 基礎

### 建立字串

```python
s = 'hello'
s2 = "HELLO"
```

### 字串相加

```python
x = 'hello'
y = 'world'
print(x + y)
# helloworld
```

### 重複字串

```python
print('=' * 30)

# =============================
```

## 字串處理

### 字串索引

每一個字串都有一個位置，這個位置叫做索引。

索引都是從0開始算。

```python
text = 'Python
```

| 字元 | P | y | t | h | o | n |
| -- | - | - | - | - | - | - |
| 索引 | 0 | 1 | 2 | 3 | 4 | 5 |

```python
print(text[0])
# P

print(text[3])
# h

# 最後一個字
print(text[-1])
# n
```

### 字串切片

`字串[開始位置：結束位置]`

`字串[開始位置：結束位置：間距]`

```python
text = 'Hello Python!!'

print(text[1:4])
# ell
```

#### 從開頭到某個位置

```python
print(text[:4])
# Hell
```

#### 從某個位置到結束

```python
print(text[6:])
# Python!!
```

#### 設定間距

```python
print(text[::2])
# HloPto!
```

#### 字串反轉

```python
print(text[::-1])
# !!nohtyP olleH
```

### 字串長度

計算字串長度。

```python
text = 'hello'
print(len(text))
# 5
```

### 字串方法

#### `upper()`

#### `lower()`

#### `strip()`

#### `replace()`

#### `find()`

#### `count()`

#### `startswith()`

#### `endswith()`

#### `split()`

#### `join()`

#### `isdigit()`

#### `isalpha()`

#### `isalnum()`

### 字串方法整理表

| 方法             | 說明       | 範例                         |
| -------------- | -------- | -------------------------- |
| `upper()`      | 轉大寫      | `"abc".upper()`            |
| `lower()`      | 轉小寫      | `"ABC".lower()`            |
| `strip()`      | 去除前後空白   | `" hi ".strip()`           |
| `replace()`    | 取代文字     | `"hi".replace("h", "H")`   |
| `find()`       | 找文字位置    | `"hello".find("e")`        |
| `count()`      | 計算出現次數   | `"banana".count("a")`      |
| `startswith()` | 是否以某文字開頭 | `"abc".startswith("a")`    |
| `endswith()`   | 是否以某文字結尾 | `"a.jpg".endswith(".jpg")` |
| `split()`      | 切割字串     | `"a,b".split(",")`         |
| `join()`       | 合併字串     | `",".join(["a", "b"])`     |
| `isdigit()`    | 是否為數字字串  | `"123".isdigit()`          |
| `isalpha()`    | 是否為文字    | `"abc".isalpha()`          |
| `isalnum()`    | 是否為文字或數字 | `"abc123".isalnum()`       |
