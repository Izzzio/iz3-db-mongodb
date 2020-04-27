# IZZZIO - MongoDB database plugin
MongoDB database plugin

## Usage

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
