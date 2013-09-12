Twitter -> Página WebSockets
=============================

Este exemplo mostra como exibir tweets em uma página conectada com websockets.

Você precisa configurar:

* O arquivo app.properties (dentro de src/main/resources)
* Maven 

Você NÃO precisa configurar:

* Um application server
* O arquivo applicationContext.xml (embora você possa, caso exista algo que você queira modificar)


Para executar, basta ir até a raiz do projeto e executar mvn exec:java. Depois de alguns segundos, basta acessar o endereço http://localhost:9090/index.html


**Este exemplo baseia-se fortemente no descrito pela própria equipe do Apache Camel: http://camel.apache.org/twitter-websocket-example.html**
