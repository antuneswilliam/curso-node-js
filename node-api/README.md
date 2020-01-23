# NPM commands

## init project
```
npm init -y
```

## npm Install
```
npm install
```

---

# Dependencies

## install nodemon
```
npm install nodemon -D
```

### start server via nodemon
Add the following script block to our package.json file
```
"dev": "nodemon server.js"
```
and then run
```
npm run dev
```
to start de server

## require-dir
```
require-dir
```

## swagger
```
npm install swagger-ui-express
```

## express
```
npm install express
```

## mongoose
```
npm install mongoose
```

### mongoose-paginate
```
npm install mongoose-paginate
```

## cors
```
npm install cors
```

---

# Docker commands

## Install mongo image
```
docker pull mongo
```

## Create container
```
docker run --name mongodb -p 27017:27017 -d mongo
```

## List online containers
```
docker ps
```

## List all containers
```
docker ps -a (listar todos os containers)
```

## Start an existing container
```
docker start mongodb
```