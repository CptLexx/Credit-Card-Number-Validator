# Отчёт о [тестировании](https://github.com/netology-code/javaqa-homeworks/tree/master/intro#%D0%B7%D0%B0%D0%B4%D0%B0%D1%87%D0%B0-2---credit-card-number-validator) `Credit Card Number Validator`

### Краткое описание

14.8.20 было проведено функциональное тестирование приложения `Credit Card Number Validator`.

На тестирование затрачено: три часа.

В результате тестирования выявлены следующие дефекты:
* [сбой валидации банковских карт системы `Diners Club - Carte Blanche`](https://github.com/Cliffart44/Java_hw_1/issues/4);
* [сбой валидации банковских карт системы `Diners Club - International`](https://github.com/Cliffart44/Java_hw_1/issues/5);
* [сбой валидации банковских карт системы `American Express (AMEX)`](https://github.com/Cliffart44/Java_hw_1/issues/6).

### Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* наработки программы [`Credit Card Number Validator`](https://github.com/Cliffart44/Java_hw_1/blob/master/CreditCardNumberValidator.txt).

В качестве тестовых данных использовались данные:
* [Тестовые номера карт](https://www.freeformatter.com/credit-card-number-generator-validator.html).

Тестирование производилось в следующем окружении:
* `Windows 10`; `версия 2004`; `тип x64`.
* `IntelliJ IDEA 2020.2 (Community Edition)`;
`Build #IC-202.6397.94, built on July 27, 2020`;
`Runtime version: 11.0.7+10-b944.20 amd64`;
`VM: OpenJDK 64-Bit Server VM by JetBrains s.r.o.`;
`Windows 10 10.0`;
`GC: ParNew, ConcurrentMarkSweep`;
`Memory: 733M`;
`Cores: 2`.
* `openjdk version "11.0.8" 2020-07-14`;
`OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.8+10)`;
`OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.8+10, mixed mode)`.
