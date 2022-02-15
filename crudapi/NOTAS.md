- Instrucción en consola para crear el proyecto:
* composer create-project --prefer-dist laravel/lumen crudapi

En la carpeta app, se encuetra la carpeta Models y los controladores dentro de la carpeta Http

- Para crear migraciones:
Desde la consola parados dentro del proyecto creado.
* php artisan make:migration libros --create=libros --> libros es el ejemplo
Las migraciones se ublican en la carpeta database
Para que se guarde la tabla en la db en la consola poner el siguiente comando
* php artisan migrate

- Para trabajar con el ORM (Eloquent):
Descomentar la linea donde se lo llama en el archivo app.php dentro de la carpetq bootstrap