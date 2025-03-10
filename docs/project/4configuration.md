# Конфигурация

В этом разделе описаны основные параметры конфигурации проекта.

## Настройка MkDocs

MkDocs использует файл `mkdocs.yml` для настройки. Пример конфигурации:

```yaml
site_name: Моя документация
nav:
  - Главная: index.md
  - О проекте: about.md
  - Контакты: contact.md
  - Установка: installation.md
  - Конфигурация: configuration.md
theme: readthedocs
```

## Параметры темы

Вы можете выбрать одну из доступных тем, таких как readthedocs, material и другие.

## Плагины

MkDocs поддерживает множество плагинов для расширения функциональности. 

Например:

- mkdocs-material: Тема Material Design.

- mkdocs-minify-plugin: Плагин для минификации HTML, CSS и JS.