# Отримуємо і виводимо весь список контактів у вигляді таблиці (console.table)

node index.js --action="list"

https://prnt.sc/RCu2gmWf9fws

# Отримуємо контакт по id і виводимо у консоль об'єкт контакту:

node index.js --action="get" --id 05olLMgyVQdWRwgKfg5J6

https://prnt.sc/kvklwTuUP0kn

або null, якщо контакту з таким id не існує.
https://prnt.sc/cnIA7HhOk2uJ

# Додаємо контакт та виводимо в консоль об'єкт новоствореного контакту

node index.js --action="add" --name Mango --email mango@gmail.com --phone 322-22-22

https://prnt.sc/j8WgUDCB8Bg8

# Видаляємо контакт та виводимо в консоль об'єкт видаленого контакту або null, якщо контакту з таким id не існує.

node index.js --action="remove" --id qdggE76Jtbfd9eWJHrssH

https://prnt.sc/nW2zM2-vguN0
