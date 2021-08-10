# APIs

![api](https://www.mapsmarker.com/wp-content/uploads/2019/02/locationiq-step3.jpg)



***1. What does REST stand for?***

Representational State Transfer **(REST)**

***2. REST APIs are designed around a __.***

REST APIs are designed around resources, which are any kind of object, data, or service that can be accessed by the client.

***3. What is an identifer of a resource? Give an example.***

A resource has an identifier, which is a URI that uniquely identifies that resource. https://adventure-works.com/orders/1

***4. What are the most common HTTP verbs?***

The most common operations are GET, POST, PUT, PATCH, and DELETE.

***5. What should the URIs be based on? ***

I’m not sure, but i think based on the data itself in API and the type of service also that provided by the API.

***6. Give an example of a good URI ***

Like : /customers/1/orders/99/products , if i need the customers and will make the URI makes sense to the data requested by the user. here they used customer then the id of the desired customer and the orders and so on.

***7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing? ***

When you make the client makes many requests to get a small amuont of data for each request (based on organizing the data in your API), this will make a load on your server and you have to aviod that. for sure it is bad thing.

***8. What status code does a successful GET request return? ***

status code 200 (ok)



***9. What status code does a successful POST request return? ***

If a POST method creates a new resource, it returns HTTP status code 201

***10. What status code does a successful DELETE request return? ***
f the delete operation is successful, the web server should respond with HTTP status code 204 (No Content)

####  Things I want to know more about 
The Back_end api 

***Resources :   [API Design Best Practices](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)*** 
