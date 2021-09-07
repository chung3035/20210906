
# HTTP request  / response

- [Hypertext Transfer Protocol (HTTP) ](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol)

## HTTP request 

```
Request syntax
A client sends request messages to the server, which consist of:[23]
1.a request line, consisting of the case-sensitive request method, a space, the request target, another space, 
   the protocol version, a carriage return, and a line feed (e.g. GET /images/logo.png HTTP/1.1);
2.zero or more request header fields, each consisting of the case-insensitive field name, a colon, optional leading whitespace, 
   the field value, and optional trailing whitespace (e.g. Accept-Language: en), and ending with a carriage return and a line feed;
3.an empty line, consisting of a carriage return and a line feed;
4.an optional message body.

In the HTTP/1.1 protocol, all header fields except Host are optional.
```
```
GET /home.html HTTP/1.1
Host: developer.mozilla.org
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10.9; rv:50.0) Gecko/20100101 Firefox/50.0
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8
Accept-Language: en-US,en;q=0.5
Accept-Encoding: gzip, deflate, br
Referer: https://developer.mozilla.org/testpage.html
Connection: keep-alive
Upgrade-Insecure-Requests: 1
If-Modified-Since: Mon, 18 Jul 2016 02:36:04 GMT
If-None-Match: "c561c68d0ba92bbeb8b0fff2a9199f722e3a621a"
Cache-Control: max-age=0
```

- [HTTP request methods](https://developer.mozilla.org/en-US/docs/Glossary/Request_header)
- [Request header](https://developer.mozilla.org/en-US/docs/Glossary/Request_header)


## HTTP response

- [List of HTTP status codes](https://en.wikipedia.org/wiki/List_of_HTTP_status_codes)
- [Response header](https://developer.mozilla.org/en-US/docs/Glossary/Response_header)

```
200 OK
Access-Control-Allow-Origin: *
Connection: Keep-Alive
Content-Encoding: gzip
Content-Type: text/html; charset=utf-8
Date: Mon, 18 Jul 2016 16:06:00 GMT
Etag: "c561c68d0ba92bbeb8b0f612a9199f722e3a621a"
Keep-Alive: timeout=5, max=997
Last-Modified: Mon, 18 Jul 2016 02:36:04 GMT
Server: Apache
Set-Cookie: mykey=myvalue; expires=Mon, 17-Jul-2017 16:06:00 GMT; Max-Age=31449600; Path=/; secure
Transfer-Encoding: chunked
Vary: Cookie, Accept-Encoding
X-Backend-Server: developer2.webapp.scl3.mozilla.com
X-Cache-Info: not cacheable; meta data too large
X-kuma-revision: 1085259
x-frame-options: DENY
```
