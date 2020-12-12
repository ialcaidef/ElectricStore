## Rendimiento y comunicaci�n

Escenario

Se crea una web para una tienda de electrodom�sticos. La aplicaci�n tiene una p�gina que muestra la venta del d�a, 
los productos clasificados por categor�as, la posibilidad de a�adir productos a su lista de compras y una p�gina de chat 
que permita a los usuarios hablar en l�nea. La aplicaci�n almacenar� en cach� el contenido de una vista.  

Los objetivos a conseguir son:

- Implementar una estrategia de cacheo.
- Administrar el estado de la aplicaci�n.
- Agregar una comunicaci�n bidireccional utilizando SignalR.


*1: Aplicaci�n de una estrategia de almacenamiento en cach�*

Para mejorar el rendimiento de la aplicaci�n web, se va a utilizar la cach�. Para ello, lo primero que haremos es a�adir un cache tag helper a una vista. 
Despu�s de eso, usar� la memoria cach� para almacenar y recuperar elementos.


*2: Gestionar el estado*

Para conservar informaci�n entre solicitudes, utilizamos el estado de sesi�n en la aplicaci�n. 

Las tares que se llevar�n a cabo son:

1. Habilitar el trabajo con sesiones
2. Usar la sesi�n para guardar los valores
3. Recuperar los valores de una sesi�n


*3: Comunicaci�n bidireccional* 

Lo primero que haremos ser� agregar una clase Hub de SignalR llamada ChatHub y se registrar� ChatHub en la clase de inicio. A continuaci�n, 
a�adiremos una vista de chat. Por �ltimo, se escribir� el c�digo JavaScript para conectarse al servidor.

Las tares que se llevar�n a cabo son:

1. A�adir una clase de SignalR Hub llamada ChatHub
2. Inscribir el ChatHub en la clase de inicio
3. A�adir una vista de chat
4. Escribir el c�digo JavaScript para conectarse al servidor
