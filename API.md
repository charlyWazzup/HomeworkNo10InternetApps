### �Qu� es REST?

REpresentational State Transfer, es un tipo de arquitectura de desarrollo web que se apoya totalmente en el est�ndar HTTP.

Nos permite crear servicios y aplicaciones que pueden ser usadas por cualquier dispositivo o cliente que entienda HTTP, por lo que es incre�blemente m�s simple y convencional que otras alternativas que se han usado en los �ltimos diez a�os como SOAP y XML-RPC.

Existen tres niveles de calidad a la hora de aplicar REST en el desarrollo de una aplicaci�n web y m�s concretamente una API que se recogen en un modelo llamado Richardson Maturity Model en honor al tipo que lo estableci�, Leonard Richardson padre de la arquitectura orientada a recursos. Estos niveles son:

* Uso correcto de URIs. 

* Uso correcto de HTTP.

* Implementar Hypermedia.

Los fundamentales principios de REST se basan en separar tu API en recursos l�gicos. Estos recursos son manipulados usando peticiones HTTP donde el m�todo (GET, POST, PUT, PATCH, DELETE) tienen un significado espec�fico.

La grandeza de REST es que estas impulsando m�todos HTTP existentes a implementar funcionalidades importantes en s�lo un simple endpoint /tickets. No hay convenci�n de nombres de m�todos para seguir y la estructura URL es limpia y clara.

#### Caracter�sticas de REST

* Protocolo cliente/servidor sin estado: cada petici�n HTTP contiene toda la informaci�n necesaria para ejecutarla, lo que permite que ni cliente ni servidor necesiten recordar ning�n estado previo para satisfacerla. Aunque esto es as�, algunas aplicaciones HTTP incorporan memoria cach�. Se configura lo que se conoce como protocolo cliente-cach�-servidor sin estado: existe la posibilidad de definir algunas respuestas a peticiones HTTP concretas como cacheables, con el objetivo de que el cliente pueda ejecutar en un futuro la misma respuesta para peticiones id�nticas. De todas formas, que exista la posibilidad no significa que sea lo m�s recomendable.

* Las operaciones m�s importantes relacionadas con los datos en cualquier sistema REST y la especificaci�n HTTP son cuatro: POST (crear), GET (leer y consultar), PUT (editar) y DELETE (eliminar).

* Los objetos en REST siempre se manipulan a partir de la URI. Es la URI y ning�n otro elemento el identificador �nico de cada recurso de ese sistema REST. La URI nos facilita acceder a la informaci�n para su modificaci�n o borrado, o, por ejemplo, para compartir su ubicaci�n exacta con terceros. 

* Interfaz uniforme: para la transferencia de datos en un sistema REST, este aplica acciones concretas (POST, GET, PUT y DELETE) sobre los recursos, siempre y cuando est�n identificados con una URI. Esto facilita la existencia de una interfaz uniforme que sistematiza el proceso con la informaci�n.

* Sistema de capas: arquitectura jer�rquica entre los componentes. Cada una de estas capas lleva a cabo una funcionalidad dentro del sistema REST.



