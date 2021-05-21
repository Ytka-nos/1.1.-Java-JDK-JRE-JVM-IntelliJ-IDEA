# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

11.05.2021   было проведено функциональное тестирование  приложения Credit Card Number Validator.

На тестирование затрачено: 

2 часа

В результате тестирования выявлены следующие дефекты:
* [Ошибка валидации для 14-и, 15-и 19-и значной карты](https://github.com/Ytka-nos/1.1.-Java-JDK-JRE-JVM-IntelliJ-IDEA/issues/1)


## Описание процесса тестирования





В качестве тестовых данных использовались данные с ресурса для регерации и валидации номеров кредитных карт   https://www.freeformatter.com/credit-card-number-generator-validator.html
Карты:
* VISA
* Discover
* Diners Club - Carte Blanche
* Visa Electron
* MasterCard
* JCB
* Diners Club - International
* InstaPayment
* American Express (AMEX)
* Diners Club - North America
* Maestro


Тестирование производилось в следующем окружении:
* версия и разрядность ОС - 20H2 64-разрядная операционная система, процессор x64
*  Java 11
