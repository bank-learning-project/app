# Учебный банк

Рабочее место сотрудника банка: клиенты, счета, внутренние переводы и выписки.
Проект предназначен для самостоятельной практики Java, Vaadin, Anchor Modeling,
собственного небольшого ORM со Smart Query Builder и инженерного процесса разработки.

Цели: увереннее применять выбранную архитектуру в работе и уметь объяснить,
продемонстрировать и самостоятельно изменить решение на собеседовании.

## Документация

- [Требования и границы проекта](docs/requirements.md)
- [Проверяемые сценарии первой версии](docs/scenarios.md)
- [Архитектура и ответственность репозиториев](docs/architecture.md)
- [Процесс разработки и учебный формат](docs/development.md)
- [Поэтапный план учебных задач](docs/learning-plan.md)

## Репозитории

| Репозиторий | Назначение |
| --- | --- |
| [app](https://github.com/bank-learning-project/app) | Общая документация, сборка приложения, конфигурация, навигация, вход и связывание компонентов |
| [banking](https://github.com/bank-learning-project/banking) | Банковский домен, прикладные сценарии, Vaadin UI, хранение данных и миграции |
| [orm](https://github.com/bank-learning-project/orm) | Самостоятельно разрабатываемая библиотека отображения Anchor-модели, Smart Query Builder и работы с PostgreSQL |

Основа: модульный монолит на Java/Vaadin без Spring, PostgreSQL, Anchor Modeling,
Flyway, Maven, WAR на Jetty. Дополнительные обязательные учебные темы:
Camunda, Artemis и BIRT.

## Текущее состояние

Согласованы правила первой версии и проверяемые сценарии P0-01.
В P0-02 описан [путь создания и чтения клиента](docs/architecture.md#p0-02-создать-и-прочитать-клиента).
Реализация приложения и ORM запланирована на следующих этапах.
Следующая задача — [P0-03 «Выбрать версии и проверить совместимость»](https://github.com/bank-learning-project/app/issues/4).

Все примеры и данные проекта должны быть синтетическими. Архитектурный ориентир —
[Finance Lab](https://github.com/finance-lab-project/app/blob/main/docs/architecture.md),
ориентир для процесса разработки —
[Java-трек ШБР 2023](https://www.youtube.com/playlist?list=PLZvfMc-lVSSOlYUajJ7Cem4nCzeRhvlwt).
