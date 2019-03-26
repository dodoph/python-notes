# python-notes

## command line Instruction 操作指令

* open ```python```
* close ```exit()```
* executive file ```python .py ```

## Input & Output

```python
name = input()
>>> Jessie

a = "Jessie"
print a
>>> Jessie
```

## String

```python
s = 'abcdef'
s[1:5]
>>> 'bcde' #not include index = 5

s[1]
>>> 'b'

s[5]
>>> 'f'

s[-1]
>>> 'f'

s[2:]
>>> 'cdef'

s[-5]
>>> 'a'

```

## List 列表

```python
class = ['ab', 'bc', 'cd']
len(classroom)

>>> 3

print classroom[2]
>>> 'cd'

print classroom[-1]
>>> 'cd'

````

### append / insert / pop

* Append method
```python
classroom = ['ab', 'bc', 'cd']
classroom.append('de')

print classroom
>>>['ab', 'bc', 'cd', 'de']

```

* Insert method
```python
name = ['Jessie', 'Kelvin', 'Chris']
name.insert(1, 'Lucy')
print name
>>> ['Jessie', 'Lucy', 'Kelvin', 'Chris']

```

* pop method

```python
name = ['Jessie', 'Kelvin', 'Chris']
name.pop(1)
print name
>>> ['Jessie', 'Chris']

```

* replace
```python
name = ['Jessie', 'Kelvin', 'Chris']
name[1] = 'Lucy'

print name
>>> ['Jessie', 'Lucy', 'Chris']

```


## Tuple 元组

* 类似于list列表
* 用```()```表示
* 定义只有一个元素的tuple，元素后面必须加逗号
* 元组一旦定义就不能修改

```python
tuple = ('name', 89, 2.33)

print tuple
>>> ('name', 89, 2.33)

print tuple[0]
>>> name #输出第一个元素

print tuple[1:2]
>>> (89,)

tuple = (2,)
print tuple
>>> (2,)

tuple = ('a', 'b', ['A', 'B']) #['A', 'B'] is a list 

print tuple[2][0]
>>> 'A'

```
