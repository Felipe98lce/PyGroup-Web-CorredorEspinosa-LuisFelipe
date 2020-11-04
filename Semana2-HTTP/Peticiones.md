# Peticiones HHTTP

HTTP define un conjunto de métodos de petición para indicar la acción que se desea realizar para un recurso determinado.

## GET
El método GET  solicita una representación de un recurso específico. Las peticiones que usan el método GET sólo deben recuperar datos.

```
GET /index.html HTTP/1.1  
User-Agent: Mozilla/4.0 (compatible; MSIE5.01; Windows NT)
Host: www.yosoy.dev
Accept-Language: es-mx
Accept-Encoding: gzip, deflate
Connection: Keep-Alive
```

## HEAD
El método HEAD pide una respuesta idéntica a la de una petición GET, pero sin el cuerpo de la respuesta.

## POST
El método POST se utiliza para enviar una entidad a un recurso en específico, causando a menudo un cambio en el estado o efectos secundarios en el servidor.

```
POST /cgi-bin/process.cgi HTTP/1.1
User-Agent: Mozilla/4.0 (compatible; MSIE5.01; Windows NT)
Host: www.yosoy.dev
Content-Type: text/xml; charset=utf-8
Content-Length: 88
Accept-Language: es-mx
Accept-Encoding: gzip, deflate
Connection: Keep-Alive
```

## PUT
El modo PUT reemplaza todas las representaciones actuales del recurso de destino con la carga útil de la petición.

```
PUT /index.htm HTTP/1.1
User-Agent: Mozilla/4.0 (compatible; MSIE5.01; Windows NT)
Host: www.yosoy.dev
Accept-Language: es-mx
Connection: Keep-Alive
Content-type: text/html
Content-Length: 182
```

## DELETE
El método DELETE borra un recurso en específico.

```
DELETE /hello.htm HTTP/1.1
User-Agent: Mozilla/4.0 (compatible; MSIE5.01; Windows NT)
Host: www.yosoy.dev
Accept-Language: es-mx
Connection: Keep-Alive
```

## CONNECT
El método CONNECT establece un túnel hacia el servidor identificado por el recurso.

```
CONNECT www.yosoy.dev HTTP/1.1
User-Agent: Mozilla/4.0 (compatible; MSIE5.01; Windows NT)
```

## OPTIONS
El método OPTIONS es utilizado para describir las opciones de comunicación para el recurso de destino.

```
CONNECT www.yosoy.dev HTTP/1.1
User-Agent: Mozilla/4.0 (compatible; MSIE5.01; Windows NT)
```

## TRACE
El método TRACE  realiza una prueba de bucle de retorno de mensaje a lo largo de la ruta al recurso de destino.

```
TRACE / HTTP/1.1
Host: www.yosoy.dev
User-Agent: Mozilla/4.0 (compatible; MSIE5.01; Windows NT)
```

## PATCH
El método PATCH  es utilizado para aplicar modificaciones parciales a un recurso.
