## Iniciando GIT - creando un repositorio
 
``` js
 /*
    1. Crear un repositorio en GitHub
    2. Crear una carpeta local donde pretendes inicializar tu repositorio GIT con mkdir "name"
    3. Ahora sigue el comando "git init" para inicializar git en esa carpeta
    4. Luego creas una carpeta README.md para poner una descripcion de tu repositorio de git
    5. Para pasar ese archivo o cualquier otro tipo de archivo a la sala de espera, utilizas git add y el nombre del archivo, en caso de querer pasar todos los archivos existentes solo se pone "."
    6. Luego con git commit -m "Descripcion de los cambios" se agrega al repositorio de git
    7. con git branch -M main entras a la rama principal donde quieres que se guarden los cambios
    8. Creamos un vinculo entre nuestro repositorio de git con el de github con el siguiente comando: git remote add origin https://github.com/"Nombre de usuario"/"Nombre de tu repositorio"
    9. Ahora para guardar los cambios en el repositorio de github utilizamos el comando git push -u "nombre del vinculo entre repositorios" "nombre de la rama en la que quieres que se guarde"
*/