# easy-database.js

Документація для пакета easy-database.js

# Приклад

const database = require("easy-database.js")
const db = new database({
  name:"test",
})

db.set("key", trur) // встановлюемо значення ключа

console.log(db.get("name"))

