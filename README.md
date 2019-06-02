I Клонируем проект 

git clone

II По подсказке (ссылка внизу справа) делаем

npm install

Добавляется папка "node_modules" с закачанными туда необходимыми файлами 

III Запускаем проект в режиме "development"

 npm start
 
 или в режиме "production"
 
 npm run build

# webpack-starter-config

Simple webpack configuration with babel, sass and webpack-dev-server.

Js and css will minify in production mode.

## Development mode

```
npm start
```

In this mode *.css and *.js will  remove from /public folder.

## Production mode

```
npm run build
```

Assets (*.css and *.js) will save in /public folder.

