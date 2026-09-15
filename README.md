# Practica de Git y GitHub

**Nombre:** Luis Angel Montes Hernandez  
**Matricula:** 2630261

## Objetivo

Crear un repositorio en mi computadora y conectarlo con github la idea fue subir los archivos, hacer un cambio desde la pagina y descargarlo para comprobar que tambien apareciera en mi carpeta

## Como hice la practica

### Primero en mi computadora

Cree la carpeta `practica-git-luis-angel-montes-hernandez` y la deje dentro de `repogithub` en el escritorio Abri PowerShell en esa carpeta, inicie Git y le puse `main` a la rama

Despues cree `README.md` y `datos.txt`. En el primero puse mis datos y en el segundo una frase sobre la practica. Revise los archivos, los pase al area de preparacion y guarde el **Primer commit**. Entendi que en esa area se eligen los cambios que van a quedar guardados en el commit

### Para subirlo a GitHub

Cree un repositorio publico con el mismo nombre no le agregue readme licencia ni `.gitignore` desde la pagina, porque los archivos ya estaban en mi computadora

Copie la direccion del repositorio y la agregue en Git con el nombre `origin`. con eso quedaron conectados Antes de subir los archivos me salio un aviso porque la carpeta aparecia como propiedad de otro usuario. Con ayuda marque esa carpeta como segura y pude hacer el primer envio Despues revise que los archivos aparecieran en github

### El cambio desde GitHub

En la pagina abri `datos.txt` y agregue la linea "Este archivo fue modificado desde GitHub." guarde el cambio con un commit y despues use `git pull origin main` en powershell Al abrir el archivo de mi computadora, la linea ya estaba ahi

### El cambio desde mi carpeta

Luego agregue "Este archivo fue modificado desde el repositorio local." en el archivo de mi computadora. Tambien complete el README. Prepare los cambios, hice el commit **Actualizacion desde repositorio local** y los subi con `git push`

al revisar GitHub ya estaban las dos lineas tambien revise el historial y que Git no marcara cambios pendientes

## Comandos que use

- `git init`: para iniciar el repositorio
- `git branch -M main`: para ponerle `main` a la rama
- `git status`: para revisar el estado de mis archivos
- `git add .`: para preparar los cambios antes de guardarlos
- `git commit -m "mensaje"`: para guardar una version y ponerle una descripcion
- `git remote add origin URL`: para agregar la direccion de mi repositorio de GitHub
- `git remote -v`: para revisar que la direccion estuviera bien
- `git push -u origin main`: para hacer el primer envio y dejar conectado el destino de los siguientes
- `git push`: para subir los commits que hice en mi computadora.
- `git pull origin main`: para traer los cambios de GitHub a mi carpeta.
- `git log --oneline`: para ver el historial de commits.
- `git config`: lo use para configurar mi nombre y agregar mi carpeta como segura cuando aparecio el aviso.

En los comandos `mensaje` es la descripcion que le puse al commit y `URL` es la direccion del repositorio.

## Archivos

- **README.md:** contiene mis datos y la explicacion de la practica al principio tenia lo basico y despues lo fui completando
- **datos.txt:** contiene la frase inicial y las dos lineas que agregue desde GitHub y desde mi computadora

## Conclusion

Ahora entiendo un poco mas lo que se explico en clase, porque la neta si me perdi tantito todavia me falta acostumbrarme a los comandos y seguir viendo videos para entender mejor como se usa todo

Tambien entendi por que cuando descargo juegos piratas o instaladores suelen venir con su README ahi explican de que trata lo que descargue y como usarlo. Antes practicamente solo habia usado github para piratear mi PS3, asi que la pagina todavia me parece confusa y sigo medio perdido al moverme por ella

Con esta practica ya logro entender un poco mejor para que sirve cada cosa, aunque todavia no del todo, la verdad. Creo que con mas tiempo y practica podre entender mas y estar a la par de los tryhards del salon fue una buena forma de repasar e ir entendiendo lo que vimos en clase.
