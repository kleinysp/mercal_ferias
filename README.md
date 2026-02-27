Instruccion para configuración del proyecto.

    Clonar el Repositorio de GitLab
        git clone https://github.com/kleinysp/mercal_ferias.git
    Acceder a la carpeta con el siguiente comando:
        cd mapa_ferias
    Instalar todas las dependencias de COMPOSER para el proyecto
        composer install
    Generamos una copia del archivo .env
        cp .env.example .env
    Ingresamos al archivo .env creado
        nano .env
    Agregamos las credenciales de la base de datos a las siguientes variables
        DB_DATABASE
        DB_USERNAME
        DB_PASSWORD
    Generar la clave de la aplicación:
    php artisan key:generate
    Ejecutar las Migraciones
        php artisan migrate
    Si estas en local, para levantar el proyecto seria el siguiente comando
        php artisan serve en una terminal 
        y
        npm run dev en una terminal diferente
    
