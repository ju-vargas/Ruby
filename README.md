# Vue-Ruby
Repositório para estudar BackEnd em Ruby on Rails + FrontEnd em Vue.js. 

## Ruby
### HTTP 
Protocolo da camada de aplicação da Internet. Segue o modelo cliente-servidor. Por exemplo: o web browser é o cliente enquanto o processo (web server) rodando em um computador que é host de um ou mais websites é o servidor. O cliente manda requests e o servidor manda responses. 
#### Request syntax 
* a request line, consisting of the case-sensitive request method, a space, the requested URI, another space, the protocol version, a carriage return, and a line feed, e.g.:
```
GET /images/logo.png HTTP/1.1
```
* zero or more request header fields (at least 1 or more headers in case of HTTP/1.1), each consisting of the case-insensitive field name, a colon, optional leading whitespace, the field value, an optional trailing whitespace and ending with a carriage return and a line feed, e.g.:
```
Host: www.example.com
Accept-Language: en
```
* an empty line, consisting of a carriage return and a line feed;
* an optional message body.
##### Request methods
Ação desejada para ser performada no recurso identificado. 
```
GET
HEAD
POST
PUT
DELETE
etc
```

#### Response syntax
* a status line, consisting of the protocol version, a space, the response status code, another space, a possibly empty reason phrase, a carriage return and a line feed, e.g.:
```
HTTP/1.1 200 OK
```
* zero or more response header fields, each consisting of the case-insensitive field name, a colon, optional leading whitespace, the field value, an optional trailing whitespace and ending with a carriage return and a line feed, e.g.:
```
Content-Type: text/html
```
* an empty line, consisting of a carriage return and a line feed;
* an optional message body.

```
The first digit of the status code defines its class:

1XX (informational)
The request was received, continuing process.

2XX (successful)
The request was successfully received, understood, and accepted.

3XX (redirection)
Further action needs to be taken in order to complete the request.

4XX (client error)
The request contains bad syntax or cannot be fulfilled.

5XX (server error)
The server failed to fulfill an apparently valid request.
```
### MCV
#### 📌 Fluxo de Funcionamento do MVC

1. O usuário faz uma requisição (exemplo: acessar uma página de produtos).
2. O Controller recebe a requisição, busca os dados no Model e os envia para a View.
3. A View renderiza esses dados em uma página HTML.
4. O usuário vê a resposta no navegador.

No Rails, routes (rotas) definem como as URLs da aplicação são mapeadas para controllers e actions. Elas são responsáveis por direcionar as requisições do usuário para o código correto da aplicação.


## Vue
