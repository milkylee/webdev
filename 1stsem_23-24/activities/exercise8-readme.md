### Exercise 8 PHP Functions: Creating Class
1. Retrieve the copy of your Exercise 5.
2. Copy the folder to your htdocs directory C://xampp/htdocs.
3. Access localhost/your-project-name in your web browser.
4. Rename all the .html file extension names to .php
    - account.php
    - cart.php
    - index.php
    - product_details.php
    - products.php
5. Create new folder name includes and create new files namely
    - header.php
    - navbar.php
    - footer.php
6. In index.php, cut the content of the element head and paste it to the newly created file header.php
7. Include the header.php to the place where you removed the head element in index.php by using the include function.
8. Do the same for navbar, cut the content of the div element class named navbar and save it to navbar.php
9. Do the same for footer, cut the content of the div element class named footer and save it to footer.php

*Your website should look the same as before.*

10. Observe that all of the other pages have the same contents of header, navbar and footer of the index.php. Do what you did so far in index.php to the other pages, account.php, cart.php, product_details.php, and products.php. This way, you will only be editting one file and it will reflect to the other pages.
11. Go to includes/navbar.php and change all .html href value to .php.
12. Test that all the pages are working. *You should not be seeing any .html extension in your web browser*
13. In products.php, create a PHP class named Products. Create a public associative array named $products with the following values:
    "iPhone 15" => 1, 
    "Lenovo Laptop 16GB RAM" => 2, 
    "Sony Tablet" => 3,
    "Sony Headset" => 4
*1st value refers to the product name and the second value refers to the image id*
14. Inside the class Products, create a function named getProductList and return the value of the products array.
15. Instantiate the class Products, call the getProductList function and save it to a variable named $productLists.
16. Loop the response of the $productLists. You may use foreach with key value pairs. 
    example: foreach ($productLists as $productName => $imageId) { }
17. Inside the loop, copy one content of the div element with class name col-4 and display it using echo. Pass the value of $imageId and $productName to html content.
18. You may now delete all div element with class name col-4 in html. You now have a dynamic list of products, you may add multiple values inside the array.


Figure 8 shows how it should look now

![Figure 8](/1stsem_23-24/activities/exercise8.png)

