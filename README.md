# classwork07-09-23

## Остаток
Для получения остатка от деления в Python 3 используется операция, обозначающаяся символом процента «%». Остаток — это оставшаяся после целочисленного деления часть числа. Операция взятия остатка используется для решения различных видов задач.
формула:

- a % b=0,1,2...b-1

Примеры:

```python
print(10 % 3)
print(5 % 10)
print(5 % 0.25)
```
1

5

0.0

## Деление без остатка
Чтобы выполнить деление на цело в Python, можно воспользоваться целочисленным делением. В этом случае результатом будет целое число, без остатка. Целочисленное деление в Python обозначается двумя косыми чертами «//».

В отличие от других языков программирования Python позволяет результату целочисленного деления быть как целым `(int)`, так и дробным `(float)` числом. В обоих случаях дробная часть отбрасывается и получается число с окончанием «.0».

Примеры нахождения целой части от деления:
```python
print(5 // 2)
print(0 // 2)
print(1234 // 5.0)
```
2

0

246.0
