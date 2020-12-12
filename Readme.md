## Rendimiento y comunicación

Escenario

Se crea una web para una tienda de electrodomésticos. La aplicación tiene una página que muestra la venta del día, 
los productos clasificados por categorías, la posibilidad de añadir productos a su lista de compras y una página de chat 
que permita a los usuarios hablar en línea. La aplicación almacenará en caché el contenido de una vista.  

Los objetivos a conseguir son:

- Implementar una estrategia de cacheo.
- Administrar el estado de la aplicación.
- Agregar una comunicación bidireccional utilizando SignalR.


*1: Aplicación de una estrategia de almacenamiento en caché*

Para mejorar el rendimiento de la aplicación web, se va a utilizar la caché. Para ello, lo primero que haremos es añadir un cache tag helper a una vista. 
Después de eso, usará la memoria caché para almacenar y recuperar elementos.


*2: Gestionar el estado*

Para conservar información entre solicitudes, utilizamos el estado de sesión en la aplicación. 

Las tares que se llevarán a cabo son:

1. Habilitar el trabajo con sesiones
2. Usar la sesión para guardar los valores
3. Recuperar los valores de una sesión


*3: Comunicación bidireccional* 

Lo primero que haremos será agregar una clase Hub de SignalR llamada ChatHub y se registrará ChatHub en la clase de inicio. A continuación, 
añadiremos una vista de chat. Por último, se escribirá el código JavaScript para conectarse al servidor.

Las tares que se llevarán a cabo son:

1. Añadir una clase de SignalR Hub llamada ChatHub
2. Inscribir el ChatHub en la clase de inicio
3. Añadir una vista de chat
4. Escribir el código JavaScript para conectarse al servidor
