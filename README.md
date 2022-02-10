# WebFont Rubik

Пакет для установки веб-шрифта: Rubik.

## Установка

Чтобы установить пакет, Вы можете воспользоваться командой в CLI:

```bash 
npm install --save https://github.com/getscope/npm-webfont-rubik
```

или в файле `package.json` создать свойство `dependencies` и добавить ссылку на github-репозиторий:

```json 
{
    "dependencies": {
        "@getscope/npm-webfont-rubik": "github:getscope/npm-webfont-rubik"
    }
}
```

и выполнить команду в CLI для обновления установленных зависимостей:

```bash 
npm update
```

## Примеры использования и подключения

```css 
body {
    font-family: 'Rubik', sans-serif;
}
```

Для импорта веб-шрифта в SCSS, Вы можете воспользоваться следующими путями:

```scss 
@import "node_modules/@getscope/npm-webfont-rubik/src/scss/_300-normal.scss";
@import "node_modules/@getscope/npm-webfont-rubik/src/scss/_400-normal.scss";
@import "node_modules/@getscope/npm-webfont-rubik/src/scss/_500-normal.scss";
@import "node_modules/@getscope/npm-webfont-rubik/src/scss/_700-normal.scss";
@import "node_modules/@getscope/npm-webfont-rubik/src/scss/_900-normal.scss";
@import "node_modules/@getscope/npm-webfont-rubik/src/scss/_all-normal.scss";
```
