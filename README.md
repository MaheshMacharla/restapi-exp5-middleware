![WhatsApp Image 2025-09-13 at 16 30 03_ac8e856e](https://github.com/user-attachments/assets/45efdc23-8cf2-4db0-8c6e-4d65b897f846)


API Test - POST Request to /api/data

The screenshot below demonstrates a successful POST request to the /api/data endpoint using Postman. The request body contains JSON data, which includes information about a product, such as its name, price, and stock status.

Request Body (POST):

{
  "product": "Smartphone",
  "price": 699,
  "inStock": true
}


Response:
The server successfully processes the data and returns a response with a confirmation message, along with the received data.

Response Body:

{
  "message": "Data received successfully!",
  "your_data": {
    "product": "Smartphone",
    "price": 699,
    "inStock": true
  }
}
