# Отчет о тестировании функции "Валидация банковских карт"

## Краткое описание
Документация "Руководство пользователя" не соответствует действительности.


30.12.2020 - 30.12.2020 было проведено тестирование функциональное участка приведенного кода.

На тестирование затрачено: 0,1 часа

В результате тестирования выявлены следующие дефекты:

Валидными картами являются только те номера карт, которые равны 16 числовым значениям, и где не одно число кроме второго не должно быть равно 0.

## Описание процесса тестирования
* подбор карт из сервиса freeformatter.com и исполнение Java кода в окружении IDE


В качестве тестовых данных использовались данные из сервиса freeformatter.com:
* В качестве тестовых данных использовалась часть кода из второго задания домашней работы:
* Допустимо использовать для банковской карты число 0 от 2 до 16 порядка.

Тестирование производилось в следующем окружении:
* windows 10 x64
* версия Java 11.0.9.1
* версия IntelliJ IDEA 2020.3
