# Codigos_estado

## HTTP (Hypertext Transfer Protocol)
Referencia: https://developer.mozilla.org/es/docs/Web/HTTP/Reference/Status

## 1xx – Informativos
- 100 Continue – continuar procesando solicitud
- 101 Switching Protocols – cambio de protocolo
- 102 Processing (WebDAV) – procesando, respuesta parcial posible
- 103 Early Hints – sugerencias de recursos mientras se procesa

## 2xx – Éxito
- 200 OK – solicitud exitosa
- 201 Created – recurso creado
- 202 Accepted – aceptado pero no procesado completamente
- 203 Non-Authoritative Information – info no autoritativa
- 204 No Content – éxito sin contenido
- 205 Reset Content – reiniciar contenido en cliente
- 206 Partial Content – respuesta parcial
- 207 Multi-Status (WebDAV) – múltiples códigos por recurso
- 208 Already Reported (WebDAV) – recurso ya reportado

## 3xx – Redirección
- 300 Multiple Choices – varias opciones
- 301 Moved Permanently – movido permanentemente
- 302 Found / Temporarily Moved – redirección temporal
- 303 See Other – ver otro recurso
- 304 Not Modified – recurso sin cambios
- 305 Use Proxy – usar proxy indicado
- 306 Switch Proxy – obsoleto
- 307 Temporary Redirect – redirección temporal, método intacto
- 308 Permanent Redirect – redirección permanente, método intacto

## 4xx – Error del cliente
- 400 Bad Request – solicitud mal formada
- 401 Unauthorized – no autorizado
- 402 Payment Required – pago requerido (reservado)
- 403 Forbidden – acceso prohibido
- 404 Not Found – recurso no encontrado
- 405 Method Not Allowed – método no permitido
- 406 Not Acceptable – formato no aceptable
- 407 Proxy Authentication Required – proxy necesita auth
- 408 Request Timeout – tiempo excedido
- 409 Conflict – conflicto con estado del recurso
- 410 Gone – recurso eliminado permanentemente
- 411 Length Required – se requiere Content-Length
- 412 Precondition Failed – precondición fallida
- 413 Payload Too Large – entidad demasiado grande
- 414 URI Too Long – URI demasiado largo
- 415 Unsupported Media Type – tipo no soportado
- 416 Range Not Satisfiable – rango inválido
- 417 Expectation Failed – cabecera Expect fallida
- 418 I'm a teapot – broma RFC 2324
- 421 Misdirected Request – petición mal dirigida
- 422 Unprocessable Entity (WebDAV) – entidad no procesable
- 423 Locked (WebDAV) – recurso bloqueado
- 424 Failed Dependency (WebDAV) – dependencia fallida
- 425 Too Early – petición enviada demasiado pronto
- 426 Upgrade Required – actualizar protocolo
- 428 Precondition Required – precondición requerida
- 429 Too Many Requests – demasiadas solicitudes
- 431 Request Header Fields Too Large – cabeceras muy grandes
- 451 Unavailable For Legal Reasons – no disponible por razones legales

## 5xx – Error del servidor
- 500 Internal Server Error – error interno
- 501 Not Implemented – no implementado
- 502 Bad Gateway – gateway inválido
- 503 Service Unavailable – servicio no disponible
- 504 Gateway Timeout – timeout del gateway
- 505 HTTP Version Not Supported – versión no soportada
- 506 Variant Also Negotiates – error de negociación de contenido
- 507 Insufficient Storage (WebDAV) – espacio insuficiente
- 508 Loop Detected (WebDAV) – bucle detectado
- 510 Not Extended – extensión requerida
- 511 Network Authentication Required – autenticación de red requerida

---

<br>

## SIP (Session Initation Protocol)

## 1xx – Informativos
- 100 Trying – intentando procesar INVITE
- 180 Ringing – teléfono sonando
- 181 Call Is Being Forwarded – llamada desviada
- 182 Queued – llamada en cola
- 183 Session Progress – media temprana
- 199 Early Dialog Terminated – diálogo temprano terminado

## 2xx – Éxito
- 200 OK – llamada aceptada / éxito
- 202 Accepted – petición aceptada
- 210 Content-Available – información disponible

## 3xx – Redirección
- 300 Multiple Choices – varias opciones
- 301 Moved Permanently – movido permanentemente
- 302 Moved Temporarily – movido temporalmente
- 380 Alternative Service – servidor alternativo

## 4xx – Error del cliente
- 400 Bad Request – solicitud mal formada
- 401 Unauthorized – no autorizado
- 403 Forbidden – acceso prohibido
- 404 Not Found – usuario no encontrado
- 408 Request Timeout – usuario no respondió
- 480 Temporarily Unavailable – usuario no disponible temporalmente
- 486 Busy Here – usuario ocupado
- 487 Request Terminated – petición terminada
- 488 Not Acceptable Here – medio no aceptable
- 440 Login Timeout – sesión expirada
- 481 Call/Transaction Does Not Exist – llamada/transacción no existe

## 5xx – Error del servidor
- 500 Internal Server Error – error interno
- 501 Not Implemented – no implementado
- 502 Bad Gateway – gateway inválido
- 503 Service Unavailable – servicio no disponible
- 504 Gateway Timeout – timeout del gateway

## 6xx – Error global
- 600 Busy Everywhere – usuario ocupado en todas partes
- 603 Decline – llamada rechazada
- 604 Does Not Exist Anywhere – usuario inexistente
- 606 Not Acceptable – medio no aceptable

