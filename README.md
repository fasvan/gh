### TODO

- ~~Исправить интеграционные тесты~~
- ~~Написать нагрузочные тесты (JMeter + taurus), сделать вывод отчётов~~
- ~~Визаулизировать результаты интеграционных тестов (Jenkins + Allure)~~
- Реализовать деплой (выбрать стек; предположение -- Docker Swarm)
- Сделать две среды с разными тестовыми данными
- Selenium-тесты: пример PageObject паттерн на Python

### Дополнительно

1. Для отчётов Allure на Jenkins был установлен Allure Plugin и добавлен CLI в разделе "конфигурация глобальных инструментов": /configureTools/
2. Для отчётов по результатам запуска Taurus был установлен Performance Plugin
3. Для работы Taurus на сервер с Jenkins'ом был установлен virtualenv.