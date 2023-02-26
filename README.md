# myHour-backend

### Goal

- Create a backend which keeps tracks of time & projects :- 
  - Login
  - Signup
  - Organize projects
  - Track time
  - Report your work
  - Coordinate projects and tasks
  - Track your work hours .

### Schema

- user
  - name, required
  - email, required, unique
  - password, required, min: 2, max:4
  - age,
- product
  - name
  - description
  - price
  - quantity
- cart
  - productId
  - userId
  - quantity

### Follow this steps:

1. npm init -y
2. npm i express mongoose
3. npm i -D nodemon dotenv
4. Folder Structure
   - src
     - config
       - db.js
     - features
       - product
         - product.model.js
         - product.router.js
       - user
         - user.model.js
         - user.router.js
       - cart
         - cart.model.js
         - cart.router.js
     - server.js
