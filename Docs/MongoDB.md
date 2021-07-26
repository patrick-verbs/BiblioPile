### Connection string to add to application code:
```
mongodb+srv://Patrick:<password>@cluster0.m0ks7.mongodb.net/myFirstDatabase?retryWrites=true&w=majority
```

### Full server code sample:
```
const { MongoClient } = require('mongodb');
const uri = "mongodb+srv://Patrick:<password>@cluster0.m0ks7.mongodb.net/myFirstDatabase?retryWrites=true&w=majority";
const client = new MongoClient(uri, { useNewUrlParser: true, useUnifiedTopology: true });
client.connect(err => {
  const collection = client.db("test").collection("devices");
  // perform actions on the collection object
  client.close();
});
```

### Tutorial
MongoDB quick start guide: [https://www.mongodb.com/blog/post/quick-start-nodejs-mongodb--how-to-get-connected-to-your-database](https://www.mongodb.com/blog/post/quick-start-nodejs-mongodb--how-to-get-connected-to-your-database)