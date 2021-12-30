# Webpack 5 module federation

## Подходящие технологии
- Single SPA: работает из коробки с поддержкой различных фремвоков Vue, React и т.п.
- Webpack 5: придется самим писать поддержку различных фремвоков

## remoteEntry.js
Лоадер чанков, содержит поле exposes в котором содержатся все компоненты, которые нужно экспортировать.

Подключение скриптов, лучше переложить на "плечи" Module Federation


## Источники
https://www.youtube.com/watch?v=ugkOEg5xJCA
https://www.youtube.com/watch?v=RcWqY4kcjDY
