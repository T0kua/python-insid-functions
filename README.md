# python-insid-functions
> helping with python work

---
### оглавление
* [Представление объекта](https://github.com/T0kua/python-insid-functions#%D0%BF%D1%80%D0%B5%D0%B4%D1%81%D1%82%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5-%D0%BE%D0%B1%D1%8A%D0%B5%D0%BA%D1%82%D0%B0)
* [Математические функции](https://github.com/T0kua/python-insid-functions#%D0%BC%D0%B0%D1%82%D0%B5%D0%BC%D0%B0%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B5-%D1%84%D1%83%D0%BD%D0%BA%D1%86%D0%B8%D0%B8)
* [Логические функции](https://github.com/T0kua/python-insid-functions#%D0%BB%D0%BE%D0%B3%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B5-%D1%84%D1%83%D0%BD%D0%BA%D1%86%D0%B8%D0%B8)
* [Работа с окружением]()

ascii complex
bytearray delattr
bytes dir
classmethod(function) dict
compile 
---
### Представление объекта
функции конвертирующие тип объекта

`srt(x)` - изменяет тип объекта на Строку

`int(x)` - изменяет тип объекта на целочисленное

`chr(int)` - Возвращает символ по его числовому представлению

`float(x)` - изменяет тип объекта на плавающие число

`bool(x)` изменяет тип объекта на Логический

`bin(int)` - преоброзование целого числа в двоичную строку

`callable(finc)` - Возврощает **True** для объекта поддерживающего вызов

```
x = 1

callable(exit) #>>>True

bin(20) #>>>'0b10100'

bool(x) #>>>True

float(x) #>>>1.0

int(x) #>>>1

chr(17257) #>>>'䍩'

str(x) #>>>"1"
```
---
### Математические функции
`abs(int)` - Возвращает модуль числа (избавление от минуса)
`abs(-5) #>>>5`
---
### Логические функции
`all(iterable)` - проверяет, все ли указанные **элементы** принимают значение "истина"
оператор И для всех элементов `element1 == True AND element2 == True AND ... elementN == True`

```
all([1,2]) #>>>True
all([]) #>>False
all([True,True,False]) #>>>False
```

`any(iterable)` - проверяет, есть ли хотя бы один **элемент** принимающий значение "истина"
оператор ИЛИ для всех элементов `element1 == True OR element2 == True OR ... elementN == True`


```
any([1,2]) #>>>True
any([]) #>>False
any([True,True,False]) #>>>True
```
---
### Работа с окружением
`dir`
