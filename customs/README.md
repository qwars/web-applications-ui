# Блоки и хуки web-applications-ui::stylussheets

Подключение

CSS: `@import './.....'`
JS: `import './....'`

## Tooltype - всплывающая подсказка, замена атрибуту title

Селектор: `[data-tooltype]`
CSS: При наведении на елемент появляется содержимое атрибута `data-tooltype`
JavaScript: обрабатывается событие `mouseenter` для элемента. Если курсор находится в области селектора то блок пытается быть в пределах видимости пользователя

> *NOTE*: Не рекомендую использовать JS подключение, лучше задать строгое позиционирование selector-element[data-tooltype]:after { top, right, bottom, left }. Уменьшит нагрузку






