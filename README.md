Twitter -> P�gina WebSockets
=============================

Este exemplo mostra como mostrar tweets  

Voc� precisa configurar:

* A m�quina EC2
* Um gtalk pr�prio para sua m�quina (� poss�vel usar o seu pr�prio, mas n�o recomendo)
* O arquivo app.properties (dentro de src/main/resources)
* Maven 

Voc� N�O precisa configurar:

* Um application server
* O arquivo applicationContext.xml (embora voc� possa, caso exista algo que voc� queira modificar)


Para executar, basta ir at� a raiz do projeto e executar mvn exec:java. Quando estiver pronto, o sistema vai mandar uma mensagem para voc� ;)


**Este exemplo baseia-se fortemente no descrito pela pr�pria equipe do Apache Camel: http://camel.apache.org/twitter-websocket-example.html**
