This API can create, read, update and destroy products.

To run and test functionality do the following:

1. git clone repo
2. cd into the repo
3. install all module: npm install
3. run the server in dev mode: npm run dev 
4. You will need a mongoDB uri: create you db link and put in dev_url under app.js
5. Test out the functionality using any API tester: POSTMAN


Examples of postman commands:

create: http://localhost:3000/products/create [POST Request]
udpate: http://localhost:3000/products/<product_id>/update [PUT request]
Delete: http://localhost:3000/products/<product_id>/delete [DELETE request]
Fetch: http://localhost:3000/products/<product_id> [GET request]