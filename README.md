

# For each new challange this W6

1. Create a new file for each challenge

2. install the symfony/var-dumper package with Composer and include vendor/autoload.php in each file
   1. run: 
   composer require symfony/var-dumper
   -  in 01,02..
   1. start file in 01,02.. with :
<?php

require __DIR__ . "/vendor/autoload.php";
   
3. Make sure vendor/ is added to your .gitignore file

4. write my code with and check it with:
php <file.php>

5. commit with a sensible message.
   1. cd W6php
   2. git add <this challange file>
   3. git commit -am ""
   4. git push

