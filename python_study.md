## Data type
```python
a = 10
b = 5.6

print(" a is", a, type(a)) # a is 10 <class 'int'>
print(" b is", b, type(b)) # b is 5.6 <class 'float'>
```

## operator
```python
x = 3
k = 6
print(" x^k = ", x ** k) # x^k
```

## operation
```python
print(a and b) # &&
print(a or b)  # ||
print(not a)   # !
print(a != b)  # XOR
```

## string
```python
str1 = 'hello'
str2 = "bye"
print(str1, str2) # hello bye

str3 = "  hello guys  "
print(str1.capitalize())   # Hello
print(str1.upper())        # HELLO
print(str1.replace('llo', 'll')) # hell
print(str3.strip())        # hello guys
```

## list
```python
arr = [1, 2, 'hi']
arr.append('bye')
elem = arr.pop()
print(arr, elem)  # [1, 2, 'hi'] bye
```

## dictionary
```python
dic = {'cat' : 'cute', 'dog' : 'pretty'}
print(dic['cat'])       # cute
print('cat' in dic)     # True
print('mouse' in dic)   #False
```

## for loop
```python
for i in range(n):
   print(i)
# 0 ~ n-1 까지 출력

for i in range(k, n):
   print(i)
# k ~ n - 1 까지 출력
```

## while loop
```python
while True:
   print(num)
   num -= 1
   if num == 0:
      break
```
