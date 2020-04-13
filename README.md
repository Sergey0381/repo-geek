# repo-geek
university
'''
**********************************************************
task 1

number = int(input('Введите число '))
stroki = input('Введите строку')

print('вы ввели число', number)
print('вы ввели строку', stroki)
**********************************************************
task 2

sec = int(input('Введите время в секундах: '))

hours = sec // 3600
minutes = (sec - hours * 3600) //60
seconds = sec % 60

print(f" {hours} час:  {minutes} минут:  {seconds} секунд")

**********************************************************
task 3

numbers = int(input('Введите число: '))

num = numbers + numbers * 11 + numbers * 111

print('Вы ввели число', num)

***********************************************************
task 4

num = int(input('Ввести число: '))
ls = []
while num > 10:
    ls.append(num % 10)
    num //= 10
result = max(ls)
print('Максимальная цифра',r)

***********************************************************
task 5
profit = int(input('Ваша выручка :'))
expenses = int(input('Ваши издержки :'))

if profit > expenses:
    print('Ваша чистая прибыль ' , profit - expenses, 'руб')
    personal = int(input('Количество работников: '))
    zar =( profit - expenses )/ personal
    print ('Прибыль фирмы в расчёте на одного сотрудника', zar ,'руб')
else:
    print('Ваш убыток', expenses - profit,'руб')

***********************************************************
task 6
a = int(input('Введите значение'))
b = int(input('Введите значение'))
day = 1
while b - a > 0:
    a = a + (a * 0.1)
    day += 1
print(day)
'''










