segundo cambio# Examen 1ª Evaluación (2ª Parte) - Control de Versiones

---
Isaac Rodríguez Solla
## Instrucciones
- Los commits de cada apartado deben tener el mensaje *"Apartado X - descripción del cambio realizado"*
- Entrega en la tarea de Moodle tu repositorio
- Solo se corrigen los commits que estén en el repositorio remoto

### Apartado 1

- Clona este repositorio.
- Modifica este Readme, poniendo tu nombre completo, realiza un `commit` con el mensaje *"Apartado 1"* y un `push`.

Pregunta 
- ¿Qué paso es fundamental cuando clonamos un repositorio ajeno para que podamos subir nuestros propios commits? Explícalo y utiliza capturas de pantalla.

Le paso fudamental es cambiar el link del repositrio, para esto en el apartado de git de pycharm vamos a manege remotes,
eliminaremos el link del repositorio copiado y agragremos el de nuestro propio reposiotio.

![img.png](img.png)

foto del nuevo repositorio
### Apartado 2

- Realiza una modificación en el código en la web de tu repositorio en GitHub
- Utiliza fetch para descargar los cambios realizados en tu repositorio.
- Modificacion para ele ejer 2
Pregunta
- Explica los pasos para que el código modificado en GitHub, llegue a tu rama principal local. Explícalo con capturas de pantalla.
 
Primero hacemos un git fetch origin Ejecuta para descargar el commit remoto sin fusionar.
![img_1.png](img_1.png)

Despues hacemos un  git log main..origin/main para verifica los nuevos commits que se acaban de descargar y que están en el remoto.

![img_2.png](img_2.png)

Por tercero hacemos un git merge origin/main para la fusión manual.
![img_3.png](img_3.png)
 .
 
hola
- Realiza otro cambio desde la web de tu repositorio en GitHub.
- Utiliza pull para descargar los cambios realizados en tu repositorio.

Pregunta
- Explica los pasos dados para que el cambio realizado en GitHub, llegue a tu rama principal local. Explícalo con capturas de pantalla.

Por ultimo hacemos cambios tanto al git en el repositorio como en el local y lanzamos git pull --rebase.

![img_5.png](img_5.png)
### Apartado 3
