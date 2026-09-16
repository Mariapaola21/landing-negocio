# Ejercicio E3 — Cacería de Códigos HTTP


## 1. Códigos HTTP Cazados en DevTools (Pestaña Network)

### 1. `200 OK` (Petición Exitosa)
* **URL probada:** `https://github.com`
* **Qué significa:** El servidor recibió la petición, la procesó correctamente y devolvió el recurso solicitado.


### 2. `301 Moved Permanently` (Redirección Permanente)
* **URL probada:** `http://google.com` (redirige a `https://www.google.com`)
* **Qué significa:** El recurso solicitado cambió de ubicación definitivamente. El servidor le indica al navegador la nueva dirección segura a donde debe ir.
* **¿De quién es la culpa?:** Informativo (el servidor guía al navegador hacia la URL correcta).

### 3. `302 Found` (Redirección Temporal)
* **URL probada:** Recarga en el navegador chrome
* **Qué significa:** El servidor redirige la petición temporalmente a otra URL.
* **¿De quién es la culpa?:** Informativo / Comportamiento esperado del servidor.


### 4. `404 Not Found` (No Encontrado)
* **URL probada:** `https://github.com/pagina-inexistente-123456`
* **Qué significa:** El servidor está funcionando bien, pero la ruta o archivo que pediste no existe o fue escrita incorrectamente.
* **¿De quién es la culpa?:**la culpa es del usuario por tener un enlace roto.


## 2. Familias de Códigos HTTP — Modelo Mental

* **200 (Éxito):** Todo salió bien.
* **202 (Aceptado):** La petición fue aceptada pero no se ha completado.
* **204 (No Content):** El servidor procesó la petición pero no devolvió ningún contenido.
* **301 (Redirecciones / Caché):** Hay que ir a otro lado o usar la copia guardada.
* **404 (Error del Cliente):** El usuario o navegador cometió un error (recurso no existe, no autorizado, etc.).
* **500 (Error del Servidor):** El servidor falló internamente, se cayó o explotó su código.
* **503 (Servidor Caído):** El servidor no está disponible temporalmente.

