x = float(input("Введите число: "))
if x % 2 == 0:
    print("Число четное")
else:
    print("Число нечетное")
if x % 5 == 0:
    print("Число кратно 5")
else:
    print("Число не кратно 5")
2
numblit = float(input("Введите количество литров топлива: "))
perlit = float(input("Введите стоимость за литр: "))
distance = float(input("Введите пройденное расстояние: "))
print(f"На топливо было потрачено:{numblit * perlit}")
print(f"Расход топлива на 100 км:{(numblit/distance)*100}")
3
x = float(input("Введите ваш доход: "))
if x < 10000:
    print(f"Налог 5%, ваш налог составляет:{(x*5)/100}")
elif 10000<=x<=50000:
    print(f"Налог 10%, ваш налог составляет:{(x*10)/100}")
else:
    print(f"Налог 15%, ваш налог составляет:{(x*15)/100}")
4
value = float(input("Введите сумму в рублях:"))
choice = input("Выберете валюту(доллары или евро):")
if choice == "доллары":
    print(f"Сумма в долларах:{value/96.09}")
elif choice == "евро":
    print(f"Сумма в евро:{value/104.4}")
else:
    print("Ошибка")
5
x = float(input("Введите ваш  рост в метрах: "))
y = float(input("Введите ваш  вес в килограммах: "))
bmi = y/(x * x)
if bmi < 18.5:
    print("Недостаточный вес")
elif 18.5 <= bmi <= 24.9:
    print("Норма")
elif 25 <= bmi <= 29.9:
    print("Избыточный вес")
elif bmi > 30:
    print("Ожирение")
6
x = int(input("Введите количество вопросов в тесте:"))
y = int(input("Введите количество правильных ответов:"))
z = (y/x)*100
if z < 50:
    print(f"Ваш результат {z}% неудовлетворителен")
elif z > 50:
    print(f"Ваш результат {z}% удовлетворителен")
