# onlineshopping
It is online based Product Booking Application for End Users/Customers. 
Customers can register, login and search products.They can add items to cart and do payment.
Application Admin can Add/Manage Sales Persons, Employees and Admins also.
Employee can add Brand and Categories, they can view reports for types like excel/PDF and Charts. 
Sales persons can add/handle Product, Stock, Order Management, Coupons and Shipping Process.
Finally Customers can search and buy product, can download invoice and feedback, track and return products.

Roles in Project:-
ADMIN
EMPLOYEE/STAFF
SALES PERSON
CUSTOMER

Module in Project:-
Brand: Every Product must be connected with one Brand. It contains code, tag Line, Image with description. Example: LG, SAMSUNG, IPHONE....

Category: Every Product even contains Categories. Name, Status(Active/Inactive). Example like Electronics, Menswear, Womenswear, Kidswear,....

Coupon: - Coupons are used to provide some sort of discount based on given voucher. With limited user and expiry date.

Customer: - He can register and login to search and buy products. He can update password, can see his profile, orders, track them ...

Product: - Sales person can add/manage Products. Product contains lot of details and connected to brand, category, status, length, width, height, cost, full and short description.

Stock: - Products count and existence to place orders can be managed by Sales persons using this module.

Cart and Shipping: Customer can add items to cart to buy them and once placed order shipping details are shared by Sales person to customer.

Order: Once Cart items are accepted then new order is placed with status OPEN now user has to payment to ACCEPT SHIPPING.

Tracking: Order status can be traced with location and details by order id which are placed by customers after login.

Feedback and Comments: Product can be reviewed and commented by multiple customers. With details rating description.

Reports: Sales person can see order related reports like OPEN, SHIPPING, DELIVERED ... and at same time EMPLOYEE can see no.of brands and categories details.

Tools and Technologies used:-
Spring Boot, Thymeleaf, Data JPA, Java Mail API, HTML, CSS, JQuery, Bootstrap, JUnit, Log4J, Maven, Heroku Cloud CLI.
