# Nginx with Node.js and Docker

The challenge was to create a simple web application using Node.js and Nginx as a reverse proxy. When the user access nginx, it should redirect the request to the Node.js application and add a register in the MySQL database with a random name in the table "people".

The return of the Node.js to the Nginx should be an h1 tag with the text "Full Cycle Rocks!" and also a list of all the names in the database.

Generate a docker-compose that will run the application and expose the port 8080.

---

### Run the application

```
docker-compose up -d
```

---

### Access the application

[http://localhost:8080/](http://localhost:8080/)

---
