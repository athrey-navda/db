# db

A website to handle Json database

Used json-server

npm install json-server

# Usage - example

Create a db.json or db.json5 file

{
"posts": [
{ "id": "1", "title": "a title", "views": 100 },
{ "id": "2", "title": "another title", "views": 200 }
],
"comments": [
{ "id": "1", "text": "a comment about post 1", "postId": "1" },
{ "id": "2", "text": "another comment about post 1", "postId": "1" }
],
"profile": {
"name": "typicode"
}
}

# Pass it to JSON Server CLI

npx json-server db.json

# Run json-server --help for a list of options
