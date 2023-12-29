# procontacto_tp

hola mi nombre es Juan José y acontinuacion dejo la resolución del practico


Ejercicio 2
💻¿Qué es un servidor HTTP?
Un servidor HTTP es un software diseñado para recibir y responder a solicitudes HTTP. Gestiona la comunicación entre clientes y servidores, generalmente para entregar páginas web al navegador del usuario.

¿Qué son los verbos HTTP? Mencionar los más conocidos.
Los verbos HTTP son comandos que indican la acción que se debe realizar en un recurso. Algunos de los más conocidos son:
GET: Obtener datos.
POST: Enviar datos para ser procesados.
PUT: Actualizar un recurso o crearlo si no existe.
DELETE: Eliminar un recurso.
HEAD: Obtener solo la información de encabezado del recurso.

¿Qué es un request y un response en una comunicación HTTP? ¿Qué son los headers?
Un request es una solicitud enviada por el cliente al servidor, mientras que un response es la respuesta proporcionada por el servidor al cliente. Los headers son metadatos que contienen información adicional sobre la solicitud o respuesta, como el tipo de contenido, la longitud del contenido, etc.

¿Qué es un queryString? (En el contexto de una URL)
Un queryString es parte de una URL que contiene datos que se envían al servidor como parámetros clave-valor. Por ejemplo, en http://ejemplo.com/ruta?nombre=usuario&edad=25, el queryString es nombre=usuario&edad=25.

¿Qué es el responseCode? ¿Qué significado tienen los posibles valores devueltos?
El responseCode es un código numérico devuelto por el servidor en la respuesta HTTP. Algunos códigos comunes son:
200 OK: Solicitud exitosa.
404 Not Found: Recurso no encontrado.
500 Internal Server Error: Error interno del servidor.

¿Cómo se envía la data en un GET y cómo en un POST?
En un GET, los datos se envían como parte de la URL (en el queryString). En un POST, los datos se envían en el cuerpo del mensaje HTTP.

¿Qué verbo HTTP utiliza el navegador cuando accedemos a una página?
El navegador utiliza el verbo GET para solicitar la página inicial.

Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles.

JSON: {"nombre": "Ejemplo", "edad": 30, "ciudad": "Ciudad Ejemplo"}

Ejemplo de XML:
<persona>
  <nombre>Ejemplo</nombre>
  <edad>30</edad>
  <ciudad>Ciudad Ejemplo</ciudad>
</persona>

Explicar brevemente el estándar SOAP.
SOAP (Simple Object Access Protocol) es un protocolo de intercambio de información estructurada en la web. Utiliza XML para definir mensajes y se centra en la comunicación entre aplicaciones a través de protocolos como HTTP y SMTP.

Explicar brevemente el estándar RESTful.
REST (Representational State Transfer) es un enfoque arquitectónico para diseñar servicios web. Utiliza operaciones estándar de HTTP (GET, POST, PUT, DELETE) y se basa en la representación de recursos a través de URLs.

¿Qué son los headers en un request? ¿Para qué se utiliza el key Content-type en un header?
Los headers en un request son metadatos que proporcionan información adicional sobre la solicitud. El key Content-type se utiliza para especificar el tipo de contenido que se está enviando en el cuerpo del mensaje, como "application/json" para datos JSON o "text/xml" para datos XML. Indica al servidor cómo debe interpretar el cuerpo del mensaje.


Ejercicio 3


¿Qué diferencias se observan entre las llamadas el punto 1 y 3?
Se puede ver cambios en los datos devueltos, como la inclusión de la nueva entrada creada con la solicitud POST. La respuesta del segundo GET refleja los datos actualizados después de realizar la solicitud POST.

Ejercicio 4

https://www.salesforce.com/trailblazer/juanaguayog49ixux4c4tg

Ejercicio 5

Lead: Representa a un cliente potencial o prospecto antes de convertirse en una oportunidad de venta.
Datos estándar: Nombre, empresa, cargo, estado, etc.

Account: Representa a una empresa o entidad con la que se tiene una relación comercial.
Datos estándar: Nombre de la cuenta, tipo de industria, número de empleados, etc.

Contact: Representa a una persona individual asociada a una cuenta.
Datos estándar: Nombre, cargo, correo electrónico, teléfono, etc.

Opportunity: Representa una venta o trato potencial con un cliente.

Datos estándar: Nombre de la oportunidad, etapa de la venta, monto esperado, etc.

Product: Representa un bien o servicio ofrecido por la empresa.
Datos estándar: Nombre, descripción, precio, etc.

PriceBook: Contiene una lista de productos y sus precios asociados.
Datos estándar: Lista de productos con precios.

Quote: Representa una cotización para un cliente con productos y precios.
Datos estándar: Productos, precios, cantidad, etc.

Asset: Representa un bien vendido o instalado en un cliente.
Datos estándar: Nombre del activo, número de serie, fecha de instalación, etc.

Case: Representa un problema o solicitud de un cliente.
Datos estándar: Descripción del caso, estado, prioridad, etc.

Article: Representa contenido como documentación o información relevante.
Datos estándar: Título, cuerpo del artículo, categoría, etc.

<mxfile host="app.diagrams.net" modified="2023-12-29T21:00:55.600Z" agent="Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/120.0.0.0 Safari/537.36" etag="vTKJMYfgmb2_BqRVeMv8" version="22.1.16" type="github">
  <diagram name="Página-1" id="baaax6Z8dfIzUIeogOmC">
    <mxGraphModel dx="954" dy="606" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="827" pageHeight="1169" math="0" shadow="0">
      <root>
        <mxCell id="0" />
        <mxCell id="1" parent="0" />
        <mxCell id="uoC-D4_zJCUfr7f5D_ew-11" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=1;exitDx=0;exitDy=0;" edge="1" parent="1" source="uoC-D4_zJCUfr7f5D_ew-1" target="uoC-D4_zJCUfr7f5D_ew-6">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="uoC-D4_zJCUfr7f5D_ew-12" value="" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="1" source="uoC-D4_zJCUfr7f5D_ew-1" target="uoC-D4_zJCUfr7f5D_ew-8">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="uoC-D4_zJCUfr7f5D_ew-1" value="ACCOUNT" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="110" y="70" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="uoC-D4_zJCUfr7f5D_ew-14" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=1;exitDx=0;exitDy=0;entryX=0.5;entryY=0;entryDx=0;entryDy=0;" edge="1" parent="1" source="uoC-D4_zJCUfr7f5D_ew-2" target="uoC-D4_zJCUfr7f5D_ew-5">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="uoC-D4_zJCUfr7f5D_ew-2" value="LEAD" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="300" y="178" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="uoC-D4_zJCUfr7f5D_ew-3" value="ASSET" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="110" y="393" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="uoC-D4_zJCUfr7f5D_ew-4" value="OPPORTUNITY" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="110" y="178" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="uoC-D4_zJCUfr7f5D_ew-5" value="PRODUCT" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="300" y="285" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="uoC-D4_zJCUfr7f5D_ew-6" value="CASE" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="110" y="500" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="uoC-D4_zJCUfr7f5D_ew-7" value="PRICEBOOK" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="490" y="70" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="uoC-D4_zJCUfr7f5D_ew-8" value="CONTACT" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="300" y="70" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="uoC-D4_zJCUfr7f5D_ew-9" value="QUOTE" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="110" y="285" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="uoC-D4_zJCUfr7f5D_ew-13" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="1" source="uoC-D4_zJCUfr7f5D_ew-8">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="360" y="180" as="targetPoint" />
          </mxGeometry>
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
