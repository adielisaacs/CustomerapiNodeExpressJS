# CustomerapiNodeExpressJS

#  Rest APIs with Node.js Express & MySQL example

## Project setup
```
download the project and unzip to a folder

in console run the following on commandline 
npm install
```

### Run
```
node server.js

### URL Definitions

http://localhost:3000/customers

post("/customers", customers.create);
  // Retrieve all Customers
  get("/customers", customers.findAll);
  // Retrieve a single Customer with customerId
  get("/customers/:customerId", customers.findOne);
  // Update a Customer with customerId
  put("/customers/:customerId", customers.update);
  // Delete a Customer with customerId
  delete("/customers/:customerId", customers.delete);
  // Create a new Customer
  delete("/customers", customers.deleteAll);
