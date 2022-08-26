## void-api
#### Simple fake api for test projects
The main goal of this project is to make project deployment easy with well thought out templates. The project is not intended to be used as a database. It is intended to be able to simply test the functionality of your application and belongs to the toolkit class.

#### Hosted
https://uastudio.site/void-api/ `sub_item` (see list down)

Team we need add separate jsons with different port
result https://uastudio.site8000/ -> /test/
result https://uastudio.site8001/void-api/ -> /animals/
folder /dbs/animals/db.json

result https://uastudio.site8002/void-api/ -> /brands/
folder /dbs/brands/db.json


Sections: 
- /void-api/
  - /animals/
  - /brands/
  - /food/
  - /snacks/
  - /anamorphic/

Database with this sign "?" - required your help

#### Written on pure JavaScript (Node.js)
For main functionality use `npm run watch`

For test use please use `npm run watch8000` what uses custom routes in `routes.json` it uses `port 8000` and no corrs

```

> void-api@1.0.0 watch /home/igavelyuk/1.Proj/void-api
> json-server --watch db.json
  \{^_^}/ hi!
  Loading db.json
  Done
  Resources
  http://localhost:3000/test
  Home
  http://localhost:3000
  Type s + enter at any time to create a snapshot of the database
  Watching...
```
#### Stucture of database json files
Json file can contain following: `objects, arrays, string, numbers, boolean, null`
