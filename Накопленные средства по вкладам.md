per_cent = {'ТКБ': 5.6, 'СКБ': 5.9, 'ВТБ': 4.28, 'СБЕР': 4.0}
money = int(input("Введите сумму:"))
deposit = [5600.0, 5900.0, 4280.0, 4000]
deposit.append(per_cent['СБЕР'] * money/100)
print(deposit)
print(max(deposit))
