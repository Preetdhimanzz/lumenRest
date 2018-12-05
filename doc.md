Login
POST /lumenblog/public/login HTTP/1.1
Host: localhost
Cache-Control: no-cache
Postman-Token: 1d30014b-3ce1-3932-d142-8f1c82bb09c5
Content-Type: multipart/form-data; boundary=----WebKitFormBoundary7MA4YWxkTrZu0gW

------WebKitFormBoundary7MA4YWxkTrZu0gW
Content-Disposition: form-data; name="email"

admin@gmail.com
------WebKitFormBoundary7MA4YWxkTrZu0gW
Content-Disposition: form-data; name="password"

123456
------WebKitFormBoundary7MA4YWxkTrZu0gW
Content-Disposition: form-data; name="username"

admin
------WebKitFormBoundary7MA4YWxkTrZu0gW--



Registration

POST /lumenblog/public/register HTTP/1.1
Host: localhost
Cache-Control: no-cache
Postman-Token: b33a4889-93ec-4849-de04-dbea02f73aa4
Content-Type: multipart/form-data; boundary=----WebKitFormBoundary7MA4YWxkTrZu0gW

------WebKitFormBoundary7MA4YWxkTrZu0gW
Content-Disposition: form-data; name="username"

admin
------WebKitFormBoundary7MA4YWxkTrZu0gW
Content-Disposition: form-data; name="email"

admin@gmail.com
------WebKitFormBoundary7MA4YWxkTrZu0gW
Content-Disposition: form-data; name="password"

123456
------WebKitFormBoundary7MA4YWxkTrZu0gW--
