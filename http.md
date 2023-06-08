###HTTP

- protocolo (conjunto de reglas) a traves de las cuales se comunican dos computadores en internet.
- client(cliente) <=> server(servidor)

reto:

T| HTML CSS WEB APIS
H| HTML CSS JAVASCRIPT
E|
W| - - - HTTP- - - - -
E|
B|

    DNS TCP TLS
    UDP TCP
        IP

IP
Internet protocol
IPV4 IPV6 (identifican de manera unica nuestra computadora en la red)

TCP
Transmition control protocol
como se va a transferir información a bajo nivel

UDP
User data protocol
parecido al TCP

TLS
transport layer security
Encriptado de la información para que un atacante no pueda ver lo que se envía.

DNS
domain name system
resuelve nombre de dominio a una ip
transforma DNS => a una dirección IP

HTTP => nos permite transportar

- css
- html
- javascript
- etc.

Códigos de estado HTTP más comunes

- Status code 200 – OK.
- Status code 301 – Moved Permanently.
- Status code 302 – Moved Temporarily.
- Status code 403 – Forbidden
- Status code 404 – Not Found
- Status code 500 – Internal Server Error
- Status code 503 ­– Service Unavailable

1xx - INFO
2xx - SECCESS
3xx - REDIRECT
4xx - ERROR CLIENT
5xx - ERROR SERVER

Info chat-gpt
1 Cabeceras de solicitud:

- User-Agent: Identifica el agente de usuario (navegador, aplicación, bot, etc.) que realiza la solicitud.
- Accept: Especifica los tipos de contenido que el cliente puede aceptar.
- Authorization: Proporciona credenciales para autenticar al cliente en el servidor.
- Cookie: Envía cookies almacenadas previamente por el servidor al cliente.
- Referer: Indica la URL de la página web desde la cual se realizó la solicitud actual.

2 Cabeceras de respuesta:

- Content-Type: Indica el tipo de contenido que se envía al cliente (por ejemplo, texto/html, imagen/jpeg, application/json, etc.).
- Content-Length: Especifica la longitud en bytes del contenido de la respuesta.
- Set-Cookie: Envía cookies al cliente para almacenar información en su lado.
- Location: Se utiliza para redirigir al cliente a una nueva URL.
- Cache-Control: Controla el almacenamiento en caché de la respuesta por parte del cliente o intermediarios.

3 Cabeceras generales:

- Date: Indica la fecha y hora en que se generó la solicitud o respuesta.
- Connection: Controla si se mantiene la conexión abierta o si se cierra después de la respuesta.
- Content-Encoding: Especifica la codificación utilizada para comprimir el contenido.
- Server: Indica el nombre del servidor web que está manejando la solicitud.
- Via: Muestra los intermediarios (proxies) que han pasado la solicitud.
