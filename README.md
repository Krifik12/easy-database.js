# easy-database.js

Документація для пакета easy-database.js

# Приклад

const database = require("easy-database.js")
const db = new database({
  name:"test", //названня файла в якому буде зберігатися значення
})

db.set("key", true) // встановлюемо значення ключа

console.log(db.get("name")) //Поверне true

