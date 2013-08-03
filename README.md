Twitter -> Página WebSockets
=============================

Este exemplo mostra como mostrar tweets  

Você precisa configurar:

* A máquina EC2
* Um gtalk próprio para sua máquina (é possível usar o seu próprio, mas não recomendo)
* O arquivo app.properties (dentro de src/main/resources)
* Maven 

Você NÃO precisa configurar:

* Um application server
* O arquivo applicationContext.xml (embora você possa, caso exista algo que você queira modificar)


Para executar, basta ir até a raiz do projeto e executar mvn exec:java. Quando estiver pronto, o sistema vai mandar uma mensagem para você ;)


**Este exemplo baseia-se fortemente no descrito pela própria equipe do Apache Camel: http://camel.apache.org/twitter-websocket-example.html**
