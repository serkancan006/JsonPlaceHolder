db.json
{
  "products": [
    { "id": 1, "name": "Product 1" },
    { "id": 2, "name": "Product 2" },
    { "id": 3, "name": "Product 3" }
  ],
  "categories": [
    { "id": 1, "name": "Category 1" },
    { "id": 2, "name": "Category 2" }
  ]
}
npm install -g json-server
json-server --watch db.json 
localhost:3000/products or localhost:3000/categories or localhost:3000


in node
npm run json-server
"json-server": "json-server --watch db.json"

json-server --watch db.json ----> -p ?    --route  ?
