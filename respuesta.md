Pregunta:¿Cuáles son las dos diferencias principales que has visto anteriormente y lo que ves en un navegador web 'normal'? ¿Qué explica estas diferencias?

1.- La imagen no carga como archivo

2.- La programación es estática, la palabra aleatoria no cambia.

(base) pcs5@pcs5-HP-EliteDesk-800-G4-SFF:~$ curl 'http://randomword.saasbook.info'

(base) pcs5@pcs5-HP-EliteDesk-800-G4-SFF:~/Documentos/Trabajo1$ curl 'http://randomword.saasbook.info' >Trabajo1.html
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100   480  100   480    0     0   1651      0 --:--:-- --:--:-- --:--:--  1655

Pregunta: Suponiendo que estás ejecutando curl desde otro shell ¿qué URL tendrás que pasarle a curl para intentar acceder a tu servidor falso y por qué?

Tendré que pasarle el local host 8081 para que se conecte a ese servidor falso; para que de esa manera acceda a la web mediante un servidor (esto provocará que el archivo html sea dinámico, de esta forma las palabras si cambiaran y la imagen cargará.

Pregunta: La primera línea de la solicitud identifica qué URL desea recuperar el cliente. ¿Por qué no ves http://localhost:8081 en ninguna parte de esa línea?


