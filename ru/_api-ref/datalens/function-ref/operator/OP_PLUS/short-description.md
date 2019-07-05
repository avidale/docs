**Синтаксис:**`value_1 + value_2`

Имеет различное поведение в зависмости от типов аргументов. Возможные варианты приведены в таблице:

| Тип `value_1`      | Тип `value_2`   | Возвращаемое значение                                                                                                                                                               |
|:-------------------|:----------------|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `Число`            | `Число`         | Сумма чисел `value_1` и `value_2`.                                                                                                                                                  |
| `Дата`             | `Число`         | Дата, на `value_2` дней большая, чем `value_1` (с округлением вниз до целого количества дней).                                                                                      |
| `Дата со временем` | `Число`         | Дата со временем, на `value_2` дней большая, чем `value_1`. Если `value_2` содержит дробную часть, то она пересчитыватся в часы (`1/24`),  минуты (`1/1440`) и секунды (`1/86400`). |
| `Строка`           | `Строка`        | Объединение (конкатенация) строк `value_1` и `value_2`.                                                                                                                             |

Изменение порядка аргументов не влияет на результат