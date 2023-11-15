 ## Ejercicio 2 ## 
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

## Ejercicio 3 ##

>1.

-	Realizar un request GET a la URL: 

![Captura de pantalla (1)](https://github.com/TomasFrano/Tomas-Frano/assets/150734518/7d9d828e-713c-4f26-a013-905f1a091cd2) 

>2
- Realizar un request POST a la URL anterior, y con mi nombre y mail en el body:

![Captura de pantalla (2)](https://github.com/TomasFrano/Tomas-Frano/assets/150734518/3c50ea24-7483-4341-b386-036f8519da5c)


>3
-	Realizar nuevamente un request GET a la URL:
  
![Captura de pantalla (3)](https://github.com/TomasFrano/Tomas-Frano/assets/150734518/7f4fbb12-8ebf-4b2d-b517-138d59c2bf8f)

- La diferencia entre las llamadas 1 y 3 es que luego de realizada la segunda request GET se muestran mis datos en la pagina al final de la misma 

## Ejercicio 4 ##

[Módulos de Trailhead](https://www.salesforce.com/trailblazer/profile)

## Ejercicio 5 ##

>Lead:

Es donde se encuentran las cuentas de los candidatos para la empresa. Los datos que se almacenan son: Nombre completo, Compañia, Estado o provincia, Correo electronico, Estado del candidato, Fecha de creacion, Alias del propietario.

>Account:

Es donde se encuentran las cuentas de las empresas con las que se tiene relacion. Los datos que se almacenan son: Nombre de la cuenta, Sitio de la cuenta, Estado o provincia de facturacion, Telefono, Tipo, Alias del propietario.

>Contact:

Es donde se guardan los contactos de los empleados que trabajan en las empresas con las que se tiene relacion. Los datos que se almacenan son: Nombre completo, Nombre de la cuenta, Cargo, Telefono, Correo electronico, Alias del propietario.

>Opportunity:

Es donde se encuentran las oportunidades de ventas. Los datos que se almacenan son: Nombre de la oportunidad, Nombre de la cuenta, Importe, Fecha de cierre, Etapa, Alias del propietario de la oportunidad.

>Product:

Es donde se encuentran los detalles de los productos. Los datos que se almacenan son: Nombre del producto, Codigo del producto, Alias del propietario.

>PriceBook

Es donde se encuentran los detallados los precios de los productos. Los datos que se almacenan son: Nombre de la lista de precios, Descripcion, Alias del propietario.

>Quote:



>Asset:

Es donde se encuentran los datos de un activo. Los datos que almacena son: Contacto, Cuenta, Estado, Numero de serie, Propietario del activo, Ubicacion.

>Case:

Es donde se encuentan todos los casos de los contactos que se deben resolver. Los datos que se almacenan son: Numero del caso, Nombre del contacto, Asunto, Estado Prioridad, Fecha/hora de apertura, Alias del propietario del caso.

>Article


![Ejercicio 5 drawio](https://github.com/TomasFrano/Tomas-Frano/assets/150734518/d14fbee6-431c-4530-aa21-8d845bce449f)


## Ejercicio 6 ##

- Soluciones de Salesforce

>¿Qué es Salesforce?

Salesforce es una **plataforma de gestión de las relaciones con los clientes** (CRM) basada en la nube que proporciona a todos los departamentos de su organización, incluidos los de marketing, ventas, servicio de atención al cliente y ecommerce, una visión unificada de sus clientes en una plataforma integrada.

>¿Qué es Sales Cloud?

Sales Cloud es una **herramienta de ventas todo en uno y CRM** que combina la mayoría de las mismas capacidades que encontrarás en otras herramientas. Sin embargo, con Sales Cloud, obtienes las funciones de automatización de ventas que necesitas en un solo lugar.

>¿Qué es Service Cloud?

Service Cloud es una **solución completa de atención al cliente** creada especialmente para dar soporte a los clientes a cualquier hora y en cualquier lugar, por teléfono, correo electrónico, redes sociales, chats y páginas o comunidades de auto ayuda.

>¿Qué es Health Cloud?

Health Cloud es una plataforma especialmente diseñada para la **gestión clínica de pacientes por medio de tecnologías on-cloud**, la cual ofrece: una comunicación más personalizado entre pacientes, miembros, proveedores y prestadores de servicios de salud, y un mejor ajuste a los procesos, servicios y datos médicos según el perfil de cuidado de cada paciente.

>¿Qué es Marketing Cloud?

Como parte de los servicios Salesforce, Marketing Cloud es un **módulo de Salesforce** que contiene múltiples herramientas para mejorar la **interacción de las marcas con sus clientes** y potenciales a través de todo tipo de canales.


- Funcionalidades de Salesforce


>¿Qué es un RecordType?

Los Record Types en Salesforce nos permiten **definir diferentes Business Process, Pages Layouts y Picklist Values** en un determinado objeto. Así mismo, los Record Types nos ayudan a **mostrar distintos tipos de información** según el perfil del usuario.

>¿Qué es un ReportType?

Un reporte es una **lista de registros que cumplen los criterios que define**. Se muestra en Salesforce en filas y columnas, y se puede filtrar, agrupar o mostrar en un diagrama gráfico. Cada reporte se almacena en una carpeta.

>¿Qué es un Page Layout?

Los diseños de página controlan el diseño y la organización de botones, campos, s-controls, Visualforce, enlaces personalizados y listas relacionadas en páginas de registros de objetos.

>¿Qué es un Compact Layout?

Un diseño compacto muestra los campos clave de un registro de un vistazo en la aplicación móvil Salesforce, Lightning Experience y en las integraciones de Outlook y Gmail.

>¿Qué es un Perfil?

Los perfiles definen cómo acceden los usuarios a objetos y datos y qué pueden hacer en la aplicación.

>¿Qué es un Rol?

Los roles controlan el nivel de visibilidad que un usuario tiene sobre los datos de su organización. Usuarios en cualquier función dada pueden ver, editar, e informar sobre todos los datos para funciones por debajo de ellos en la jerarquía de roles.

>¿Qué es un Validation Rule?

Las reglas de validación verifican que los datos que un usuario introduce en un registro cumplen con las normas que especifica antes de que el usuario guarde el registro. Una regla de validación puede contener una fórmula o expresión que evalúa los datos en uno o más campos y ofrece un valor “Verdadero” o “Falso”.

>¿Qué diferencia hay entre una relación Master Detail y Lookup?

En las relaciones de búsqueda se usan cuando los objetos están relacionados solo en ciertos casos. Los objetos de las relaciones de búsqueda suelen funcionar como objetos independientes que tienen sus propias fichas en la interfaz de usuario. En las relaciones del tipo principal-detalle, el objeto de detalle no funciona de manera independiente. En realidad, este objeto depende del objeto principal. Por lo tanto, si se elimina un registro del objeto principal, también se eliminarán todos los registros relacionados del objeto de detalle. A la hora de crear relaciones principal-detalle, siempre se crea el campo de relación en el objeto de detalle.

>¿Qué es un Sandbox?

Un Sandbox es una copia de su organización en un entorno aislado que puede usar para distintos fines, como pruebas y capacitación. Los sandbox están completamente aislados de su organización de producción de Salesforce.

>¿Qué es un ChangeSet?

Un conjunto de cambios entrantes es un conjunto de cambios que se ha enviado desde otra organización de Salesforce a la organización en la que ha iniciado sesión. Un conjunto de cambios se debe implementar para que los cambios surtan efecto.

>¿Para qué sirve el import Wizard de Salesforce?

Data Import Wizard es una herramienta de carga de datos integrada en Salesforce para todas las ediciones.

>¿Para qué sirve la funcionalidad Web to Lead?

Puede utilizar los formularios Web-to-Lead para definir una campaña o fuente de clientes potenciales colocando valores dentro de los campos ocultos. Estos valores jugarán un papel clave en el respaldo de las acciones automatizadas una vez que los clientes potenciales lleguen a Salesforce.

>¿Para qué sirve la funcionalidad Web to Case?

Recopile las solicitudes de servicio de atención al cliente directamente del sitio web de su empresa y genere automáticamente casos nuevos con Caso Web.

>¿Para qué sirve la funcionalidad Omnichannel?

Omni- canal es una función personalizable y flexible que se puede configurar de forma declarativa en Salesforce, es decir, sin necesidad de escribir código. OmniCanal ayuda al enrutamiento automático de diferentes tipos de elementos de trabajo (como casos y clientes potenciales) a los agentes.

>¿Para qué sirve la funcionalidad Chatter?

Chatter es una aplicación de colaboración en tiempo real de Salesforce que permite a sus usuarios trabajar juntos, comunicarse y compartir información.

- Conceptos generales

>¿Qué significa SaaS?

El software como servicio (SaaS) es un modelo de entrega de software basado en la nube en el que el proveedor de la nube desarrolla y mantiene el software de las aplicaciones en la nube, proporciona actualizaciones automáticas del mismo y lo pone a disposición de sus clientes a través de Internet con un sistema de pago por uso.

>¿Salesforce es Saas?

No, Salesforce es una compañia de PaaS

>¿Qué significa que una solución sea Cloud?

Cloud computing es la disponibilidad bajo demanda de recursos de computación como servicios a través de Internet. Esta tecnología evita que las empresas tengan que encargarse de aprovisionar, configurar o gestionar los recursos y permite que paguen únicamente por los que usen.

>¿Qué significa que una solución sea On-Premise?

El termino on-premises se refiere al hecho que los titulares de la licencia instalan el software en su propio entorno informático, sin recurrir a la nube o necesitar acceso a internet.

>¿Qué es un pipeline de ventas?

El pipeline de ventas se refiere a cada uno de los pasos de su proceso de ventas que sigue un representante de ventas para llevar una venta desde el principio hasta el final.

>¿Qué es un funnel de ventas?

El embudo de ventas es una forma de medir y conocer mucho mejor a tus clientes potenciales o buyer persona. Abarca todas las actividades, desde atraer nuevos visitantes hasta la generación de ventas con una estrategia de Inbound Marketing incrementando así la facturación mensual de tu negocio.

>¿Qué significa Customer Experience?

La experiencia del cliente es cómo se relaciona una empresa con sus clientes en todos los aspectos del recorrido de compra, desde el marketing hasta las ventas y el servicio al cliente pasando por cada punto intermedio. En gran parte, es la suma total de todas las interacciones que un cliente tiene con tu marca.

>¿Qué significa omnicanalidad?

La omnicanalidad es una estrategia de marketing que crea experiencias valiosas entre una empresa o negocio y sus clientes, a través de todos los medios de contacto que tiene vigentes, ya sean físicos o digitales.

>¿Qué significa que un negocio sea B2B?¿Qué significa que un negocio sea B2C?¿Qué es un KPI?

El B2B (business to business) es el modelo de negocio en el que se realizan transacciones comerciales entre empresas. En cambio, en el modelo B2C (business to consumer) esas transacciones se efectúan entre negocios y los consumidores.
El KPI (Key Performance Indicator o, en Español, Indicador Clave de Rendimiento) es un sistema de medición que, expresado normalmente en un porcentaje, nos dice el grado de progreso o cumplimiento de un objetivo de la empresa.

>¿Qué es una API y en qué se diferencia de una Rest API?

Por lo general, la API sigue el formato de aplicación a aplicación, mientras que REST sigue una estructura diferente: Cliente-Servidor. El cliente y el servidor están evolucionando de forma independiente, proporcionando más flexibilidad en el trabajo.

>¿Qué es un Proceso Batch?

El modo de lotes ejecuta una serie de procesos de Cargador de datos en un orden concreto utilizando un archivo por lotes. Puede volver a ejecutar la misma secuencia de procesos utilizando un archivo 

>¿Qué es Kanban?

La metodología Kanban se implementa por medio de tableros Kanban. Se trata de un método visual de gestión de proyectos que permite a los equipos visualizar sus flujos de trabajo y la carga de trabajo. En un tablero Kanban, el trabajo se muestra en un proyecto en forma de tablero organizado por columnas.

>¿Qué es un ERP? 

La planificación de recursos empresariales, también conocida como ERP, es un sistema que ayuda a automatizar y administrar los procesos empresariales de distintas áreas: finanzas, fabricación, venta al por menor, cadena de suministro, recursos humanos y operaciones.

>¿Salesforce es un ERP?

Salesforce es un CRM ya que se involucra en la gestion ed las relaciones con los clientes, mientras que el ERP se ocupa de la planificacion de los recursos empresariales







































