
# SSL certificate instructiom

```php
openssl version
```
```php
openssl genrsa -out localhost.key 2048
```
```php
openssl req -new -key localhost.key -out localhost.csr
```
```php
openssl x509 -req -days 365 -in localhost.csr -signkey localhost.key -out localhost.crt
```
```php
https://slproweb.com/products/Win32OpenSSL.html
```