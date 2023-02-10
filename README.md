# Primeros pasos en git
## **Iniciando**
* Crear un repositorio
    >\>&nbsp;&nbsp;git init

* Visualizar el estado de nuestros archivos
    >\>&nbsp;&nbsp;git status

* Agregar un archivo, varios archivos, todos los archivos
    >\>&nbsp;&nbsp;git add "nombre_archivo"
    
    >\>&nbsp;&nbsp;git add "nombre_archivo" "nombre_archivo2"
    
    >\>&nbsp;&nbsp;git add .

* Quitar seguimiento a un archivo, varios archivos, todos los archivos
    >\>&nbsp;&nbsp;git reset "nombre_archivo"
    
    >\>&nbsp;&nbsp;git reset "nombre_archivo" "nombre_archivo2"
    
    >\>&nbsp;&nbsp;git reset .

* Crear un commit
    >\>&nbsp;&nbsp;git commit -m "Descripción del commit"

* Agregar archivos con seguimiento y crear commit
    >\>&nbsp;&nbsp;git commit -am "Descripción del commit"

* Recuperar el proyecto desde el ultimo commit.
    >\>&nbsp;&nbsp;git checkout -- .

* Logs
    >\>&nbsp;&nbsp;git log

<br>

---
## **Ramas**

* Listar ramas
    >\>&nbsp;&nbsp;git branch

* Crear una nueva rama
    >\>&nbsp;&nbsp;git branch "nombre_rama"

* Renombrar una rama
    >\>&nbsp;&nbsp;git branch -m master main

* Cambiarme a una rama nueva
    >\>&nbsp;&nbsp;git checkout "nombre_rama"

* Crear y cambiarme a una rama nueva
    >\>&nbsp;&nbsp;git checkout -b "nombre_rama"

* Eliminar una rama
    >\>&nbsp;&nbsp;git checkout -d "nombre_rama"

    >\>&nbsp;&nbsp;git checkout -d "nombre_rama" -f

* Fusionar dos ramas
    >\>&nbsp;&nbsp;git merge "nombre_rama"

<br>

---
#### Este readme fue modificado en la pagina de Github
##### la línea que esta aqui fue modificada
