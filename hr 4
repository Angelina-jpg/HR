from math import log, sin, cos, tan, radians, log10, pi
from random import randint 
print('программа 1')
N = int(input('Введите число '))
a = int(input('Ведите начало множества '))
b = int(input('введите конец множества '))
if N % 2 == 0:
    N = N-1
for i in reversed(range(1, N+1)):
    if a <= i <= b:
        continue
    if i % 2 == 0:
        continue
    print(i)

print('Программа 2')
strk = "1"
while not ('конец' in strk):
    strk = str(input('введите строку'))
    if "Лого" in strk:
        print(log(len(input('введите строку'))))
    if 'Триго' in strk:
        a = radians(float((input('введите градусы'))))
        print('Синус числа = ', sin(a))
        print('Косинус числа =', cos(a))
        print('Тангенс числа =', tan(a))
        print('Котангенс числа =', cos(a) / sin(a))

print('программа 3')
n = int(input("введите число от 0 до 1000 "))
a = randint(0, 1000)
b = randint(0, 1000)
if i in range(min(a, b), max(a, b)):
    print('Lucky')
else:print('Try again')

print('программа 4')
c = 1
while not (c == 'N'):
    a = int(input('введите число не равное 0 '))
    b = int(input('введите число не равное 0 '))
    m = randint(min(a, b), max(a, b))

    for i in range(1, m):
        print(log10(i))
    c = input(('Желаете продолжит ? Y/N'  ))


print('программа 5')
i = int(input('введите число'))
for i in range(1, i):
    print('длина окружности с радиусом', i, ':', i * 2 * pi)
    print('Площадь круга с радиусом', i, ':', i ** 2 * pi)
