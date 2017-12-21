# Linux Tweet App

Este es el sitio web de NGINX muy simple que permite a un usuario enviar un tweet.

Para usarlo: 

Construye:
`docker build -t linux_tweet_app .`

Ejecuta:
`docker container run --detach -p 80:80 linux_tweet_app`
