### Informacion sobre el repositorio
---
Aqui se alojaran los desafios 1 y 2 del Bootcamp Java Developer de EducacionIT.

Localmente se clono este repositorio en el disco d/estudios/educacionit/bootcamp-java-git-desafios (cumpliendo con el desafio 2)


---

### GIT: Desafio 1
---
1. Crea:
    - Un nuevo repositorio
    - El README.md
2. Realiza el **commit** inicial
3. Sube todos los cambios que haya hecho durante el dia
4. Realiza un nuevo commit a tu repositorio
5. Presenta el log actual de proyecto, con los identificadores de cada **commit**. Haz un **log** de todos los **commit**.

---

### GIT: Desafio 2
---
1. Clona en otra carpeta el repositorio que empezaste, realiza algunos cambios y haz un commit
2. Importa el código fuente de NestJS (publicado en **[este](https://github.com/nestjs/nest)** repositorio) a nuestro repositorio para tener control total.

---

### GIT: Desafio 3
---
1. Dentro del repositorio crear una nueva branch custom-navbar, crear archivos. Luego pausar el trabajo sin commitearlo, para borrar el archivo status.js del branch master.
    - Dentro de la rama custom-navbar git stash --include--untracked -> git checkout main -> git rm status.js -> git add . -> git commit -m"" -> git push -> git checkout custom-navbar -> git stash pop
2. Subir a producción una nueva interfaz en React.Js para el home Banking de un cliente. Su desarrollo se encuentra en la rama _*front-react*_. Subir los cambios a la rama master.
