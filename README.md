## <p align = "center"> PRACTICA Nº1</p>
##  <p align = "center">SISTEMAS EMPRESARIALES</p>

|||
|----------|-------------|
|Carrera:| Ingenieria De Sistemas|
|Materia:| Tecnologias Emergentes II|
|Apellidos y Nombres:| Ajno Huchani Hugo Vladimir|
|C.I.:| 8348500 L.P.|
|Lugar y Fecha:| El Alto - 2019|
## 1. EXPLI  QUE SON LOS SISTEMAS EMPRESARIALES
El sistema de información empresarial constituye el conjunto de recursos de la empresa que sirven como soporte para el proceso básico de captación, transformación y comunicación de la información.
Un sistema de información debe ser eficaz y eficiente. Es eficaz si facilita la información necesaria, y es eficiente si lo realiza con los menores recursos posibles.

Un SIE debe adaptarse a las necesidades concretas de cada organización y a su estructura organizativa. Cuando se piensa en una implantación nunca se parte de cero pues todas las empresas disponen de algún tipo de información, más o menos rudimentario, con distintos grados de calidad/fiabilidad y con niveles de accesibilidad mayores o menores, etc. Esa información debe contemplarse como parte del SIE.

## 2. DESCRIBA LAS CARACTERISTICAS MAS IMPORTANTES DE UNA APLICACION EMPRESARIAL
####  1. flexible y escalable
para que crezca según las necesidades de la empresa. Es decir, se trata de que el software sea capaz de adaptarse a las funciones y necesidades que vayan surgiendo en la organización.
#### 2. agil y multidispositivo
Los usuarios deben poder acceder a los datos desde cualquier lugar de forma segura y fiable.
#### 3. sencillo
Para no perder tiempo con programas informáticos complicados. Lo ideal es que las herramientas sean muy intuitivas y fáciles de usar. Es importante también contar con un buen soporte por si surge cualquier tipo de problema
#### 4. medible
Cada acción y los resultados obtenidos deben quedar registrados para proceder con su análisis. Este punto es de vital importancia para el buen desarrollo de un negocio, sobre todo cuando se trata de emprendedores
## 3. PROPONGA  5 INSTITUCIONES QUE REQUIERAN  APLICACION QUE REQUIERAN APLICACION  DE MISION CRITICA
#### Policia Boliviana
actualmente esta institucion no cuenta con un sistema de control de multas a  los conductores lo cuaql provoca errores en la cobranza y recoleccion de dichas multas.
## 4. LAS DIFERENCIAS ENTRE ESCABILIDAD HORIZONTAL Y ESCABILIDAD VERTICAL
#### escabilidad vertical
La escalabilidad vertical o hacia arriba, este es el más simple, pues significa crecer el hardware de uno de los nodos, es decir aumentar el hardware por uno más potente, como disco duro, memoria, procesador, etc. pero también puede ser la migración completa del hardware por uno más potente. El esfuerzo de este crecimiento es mínimo, pues no tiene repercusiones en el software, ya que solo será respaldar y migrar los sistemas al nuevo hardware.
#### escabilidad horizontal
El escalamiento horizontal es sin duda el más potente, pero también el más complicado. Este modelo implica tener varios servidores (conocidos como Nodos) trabajando como un todo. Se crea una red de servidores conocida como Cluster, con la finalidad de repartirse el trabajo entre todos nodos del cluster, cuando el performance del cluster se ve afectada con el incremento de usuarios, se añaden nuevos nodos al cluster, de esta forma a medida que es requeridos, más y más nodos son agregados al cluster.
## ¿QUE ES UN SERVIDOR WEB  Y QUE ES UN SERVIDOR DE APLICACION?
#### servidor web
El servidor web (también llamado webserver en inglés) es el software que se encarga de despachar el contenido de un sitio web al usuario.

Este proceso de despacho, que a simple vista parece muy simple, es en realidad más complejo de lo que parece, pues toda la «magia» de un webserver ocurre fuera de quien está navegando por un sitio web. Existen multitud de servidores web, y entre los más conocidos podemos encontrar por ejemplo a Apache, Nginx, LiteSpeed o IIS.
#### servidor de aplicacion
Un servidor de aplicaciones es un programa de servidor en un equipo en una red distribuida que proporciona la lógica de negocio para un programa de aplicación. El servidor de aplicaciones se ve frecuentemente como parte de una aplicación de tres niveles, que consta de un servidor gráfico de interfaz de usuario (GUI), un servidor de aplicaciones (lógica empresarial) y un servidor de bases de datos y transacciones.

## CON UN GRAFICO EXPLIQUE COMO FUNCIONA EL PROTOCOLO  HTTP
![IMAGEN](http://www.hermosaprogramacion.com/wp-content/uploads/2015/01/http-protocolo-peticion.png)

## 7. EXPLIQUE LOS ELEMENTOS  IMPORTANTES DE REQUEST EN HTTP
HTTP, de sus siglas en inglés: "Hypertext Transfer Protocol", es el nombre de un protocolo el cual nos permite realizar una petición de datos y recursos, como pueden ser documentos HTML. Es la base de cualquier intercambio de datos en la Web, y un protocolo de estructura cliente-servidor, esto quiere decir que una petición de datos es iniciada por el elemento que recibirá los datos (el cliente), normalmente un navegador Web. Así, una página web completa resulta de la unión de distintos sub-documentos recibidos, como, por ejemplo: un documento que especifique el estilo de maquetación de la página web (CSS), el texto, las imágenes, vídeos, scripts, etc...    
![IMAGEN](https://mdn.mozillademos.org/files/13677/Fetching_a_page.png)
Clientes y servidores se comunican intercambiando mensajes individuales (en contraposición a las comunicaciones que utilizan flujos continuos de datos). Los mensajes que envía el cliente, normalmente un navegador Web, se llaman peticiones, y los mensajes enviados por el servidor se llaman respuestas.
![IMAGEN](https://mdn.mozillademos.org/files/13673/HTTP%20&%20layers.png)

## 8. EXPLIQUE LOS ELEMENTOS IMPORTANYES DE RESPONSE EN HTTP
Los mensajes HTTP, son los medios por los cuales se intercambian datos entre servidores y clientes. Hay dos tipos de mensajes: peticiones, enviadas por el cliente al servidor, para pedir el inicio de una acción; y respuestas, que son la respuesta del servidor. 

Los mensajes HTTP están compuestos de texto, codificado en ASCII, y pueden comprender múltiples lineas. En HTTP/1.1, y versiones previas del protocolo, estos mensajes eran enviados de forma abierta a través de la conexión. En HTTP/2.0 los mensajes, que anteriormente eran legibles directamente, se conforman mediante tramas binarias codificadas para aumentar la optimización y rendimiento de la transmisión.
![IMAGEN](https://mdn.mozillademos.org/files/13825/HTTPMsg2.png)

## 9. DESCRIBA CON UN GRAFICO LA ARQUITECTURA JAVA EE
![IMAGEN](https://camo.githubusercontent.com/aeb3864c8404eda0c595db6b5d9ebf0748b61b05/687474703a2f2f736e61672e67792f3962624e682e6a7067)

## 10. EXPLIQUE CUALES SON LOS CONTENEDORES, COMPONENTES  Y SERVICIOS DE JAVA EE
#### contenedores

Los contenedores son la interface entre un componente y el bajo nivel, es especifico para la plataforma, antes de que se pueda ejecutar el componente web, el bean o la aplicación cliente deben ser cargados en un modulo java EE y desplegarlo en el contenedor. al momento de desplegarlo cada componente puede tener su propia configuración en cuanto a seguridad, gestión de transacciones JNDI etc.
TIPOS DE CONTENEDORES
En la siguiente figura se muestra los tipos de contenedores para los diferentes componentes:

![IMAGEN](http://2.bp.blogspot.com/-xtOAc9rZSpc/U9_4CLOvnRI/AAAAAAAAAPQ/vX2vnfJhcWk/s1600/Captura.PNG)

Java EE Server: La porción de tiempo de ejecución de un producto Java EE. provee los contenedores web y de ejb.

Contenedor EJB: Maneja la ejecución de los enterprise beans.

Contenedor Web: Maneja la ejecución de las paginas web, servlets y algunos componentes ejb para las aplicaciones Java EE.

Contenedor de aplicación cliente: Maneja la ejecución de la aplicación cliente no necesita un servidor de aplicaciones.

Contenedor Applet: Maneja la ejecución de applets, no necesita servidor de aplicaciones, consiste en un browser y el plugin web de java.

#### componentes
Una serie de componentes de Java ES proporcionan los servicios principales que dan respaldo a las soluciones de software distribuidas. Entre estos servicios del sistema se incluyen los servicios de portal, identidad y seguridad, contenedor web, aplicaciones de J2EE y persistencia.

Los componentes de servicios del sistema que proporcionan estos servicios distribuidos y los servicios que éstos proporcionan se muestran en orden alfabético y se describen brevemente en la siguiente tabla. Cada componente de servicios del sistema es un proceso de servidor con varios subprocesos que admite el uso de una gran cantidad de clientes. Para obtener más información sobre cada componente, consulte Componentes de servicios del sistema.

|||
|----------|-------------|
|Componente | Servicios del sistema proporcionados |
|Sun Java System Access Manager| Incluye servicios de administración de acceso y de administración de identidades digitales. Los servicios de administración de acceso incluyen la autenticación (también el inicio de sesión único) y la autorización basada en funciones para acceder a las aplicaciones y los servicios. Estos servicios incluyen la administración centralizada de cuentas de usuario individuales, roles, grupos y directivas.|
|Sun Java System Application Server| Incluye servicios de contenedor de J2EE para componentes de Enterprise JavaBeansTM (EJB), como beans de sesión, beans de entidad y beans controlados por mensajes. El contenedor incluye servicios de infraestructura necesarios para que interactúen los componentes distribuidos y bien acoplados, lo que convierte a Application Server en una plataforma para el desarrollo y la ejecución de aplicaciones de comercio electrónico y servicios web. Application Server también proporciona servicios de contenedor web.|
|Sun Java System Directory Server|Incluye un depósito central para almacenar y administrar información de intranet e Internet como, por ejemplo, perfiles de identidad (empleados, clientes, proveedores, etc.), credenciales de usuario (certificados de clave pública, contraseñas y números de identificación personal), privilegios de acceso, información de recursos de aplicaciones e información de recursos de  |
|Java DB [Java ES 5 es la primera versión que incluye Java DB como componente de producto. Java DB se introdujo por primera vez como componente compartido en Java ES 2005Q4, con el nombre de Derby Database.]| Proporciona una base de datos ligera para el desarrollo de aplicaciones de Java. Java DB es una distribución compatible de Sun de la base de de datos de código abierto Apache Derby, implementada por competo mediante tecnología de Java.|

### servicios

Un Servicio Web es un componente software con las siguientes características:

Es accesible a través del interface SOAP (Simple Object Access Protocol).
Su interface se describe en un documento WSDL (Web Service Description Language).
SOAP es un protocolo de mensajería XML extensible que forma la base de los Servicios Web. 
SOAP proporciona un mecanismo simple y consistente que permtie a una aplicación enviar mensajes XML a otra aplicación. Un mensaje SOAP es una transmisión de una-via desde un emisor SOAP a un receptor SOAP, y cualquier aplicación puede participar en este intercambio como emisor o receptor. Los mensajes SOAP se pueden combinar para soportar muchos comportamientos de comunicación, incluyendo, solicitud/respuesta, respuesta solicitada, mensajería asíncrona de una-vía, o incluso notificación. SOAP es un protocolo de alto nivel que sólo define la estuctura del mensaje y unas pocas reglas para su procesamiento. Es completamente independiente del protocolo de transporte subyacente, por eso los mensajes SOAP se pueden intercambiar sobre HTTP, JMS o protocolos de transporte de e-mail. Actualmente el protocolo HTTP es el más utilizado para los mensajes HTTP.


## 11.INVESTIGUE LOS METODOS MAS UTILIZADOS DE LAS CLASES  HTTPSERVELET, HTTPSERVLETRESQUET Y HTTPSERVELETRESPONSE, Y PARA CADA UNO DE LOS METODOS MUESTRE UN EJEMPLO

### clase httpservelet
init(ServletConfig config): Es el método utilizado para crear una nueva instancia del servlet (análogo al constructor).
Este método puede ser sobreescrito para realizar tareas como crear una conexión a una BD que se mantendrá mientras el servlet se mantenga cargado y puede ser utilizada por cada petición. ServletConfig contiene los parámetros de inicialización que entrega el servidor al servlet.
getServletConfig(): Retorna la configuración dada para la inicialización del servlet.
service(ServletRequest req, ServletResponse res): Este método es el que se llama cuando se recibe una petición de un cliente y en su implementación normal para HTTP verifica el tipo de solicitud GET, POST, etc. y la redirige a los métodos respectivos. En general no es necesario reimplementar este método.
destroy(): Este método es llamado por el servidor para indicar que el servlet será destruido. Es llamado sólo una vez y uno debe encargarse de esperar por posibles peticiones en curso

![IMAGEN](https://i.ytimg.com/vi/LU_6IVpL-f4/maxresdefault.jpg)


### clase httpserveletresquet

El método getParameter devuelve el valor de un parámetro nombrado. Si nuestro parámetro pudiera tener más de un valor, deberíamos utilizar getParameterValues en su lugar. El método getParameterValues devuelve un array de valores del parámetro nombrado. (El método getParameterNames proporciona los nombres de los parámetros.

Para peticiones GET de HTTP, el método getQueryString devuelve en un String una línea de datos desde el cliente. Debemos analizar estos datos nosotros mismos para obtener los parámetros y los valores.
https://3.bp.blogspot.com/-ChzmJMJo9iE/WjwEzCuH-LI/AAAAAAAAD8s/4Cc-JGhq7EU_kEYUH_Dd4Xe28nfP0VN_QCLcBGAs/s1600/servlet.png

### clase httpresponse
AddHeader(<Name>,<Value>)

       Agrega un header con el valor dado.

      Ejemplo: AddHeader(“User-Agent”, “GeneXus”)

      <Name>-      String

      <Value>-      String

 

       AddString(<Value>)

       Agrega el contenido del string al buffer de datos a enviar.

      <Value>-      String

 

       AddFile(<Value>)

       Agrega el contenido del archivo al buffer de datos a enviar.

      <Value>-      String
      
      
      
      
![IMAGEN](https://i.ytimg.com/vi/_Hq7TF12NMw/maxresdefault.jpg)

      
