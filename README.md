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
npm -g ile yapılışı
npm install -g json-server
json-server --watch products.json     or     json-server --watch db.json 
localhost:3000/products or localhost:3000/categories or localhost:3000

bazı ayarlamalar
$ json-server --watch db.json --port 3004
learn
?--route  
?routes.json
?lowdb 

node ile yapılışı
npm init
package.json script
"json-server": "json-server --watch products.json"
npm run json-server


git ile yapılışı  -> gördüğü dosya db.json
https://my-json-server.typicode.com/typicode/demo
https://my-json-server.typicode.com/serkancan006/JsonPlaceHolder