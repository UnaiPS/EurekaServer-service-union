# Integration System

_Es una aplicación para adaptar una base de datos a otra base de datos, permitiendo al usuario poder utilizar los parámetros que el desee. Pudiendo así seleccionar los datos que le interese._

## Comenzando 🚀

_Estas instrucciones te permitirán obtener una copia del proyecto en funcionamiento en tu máquina local para propósitos de desarrollo y pruebas._

### Pre-requisitos 📋

* [OpenJDK 13](https://openjdk.java.net/projects/jdk/13/) 
_Se descomprime el archivo zip descargado.
Clic derecho sobre el archivo y Extraer todo.
Seleccionamos la ubicación donde queremos que quede los binarios del JDK. En mi caso voy a utilizar: c:\\java._

_Se ha creado una carpeta llamada jdk-13.0.2. Debemos recordar esta ruta porque la configuraremos en las variables de entorno.
Creación de las variables de entorno.
Se debe crear la variable de entorno JAVA\_HOME y se debe actualizar la variable de entorno PATH. La primera se utilizará para que java sepa dónde se encuentra la instalación del JDK y la segunda es para poder ejecutar los comandos de java (como javac, java, etc) desde cualquier lugar._

_*JAVA_HOME*
En la lupa de la barra de windows escribiremos: Editar las variables de entorno del sistema y damos clic en la opción que nos da.
Se abre la ventana de Propiedades del sistema y en la pestaña de Opciones avanzadas seleccionamos Variables de entorno.
Podemos crear las variables de entorno para el usuario actual o para el sistema. Yo sugiero que lo hagan para el sistema, con el fin de que cualquier usuario tenga acceso a la ejecución de java.
En el grupo de Variables del sistema seleccionamos el botón de Nueva...
En el nombre escribiremos: JAVA\_HOME
En el valor escribiremos la ruta donde se descomprime el jdk, en mi caso será: c:\\java\\jdk-13.0.2.
Clic en aceptar. Ya debe aparecer esta variable en el grupo._

_*PATH*
Si no tienes abierta la ventana de Variables de entorno abrela como se muestra en los dos primeros items del punto anterior.
En el grupo Variables del sistema ubica la variable Path, selecciónala y da clic en Editar...
Podrás ver todos los valores de Path. No los modifiquen o eliminen!.
Agrega un nuevo valor dando clic en el botón Nuevo y digitando la ruta de la instalación de java agregando la carpeta bin. En mi caso es: c:\\java\\jdk-13.0.2\\bin.
Das clic en aceptar, luego en aceptar y luego nuevamente en aceptar.
Ahora ya puedes abrir una consola dando clic en la lupa de la barra de windows, escribes cmd y seleccione símbolo del sistema._

* [Node.JS](https://nodejs.org/es/) 
_Seguir los pasos del instalador y dejar todo por defecto._

* [Vue CLI](https://cli.vuejs.org/guide/installation.html) 
_Utilizando el símbolo del sistema o CMD vamos a instalar Vue CLI con el comando:_
```
npm install -g @vue/cli @vue/cli-service-global
```
_o el comando:_ 
```
yarn global add @vue/cli @vue/cli-service-global
```
_Para comprobar la instalación y la versión se utiliza el comando:_
```
vue --version
```
* [Visual Studio Code](https://code.visualstudio.com/download)
_Seguir los pasos del instalador y dejar todo por defecto._

* [Spring Boot](https://spring.io/tools) 
_Descargariamos el archivo comprimido de la página oficial, una vez descargado descomprimimos y ejecutamos la aplicación de STS o Spring Tools Suite. Una vez ejecutada seleccionamos el JDK que tenemos instalado en el apartado de “Installed JREs”, ya estaría listo para comenzar.

Si desea hacerlo desde Eclipse vaya al [MarketPlace](https://www.eclipse.org/community/eclipse_newsletter/2018/february/springboot.php) y allí lo busca descargar, todo esta automatizado._

* [MySQL](https://www.mysql.com/downloads/) 
_Seguir los pasos del instalador y dejar todo por defecto. Si el usuario lo desea, seleccionar la opción de MySQL Workbench para tener entorno visual de MySQL._

### Instalación 🔧

_Para empezar deberá crear una base de datos con el mismo nombre de las *Properties* del proyecto Connections-service._

_Una vez instalado el entorno, accedemos a los repositorios de Git y clonamos dichos repositorios a nuestro máquina. Después debe acceder desde el símbolo del sistema o CMD a la carpeta del proyecto de Commons y ejecutar el comando mvnw.cmd install._

_Por último deberá  clona todos los proyectos, excepto el de vue que se clona en visual studio code._

## Despliegue 📦

_Para empezar la ejecución debemos hacerlo en el siguiente orden:_
* _Primero ejecutamos [MySQL](https://www.mysql.com/)_
* _Segundo ejecutamos [Spring Boot](https://spring.io/)_
* _Tercero ejecutamos [VUE](https://vuejs.org/)_

## Construido con 🛠️

* [MySQL](https://www.mysql.com/) - La Base de datos utilizada
* [Maven](https://maven.apache.org/) - Manejador de dependencias
* [Spring Boot](https://spring.io/) - El Framework utilizado en el back
* [VUE](https://vuejs.org/) - El Framework utilizado en el front

## Versionado 📌
Se utiliza [GitHub](https://github.com)  para el control de versiones.


## Autores ✒️

* **Unai Pérez Sánchez** - *GitHub* - [UnaiPS](https://github.com/UnaiPS)
* **Jon Mateo Bengoetxea** - *GitHub* - [jMaben](https://github.com/jMaben)
