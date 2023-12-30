# Procontacto_tp

*Hola mi nombre es Juan José tengo 32 años soy Diseñador Grafico, Diseñador UX/UI, CM, con conocimiento en HTML,CSS (https://github.com/coloradoar/atp), acontinuación dejo la resolución de la prueba tecnica.*

--------------------------------------------------------------------------------

### Ejercicio 1

1.  Instalar el IDE Visual Studio Code ✔️
2.  Instalar GIT y GIT Bash ✔️

--------------------------------------------------------------------------------
   
### Ejercicio 2

1.  Un servidor HTTP es un software diseñado para recibir y responder a solicitudes HTTP. Gestiona la comunicación entre clientes y servidores, generalmente para entregar páginas web al navegador del usuario.
2.  Los verbos HTTP son comandos que indican la acción que se debe realizar en un recurso. Algunos de los más conocidos son:
   GET: Obtener datos.
   POST: Enviar datos para ser procesados.
   PUT: Actualizar un recurso o crearlo si no existe.
DELETE: Eliminar un recurso.
HEAD: Obtener solo la información de encabezado del recurso.
3. Un request es una solicitud enviada por el cliente al servidor, mientras que un response es la respuesta proporcionada por el servidor al cliente. Los headers son metadatos que contienen información adicional sobre la solicitud o respuesta, como el tipo de contenido, la longitud del contenido, etc.
4. Un queryString es parte de una URL que contiene datos que se envían al servidor como parámetros clave-valor. Por ejemplo, en http://ejemplo.com/ruta?nombre=usuario&edad=25, el queryString es nombre=usuario&edad=25.
5. El responseCode es un código numérico devuelto por el servidor en la respuesta HTTP. Algunos códigos comunes son:
200 OK: Solicitud exitosa.
404 Not Found: Recurso no encontrado.
500 Internal Server Error: Error interno del servidor.
6. En un GET, los datos se envían como parte de la URL (en el queryString). En un POST, los datos se envían en el cuerpo del mensaje HTTP.
7. El navegador utiliza el verbo GET para solicitar la página inicial.
Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles.

JSON:

{"nombre": "Ejemplo", "edad": 30, "ciudad": "Ciudad Ejemplo"}

Ejemplo de XML:


![XmlExample](https://github.com/coloradoar/procontacto_tp/assets/84077767/83cceecf-3d0c-4f1b-a433-abd2d1a31140)

8. Explicar brevemente el estándar SOAP.
SOAP (Simple Object Access Protocol) es un protocolo de intercambio de información estructurada en la web. Utiliza XML para definir mensajes y se centra en la comunicación entre aplicaciones a través de protocolos como HTTP y SMTP.
9. REST (Representational State Transfer) es un enfoque arquitectónico para diseñar servicios web. Utiliza operaciones estándar de HTTP (GET, POST, PUT, DELETE) y se basa en la representación de recursos a través de URLs.
10. Los headers en un request son metadatos que proporcionan información adicional sobre la solicitud. El key Content-type se utiliza para especificar el tipo de contenido que se está enviando en el cuerpo del mensaje, como "application/json" para datos JSON o "text/xml" para datos XML. Indica al servidor cómo debe interpretar el cuerpo del mensaje.

------------------------------------------------------------------------------------------

### Ejercicio 3

- Primer request [GET]

  <img width="1055" alt="get1" src="https://github.com/coloradoar/procontacto_tp/assets/84077767/8ce12a12-7615-4249-b704-dd8e252186ff">

- Request [POST]

  <img width="1051" alt="post" src="https://github.com/coloradoar/procontacto_tp/assets/84077767/94f97836-9ff1-4da8-b517-21aefa8b9ba6">

- Segundo request [GET]

  <img width="1013" alt="get2" src="https://github.com/coloradoar/procontacto_tp/assets/84077767/7dd5fda2-a643-4071-8461-e4b6516abfe5">


>Se puede ver cambios en los datos devueltos, como la inclusión de la nueva entrada creada con la solicitud POST. La respuesta del segundo GET refleja los datos actualizados después de realizar la solicitud POST.

--------------------------------------------------------------------------------------------

### Ejercicio 4

Pueden ver mi perfil del SalesForce [aquí](https://www.salesforce.com/trailblazer/juanaguayog49ixux4c4tg).

---------------------------------------------------------------------------------------------

### Ejercicio 5

1. Lead: Representa a un cliente potencial o prospecto antes de convertirse en una oportunidad de venta.
Datos estándar: Nombre, empresa, cargo, estado, etc.

2. Account: Representa a una empresa o entidad con la que se tiene una relación comercial.
Datos estándar: Nombre de la cuenta, tipo de industria, número de empleados, etc.

3. Contact: Representa a una persona individual asociada a una cuenta.
Datos estándar: Nombre, cargo, correo electrónico, teléfono, etc.

4. Opportunity: Representa una venta o trato potencial con un cliente.

5. Datos estándar: Nombre de la oportunidad, etapa de la venta, monto esperado, etc.

6. Product: Representa un bien o servicio ofrecido por la empresa.
Datos estándar: Nombre, descripción, precio, etc.

7. PriceBook: Contiene una lista de productos y sus precios asociados.
Datos estándar: Lista de productos con precios.

8. Quote: Representa una cotización para un cliente con productos y precios.
Datos estándar: Productos, precios, cantidad, etc.

9. Asset: Representa un bien vendido o instalado en un cliente.
Datos estándar: Nombre del activo, número de serie, fecha de instalación, etc.

10. Case: Representa un problema o solicitud de un cliente.
Datos estándar: Descripción del caso, estado, prioridad, etc.

11. Article: Representa contenido como documentación o información relevante.
Datos estándar: Título, cuerpo del artículo, categoría, etc.

Diagrama

![alt text](https://github.com/coloradoar/procontacto_tp/assets/84077767/e7c4620a-14e1-41c2-ad88-593cba31ea82)


------------------------------------------------------------------------------------------------------------


### Ejercicio 6

A. Salesforce es una plataforma de gestión de relaciones con los clientes (CRM) basada en la nube que ofrece una variedad de soluciones para ventas, servicio al cliente, marketing y más.
B. Sales Cloud es una solución de Salesforce diseñada para mejorar los procesos de ventas y la gestión de oportunidades, clientes potenciales y cuentas.
C. Service Cloud es una solución de Salesforce centrada en ofrecer un excelente servicio al cliente, gestionando casos, solicitudes y facilitando la colaboración en equipo.
D. Health Cloud es una solución específica para el sector de la salud que permite a los profesionales sanitarios gestionar la atención al paciente de manera más efectiva.
E. Marketing Cloud es una solución de Salesforce para la gestión y automatización de marketing, facilitando la creación y ejecución de campañas personalizadas.

Funcionalidades de Salesforce:
A. Un RecordType en Salesforce define los diferentes conjuntos de campos y páginas de diseño que estarán disponibles para un objeto en particular.
B. Un ReportType en Salesforce define las relaciones entre objetos y determina qué campos están disponibles para la creación de informes.
C. Un Page Layout en Salesforce define la disposición de los campos, secciones y acciones en una página de registro.
D. Un Compact Layout en Salesforce define los campos esenciales y las acciones que se muestran en la vista de lista de registros.
E. Un Perfil en Salesforce controla el acceso y los privilegios de un usuario, especificando qué datos y acciones puede ver y realizar.
F. Un Rol en Salesforce determina el nivel de acceso a los datos para un usuario, especialmente en la jerarquía de ventas.
G. Una Validation Rule en Salesforce establece condiciones para garantizar que los datos ingresados cumplan con ciertos criterios antes de guardarse.
H. Una relación Master-Detail en Salesforce implica una dependencia fuerte, donde el maestro controla ciertos aspectos del detalle. Una relación Lookup es más independiente y no impone restricciones de eliminación.
I. Un Sandbox en Salesforce es un entorno de desarrollo y prueba aislado que replica la configuración y los datos de una organización Salesforce.
J. Un ChangeSet en Salesforce es una herramienta para migrar configuraciones y desarrollos entre entornos Salesforce.
K. El Import Wizard facilita la importación de datos a Salesforce desde archivos CSV.
L. Web to Lead permite capturar automáticamente la información de clientes potenciales desde formularios web y crear registros en Salesforce.
M. Web to Case automatiza la creación de casos en Salesforce a partir de formularios web.
N. Omnichannel en Salesforce permite gestionar de manera integrada la atención al cliente a través de múltiples canales.
O. Chatter es una funcionalidad de colaboración social en Salesforce que facilita la comunicación y el intercambio de información entre usuarios.

Conceptos generales:
A. Software as a Service (SaaS) es un modelo de entrega de software donde las aplicaciones están alojadas en la nube y se accede a ellas a través de internet.
B. Sí, Salesforce es una solución SaaS, ya que proporciona servicios de software a través de la nube.
C. Cloud significa que la solución se entrega a través de la nube (internet) en lugar de instalarse localmente en dispositivos individuales.
D. On-Premise significa que la solución se instala y opera en la infraestructura local de la organización, en lugar de depender de servicios en la nube.
E. Un pipeline de ventas es un conjunto de etapas que representa el proceso de ventas, desde la adquisición de clientes potenciales hasta el cierre de ventas.
F. Un funnel de ventas es una representación visual del proceso de ventas, mostrando la conversión de clientes potenciales a clientes a lo largo de varias etapas.
G. Customer Experience (CX) se refiere a la percepción general de un cliente sobre su interacción con una empresa a lo largo de su ciclo de vida.
H. Omnicanalidad se refiere a la capacidad de una empresa para brindar una experiencia consistente al cliente a través de múltiples canales de comunicación.
I. B2B significa Business to Business (negocio a negocio), B2C significa Business to Consumer (negocio a consumidor), y KPI significa Key Performance Indicator (indicador clave de rendimiento).
J. Una API (Interfaz de Programación de Aplicaciones) es un conjunto de reglas que permite que diferentes aplicaciones se comuniquen entre sí. Una REST API es un tipo específico de API que sigue los principios de la arquitectura REST para la comunicación.
K. Un Proceso Batch en Salesforce es un proceso automatizado que realiza una secuencia de operaciones en lotes sobre registros.
L. Kanban es un método visual para gestionar el trabajo, que se basa en tarjetas que representan tareas y se mueven a través de columnas que representan estados del proceso.
M. Un ERP (Enterprise Resource Planning) es un sistema de planificación de recursos empresaria.


-------------------------------------------------------------------------------------------------------------


### Ejercicio 7

<img width="1440" alt="Captura de pantalla 2023-12-29 a la(s) 20 36 21" src="https://github.com/coloradoar/procontacto_tp/assets/84077767/cbb9ccbf-ec96-41f2-8a90-28cd3ca057e3">

<img width="1278" alt="Captura de pantalla 2023-12-29 a la(s) 20 39 14" src="https://github.com/coloradoar/procontacto_tp/assets/84077767/abe06d42-bae6-44da-8b5c-bef02158bc8a">

<img width="502" alt="Captura de pantalla 2023-12-29 a la(s) 20 38 34" src="https://github.com/coloradoar/procontacto_tp/assets/84077767/0f16acb5-cf1f-4353-8c39-97daf750c76f">

<img width="1207" alt="Captura de pantalla 2023-12-29 a la(s) 21 25 32" src="https://github.com/coloradoar/procontacto_tp/assets/84077767/957d5559-91fe-4162-a4ab-9e8d895c3632">


<img width="1440" alt="success2" src="https://github.com/coloradoar/procontacto_tp/assets/84077767/068d384f-0d32-410c-bb3c-04618a63574f">

<img width="1440" alt="success1" src="https://github.com/coloradoar/procontacto_tp/assets/84077767/230894c0-5ba2-457f-a4f9-c2fdc01d87a7">

<img width="1091" alt="success" src="https://github.com/coloradoar/procontacto_tp/assets/84077767/5476b81a-f9e0-4b28-8b44-bbadc48b8c8b">
