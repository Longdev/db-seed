# db-seed

Error db:seed 

Try the following commands on your shell:

Clear Laravel cache and the compiled classes

  1. php artisan cache:clear

  2. php artisan clear-compiled
  
  
Change the storage and cache directories permission

3. sudo chmod -R 777 storage

4. sudo chmod -R 777 bootstrap/cache


Regenerate the composer autoload file

5. composer dump-autoload
