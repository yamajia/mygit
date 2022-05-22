## Python 数字

### Python 数字
<font size=10>Python 中有三种数字类型：</font>
* int
* float
* complex

<font size=10>为变量赋值时，将创建数值类型的变量：</font>
```python
  x = 10   # int
  y = 6.3  # float
  z = 2j   # complex
```
<font size=10>如需验证 Python 中任何对象的类型，请使用 ` type() ` 函数：</font>
```python
  print(type(x))
  print(type(y))
  print(type(z))
```

### Int
<font size=10>Int 或整数是完整的数字，正数或负数，没有小数，长度不限。</font>
<font size=10>整数：</font>
```python
  x = 10
  y = 37216654545182186317
  z = -465167846
  
  print(type(x))
  print(type(y))
  print(type(z))
```

### Float
<font size=10>浮动或“浮点数”是包含小数的正数或负数。</font>
<font size=10>浮点：</font>
```python
  x = 3.50
  y = 2.0
  z = -63.78
  
  print(type(x))
  print(type(y))
  print(type(z))
```
<font size=10>浮点数也可以是带有“e”的科学数字，表示 10 的幂。</font>
<font size=10>浮点：</font>
```python
  x = 27e4
  y = 15E2
  z = -49.8e100
  
  print(type(x))
  print(type(y))
  print(type(z))
```

### 复数
<font size=10>复数用 "j" 作为虚部编写：</font>
<font size=10>复数：</font>
```python
  x = 2+3j
  y = 7j
  z = -7j
  
  print(type(x))
  print(type(y))
  print(type(z))
```

### 类型转换
<font size=10>您可以使用 ` int() `、` float() ` 和 ` complex() ` 方法从一种类型转换为另一种类型：</font>
<font size=10>从一种类型转换为另一种类型：</font>
```python
  x = 10 # int
  y = 6.3 # float
  z = 1j # complex
  
  # 把整数转换为浮点数
  
  a = float(x)
  
  # 把浮点数转换为整数
  
  b = int(y)
  
  # 把整数转换为复数：
  
  c = complex(x)
  
  print(a)
  print(b)
  print(c)
  
  print(type(a))
  print(type(b))
  print(type(c))
```
<font size=10>注释：您无法将复数转换为其他数字类型。</font>

### 随机数
<font size=10>Python 没有 ` random() ` 函数来创建随机数，但 Python 有一个名为 ` random ` 的内置模块，可用于生成随机数：</font>
<font size=10>导入 random 模块，并显示 1 到 9 之间的随机数：</font>
```python
  import random
  
  print(random.randrange(1,10))
```
<font size=10>在 Random 模块参考手册 中，您将了解有关 Random 模块的更多信息。</font>
