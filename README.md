# Super Shop

An example shop developed in vanilla PHP.

## [Step 1](https://github.com/arestivo/supershop/tree/step1)

Initial page developed using only HTML and CSS:

  * Created folder for images
  * Created folder for css
  * Added css/style.css
  * Added images/products/1.png
  * Added images/site/logo.svg
  * Added index.php

## [Step 2](https://github.com/arestivo/supershop/tree/step2)

Organize the HTML code into separate template files:

  * Created folder templates/common
  * Created folder templates/category
  * Created folder templates/product
  * Added templates/common/header.php
  * Added templates/category/list_categories.php
  * Added templates/product/list_products.php
  * Added templates/common/footer.php
  * Moved code from index.php to new files

## [Step 3](https://github.com/arestivo/supershop/tree/step3)

Created the database:

  * Created folder database
  * Added database/connection.php
  * Added database/shop.sql
  * Generated database/shop.db using sqlite3
  * Added images for 3 more products in images/products
  * Included database/connection.php in index.php

## [Step 4](https://github.com/arestivo/supershop/tree/step4)

Categories are now listed from the database:

  * Added database/category.php
  * Used getAllCategories in index.php
  * Updated templates/category/list_categories.php

## [Step 5](https://github.com/arestivo/supershop/tree/step5)

Products are now listed from the database:

  * Added database/product.php
  * Used getAllProducts in index.php
  * Updated templates/product/list_products.php

## [Step 6](https://github.com/arestivo/supershop/tree/step6)

Started session:

  * Created folder includes
  * Added includes/init.php
  * Added includes/session.php

  * Pages now include includes/init.php instead of database/connection.php



