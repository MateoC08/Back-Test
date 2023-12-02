# [Nombre de proyecto]

## Sec [01] - Grupo N° [11]

### Integrantes

| Nombre                               | Carnet        |
| ------------------------------------ | ------------- |
| María Auxiliadora Martínez Avila     |  00090121     |
| Paola Elizabeth Saracay Cruz         |  00376721     |
| Mateo Emiliano Corcio Arias          |  00027922     |

# Usuario de prueba
Puedes emplear esta información de acceso para evaluar la interfaz del cliente:
```
   Correo: 000945@gmail.com
   Contraseña: GatosGordos6
```
# Instalación
Instalar node.js utilizando yarn
Primero tienes que instalar nvm ejecutando el siguiente comando:
```
   wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
```
Cierra y vuelve a abrir tu terminal: Después de instalar nvm, es posible que necesites cerrar y volver a abrir tu terminal para que los cambios surtan efecto.

Instala Node.js con nvm: Luego, puedes instalar una versión de Node.js utilizando nvm. Por ejemplo, para instalar la versión LTS más reciente, puedes ejecutar:
```
   nvm install --lts
```
Esto instalará la versión LTS más reciente de Node.js.

Instala Yarn: Una vez que Node.js esté instalado, puedes usar npm (el gestor de paquetes que viene con Node.js) para instalar Yarn globalmente. Ejecuta el siguiente comando:
```
   npm install -g yarn
```
Esto instalará Yarn de forma global en tu sistema.

Después de seguir estos pasos, deberías tener Node.js y Yarn instalados en tu sistema.

Ejecutando la aplicación
Ahora, para utilizar la aplicación, solo necesitas ejecutar este comando:
```
   yarn dev
```
Conectando al cliente
Después de ejecutar el comando anterior, ahora puedes acceder al servidor con el link proporcionado en la terminal.

# Información útil
## Paquetes utilizados

axios

moment

react

react-router-dom

react-hook-form

react-custom-roulette

react-tostify

## Manual del usuario
Inicio de sesión
En la página de inicio de sesión, los usuarios que ya tienen una cuenta pueden acceder al sitio web completando los campos obligatorios

![image](https://github.com/Programacion-Web-02-2023/proyecto-equipo-11-sec-01-cualquier-nombre/assets/93175738/38745bbd-68e5-492c-84f2-5b4bf7cdfd3e)


Registro
Si no dispones de una cuenta, los usuarios tienen la opción de crear una nueva llenando los campos obligatorios que se presentan

![image](https://github.com/Programacion-Web-02-2023/proyecto-equipo-11-sec-01-cualquier-nombre/assets/93175738/c713778f-74ca-4e87-9508-a9e029bb2ab0)


Página de inicio
Después de iniciar sesión o registrarse, lo primero que verás es la página de inicio, donde tendrás dos opciones para explorar el sitio

![image](https://github.com/Programacion-Web-02-2023/proyecto-equipo-11-sec-01-cualquier-nombre/assets/93175738/f4c9e62d-b41e-4bca-b681-8b9e83cbad8f)


Ruleta
Si decides seleccionar la opción de quiz, te encontrarás con una ruleta. Al presionar el botón para girar, se elige aleatoriamente un tema sobre el cual se realizará el quiz. Una vez que la ruleta ha terminado de girar, se muestra en pantalla la opción seleccionada y al presionar el botón de "Vamos", puedes iniciar el quiz relacionado con ese tema

![image](https://github.com/Programacion-Web-02-2023/proyecto-equipo-11-sec-01-cualquier-nombre/assets/93175738/d1e3c3b6-337b-46cf-9b8e-c504e180dc4c)


Quiz
Después de hacer clic en el botón "Vamos", verás la siguiente vista que muestra cómo lucen los quizzes. Al finalizar, se mostrará la puntuación alcanzada por los usuarios, junto con el feedback de las preguntas respondidas correctamente (marcadas en verde), las opciones seleccionadas por los usuarios (marcadas en azul) y las respuestas incorrectas (marcadas en rojo). Además, se proporcionará un video para complementar los temas

![image](https://github.com/Programacion-Web-02-2023/proyecto-equipo-11-sec-01-cualquier-nombre/assets/93175738/f37ea5ee-d431-436e-bbbe-0ed3a3dae0cd)

![image](https://github.com/Programacion-Web-02-2023/proyecto-equipo-11-sec-01-cualquier-nombre/assets/93175738/fc81e79b-4fac-4435-bdee-feeee5fe6a00)



Comentarios
Si eliges la opción de comentarios, los usuarios tienen la posibilidad de acceder a un foro donde pueden publicar sus comentarios relacionados con los temas abordados

![image](https://github.com/Programacion-Web-02-2023/proyecto-equipo-11-sec-01-cualquier-nombre/assets/93175738/227bf0f8-64f3-44da-b49e-8f6dc68a170a)


## Configurar variables de entorno
Lo primero que debes hacer antes de ejecutar la aplicación es crear un archivo .env en el directorio raíz del proyecto y agregar las siguientes variables:
```
     # PORT
     PORT= Tu puerto

     # MONGO URL
     MONGO_URL= Tu cadena de conexión MongoDB

     # TOKEN 
     TOKEN_SECRET= Tu JWT secreto
```
## Ejecutando la aplicación
Ahora puedes usar la API ejecutando el siguiente comando:
```
   yarn start
```
También puedes ejecutar si quieres utilizar el modo desarrollador:
```
     yarn run dev
```
## Conectando al servidor
Después de ejecutar localmente la aplicación, puede conectarse al servidor utilizando la siguiente URL:
```
     http://localhost:4000/
```
# Información útil
## Paquetes usados
Puedes echar un vistazo a los paquetes usados ​​en el siguiente enlace:

cookie-parser

cors

debug

dotenv

express

http_errors

jsonwebtoken

jwt-decode

mongoose

morgan

# Notas de la versión
v 1.0.0

# Enlaces útiles
Documentación API

# Formato de endpoints
Para realizar solicitudes a endpoints de la API, sigue estos pasos en Insomnia:

Abre Insomnia:

-Inicia sesión en Insomnia o abre la aplicación.

Crea una Nueva Solicitud:

-Para cada endpoint, crea una nueva solicitud.

-Haz clic en el botón "New Request" o utiliza la combinación de teclas Ctrl + N.

Configura la Solicitud:

-Selecciona la nueva solicitud y configura los siguientes detalles:

-Selecciona la nueva solicitud y configura los siguientes detalles:

-URL: Ingresa la URL completa del endpoint específico que estás probando.

Añade Parámetros:

-Si el endpoint requiere parámetros, encabezados u otros detalles, ajústalos en la sección correspondiente de la solicitud.

Envía la Solicitud:

-Haz clic en el botón "Send" para enviar la solicitud al servidor.

Interpreta la Respuesta:

-Examina la respuesta en la sección de respuesta de Insomnia para comprender el resultado de la solicitud.

Estructura General de las Solicitudes:
Endpoint: POST /logIn

Descripción: Permite a los usuarios iniciar sesión y obtener un token de autenticación.

Parámetros: Correo (correo): El correo del usuario. Contraseña (contrasena): La contraseña del usuario.

Método: POST

Ejemplo de Solicitud (JSON):
```
     {
     "correo": "ejemplo@dominio.com",
     "contrasena": "password123""
     }
```
Respuesta Exitosa (Código 200 - OK):
```
     {
     "token": "eyJhbGciOiJIUzI1NiIsIn..."
     }
```
Respuesta de Error (Código 404 - Not Found):
```
     {
       "error": "Usuario no encontrado"
     }
```
Respuesta de Error (Código 401 - Unauthorized):
```
     {
       "error": "Contraseña incorrecta."
     }
```
Respuesta de Error (Código 500 - Internal Server Error):
```
     {
       "ok": false,
       "msg": "Error interno del servidor",
       "error": "Detalles del error"
     }
```
Nota: Repite estos pasos para otros endpoints, ajustando la URL, los parámetros y el método según la documentación específica de cada endpoint.
