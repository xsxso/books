# books

- Installed MongoDB [custom mode and without Compass] and made sure the folder c:/data/bin exists.

- Installed Angular CLi @ c:\ via npm install -g @angular/cli ran at the command line level. 

- Opened command prompt, CD'd to C:\Program Files\MongoDB\Server\4.0\bin and ran mongod. Left it running in the background.

- Opened another command prompt, CD'd to C:\Program Files\MongoDB\Server\4.0\bin and ran mongo. Can now play with Mongo commands.

- Played with Mongo commands: 

1. use insertdbname

2. show insertdbname

3. show dbs, show collections

4. db.createCollection("name"), 

5. db.collectionname.insert({"key":"value"})

6. db.collectionname.find({}) - shows all the items in the collection

- Cloned the project to my desktop, CD'd into server

C:\Users\elis\Desktop\Clone of 4578_25\Full-stack-4578_25\03_Node\Book store - mongo + node + angular\server

ran npm i and then npm start. 

Then CD's into client

C:\Users\elis\Desktop\Clone of 4578_25\Full-stack-4578_25\03_Node\Book store - mongo + node + angular\client

ran npm i and then ng serve --open

Installed cURL using these instructions https://develop.zendesk.com/hc/en-us/articles/360001068567-Installing-and-using-cURL

Added C:/curl to Windows global variable

POST of a new user 

curl -v -X POST -H "Content-type: application/json" -d  "{\"firstName\":\"Bob\",\"lastName\": \"Bryce\",\"userName\": \"BobB\",\"password\":\"36bbe50ed96841d10443bcb670d6554f0a34b761be67ec9c4a8ad2c0c44ca42c\"}" localhost:6000/api/users






