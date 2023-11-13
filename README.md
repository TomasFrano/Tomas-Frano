 # Ejercicio 2 # 
>1.¿Que es un servudor HTTP?

Un servidor web es un ordenador de gran potencia que se encarga de “prestar el servicio” de transmitir la información pedida por sus clientes (otros ordenadores, dispositivos móviles, impresoras, personas, etc.) 
Los servidores web son un componente de los servidores que tienen como principal función almacenar, en web hosting, todos los archivos propios de una página web (imágenes, textos, videos, etc.) y transmitirlos a los usuarios a través de los navegadores mediante el protocolo HTTP.

>2.	¿Qué son los verbos HTTP? Mencionar los más conocidos

HTTP define un conjunto de métodos de petición para **indicar la acción** que se desea realizar para un recurso determinado. Aunque estos también pueden ser sustantivos, estos métodos de solicitud a veces son llamados HTTP verbs

Los verbos mas conocidos son:

- GET :
El método GET solicita una representación de un recurso específico. Las peticiones que usan el método GET sólo deben recuperar datos.

- HEAD :
El método HEAD pide una respuesta idéntica a la de una petición GET, pero sin el cuerpo de la respuesta.

- POST :
Envía datos para que sean procesados por el recurso identificado en la URL de la línea petición. Los datos se incluirán en el cuerpo de la petición. A nivel semántico está orientado a crear un nuevo recurso, cuya naturaleza vendrá especificada por la cabecera Content-Type.

- PUT :
Envia datos al servidor, pero a diferencia del método POST la URI de la línea de petición no hace referencia al recurso que los procesará, sino que identifica a los propios datos.

- DELETE :
El método DELETE borra un recurso en específico.

- CONNECT :
se utiliza para saber si se tiene acceso a un host, no necesariamente la petición llega al servidor, este método se utiliza principalmente para saber si un proxy nos da acceso a un host bajo condiciones especiales, como por ejemplo "corrientes" de datos bidireccionales encriptadas.

- OPTIONS :
Devuelve los métodos HTTP que el servidor soporta para un URL específico. Esto puede ser utilizado para comprobar la funcionalidad de un servidor web mediante petición en lugar de un recurso específico

- TRACE :
El método TRACE realiza una prueba de bucle de retorno de mensaje a lo largo de la ruta al recurso de destino.

- PATCH :
función es la misma que PUT, el cual sobrescribe completamente un recurso. Se utiliza para actualizar, de manera parcial una o varias partes

>3.¿Qué es un request y un response en una comunicación HTTP? ¿Qué son los headers? 

**Request** es la primera parte del proceso, donde la parte cliente hace una petición o request que llegará al servidor web. **Response** es la solución que brinda el servidor web después de hacer lo que necesita para darle respuesta. Aquí puede ejecutar un programa que tenga instalado, consultar una base de datos o cualquier otro archivo, entre otras herramientas. Una vez haya recogido la información, la unirá en el formato solicitado y la devolverá como respuesta. El **header** web es el término que hace referencia a la parte superior de un sitio web. Al ser lo primero que el usuario visualiza, debes tener en cuenta dos cosas. Primero, que los usuarios puedan navegar fácilmente por él. Y, segundo, ofrecer información relevante sobre tu identidad para conectar lo antes posible con tus visitantes.

>4.¿Qué es un queryString? (En el contexto de una url)

Las Query String o cadenas de consultas es un término que se utiliza para hacer referencia a una interacción con una base de datos. Además, es la parte de una URL que contiene los datos que deben pasar a las aplicaciones web. Las Query String permiten acceder a páginas web dinámicas con distintas variables consiguiendo así que las páginas web no estén compuestas de decenas de directorios y permitiendo que su estructura esté basada en URLs amigables.

>5.¿Qué es el responseCode? ¿Qué significado tiene los posibles valores devueltos?

Los códigos de estado de respuesta HTTP indican si se ha completado satisfactoriamente una solicitud HTTP específica. Las respuestas se agrupan en cinco clases: 
Respuestas informativas
Respuestas satisfactorias
Redirecciones 
Errores de los clientes 
Errores de los servidores

>6.¿Cómo se envía la data en un Get y cómo en un POST? 

**Con el método GET**, los datos que se envían al servidor se escriben en la misma dirección URL. Toda la información introducida por el usuario (los llamados “parámetros URL”) se transmiten tan abiertamente como el URL en sí mismo. Esto tiene ventajas y desventajas. Una ventaja es que los parámetros URL se pueden guardar junto a la dirección URL como marcador. De esta manera, puedes introducir una búsqueda y más tarde consultarla de nuevo fácilmente y una desventaja su débil protección de los datos. Los parámetros URL que se envían quedan visibles en la barra de direcciones del navegador y son accesibles sin clave en el historial de navegación, en el caché y en el log de los servidores.
**El método POST** introduce los parámetros en la solicitud HTTP para el servidor. Por ello, no quedan visibles para el usuario. Además, la capacidad del método POST es ilimitada. Su ventaja en lo relativo a los datos, como, por ejemplo, al rellenar formularios con nombres de usuario y contraseñas, el método POST ofrece mucha discreción. Los datos no se muestran en el caché ni tampoco en el historial de navegación. La flexibilidad del método POST también resulta muy útil. Y su desventaja Cuando una página web que contiene un formulario se actualiza (por ejemplo, cuando se retrocede a la página anterior) los datos del formulario deben transferirse de nuevo (puede que alguna vez hayas recibido una de estas advertencias). Por este motivo, existe el riesgo de que los datos se envíen varias veces por error, lo que, en el caso de una tienda online, puede dar lugar a pedidos duplicados. No obstante, las webs modernas de las tiendas suelen estar preparadas para evitar este tipo de problemas.

>7.¿Qué verbo http utiliza el navegador cuando accedemos a una página?


**GET** Es el método de petición HTTP más utilizado con diferencia. Una petición GET solicita al servidor una información o recurso concreto. Cuando te conectas a un sitio web, tu navegador suele enviar varias peticiones GET para recibir los datos que necesita para cargar la página.

>8.Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles.

- JSON está constituído por dos estructuras:

  - Una colección de pares de nombre/valor. En varios lenguajes esto es conocido como un objeto, registro, estructura, diccionario, tabla hash, lista de claves o un arreglo asociativo.
  - Una lista ordenada de valores. En la mayoría de los lenguajes, esto se implementa como arreglos, vectores, listas o sequencias.
 
- HTM tiene las siguientes caracteristicas :
  
  - Los elementos de un documento XML deben seguir una estructura de “árbol” (estrictamente jerárquica).
  - Los elementos deben estar correctamente anidados.
  - Los elementos no se pueden superponer entre ellos.
  - Sólo puede haber un elemento raiz, en el que estén contenidos todos los demás.

>9.Explicar brevemente el estándar SOAP

SOAP es un protocolo escrito en XML para el intercambio de información entre aplicaciones. Es un formato para enviar mensajes, diseñado especialmente para servir de comunicación en Internet, pudiendo extender los HTTP headers. Es una forma de definir qué información se envía y cómo mediante XML.

>10.Explicar brevemente el estándar REST Full

**REST** es una interfaz para conectar varios sistemas basados en el protocolo HTTP (uno de los protocolos más antiguos) y nos sirve para obtener y generar datos y operaciones, devolviendo esos datos en formatos muy específicos, como XML y JSON.

>11.¿Qué son los headers en un request? ¿Para qué se utiliza el key Content-type en un header?

Los HTTP headers son la parte central de los HTTP requests y responses, y transmiten información acerca del navegador del cliente, de la página solicitada, del servidor, etc. La primera línea es la línea del request, que contiene su información básica (método HTTP, URL y versión)
Content-Type es la propiedad de cabecera (header) usada para indicar el media type (en-US) del recurso. Content-Type dice al cliente que tipo de contenido será retornado hace 3 días.

# Ejercicio 3 #






























