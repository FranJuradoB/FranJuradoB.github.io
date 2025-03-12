# Ejercicios Git y Github I

## Repositorio DEAW

Crear un repositorio en vuestro GitHub llamado DEAW.

![img1](./screenshots/1.jpg)
![img2](./screenshots/2.jpg)

Clonar vuestro repositorio en local.

![img3](./screenshots/3.jpg)

Le metemos mkdocs instalándolo primero.

![img4](./screenshots/4.jpg)

Creamos nuevo proyecto.
![img5](./screenshots/5.jpg)

Podemos modificar el archivo mkdocs.yml con ```nano```

![img6](./screenshots/6.jpg)


## Readme

Crear en vuestro repositorio local un documento README.md
.
![img7](./screenshots/7.jpg)

![img8](./screenshots/8.jpg)

Agregamos el archivo a nuestro repositorio con ```git add .```

![img9](./screenshots/9.jpg)

## Commit
Realizar un commit inicial con el comentario Comenzamos con los ejercicios de Git

![img10](./screenshots/10.jpg)

## Push
Subir los cambios al repositorio remoto

![img11](./screenshots/11.jpg)

![img12](./screenshots/12.jpg)

## Ignorar archivos
Crear en el repositorio local un fichero llamado privado.txt

Crear en el repositorio local una carpeta llamada privada

![img13](./screenshots/13.jpg)

Realizar los cambios oportunos para que tanto el archivo como la carpeta sean ignorados por git. 

Debemos crear primero el archivo ```.gitignore``` y lo modificamos poniendo lo que nos interese ocultar:

![img14](./screenshots/14.jpg)

![img15](./screenshots/15.jpg)

Vemos que directamente nos lo oculta: 

![img16](./screenshots/16.jpg)

## Añadir fichero 1.txt
Creamos primero el archivo de texto con ```touch 1.txt``` y comprobamos su estado con ```git status```

![img17](./screenshots/17.jpg)

Posteriormente lo añadimos con ```git add .```

## Crear un tag y subirlo al repositorio remoto

Ahora creamos una etiqueta con el comando ```git tag "nombre"``` y comprobamos que la ha creado listándola con ```git tag```

![img18](./screenshots/18.jpg)

Y hacemos commit de dicho cambio: 

![img19](./screenshots/19.jpg)

## Cuenta de GitHub
Ahora vamos a personalizar la cuenta de GitHub, en cuanto a su apariencia. Concretamente podemos modificar la foto de perfil, que por razones de privacidad no pondré la mía. Nos ceñimos a una imagen cualquiera, pero se puede modificar en la siguiente interfaz.

![img20](./screenshots/20.jpg)

También podemos modificar el llamado doble-factor de autenticación, para tener una capa extra de protección en nuestra cuenta.

![img21](./screenshots/21.jpg)

## Uso social de GitHub

Preguntar los nombres de usuario de GitHub de 2 de tus compañeros de clase, búscalos y sígueles.

Seguir los repositorios DEAW del resto de tus compañeros.

![img22](./screenshots/22.jpg)

Añadir una estrella a los repositorios DEAW del resto de tus compañeros.

![img23](./screenshots/23.jpg)

## Crear una tabla
Crear una tabla en el fichero README.md con la información básica de los compañeros de clase.

![img24](./screenshots/24.jpg)

## Colaboradores

Añadir a un compañero de clase como colaborador del repositorio DEAW.

![img25](./screenshots/25.jpg)
![img26](./screenshots/26.jpg)

## Crear una rama v0.2 y añadir un fichero 2.txt

Crear una rama v0.2 y cambiar a esa rama.

Con la opción ```git checkout -b v0.2``` creamos la rama y nos cambiamos automáticamente a ella.

![img27](./screenshots/27.jpg)

Creamos el archivo de texto con ```touch 2.txt``` y lo modificamos con ```nano 2.txt``` y finalmente comprobamos como siempre con ```git status```

## Crear rama remota v0.2

Creamos la rama remota con el comando ```git push -u origin v0.2```

![img28](./screenshots/28.jpg)

## Merge Directo

Posicionarse en la rama master.

Hacer un merge de la rama v0.2 en la rama master.

![img29](./screenshots/29.jpg)

## Merge con conflicto

En la rama master poner Hola en el fichero 1.txt y hacer commit.

Posicionarse en la rama v0.2 y poner Adios en el fichero 1.txt y hacer commit.

Posicionarse de nuevo en la rama master y hacer un merge con la rama v0.2

![img30.](./screenshots/30.jpg)

## Listado de ramas

![img31](./screenshots/31.jpg)

## Arreglar el conflicto

![img32](./screenshots/32.jpg)

## Listado de ramas

Tenemos varias opciones para ello. Actualmente no me muestra como debería por estar usando window con bash en vez de linux:

![img33](./screenshots/33.jpg)