# books

- Installed MongoDB [custom mode and without Compass] and made sure the folder c:/data/bin exists.

- Opened command prompt, CD'd to C:\Program Files\MongoDB\Server\4.0\bin and ran mongod. Left it running in the background.

- Opened another command prompt, CD'd to C:\Program Files\MongoDB\Server\4.0\bin and ran mongo. Can now play with Mongo commands.

- Played with Mongo commands: 

1. use insertdbname

2. show insertdbname

3. show collections, 

4. db.createCollection("name"), 

5. db.collectionname.insert({"key":"value"})

6. db.collectionname.find({}) - shows all the items in the collection

- Cloned the project to my desktop, CD'd into server

C:\Users\elis\Desktop\Clone of 4578_25\Full-stack-4578_25\03_Node\Book store - mongo + node + angular\server

ran npm i and then npm start. 

Then CD's into client

C:\Users\elis\Desktop\Clone of 4578_25\Full-stack-4578_25\03_Node\Book store - mongo + node + angular\client

ran npm i and then ng serve --open
