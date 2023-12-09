Отримуємо і виводимо весь список контактів у вигляді таблиці (console.table)
node index.js --action="list":

https://monosnap.com/file/4fmFv4DG8yqDFUlD1UHHa4WtQCAE8U

Отримуємо контакт по id і виводимо у консоль об'єкт контакту або null, якщо контакту з таким id не існує.
node index.js --action="get" --id 05olLMgyVQdWRwgKfg5J6:

https://monosnap.com/file/AOtW6Hp36bG7mlxibUwAgNJbKWpwLV

Додаємо контакт та виводимо в консоль об'єкт новоствореного контакту
node index.js --action="add" --name Mango --email mango@gmail.com --phone 322-22-22:

https://monosnap.com/file/o6nN65LbSSAbh7FxBCbQwYL4ePK4Gz

Видаляємо контакт та виводимо в консоль об'єкт видаленого контакту або null, якщо контакту з таким id не існує.
node index.js --action="remove" --id qdggE76Jtbfd9eWJHrssH:

https://monosnap.com/file/2MHAQMYon1Nt3DIUIeTOFXwrAExXlh
