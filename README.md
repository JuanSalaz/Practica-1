

**Práctica N° 1**

**Sistemas empresariales**

**CARRERA: INGENIERIA DE SISTEMAS**                                   

**MATERIA: TECNOLOGIA EMERGENTES II**

**APELLIDOS Y NOMBRES: SALAZ MAMANI JUAN RODRIGO**

**CI: 9247112**

**FECHA ENTREGA: 13-AGO-2019**

**1) Explique que son los sistemas empresariales.**

*Un sistema empresarial es un sistema central de la organización, que garantiza que la información se pueda transmitir atraves de todas las funciones empresariales, y todos los niveles de gestión, para soportar la operación y administración de una empresa.* 

**2) Describa cuales son las características más importantes de una aplicación empresarial**
 

- Cliente Web
- Directory &
Security
Services (LDAP)
- Enterprise Information
Systems EIS.
- Servicios vía
Web
Services.
- Inteligencia de
Negocios.
- Base Datos
Empresa
- Aplicaciones Desktop
- otros Dispositivos

**3) Investigue y proponga cinco (5) instituciones que requerirían aplicaciones de misión crítica. Justifique su respuesta.**

**4) Explique cuáles son las diferencias entre la escalabilidad horizontal y escalabilidad vertical**.

 *La diferencia es que en la escalabilidad vertical es que el esfuerzo de este crecimiento es mínimo mientras que el horizontal tiene el modelo que implica tener varios servidores (conocidos como Nodos) trabajando como un todo*.

**5) Que es un servidor Web y que es un servidor de aplicaciones.**

**Servidor Web**

*Es un servidor que almacena los documentos que componen una página web (HTML, CSS, PHP…) y se la proporciona al usuario para que la visualice completa en su navegador de Internet.*
#Servidor de aplicaciones.
*Es un tipo de servidor que ejecuta determinadas aplicaciones proporcionando servicios a los ordenadores cliente.Normalmente este tipo de servidores suelen ejecutar aplicaciones J2EE ya que ofrece los estándares para contener los componentes de las aplicaciones si bien, también pueden ejecutar otras como son las del tipo Microsoft conformando los servidores de aplicaciones Windows.*

**6) Con un gráfico explique cómo funciona el protocolo HTTP.**

![](https://1.bp.blogspot.com/-bJuW1IfNxAo/XUi2FBvQE9I/AAAAAAAAAjU/JrW39_ERfHsWYm9bMblaQ6TYtMdqHQ-PgCLcBGAs/s1600/protocolo%2Bhttp.JPG)

**7) Explique los elementos importantes de REQUEST en HTTP.**

*Elementos importantes de REQUEST en HTTP:*

- Método http (la acción a realizar)
- La página para acceder (una url)
- Parámetros de formulario (como argumentos de un método)

**8) Explique los elementos importantes de RESPONSE en HTTP.**

*Elementos importantes de RESPONSE en HTTP:*

- Un código de estado (para saber si la solicitud fue exitosa)
- Tipo de contenido (texto, imagen, HTML, etc.)
- El contenido (el HTML real, la imagen, etc.)

**9) Describa con un gráfico la arquitectura Java EE.**

![imagen 2](https://image.slidesharecdn.com/jatunandjavaee-110905104600-phpapp02/95/desarrollo-de-aplicaciones-empresariales-con-java-ee-4-728.jpg?cb=1316098712)

**10) Explique cuáles son los contenedores, componentes y servicios de Java EE
Java EE se basa en tres conceptos claves:**

- Servicios
- Contenedores
- Componentes

***Los Contenedores:** Son entornos en tiempo de ejecución, es decir un programa que se está ejecutando y tu aplicación la montas sobre este como si fuera un plugin o el cassette para una consola de juegos. Hay varios tipos de contenedores y la agrupación de ellos forman un servidor de aplicaciones.*

***Los Servicios:** Son todas esas características de las que hablamos al comienzo. Estos servicios son proporcionados por un contenedor. Así el programador se concentra en su lógica de negocio y usa estos servicios para su aplicación.*

***Los Componentes:** Son objetos POJO que pueden ser reusados. Estos contienen la lógica de negocio de la aplicación y usan los servicios proporcionados por el contenedor. Hay varios tipos de componentes y según ese tipo son instalados(desplegados) en un contenedor u otro.*

**11) Investigue los métodos más utilizados de las clases HttpServlet, **HttpServletRequest** **y **HttpServletResponse**, **y para cada uno de los métodos muestre un ejemplo.**

*Los  métodos  más  utilizados  de  la  clase  HttpServlet.*

1. doGet(HttpServletRequest req, **HttpServlet** resp): Es el método llamado para procesar información que haya sido enviado con el método GET. Este método es llamado concurrentemente para cada cliente por lo que hay que estar atento por posibles variables compartidas que causen problemas.

2. doPost(HttpServletRequest req, HttpServletResponse resp): Ídem al anterior pero para el método POST, en general se implementa sólo un método y el otro lo referencia.

*Los  métodos  más  utilizados  de  la  clase **HttpServletRequest.***

1. getHeader(String name): Permite obtener el valor de los Headers de HTTP con que fue llamado el servlet.
2. getCookies(): Retorna un arreglo que contiene todas las cookies que el cliente envía al servlet.
3. getSession(): Retorna la sesión en la cual se encuentra el cliente.

*Los  métodos  más  utilizados  de  la  clase **HttpServletResponse.***

1. addCookie(Cookie cookie): Para definir nuevas cookies en el cliente.
2. setHeader(String name, String value): Para definir un header HTTP a enviar al cliente.
3. sendRedirect(String location): Envía un mensaje al cliente para redireccionar la respuesta a la dirección señalada







