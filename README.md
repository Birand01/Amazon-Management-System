# Content of Amazon-Management-System1 

The following requirements for a database regarding the Amazon management system. Amazon is an online shopping website:
• A customer has a ”customerID”, an ”email” and a ”password”.
• A customer may have several payment infos.
• An payment info has a ”cardNumber”, a ”expirationDate” and a ”securityCode”. However, cardNumber is unique only for a given customer. Different customers can have payment info with the
same cardNumber.
• A customer can be either a ”regular” or a ”prime”.
• A ”regular” customer should pay for shipping and has a ”giftCard” and ”coupon”. Delivery of
order by a shipper is paid by a ”regular” customer.
• A ”prime” customer can place an order without shipping payment and has a ”freeShipping”, a
”primeReading”, a ”primePhotos” and a ”primeMusic”.
• A supplier has a ”supplierID”, a ”name”, a ”address”, and a ”contact”.
• A supplier supplies a product.
• A shipper has a ”shipperID”, a ”name”, and a ”contact”.
• A shipper delivers order.
• A product has a ”productID”, a ”name”, and a ”amount”.
• A customer can place an order.
• An order has a ”orderID” and a ”totalCost”.
• Each order should be delivered by a single shipper.
• Each order should include at least one product.
• Each order should be placed by a customer.
• Each product should be supplied by some supplier.

This project contains the following,
• E-R diagram and corresponding schemata (image file),
• MYSQL create table scripts.


# Content of Amazon-Management-System2
Constructed a physical database according to given ER diagram. To construct the physical database, it
is required to use a database management system.
There are bunch of  SQL statements corresponding to the below queries,

a) List all the prime customers.
b) List the regular customer(s) which has the highest coupon.
c) List the productID, product name and amount of products that have been bought by exactly
one customer such that none of these products are bought by any other customer.
d) List the orderID and total cost of orders which has the same shipperID.
e) List the name and address of the suppliers which supplied at least 2 different products.
f) Delete product(s) which has the lowest amount.
g) Find the order which has the maximum total cost, update it’s total cost so that its total cost
becomes same as the minimum total cost at the end of the update.

# Content of Conceptual Design
I designed a conceptual database regarding my research interests,education, personal interests etc. 
 This project is including:
• Schemas of the database
• E-R diagram of the database



