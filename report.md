# Отчёт о тестировании приложения "Money transfer"

## Краткое описание

При текущем балансе 2 000 000 000  после пополения на 500 000 000 итоговое значение получаем с ошибкой

## Описание тестов

Проведено функциональное Smoke тестирование основной функции приложения

## Результаты

1. 100% не успешных тестов
2. [Отрицательное значение при пополнении баланса](https://github.com/eaasy0/Money-Transfer-/issues/1#issue-825957451)

## Общие рекомендации

Тип данных int в нашем случае не подходит для хранения значения больше 2 147 483 647, нужно использовать тип данных long 
