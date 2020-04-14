

task
1

number_1 = int(input('Введите первое число '))
number_2 = int(input('Введите второе число '))
number_3 = int(input('Введите третье число '))

stroka_1 = input('Введите строку')
stroka_2 = input('Введите строку')
stroka_3 = input('Введите строку')

print('вы ввели числа', number_1, number_2, number_3)
print('вы ввели строку', stroka_1, stroka_2, stroka_3)

task
2

sec = int(input('Введите время в секундах: '))

hours = sec // 3600
minutes = (sec - hours * 3600) // 60
seconds = sec % 60
print("{:.2f} часы:{:.2f} минуты:{:.2f} секунды: ".format(hours, minutes, seconds))

task
3
numbers = int(input('Введите число: '))

num = numbers + numbers * 11 + numbers * 111

print('Число после преобразования', num)

** ** ** ** ** ** ** ** ** ** ** ** ** ** ** ** ** ** ** ** ** ** ** ** ** ** ** ** ** 
task
4
a = int(input('Введите целое число: '))
m = a % 10
a = a // 10
while a > 0:
    if a % 10 > m:
m = a % 10
a = a // 10
print('Максимальная цифра в вашем числе', m)

task
5
profit = int(input('Ваша выручка :'))
expenses = int(input('Ваши издержки :'))

if profit > expenses:
    print('Ваша чистая прибыль ', profit - expenses, 'руб.')
    personal = int(input('Количество работников? : '))
    zp = (profit - expenses) / personal
    print('Прибыль фирмы в расчёте на одного сотрудника', zp, 'руб.')
else:
    print('Ваш убыток', expenses - profit, 'руб.')


task
6
a = int(input('Введите дситанцию первого дня пробежки в километрах:'))
b = int(input('Введите параметры требуемой дистанции в километрах:'))
day = 1
while b - a >= 0:
    a = a + (a * 0.1)
    day += 1
print('Через', day, 'дней вы достигнете требуемого результата.')

