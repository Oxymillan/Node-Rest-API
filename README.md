## NODE Restful API
> User Authentication using JWT
> DOM to JSON using multer

### Usage
> You need to have Node.js installed on your system
> Install dependencies and run using

```
# npm install
# npm start
```
> The server will start on port http://localhost:3000/

### Routes

```
METHOD         ROUTES                      MIDDLEWARE
-----------------------------------------------------
POST           /user/signup
POST           /user/login
DELETE         /user/:userId               Check auth
GET            /products
POST           /products                   Check auth
GET            /products/:productId
PATCH          /products/:productId        Check auth
DELETE         /products/:productId        Check auth
GET            /orders                     Check auth
POST           /orders                     Check auth
GET            /orders/:orderId            Check auth
DELETE         /orders/:orderId            Check auth
```