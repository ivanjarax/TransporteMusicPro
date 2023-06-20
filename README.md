# TransporteMusicPro - TunePunk
Proyecto para el ramo de integracion de plataformas 004D, nombre music pro caso transporte
TunePunk

Instrucciones:
1. Clonar repositorio: abrir laragon y escribir lo siguiente
  ```   
  git clone  https://github.com/ivanjarax/TransporteMusicPro 
  ```
3. Crear una Base en Laragon:
   Configurar Base de Datos, usuario por default root y la contraseña es vacia.
   ```
   DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=tu_basedatos
    DB_USERNAME=root
    DB_PASSWORD=
    ```
4. Entrar a la carpeta repositorio<br>
   ```
   cd TunePunk
   ```
5. Instala las dependencias de Composer:<br>
   ```
   composer install
   ```
7. Ejecuta las migraciones y los seeders para crear y poblar la base de datos:<br>
    ```
    php artisan storage:link
    php artisan migrate:fresh --seed
    ```
Drive documentacion https://drive.google.com/drive/folders/1m95CBLAmbwzIRtLWUsGR_73uPrNhb2TC?usp=drive_link
