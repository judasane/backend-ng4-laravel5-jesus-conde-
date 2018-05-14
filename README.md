
# Curso de Angular 4 con Laravel 5 (Backend)

  

Este proyecto usa Laravel

Este repositorio es un fork del repositorio creado por [javierescolar](https://github.com/javierescolar) con base en el [curso](https://www.youtube.com/watch?v=H5jfnstvNXA&list=PLEtcGQaT56chhi-qsqxIrUG_n9pXYCZ8z) desarrollado por [Jesús Conde](https://github.com/0utKast)
  

## Pasos de Instalación

  
0. Clona el repositorio git en la carpeta de servidor de tu ordenador (en el caso de usar xampp en windows sería xampp/htdocs
1. Ejecuta `composer install` en el directorio descargado después de clonar el repositorio, para descargar las dependencias.
2. Crea una base de datos con el nombre ***api-galeria*** 
3. Cambia el nombre del archivo example.env en el directorio raíz a .env y configura ahí los datos de la base de datos.
4. En la consola, desde el directorio de la aplicación, ejecuta `php artisan key:generate`
5. Ejecuta también el comando `php artisan migrate --seed` para hacer la migración de la base de datos y ejecutar el seeder para guardar los datos de prueba en la base de datos
6. Prueba la aplicación en http://localhost/api-galeria/public/api/v1/images (el servidor debe estar funcionando correctamente)

  
## Notas
- En este repositorio no hago uso de Homestead, sino xampp sobre windows.
 - Este repositorio funciona en conjunto con el repositorio de [frontend](https://github.com/judasane/frontend-ng4-laravel5-jesus-conde-) del curso
- Resalto que la propiedad intelectual del curso es de Jesús Conde.
- Existen [otros repositorios](https://github.com/0utKast?tab=repositories) oficiales con los archivos usados en el curso vídeo a vídeo, desarrollado por el mismísimo Jesús Conde.


