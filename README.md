![Трансфер](https://www.hinditrendz.com/wp-content/uploads/2020/03/fund-money-transfer-2048x1366.jpg)
# Отчёт о тестировании: Money Transfer

## Краткое описание

13.07.2021 - 13.07.2021 было проведено белоящичное юнит тестирование кода приложения "Money Transfer".

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты (cмотри Issues данного репозитория): 
* [Неверный вывод значения итоговой суммы счета клиента после пополнения счета](https://github.com/Dmitruzd21/Money-Transfer/issues/1)


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* [Тест-кейс #1 - Вывод итоговой суммы счета клиента, который привышает диапазон типа данных int, после пополнение счета](https://github.com/Dmitruzd21/Money-Transfer/issues/2)

В качестве тестовых данных использовались данные: https://github.com/netology-code/javaqa-homeworks/tree/master/programming


### **Тестовые данные с ожидаемым результатом "Итоговый баланс счета клиента - 2 500 000 000**
Входные данные:
текущий баланс счёта клиента - переменная типа int, значение - 2_000_000_000 (два миллиарда рублей)*

сумма перевода - переменная типа int, значение - 500_000_000 (пятьсот миллионов рублей)

переменная для хранения итогового значения - тип int

**Тестирование производилось в следующем окружении:**
* VivoBook_ASUSLaptop X509DA_M509DA
* Windows 10
* Openjdk version "11.0.11" 2021-04-20, 
OpenJDK Runtime Environment AdoptOpenJDK-11.0.11+9 (build 11.0.11+9)
OpenJDK 64-Bit Server VM AdoptOpenJDK-11.0.11+9 (build 11.0.11+9, mixed mode)
* Git 2.31.1.windows.1