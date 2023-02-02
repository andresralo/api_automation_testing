<h1 align="center"><img src="https://jmeter.apache.org/images/logo.svg" alt="Apache JMeter logo" /></h1>

# Reto API Automation Testing

T-Evolvers

## Acerca del Proyecto

Este proyecto contiene la automatizacion de un Api del Booking [restful-booker](#https://restful-booker.herokuapp.com/apidoc/index.html)

##  ¿Qué hace?

El archivo [TestQAAutomation.jmx](https://github.com/andresralo/api_automation_testing/commit/9757ca990ed8ae0e1cb3ffa882cac762118fca7d#diff-43b797a1225410e66fbd91d2ea9881736bc927dc3257675e761e69377135aa7b) contiene un pull de test automaticos que interactuan con los 
los siguientes paths de el Api:

- Auth-Create Token
- CreateBoking
- GetBooking
- UpdateBooking

##  Características
Esta test automatizado esta diseñado como un archivo .jmx para ser ejecutado en la interfas Apache Jmeter la cual podras descargar [aqui](#https://jmeter.apache.org/download_jmeter.cgi)

![img.png](https://github.com/andresralo/api_automation_testing/blob/main/img/img.png)



## ¿Qué es Apache Jmeter y por qué usarlo ?
Una aplicación Java de código abierto diseñado para medir el rendimiento y cargar aplicaciones de prueba.
Apache JMeter puede medir el rendimiento y realizar pruebas de carga de aplicaciones web estáticas y dinámicas.

Se puede usar para simular una carga pesada en un servidor, grupo de servidores, red u objeto para probar su fuerza o para analizar el rendimiento general bajo diferentes tipos de carga.

Ademas al automatizar peticiones al servidor se reducen los tiempos en los test logrando mayor eficiencia de equipos de trabajo. 

## Requisitos
- Apache Jmeter 
- Interprete Java [JDK](https://www.oracle.com/co/java/technologies/downloads/#jdk17-windows) 
![img_1.png](https://github.com/andresralo/api_automation_testing/blob/main/img/img_1.png)
- Variable de entrono JAVA_HOME

## Ejecutando JMeter

Inicia Apache Jmeter ingresando a la carpeta donde se almaceno la [descarga](#https://jmeter.apache.org/download_jmeter.cgi) en el path ...\apache-jmeter-5.5\bin selecciona el archivo `jmeter.bat` o `jmeter.sh`.
![img_2.png](https://github.com/andresralo/api_automation_testing/blob/main/img/img_2.png)


![img_3.png](https://github.com/andresralo/api_automation_testing/blob/main/img/img_3.png)
- El recuadro amarillo muestra una imagen de escobilla el cual  funciona como limpiador de resultados.
- Dirijase al recuadro rojo para observar resultados de las peticiones enviadas.
- En los recuadros blancos puede identificar las validaciones realizadas en las respuestas de las diferentes peticiones de acuerdo a su respuesta esperada.


