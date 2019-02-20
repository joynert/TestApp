# TestApp

Requerimientos Minimos:

PHP : 5.6
Mysql: 5.7
Apache: 2.4

Desarrollado con:

CodeIgniter, Bootstrap y Jquery !

#Paso 1

Para comenzar la app se debe descomprimir el archivo .rar, luego se debe copiar los ficheros en su servidor de aplicaciones WEB Apache (debe estar activo y funcional el modulo mod_rewirte, de lo contrario el aplicativo podria no funcionar).

#Paso 2

Descargar el archivo .SQL (existen 2 app_database_structure.sql y app_database.sql, el primero solo contiene la estructura de la base de datos y la informacion de productos, el segundo contiene la estructura y datos de prueba) y ejecutar en su servidor de MySql.

#Paso 3

Abrir el fichero "App/application/config/database.php" y editar los datos de BD correspondientes a las credenciales de su servidor.

#Paso 4 - Opcional

Abrir el fichero "App/application/config/config.php" y la linea 26 : $config['base_url'] = 'http://localhost/App';  y escribir la URL base segun sea el caso.

#Paso 5

Ejecutar y realizar los casos de pruebas.
