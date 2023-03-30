# easy-database.js
- npm install easy-database.js
- Документація для пакета easy-database.js
- Розробник Krifik
- Діскорд Krifik#4967
- Телеграм @Krifik6

# Приклад

```javascript
const database = require("easy-database.js")
const db = new database({
  name:"test", 
})
//названня файла в якому буде зберігатися значення

db.set("key", true) // встановлюемо значення

console.log(db.get("key")) //Поверне true
```

# Функії
```javascript
set(key, value) - встановити значення

get(key) - отримати значення

reset(key) - обнулити

```
# Приклад Використання reset
```javascript
const database = require("easy-database.js")
const db = new database({
  name:"test", 
})
//названня файла в якому буде зберігатися значення

db.set("key", true) // встановлюемо значення true

db.reset("key") // Робимо обнулення

console.log(db.get("name")) //Поверне undefined
```

# Інше 
- Ця бібліотека дуже легка в використанні тому можуть бути недоліки
- Бібліотека зроблена не на всі 100 відсотків тому можуть бути помилки
- Біблеотека створена не для виликих проектів
- Для нашої бібліотеки є кращі аналоги
- [За допомогую пишіть сюди](https://discord.com/channels/796504104565211187/975785826401263706)


