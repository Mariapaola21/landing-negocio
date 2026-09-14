# Ejercicio E5 — Romper y Arreglar (Resolución de Conflictos en Git)




## 1. ¿Cómo se provoca un conflicto en Git?
1. Se crea una rama secundaria y se modifica una línea de un archivo.
2. Se regresa a la rama principal  y se modifica la misma línea del mismo archivo con un contenido diferente.
3. Al intentar fusionar las ramas con `git merge rama-secundaria`, Git detecta cambios contradictorios en la misma línea y no sabe cuál versión elegir automáticamente, generando un estado de **CONFLICT**.



## 2. Marcadores de Conflicto que inserta Git
Git marca el archivo con estos símbolos para que el desarrollador decida:
* `<<<<<<< HEAD`: Lo que está en tu rama actual (`main`).
* `=======`: La línea divisoria.
* `>>>>>>> rama-secundaria`: Lo que viene de la otra rama.

---

## 3. ¿Cómo se resuelve el conflicto?
1. El desarrollador abre el archivo en conflicto y revisa ambas versiones.
2. Se eliminan los marcadores (`<<<<<<<`, `=======`, `>>>>>>>`) y se deja el código definitivo.
3. Se guarda el archivo y se ejecuta `git add` y `git commit` para confirmar la fusión resuelta.
