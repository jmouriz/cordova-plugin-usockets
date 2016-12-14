# cordova-plugin-usockets
Apache Cordova Plugin for libusockets library

> Estoy intentando desarrollar un puente idiomático entre JavaScript y C usando Java a través de la interfaz JNI para incorporar funciones JavaScript a un proyecto Apache Cordova.
>
> En un primer intento compilé libusockets para un procesador ARM 7 con la biblioteca estándar incluída en Android y todo parece andar bien. Hay que configurar el Makefile para que utilice la cadena de herramientas del compilador que genera binarios para otros destinos. [Repositorio del código de libusockets](https://github.com/jmouriz/libusockets).
>
> Ahora estoy construyendo un plugin muy rudimentario para un proyecto Apache Cordova. A este plugin lo voy a alojar aquí mismo. En principio, probé ejecutar un binario con un servidor nativo a través del shell de Android desde JavaScript pero la idea es hacerlo a través de JNI porque no encuentro la manera de ejecutar la instrucción select(2) de C en JavaScript.
