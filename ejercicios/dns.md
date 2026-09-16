# Ejercicio E2 — Arqueología DNS
# Maria Paola  

## 1. Consultas realizadas con `nslookup y nslookup -debug`

### 1. UNAD
**DOMINIO:** unad.edu.co (TIENE UN ALIAS CNAME: appoci.unad.edu.co)
**DIRECCION IP:** tiene dos dirrecciones la primera es tipo IPv4 es 157.137.230.77 y la otra es de la generacion IPv6 2800:800:900:4::9d89:e64d contiene numeros letras y hexadecimales.
**TTL AMBOS:** 142 segundos (2 minutos y 22 segundos)
**TIPO DE REGISTRO:**
**Dirección IPv4 (Registro A):**
**Dirección IPv6 (Registro AAAA):** 

### 2. FACEBOOK
**DOMINIO:** facebook.com
**DIRECCION IP:** tiene dos dirrecciones la primera es tipo IPv4 es 57.144.84.1
 y la otra es de la generacion IPv6 2a03:2880:f321:1:face:b00c:0:25de contiene numeros letras y hexadecimales.
**TTL AAAA:** = 60 (1 min)
**TTL A:** = 26 seg 
**Dirección IPv4 (Registro A):**
**Dirección IPv6 (Registro AAAA):** 


### 3. GitHub 
- **Dominio:** `github.com`
- **Dirección IP obtenida:** `140.82.113.3`
- **TTL (Caché):** 37 segundos
- **Tipo de registro:** Registro A (IPv4)



## 2. Conceptos Clave Demostrados
* **¿Qué es el DNS?**
Sabemos que un computador no se comunica de la misma forma que un humano el tiene un lenguaje diferente, lo mismo los servidores ellos no entienden nuestro lenguaje sino que entienden las direcciones IP. El DNS es el sistema que traduce nombres de dominio legibles para humanos a direcciones IP numéricas que entienden los servidores. por ejemplo nosotros conocemos github como github.com pero un servidor no lo entiende el DNS lo traduce a 140.82.113.3.
* **¿Qué es un Registro A?**
Es un registro DNS que asocia un nombre de dominio con direccion IPv4 que es la que ya se esta agotando por lo que se esta utilizando la IPv6 que es una direccion mas larga y compleja.

* **¿Qué es el TTL (Time to Live)?**
Es el tiempo que los servidores y routers intermediarios guardan la informacion DNS antes de volver a consultar a la fuente oficial.

