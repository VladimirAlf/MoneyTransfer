# Отчёт о тестировании Пополнение банковского счета

## Краткое описание

08.07.21. - 08.07.21. было проведено функциональное тестирование приложения Пополнение банковского счета.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [Счет отрицательный при пополнении положительного баланса](https://github.com/VladimirAlf/MoneyTransfer/issues/1)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Код](https://github.com/VladimirAlf/MoneyTransfer/commit/d3f88dc53660e07bf3466f3d1ec70be3ddb3719a#diff-1597d2955516e4d404c9395c883d26475c58b27032926237f062392226c69fe9)


В качестве тестовых данных использовались данные:
* Текущий баланс счёта: 2 000 000 000 рублей перевод на баланс счёта: 500 000 000 рублей. Сумма 2 500 000 000 рублей.

Тестирование производилось в следующем окружении:
* Windows 10 Home, 64-разрядная ОС
* OpenJDK11U-jdk_x64_windows_hotspot_11.0.11_9
* Intellij IDEA Community Edition 2021.1.3
