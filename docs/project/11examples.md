# 11. Примеры

В этом разделе приведены примеры использования проекта.

## Пример 1: Базовая настройка

```yaml
site_name: Моя документация
nav:
  - Главная: index.md
  - О проекте: about.md
```

## Пример 2: Использование плагинов


```yaml
plugins:
  - search
  - minify:
      minify_html: true
```

## Пример 3: Кастомизация темы

```yaml
theme:
  name: material
  palette:
    primary: teal
    accent: pink
```