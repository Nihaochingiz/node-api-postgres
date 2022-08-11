# node-api-postgres

Функционирующий сервер API, который работает на Node.js и подключен к активной базе данных PostgreSQL
 
Functioning API server that runs on Node.js and is hooked up to an active PostgreSQL database

Methods:
app.get('/users', db.getUsers)
app.get ('/users/:id', db.getUserById)
app.post('/users', db.createUser)
app.put('/users/:id', db.updateUser)
app.delete('/users/:id', db.deleteUser)
