<h1> Mohaimen's Basic CRUD API </h1>

This API can create, read, update and destroy products.

To run and test functionality do the following:
<li> 1. git clone repo </li>
<li> 2. cd into the repo </li>
<li> 3. install all module: npm install </li>
<li> 4. run the server in dev mode: npm run dev </li> 
<li> 5. You will need a mongoDB uri: create you db link and put in dev_url under app.js </li>
<li >6. Test out the functionality using any API tester: POSTMAN </li>


<h4> Examples of postman commands: </h4>

<li> create: http://localhost:3000/products/create [POST Request] </li>
<li> udpate: http://localhost:3000/products/<product_id>/update [PUT request] </li>
<li> Delete: http://localhost:3000/products/<product_id>/delete [DELETE request] </li>
<li> Fetch: http://localhost:3000/products/<product_id> [GET request] </li>
