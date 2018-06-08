# randomstuff
Just some random Stuff, I will need to refer from time to time

## Generate CSR
```
openssl genrsa -des3 -out server.pass.key 2048
openssl rsa -in server.pass.key -out server.key
openssl req -nodes -new -key server.key -out server.csr
```
