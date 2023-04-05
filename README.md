# easy-database.js
- Версія 1.1.0
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

# Функції
```javascript
set(key, value) - встановити значення

get(key) - отримати значення

reset(key) - обнулити

addition(key, value) - додавання

subtraction(key, value) - віднімання

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

console.log(db.get("key")) //Поверне undefined
```

# Приклад Використання addition

```javascript
const database = require("easy-database.js")
const db = new database({
  name:"test", 
})
//названня файла в якому буде зберігатися значення

db.set("key", 8) //Встановлюєио значення 8

db.addition("key", 6) // Додаємо 6

console.log(db.get("key")) // Поверне 14
```

# Приклад Використання subtraction
```javascript
const database = require("easy-database.js")
const db = new database({
  name:"test",
})
//названня файла в якому буде зберігатися значення

db.set("key", 8) //Встановлюєио значення 8

db.subtraction("key", 6) // Віднімаємо 6

console.log(db.get("key")) // Поверне 2
```

# Помилки
<div style="color:red;">
easy-database.js error 
<br>
typeof must be number</div> - Тип даних має бути числом рішення змінити value на число

# Інше 
- Ця бібліотека дуже легка в використанні тому можуть бути недоліки
- Бібліотека зроблена не на всі 100 відсотків тому можуть бути помилки
- Біблеотека створена не для виликих проектів
- Для нашої бібліотеки є кращі аналоги
- [За допомогую пишіть сюди](https://discord.com/channels/796504104565211187/975785826401263706)



