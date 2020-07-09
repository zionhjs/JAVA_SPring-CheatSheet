# MongoDB Operations (Mac only) 

## 1 Install and connect MongoDB:
- 1.1 install homebrew  $ `xcode-select --install`

- 1.2 install mongoDB
- $ `brew tap mongodb/brew` 
- $ `brew install mongodb-community@4.2`

- 1.3 running mongoDB Server
- $ `brew services start mongodb-community`

- 1.4 connect to database
- $ `mongo` 

## 2 After entering the Mongo console:
- 2.1 basic knowledge of MongoDB
- Database(Mongo) = Schema(SQl)
- Collections(Mongo) = Tables(SQL)
- Document(Mongo) = Row/Record(SQL)

- 2.2 basic Database operations
- show all databases -> $ `show dbs`
- show current database -> $ `db`
- change to another database -> $ `use DB_NAME`
- Delete database -> $ `db.dropDatabase()`

- 2.3 basic Collection operations
- view all collections in a Database -> $ `show collections`
- Create a new collection in the current database -> $ `db.createCollection("Collection_Name)`
- Destroy a collection -> $ `db.CollectionName.drop()`

## 3 CRUD operations in MongoDB
- 3.1 Create - Insert a document into a collection
- $ `db.CollectionName.insert({Document_Name})`

- 3.2 Read - Retriving documents from a collection
- $ `db.CollectionName.find({Document_Name})`

- 3.3 Destory - Removing documents from a collection
- $ `db.CollectionName.remove({Document_Name})`

- 3.4 Update - Updating documents in a collection
- $ `db.collectionName.update({Document_Name, value}, {Document_Name, value}...)`

## for more Operations please read [MongoDB Docs](https://mongodb.github.io/mongo-java-driver/4.0/driver/)