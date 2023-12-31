# Grocy Store
This is a web application for a fruit store. The application allows users to view available fruits, add fruits to their cart, and purchase fruits. The application also has an admin section that allows an administrator to add new, update and delete grocery to the store.

## Setup

Run this command to get the backend started:

```console
$ json-server --watch db.json
```

Test your server by visiting this route in the browser:

[https://code-33jd.onrender.com/products]

Then, open the `index.html` file on your browser to run the application.

Write your code in the `src/index.js` file. The base URL for your API will be
[https://code-33jd.onrender.com/products].

## Core Deliverables

 A user, can:

1. View fruits: The user can view all the available fruits on the website.

2. Add fruits to cart: The user can add fruits to their cart by clicking the "Add to cart" button on each fruit card. They can also select the quantity they want to purchase.

3. Purchase fruits: The user can purchase the fruits in their cart by clicking the "Buy" button. This will multiply the purchased   quantity from the product price to get the total amount to be paid


   ```txt
   GET /products/
   Example Response:
   {
    "id": 1,
    "name": "Apple",
    "image": "https://img.freepik.com/premium-photo/red-apples-isolated-white-background-ripe-fresh-apples-clipping-path-apple-with-leaf_299651-595.jpg",
    "quantity": "kg",
    "price": "$10"
  },
   ```

   An Admin can:

 1. Add Grocery to the store: The admin can add new GRoceryto the store by filling out a form in the admin section. The form requires the admin to enter the fruit name,image link, and price.

 2. Update Grocery to the store: The admin can update new fruits to the store by filling out a form in the admin section. The form requires the admin to enter the grocery id, name , price and image.

 3. Delete Grocery from the store: The admin can delete a grocery from the store by clicking the "Delete" button on the fruit card.

   ```txt
   Post /products
   Example response:
   [
      {
    "name": "Apple",
    "image": "https://img.freepik.com/premium-photo/red-apples-isolated-white-background-ripe-fresh-apples-clipping-path-apple-with-leaf_299651-595.jpg",
    "price": "$10"
  },
  {
    
    "name": "Banana",
    "image": "https://metrob2b-storage.azureedge.net/products/192242/primary.jpg",
     "price": "$10"

  },
   ]
   ```

   ```txt
   Patch/products/1
   Example Response:
   {
    "id": 1,
    "name": "Apple",
    "image": "https://img.freepik.com/premium-photo/red-apples-isolated-white-background-ripe-fresh-apples-clipping-path-apple-with-leaf_299651-595.jpg",
    "price": "$10"
  },
   ```



### Technologies Used

     Technologies Used HTML CSS JavaScript JSON Fetch API 

## Credits

    This application was developed by Grace Makena Njagi. If you have any questions or suggestions, please contact me at keshgrace62@gmail.com

## References
   The API used for the project https://code-33jd.onrender.com/products

## Author
    Grace Makena Njagi

## License 
   MIT License

