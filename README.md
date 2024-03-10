# Manual

### Comandos Git

En este manual recopilamos informació de algunos comandos que nos serviran a lo largo de este curso, donde veremos su sintaxis y una breve descripción.

### Algunos comandos:
- ***ls***   
``Este comando sirve para listar las carpetas desde mi ubicación.``

- ***mkdir***   
``Puedes crear carpeta con este comando y debes dar el nombre de la carpeta.``

- ***cd***   
``Este comando te permite moverte entre carpetas ir de una carpeta a otra.``

- ***..cd***   
``Este comando te permite salir de una carpeta o ir al nivel anterir si es lo que necesitas.``

- ***cd***   
``Te sirve para moverte entre carpetas y acceder a ellas, sabiendo el lugar donde estas ubicado.``

- ***rm -rf***   
``Borra o elimina carpetas que deseemos eliminar de nuestro archivo.``

- ***rm ->***   
``Borra o elimina archivos .txt, .js .sh``

-   ***nano(nombre archivo) -> Salir***
- control + x => Salir
- y => confrmar
- enter

- ***code .***   
``Abrir visual estudio code``
---

## COMANDOS GIT:


- ***git add***    
``git add se usa para agregar archivos al área de preparación. Por ejemplo, el siguiente comando de Git básico indexará el archivo temp.txt: ``
* git add <temp.txt>


- ***git commit*** 
`` git commit creará una instantánea de los cambios y la guardará en el directorio git. ``
* git commit –m “El mensaje que acompaña al commit va aquí”


- ***git confirg*** 
`` puede ser usado para establecer una configuración específica de usuario, como el email, nombre de usuario y tipo de formato, etc. Por ejemplo, el siguiente comando se usa para establecer un email: ``
* git config --global user.email tuemail@ejemplo.com

- ***git status*** 
`` Mmuestra la lista de los archivos que se han cambiado junto con los archivos que están por ser preparados o confirmados. ``
* git status

- ***git push*** 
`` git push se usa para enviar confirmaciones locales a la rama maestra del repositorio remoto. Aquí está la estructura básica del código: ``
* git push  origin <rama donde estes ubicado>
---

### Tambien puedes crear una rama para hacer cambios a tu repositorio y luego unirlo cuando sea funcional:
`` Las ramas te permiten trabajar en diferentes características o correcciones de errores sin afectar la rama principal (generalmente llamada main o master). ``

## Para crear ramas en un repositorio:

 ***git checkout*** 
`` Crea ramas y te ayuda a navegar entre ellas. Por ejemplo, el siguiente comando crea una nueva y automáticamente se cambia a ella:: ``

* command git checkout -b <branch-name>

git checkout -b nombre-de-la-rama


---
## Como crear un repositorio desde Git Bash:


*  Obtén la URL del repositorio:
    *  Navega a la página principal del repositorio en GitHub.com.
    * Encima de la lista de archivos, haz clic en “Código”.
    * Copia la dirección URL del repositorio.
* Abre la línea de comandos:
    * Abre la terminal o Git Bash en tu computadora.
* Cambia al directorio deseado:
    * Utiliza el comando cd para cambiar al directorio donde deseas clonar el repositorio.
* Clona el repositorio:
Escribe el siguiente comando y pega la dirección URL que copiaste antes:

    * git clone [URL_DEL_REPOSITORIO]
 
* git commit "mensaje para el commit"
    *   Hacer confirmaciones (commits):
    * Después de hacer cambios en los archivos, realiza confirmaciones para guardar esos cambios en el historial del repositorio.

* Utiliza git add
    * para agregar los archivos modificados y luego git commit -m "Mensaje de confirmación" para confirmar los cambios.

* utiliza git push
    * para enviar tus confirmaciones al repositorio en GitHub.
    * También puedes usar git pull para obtener los cambios más recientes del repositorio remoto.


### Se pueden tener Imagenes

Para tener una imagen, debes saber la ubicacion del archivo, teniendo la información, puedes acceder a ella con los comandos cd..(nombre de la carpeta, si esta en la misma linea accedes a ella) o ..cd, (si necesitas salir de tu ubicacion y moverte según lo desees), 
Puede mostrar una imagen agregando y ajustar el texto alternativo en . El texto alternativo es un texto corto equivalente a la información de la imagen. Luego, escribe el vínculo de la imagen entre paréntesis

* ``![ ]()`` Sintaxis  para una imagen

![Mi mascota Lulo, recuerdo.](photo1.jpegphoto1.jpeg)

