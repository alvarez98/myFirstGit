# Metodos HTTP
HTTP contiene un grupo de peticiones(HTTP verbs) que nos ayudan a especificar la accion que se requiere realizar en un elemento determinado. Estas peticiones tienen diferentes semanticas, pero también tienen similitudes.
* Clasificacion
1. Peticiones HTTP Safe
Se considern safe si no se altera el estado del servidor
2. Peticiones Idempotent
Se refiere cuando una solicitud identica puede realizarse una o demasiadas veecs consecutivamente obteniendo el mismo resultado dejando al servidor en el mismo estado.
* Peticiones HTTP:
1. Get
2. Options
3. Head
4. Put
5. Post
6. Delete
7. Connect
8. Trace

# Codigos de Estado HTTP

Son los codigos de estado en las respuestas HTTP que un servidor puede devolver cuando recibe una peticion HTTP request mantenidos por la Internet Assigned Numbers Authority. El primer digito del codigo de estado especifica uno de los 4 tipos de respuesta, el minimo para que un cliente pueda trabajar con  HTTP  es que reconozca estas 5 clases. 
1. 1xx Respuestas informativas
Indica una respuesta provisional que sirven para expermientos tales como: 100 Continue, 101 Switching Protocols y 102 Processing(WebDAV; RFC 2518).
2. 2xx Peticiones correctas
Indica que la accion solicitada por el cliemte ha sido recibida, entendida, aceptada y procesada correctamente: 200 OK, 201 Created, 202 Acepted, 203 Non-Authority Information, 204 No Content, 205 Reset Content, 206 Parcial Content, 207 Multi-Status(WebDAV; RFC 4918)
3. Cuando el cliente debe tomar una accion adicional para completar el request. 300 Multiple Choices, 301 moved Permanently, 302 Found, 303 Found, 303 See Other, 304 NOt Modified, 305 Use Proxy, 307 Temporary Redirect, 308 Permanent Redirect.
4. 4xx Errores del cliente 
Cuando el servidor debe incluir una entidad que contiene una explicacion del error, y su duracion.
400 Bad Request, 401 Unauthorized, 402  Payment Required, 403 Forbidden, 404 Not Found, 405 Method Not Allowed, 406 Not Acceptable, 407 Proxy Authentication Required, 408 Request Timeout, 409 Conflict, 410 Gone, 411 Length Required, 412 Precondition Failed, 413 Request Entity Too Large, 414 Request-URI Too Long, 415 Unsupported Media Type, 416 Requested Range Not Satisfiable(RFC 7233), 417 Expectation Failed, 418 I'm a teapot(RFC 2324).
5. 5xx Errores del servidor 
Cuando el servidor falla al completar una solicitud aparentemente válida. 500 Internal Server Error, 501 Not Implemented, 502 Bad Gateway, 503 Service Unavailable, 504 Gateway Timeout, 505 HTTP Version Not Supported, 511 Network Authentication Required(RFC 6585).

# Metodologia de desarrollo de Software (SCRUM)
Es un proceso en el que se aplican de manera regular un cnonjunto de buenas practicas para trabajar colaborativamente en equipo. En SCRUM un proyecto se ejecuta en ciclos temporales cortos de duracion fija (iteraciones de 2, 3 o 4 semanas). Cada iteración debe proporcionar un resultado completo. El proceso parte de la lista de objetivos o plan de proyecto. En esta el cliente prioriza los objetivos y quedan repartidos en iteraciones y entregas.
* Planificacion de la iteracion.
1. Seleccion de requisitos
2. Planificacion de la iteracion.
* Ejecucion de la iteracion
Se responden: 
1. ¿Qué eh hecho de la ultima reunion para ayudar al cumplimiento del objetivo?
2. ¿Qué voy a hacer a partir de este momento para ayudar al cumplimiento del objetivo?
3. ¿Cuales son los impedimentos para cumplir el objetivo?
Un facilitador elimina los obstaculos que el equipo no pueda resolver, protege al equipo de interrupciones externas.
* Inpección y adaptación
1. Revisión 
2. Retrospectiva
