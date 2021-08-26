# Microservice Product

### Endpoints:

#### Save Product

....
POST /api/product HTTP/1.1
Host: localhost:3333
Authorization: Basic base64(username:password)
Content-Type: application/json
Content-Length: 45

{
"name": "test 2",
"price": 4.7
}
....

#### GET Products

....


GET /api/product HTTP/1.1
Host: localhost:3333
Authorization: Basic base64(username:password)
Content-Type: application/json
Content-Length: 45

{
"name": "test 2",
"price": 4.7
}

....


#### Delete Product

....

DELETE /api/product/2 HTTP/1.1
Host: localhost:3333
Authorization: Basic base64(username:password)
Content-Type: application/json
Content-Length: 45

{
"name": "test 2",
"price": 4.7
}

....