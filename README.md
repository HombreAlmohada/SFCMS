# SFCMS

*SFCMS* _(Nombre provisional)_ es un CMS hecho con Symfony.

Requisitos que debe cumplir:
- Seguridad: Login de usuarios, roles, etc
- Búsquedas
- Breadcrumbs
- SEO
- Paginación



### INSTALACIÓN

1. Clonar el repositorio
`git clone https://github.com/HombreAlmohada/SFCMS.git`

2. Dar permisos a los directorios de caché y logs
`chmod -R 777 var/cache`
`chmod -R 777 var/logs`

3. Ejecutar el siguiente comando para descargar todos los vendors y archivos de configuración.
_(Es necesario composer)_
`composer install`

4. Crear la base de datos en local y configurarla en el archivo _app/config/parameters.yml_
