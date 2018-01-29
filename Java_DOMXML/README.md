En este ejemplo revisamos el uso del DOM en Java para accesar las islas de datos de un XML, este podría ser el 
resultado de una consulta de un servicio WEB.

Para este ejemplo se utilizaron las librerías:

import javax.xml.parsers.DocumentBuilder;
import javax.xml.parsers.DocumentBuilderFactory;
import javax.xml.parsers.ParserConfigurationException;

import javax.xml.transform.OutputKeys;
import javax.xml.transform.Transformer;
import javax.xml.transform.TransformerException;
import javax.xml.transform.TransformerFactory;
import javax.xml.transform.dom.DOMSource;
import javax.xml.transform.stream.StreamResult;
