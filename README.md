# IZZZIO - MongoDB database plugin
MongoDB database plugin

## Usage

Install globally by

```
npm -g i iz3-db-mongodb
```

or install as depency in DApp

```
npm i --save iz3-db-mongodb
```

Example - anonymus connection
config.json
```
  "blocksDB": "mongodb://localhost:27017/blocksByPlugin",
  "accountsDB": "mongodb://localhost:27017/accountByPlugin",
```

Example - connection with auth
config.json
```
 "blocksDB": "mongodb://dbUser:dbPass@localhost:27017/blocksByPlugin",  
 "accountsDB": "mongodb://dbUser:dbPass@localhost:27017/accountByPlugin",
```
