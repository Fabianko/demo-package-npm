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

