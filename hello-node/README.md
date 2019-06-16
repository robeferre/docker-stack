# hello-node

Dependencies:

* Node.js v6

Install the requirements:

```
npm install
```

Configure the application:

```
export RABBITMQ_HOST=127.0.0.1
export RABBITMQ_PORT=5672
export RABBITMQ_QUEUE=hello
export MYSQL_HOST=127.0.0.1
export MYSQL_USER=root
export MYSQL_PASSWORD=5andar
export MYSQL_DB=hello
```

Run the app localy:

```
node app.js
```
