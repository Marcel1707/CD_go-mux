## Additional functionality

I added the following two routes to the REST API:

- DELETE /products -> deletes all existing products in the database
- GET /products/filter?minPrice=10&maxPrice=20 -> filters all products with the specified minimum and maximum price (both inclusive)