# tweetfony

## Instalación del proyecto:

1. Clonar el repositorio.
2. Ejecutar ``composer install`` para instalar las dependencias software.
3. Hacer una copia del archivo ``.env`` llamada ``.env.local`` y personalizar la configuración de la base de datos.
4. Ejecutar ``php bin/console doctrine:migrations:migrate`` para ejecutar las migraciones
5. Copiar el pack de datos iniciales
6. Ejecutar ``php bin/console doctrine:fixtures:load`` para cargar los datos de ejemplo.