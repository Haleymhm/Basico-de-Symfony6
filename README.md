# Basico-de-Symfony6
Curso Básico de Symfony 6 - PLATZI

## Requerimientos
Tener instalado PHP 8.0 o superior,  Mysql 5.6 o superior, composer

## Instalación

1. Clonar el proyecto
   ` git clone https://github.com/Haleymhm/Basico-de-Symfony6.git `

2. Ingresar a la carpeta del proyecto
    ``` 
    cd Basico-de-Symfony6
    ```

3. Instalar las librerías
    ``` 
    composer install
    ```
4. Crear la base de datos e importar la estructura desde el archivo Estructura_db.sql
    
    1. Editar el archivo  **.env** y colocar los datos de conecion a su servidor de base de datos
    2. Ejecutar el comando *php bin/console doctrine:database:create* para crear la base de datos
    3. Ejecutar el comando *php bin/console doctrine:migrations:migrate* para crear las tablas dentro de la base de datos
    


5. Iniciar la aplicación
    ``` 
    symfony serve 
    ```
