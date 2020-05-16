# backend sprint 13 v.1.3.0

## Практическая работа №13

Изучение серверного программирования на node.js с использованием express.js.
Добавлена поддержка mongo.db
  
### Функционал:
```
GET /users - возвращает всеx пользователей
```
```
GET /users/id - возвращает пользователя по id, и сообщение об ошибке, если user не найден
```
```
POST /users - создает нового пользователя на запрос формата {"name": "...","about":"...","avatar":"url"} 
```
```
PATCH /users/me - обновляет имя и описание пользователя на запрос формата {"name": "...","about":"..."} 
```
```
PATCH /users/avatar - обновляет аватар пользователя на запрос формата {"avatar": "url"} 
```
```
GET /cards - возвращает все карточки
```
```
POST /cards - создает карточку на запрос формата {"name": "...","link":"url"}
```
```
DELETE /cards/id - удаляет карточку по id
```
```
PUT /cards/id/likes - добавляет лайк по id
```
```
DELETE /cards/id/likes - удаляет лайк по id
```
```
GET /someOtherPath - сообщение об ошибке, если путь не найден
```


## Установка

Для установки необходимо наличие Node.js и npm

Сохраните проект у себя на компьютере:
```
git clone https://github.com/t0nyhat/back_12.git
```

В корне проекта через консоль/терминал запустите команду:
``` 
npm install
```

#### Доступные команды:  
Запуск локального сервера с хот релоудом:  
```
npm run dev
```  
Запуск продакшн сервера:  
```
npm run start
```
