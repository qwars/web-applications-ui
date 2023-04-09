# web-applications-ui::stylussheets

stylussheets - ветка для подключения и разработ CSS в проектах

Подключение

git submodule add -b stylussheets git@github.com:qwars/web-applications-ui.git develop/stylesheets

Обновляем

git submodule update --init --recursive 

Внедрение с обработчиками JS

`import './stylesheets'`

или без обработчиков в CSS

`@import './stylesheets'`

или можно по отдельности любой из наборов

## Особенности

Если версия Imba не поддерживает некоторые атрибуты тегов, то можно их добавить в список поддеррживаемых

Можно просто подключить эти исправления и сразу все стили как `import './stylesheets'`

Не достающие атрибуты добавляются как ` attr:name-atribute`

