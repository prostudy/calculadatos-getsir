<img src="http://calculadatos.getsir.mx/descargas/images/logo.png" width="50%">
<hr>
**CalculaDato**s es una aplicación que permite al usuario conocer a través de una estimación el valor en pesos de los datos personales, para obtener este resultado se tomo como base la fórmula propuesta por el INAI con algunas modificaciones con el objeto de considerar una clasificación más específica basada en la sensibilidad de los datos personales.

Cuando el usuario realiza un cálculo además de la estimación en pesos obtendrá un listado con los posibles daños que pudiera sufrir en caso de alguna vulneración, relacionada con los tipos de datos seleccionados previamente y asociados a estos daños se le proporcionará un conjunto de tips para mejorar la forma en que proteje los datos personales. El resultado obtenido del cálculo tiene la opción para poder ser compartido en las redes sociales o medios que determine el usuario como una forma de difusión para la aplicación.

Para lograr un mayor uso de la app y a su vez reforzar la concientización en protección de los datos personales CalculaDatos proporciona al usuario una sección de Retos donde él podrá dar solución a un conjunto de desafíos clasificados en tres tipos, uno donde podrá estimar el valor de los datos personales a partir de un listado proporcionado, segundo donde a partir de un monto total, él tendrá que determinar la combinación de datos que proporciona el resultado y como tercer tipo el usuario deberá dar respuesta a preguntas sobre definiciones y conceptos relacionados con la protección de los datos personales. Para el soporte a esta sección fue desarrollada una base de datos con 50 retos, clasificados y ponderados por niveles, estos son otorgados al usuario una vez que va dando respuesta y reuniendo determinada puntuación. Los niveles que puede obtener el usuario son: aprendiz, ciudadano consciente y agente del INAI y estos podrán ser consultados en todo momento por el usuario en el menú de Perfil donde se le brindaran datos sobre su puntuación y logros obtenidos. El usuario tiene en todo momento dehabiliar la opción que le permita poder reintentar los retos hasta que encuentre la respuesta correcta.

De forma adicional la aplicación cuenta con una sección de Conoce+ donde el usuario podrá consultar diferentes conceptos y definiciones importantes en materia de datos personales, esta base de datos contiene 36 elementos.

 Los recursos donde se encuentra información detallada de la aplicación y su desarrollo se encuentran en:

> ##### Página oficial de la aplicación: <a href="http://calculadatos.getsir.mx/" target="_blank">CalculaDatos</a>

> #####  Video de la aplicación: <a href="http://calculadatos.getsir.mx/descargas/CalculaDatos-Video.mp4" target="_blank">Video</a>
Audio:
 Drops of H2O ( The Filtered Water Treatment ) by J.Lang (c) 2012 Licensed under a Creative Commons Attribution (3.0) license. http://ccmixter.org/files/djlang59/37792 Ft: Airtone
 

> #####  Presentación CalculaDatos: <a href="#" target="_blank">Presentación</a>

> #####  Repositorio GitHub: <a href="https://github.com/prostudy/calculadatos-getsir" target="_blank">GitHub</a>

> #####  Manual usuario: <a href="https://github.com/prostudy/calculadatos-getsir/wiki/Manual-de-usuario" target="_blank"> Manual de usuario</a>

> #####  Manual para el desarrollador: <a href="https://github.com/prostudy/calculadatos-getsir/wiki/Manual-para-el-desarrollador" target="_blank"> Manual para el desarrollador</a>

CalculaDatos es una aplicación que en versiones avanzadas podría mejorar en un futuro para reforzar en el titular la protección de los datos personales, mediante la estimación del riesgo, considerado que tan expuesto esta el titular con relacion al tipo de datos personales que proporciona (valor en $) y los lugares donde los comparte o deposita, esto permitirá generar mayor conciencia para que los titulares identifiquen todos los posibles lugares donde se encuentran sus datos y fomentará el uso de sus derechos ARCO para reducir su nivel de exposición.
<hr>
###Autores

M.A. Miriam J. Padilla Espinosa<br/>
Ing. Oscar J. Gascon Busio (PMP)®
<hr>

##Instalación rápida

<p>Para poder probar el proyecto se proponen 3 alternativas, las dos primeras son una forma de instalación rápida, la tercera necesita mayor configuración</p>
<ol>
<li>Probar el proyecto instalando un archivo apk sobre un dispositivo con sistema operativo Android 4.2+.</li>
<li>Probar el proyecto ejecutando el entorno de desarrollo Xcode.</li>
<li>Probar el proyecto por medio de un navegador web en una PC o Mac.</li>
</ol>

<p>Estos tres procesos estan detallados en el<a href="https://github.com/prostudy/calculadatos-getsir/wiki/Manual-para-el-desarrollador" target="_blank"> Manual para el desarrollador</a></p>


<p>Aquí se detalla el primer caso, <b>instalar un archivo apk sobre un dispositivo con sistema operativo Android 4.2+:</b></p>

<p>1.- Ingresar a la página oficial de la aplicación: http://calculadatos.getsir.mx/</p>

<p>2.- Descargar el paquete de instalación, para lo cual hay que ir a la parte inferior de la pantalla y en la sección de descargas ubicar la opción:  <b>Paquete de instalación para plataformas Android.</b><br/>
Esta es la url directa: http://calculadatos.getsir.mx/descargas/android-debug.apk</p>

<p>Se puede ingresar directamente desde el dispositivo y descargar el paquete.</p>

<p>3.- Ingresar a la Configuración del dispositivo y en la parte de seguridad  permitir la instalación de aplicaciones que no provienen de la tienda de aplicaciones, como se muestra en la siguiente imagen:</p>
<img src="http://calculadatos.getsir.mx/descargas/images/origenesDesconocidos.png" width="40%"/>


<p>4.- Instalar la aplicación.</p>

<hr>

###* Alternativas para probar la aplicación dentro de Android Studio y Xcode

<p>Si se desea un mayor control sobre la instalación, es posible utilizar los archivos de la carpeta <a href="https://github.com/prostudy/calculadatos-getsir/tree/master/platforms" target="_blank">platforms.</a></p>
<p>Estos archivos pueden importarse hacia <a href="https://developer.android.com/intl/es/sdk/index.html" target="_blank">Android Studio</a> o hacia <a href="https://developer.apple.com/xcode/" target="_blank">Xcode</a> segun la plataforma.</p>

### Instalación Avanzada.
Para compilar el proyecto sin utilizar Android Studio o Xcode	es necesario	configurar	el	ambiente	de	trabajo,	para	lo	cual	se	necesitará	instalar	algunos	paquetes.


Nota:	Se	considera	que	el	ambiente	de	trabajo	será	un	sistema	operativo	Mac	OS	X.	Sin	embargo,	
también	puede	ejecutarse	esta	guía	sobre	sistemas	operativos	Windows.


 1. Instalar	Node	JS.-		Ingresar	a	la	página	oficial	de	Node	JS	https://nodejs.org/en/ y	
descargar	la	versión	estable.
 2. Instalar	cordova	y	ionic	framework.- Utilizando	una	Terminal	ejecutar	el	siguiente	
comando:

> $ npm install -g cordova ionic

Se	deben	tener	permisos	de	administrador	para	instalar	estos	paquetes.

Para	mayor	información	consultar	la	página	oficial	de	Ionic	Framework	
http://ionicframework.com/getting-started/

 3.- Clonar	el	repositorio		en	donde	se	encuentra	el	proyecto	o	en	su	defecto	
descargar	el	zip.	 https://github.com/prostudy/calculadatos-getsir.git

 4.- Ingresar	por	medio	de	una Terminal	al	directorio	en	donde	han	sido	extraídos	los	archivos	
de	la	aplicación y ejecutar el comando:

> @CalculaDatosDev> ionic build android

5.- Al terminar de compilar, se muestra un mensaje indicando la ruta donde se generó el archivo .apk:

>BUILD SUCCESSFUL
<br>Total time: 20.075 secs
<br>Built the following apk(s):
    /CalculaDatosDev/platforms/android/build/outputs/apk/android-debug.apk
    <br>BUILD SUCCESSFUL

6.- Ahora se puede instalar la aplicación copiando este archivo a un dispositivo Android, como se indica en el paso número 3 de la Instalación rápida.

Nota: En caso de ser necesario consultar al equipo de desarrollo.

Para más información: http://ionicframework.com/docs/guide/installation.html
<hr>

###Screenshots

<img src="http://calculadatos.getsir.mx/descargas/images/Pantalla de la Calculadora.png" width="35%"/>
<img src="http://calculadatos.getsir.mx/descargas/images/Pantalla de Principios de usuario.png" width="35%"/>
<img src="http://calculadatos.getsir.mx/descargas/images/Pantalla de Resultado de la estimacion.png" width="35%"/>
<img src="http://calculadatos.getsir.mx/descargas/images/Pantalla para ingresa un alias..png" width="35%"/>
<img src="http://calculadatos.getsir.mx/descargas/images/Pantalla de retos..png" width="35%"/>
<img src="http://calculadatos.getsir.mx/descargas/images/Pantalla de avance de nivel..png" width="35%"/>
<img src="http://calculadatos.getsir.mx/descargas/images/Pantalla de Conoce +.png" width="35%"/>
<img src="http://calculadatos.getsir.mx/descargas/images/Pantallas de configuracion.png" width="35%"/>


###LICENSE
CalculaDatos is licensed under GNU GENERAL PUBLIC LICENSE. For more information, see the LICENSE file in this repository.
