Создание private-key openssl
openssl genrsa -out jwt-private.pem 2048

Создание public_key openssl
openssl rsa -in jwt-private.pem -outform PEM -pubout -out jwt-public.pem
