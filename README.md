# Act1. Introducción a Spring Boot - Configuración y Primeros Controladores

Primer proyecto de Rest API en Spring desplegado en VPS (Hostinger).

## Funcionamiento
El proyecto consiste en una Rest API basica e inicial que tiene dos controladores `NombreRestController` y `SumaRestController`. El primer controlador cuenta con dos `getMapping` para dos endpoints `/nombre` y `/datos_personales`, y el segundo controlador `SumaRestController` con el endpoint `/sumar` con `@RequestParagrams` para recibir dos parametros, en este caso dos numeros y el endpoint mostrara un json con los valores dados, para este endpoint un ejemplo de ruta seria `sumar?num1=5&num2=15`

### Despliegue
El proyecto se encuentra desplegado y funcionando correctamente en este [link](https://veterinariabobby.tech/eaecact1_t4/) .

Las rutas para los endpoints serian
* [https://veterinariabobby.tech/eaecact1_t4/nombre](https://veterinariabobby.tech/eaecact1_t4/nombre)
* [https://veterinariabobby.tech/eaecact1_t4/datos_personales](https://veterinariabobby.tech/eaecact1_t4/datos_personales)
* [https://veterinariabobby.tech/eaecact1_t4/sumar?num1=5&num2=15](https://veterinariabobby.tech/eaecact1_t4/sumar?num1=5&num2=15) (Ejemplo con 5 y 15)

## Funcionamiento en PostMan
### Primer Endpoint
![prueba en postman](https://i.postimg.cc/tRNdfLy0/image.png)

### Segundo Endpoint
![Prueba en postman](https://i.postimg.cc/YCGWpVcB/image.png)

### Tercer Endpoint
![Prueba en Postman](https://i.postimg.cc/XqqvsG4b/image.png)
