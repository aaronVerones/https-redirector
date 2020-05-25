# https-redirector
Simple Node server that redirects any HTTP request to HTTPS.
Especially useful for single-tenant applications with multiple systems behind a Load Balancer.

### Quickstart
command: 
```
docker run -p [host-port-to-redirect]:80 aaronverones/http-redirector
```
examples:

```
docker run -p 3000:80 aaronverones/http-redirector
```
```
docker run -p 80:80 aaronverones/http-redirector
```


