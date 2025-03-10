# 14. Кастомизация

В этом разделе описаны способы кастомизации вашей документации.

## Кастомизация темы

Вы можете изменить цветовую схему, шрифты и другие параметры темы, отредактировав файл `mkdocs.yml`.

```yaml
theme:
  name: material
  palette:
    primary: indigo
    accent: blue
```

## Добавление собственных стилей
Создайте файл extra.css в директории docs/stylesheets и подключите его в mkdocs.yml.

```yaml
extra_css:
  - stylesheets/extra.css
```

## Добавление JavaScript
Вы можете добавить собственные JavaScript файлы, создав их в директории docs/javascripts и подключив в mkdocs.yml.

```yaml
extra_javascript:
  - javascripts/extra.js
```

Эти файлы можно использовать для создания структуры документации в MkDocs. Вы можете скопировать их в директорию `docs` вашего проекта и настроить `mkdocs.yml` для их отображения.
