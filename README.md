# grx-moad

Herramienta de configuración de equipos linux para el uso de aplicaciones de administración electrónica.

**Software necesario:**

* Open JDK (xenyal - bionic) u Oracle JDK (trusty) para la aplicación autofirma.

* libnss3-tools para el uso de las herramientas **certutil** y **pk12util** de importación y exportación de certificados electrónicos a los almacenes de certificados de mozilla y chrome.

* Autofirma para firmado de documentos y acceso a aplicaciones web de administración electrónica.

* Google chrome (si no está instalado).


**Importación de certificados:**

* Importa los certificados de CA a los almacenes de Mozilla Firefox y Google Chrome.

* Inicializa los perfiles de usuario de los navegadores y los almacenes de certificados si no existen.

* Instala un certificado personal en dichos almacenes si se provee.

**Configuración de la conexión a través de proxy:**

Se configura la conexión del equipo para el uso del servidor proxy de Diputación de Granada en caso de que sea necesario. Solicitará credenciales válidas.

Se suministra el paquete **grx-moad.deb** que deberá instalarse en el sistema. Este habilita la ejecución de un comando **grx-moad** que permite ejecutar las tareas indicadas.

**Sintaxis**

*grx-moad -u usuario [-c] [ruta-del-certificado-personal] [-p] [contraseña-del-certificado]*
