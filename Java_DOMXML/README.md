En este ejemplo revisamos el uso del DOM en Java para accesar las islas de datos de un XML, este podría ser el 
resultado de una consulta de un servicio WEB.

Para este ejemplo se utilizaron las librerías:

- import javax.xml.parsers.DocumentBuilder;
- import javax.xml.parsers.DocumentBuilderFactory;
- import javax.xml.parsers.ParserConfigurationException;

- import javax.xml.transform.OutputKeys;
- import javax.xml.transform.Transformer;
- import javax.xml.transform.TransformerException;
- import javax.xml.transform.TransformerFactory;
- import javax.xml.transform.dom.DOMSource;
- import javax.xml.transform.stream.StreamResult;

En este ejemplo, se puede apreciar la navegación por tres ejemplos de documentos XML, el tercero corresponde a uno que se obtiene
de consultar un servicio WEB de acceso público (Biblioteca del Congreso Nacional de Chile). Si desean probar con otras consultas
del mismo servicio deben referirse a la siguiente URL:

https://www.leychile.cl/Consulta/legislacion_abierta_web_service
