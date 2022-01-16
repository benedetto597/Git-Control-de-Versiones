<div align="center">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/3f/Git_icon.svg/1024px-Git_icon.svg.png" width="300px"> </img> 
    
<!-- Encabezado -->
## Git | Control de versiones
## Enero 2022
### Autor 
</div>

| Nombre | Numero De Cuenta | Correo |
|:-------------:| :-----:|:-----:|
| Edgar Josué Benedetto Godoy | `20171033802` | [Gmail](mailto:ejbg597@gmail.com) |

_____

### Definición
* Git es un **software de control de versiones** diseñado por Linus Torvalds, pensando en la eficiencia, la confiabilidad y compatibilidad del mantenimiento de versiones de aplicaciones cuando estas tienen un gran número de archivos de código fuente.

### Funciones
* Controlar y administrar las distintas versiones de un programa
* Contribuir con varios desarrolladores en cualquier parte del mundo
* Revertir cualquier cambio hecho por cualquier desarrollador en una rama especifica
* Se pueden trabajar con repositorios locales o remotos
  
### Estados 
| Estado | Descripción |
|:-------|:------------|
|Working Directory |Donde se trabaja con todos los archivos|
|Staging Area|Donde se agregan los archivos a guardar en git|
|Repository|Donde se guardan los archivos en formato git| 
### Comandos básicos
* **git init** : Inicializa un repositorio git
* **git status** : Muestra el estado de los archivos (si estan en staging area o en el respositorio)
* **git add < files >** : Agregar archivos al staging area
* **git commit** : Guardar los archivos del staging area al repositorio (crear un primer snapshot)
* **git push** : Enviar los archivos del staging area a un repositorio remoto
* **git pull** : Recibir los archivos de un repositorio remoto (cambios hechos por otros desarrolladores)
* **git log** : Muestra los commits hechos en el repositorio
* **git checkout** : Deshacer los cambios hechos en el staging area
* **git branch** : Crear una rama
* **git merge** : Unir dos ramas
* **git clone** : Clonar un repositorio

### Bibliogrfía
* [Git Pagina Oficial](https://git-scm.com/)
* [Git Documentación](https://git-scm.com/docs)