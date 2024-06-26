# Репозиторий MLOps

Данный репозиторий создан для выполнения проекта в ходе прохождения курса [**MLOps и production в DS исследованиях 3.0**](https://ods.ai/tracks/mlops3-course-spring-2024)


## Инструкция к репозиторию

* `.pre-commit-config.yaml` - файл для настройки pre-commit хуков в проекте;
* `pyproject.toml` - содержит информацию о зависимостях и настройках проекта;
* `requirements.txt` - ??
* ``


## Методология ведения репозитория

Для внесения изменений в репозиторий используйте следующий порядок действий:
1. Создайте новую ветку для разработки с помощью команды `git checkout -b new-feature`.
2. Внесите необходимые изменения и убедитесь, что код соответствует стандартам.
3. Запустите линтеры и форматеры перед коммитом с помощью команды `pre-commit run --all-files`.
4. Закоммитьте изменения и отправьте `pull request` в основную ветку.
5. Ожидайте проверки кода и мержа изменений.

Для сборки и запуска Докер контейнера:
1. Выполнить команду сборки контейнера: `docker build -t myproject .`
2. Выполнить команду запуска контейнера: `docker run -p 8000:8000 myproject`
