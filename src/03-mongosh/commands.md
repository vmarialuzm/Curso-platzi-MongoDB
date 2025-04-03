# Connect to container

```sh
docker-compose exec mongodb bash
```

# Connect with mongosh

```sh
mongosh "mongodb+srv://2015024505:VNtZJXjQUYgTO7e7@cluster0.foaikjb.mongodb.net/"
mongosh "mongodb://localhost:27017/?tls=false"
```

```sh
show dbs
show collections
```

```sh
use ("platzi")
db.products.find()
```
