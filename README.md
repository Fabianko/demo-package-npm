# demo-package-npm
create npm package example

use platzi course

Comando para crear un package definiendo toda la informacion
> npm init

Comando para crear un package por defecto
> npm init -y

Se puede setear elementos previos y cada vez que se crea un package se setean estos valores por defecto
> npm set init.author.email "fabian.arismendi@usach.cl"
> npm set init.author.name "Fabian Arismendi"
> npm set init.license "MIT"

Ver los paquetes instalados globales
> npm list -g --depth 0

En caso de instalar packages globales y lanza errores de permisos
https://docs.npmjs.com/resolving-eacces-permissions-errors-when-installing-packages-globally

Ver paquetes desactualizados
> npm outdate

Ver detalle de paquetes desacutalizados
> npm outdate --dd

actualizar paquetes
> npm update

Versionado semantico
![versionNPM](https://static.platzi.com/media/user_upload/wheelbarrel-no-tilde-caret-white-bg-w1000-72ca1a72-4c7f-4abe-8482-425c01a72f89.jpg)

ver detalle de una ejecucion
> npm "comando" --dd

limpiar packetes con errores
> npm cache clean --force
> npm cache verify

borrar packetes instalados
> rm -rf node_modules/


otra opciones de borrar node modules es con rimraf
> sudo npm install -g rimraf
> rimraf node_modules/

Seguridad
Para ver posibles problemas 
> npm audit
Para reparar automaticamente algunas tareas
> npm audit fix

