### Exercise 9 Introduction to MySQL
1. Access phpmyadmin in your web browser http://localhost/phpmyadmin/
2. Login and create database name ecommerce.
3. In your ecommerce database, create 2 tables products and categories.
*Categories*
  - Create new columns id and name
  - Insert the following data in categories table:
    - id: 1, name: Laptops
    - id: 2, name: Desktop PC
    - id: 3, name: Tablets
    - id: 4, name: Smart Phones
*Products*
  - Create new columns `id`, `category_id`, `name`, `description`, `slug`, `price`, `photo`, `date_view`, and `counter`
  - Insert the following data in products table:
    - id: 1, category_id: 1, 
    - name: 'DELL Inspiron 15 7000 15.6', 
    - description: '<p>15-inch laptop ideal for gamers. Featuring the latest Intel&reg; processors for superior gaming performance, and life-like NVIDIA&reg; GeForce&reg; graphics and an advanced thermal cooling design.</p>\r\n', 
    - price: 899, 
    - photo: 'dell-inspiron-15-7000-15-6.jpg', 
    - date_view: '2023-10-24', 
    - counter: 1
4. Create a PHP file and connect to MySQL. 
5. Display the list of products from MySQL to your PHP file.

