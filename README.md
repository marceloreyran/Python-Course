### 1.1. Introducción y objetivos
- Python se ha convertido en uno de los lenguajes de programación más populares
debido a su potencia y su facilidad para aprenderlo. En este tema pondremos en
contexto qué es Python y qué características han hecho que este lenguaje sea uno de
los más utilizados, sobre todo en campos de inteligencia artificial o análisis de datos.
Además, en este tema prepararemos nuestros equipos para poder desarrollar en
- Python. Para ello, explicaremos cómo instalar las dos distribuciones más populares
dentro de Python y cómo instalar nuevos módulos en estas distribuciones para
aumentar el número de funcionalidades. Por último, describiremos diferentes
herramientas disponibles para desarrollar en este lenguaje y nos centraremos en
- Jupyter Notebook, que será el entorno de desarrollo que usaremos a lo largo del
curso. Los objetivos que trataremos son: 
1. Contextualizar Python desde su historia y sus características.
2.  Comprender el problema de las versiones que ha existido hasta este año.
3. Conocer los pasos para instalar Python en nuestro equipo.
4. Conocer las distintas herramientas existentes para programar en Python.
5. Comprender el entorno de desarrollo de Jupyter Notebook. 

### 1.2. ¿Qué es Python?
- Python es un lenguaje de propósito general que en los últimos años se ha ido
haciendo cada vez más popular en áreas como data science o la inteligencia artificial.
Contexto de Python
- Para entender un poco de dónde viene y por qué se ha vuelto tan popular, vamos a
repasar su historia y las características más importantes.
Historia
- Python fue creado en 1989 por Guido van Rossum. Guido empezó a implementar este
lenguaje como pasatiempo con el objetivo de que fuera fácil de usar y aprender, pero,
a la vez, que fuese un lenguaje potente.

- Van Rossum le dio el nombre de «Python» en homenaje al grupo Monty Python del
que era fan. Aunque su desarrollo empezó en 1989, la primera versión no se
publicaría hasta principios de 1991. Como hemos dicho, el objetivo principal de este lenguaje era que fuese fácil de entender, es decir, que el código que se escribiese. 
- Python fuese más legible que con otros lenguajes de la época como C++ o Java.
Para lograr este objetivo, el desarrollador Tim Peters creó el Zen de Python, que
define un conjunto de reglas que representan la filosofía de Python. Todos los
usuarios pueden acceder a este conjunto de reglas a través de un easter egg que se
introdujo en Python. Para verlo, solo tenemos que ejecutar la instrucción import this
en una terminal con Python.
- Siguiendo la filosofía propuesta en el Zen de Python, se creó una guía de estilo que
se encuentra descrita en el Python Enhancement Proposal, abreviado como PEP,
versión 8. Esta guía contiene las reglas de estilo que se aplicaron a la hora de
desarrollar Python para que se sigan en el desarrollo de nuevas aplicaciones.


### Ventajas de Python

- Python tiene varias propiedades que lo han convertido en un lenguaje muy potente
y fácil de aprender. Estas propiedades son las siguientes:
- Tipado dinámico: Python no necesita que definamos el tipo de las variables
cuando las inicializamos como pasa, por ejemplo, en Java o C. Cuando inicializamos
una variable Python le asigna el tipo del valor que le estamos asignando. Incluso,
durante la ejecución, una misma variable podría contener valores con distintos
tipos. Esta propiedad hace que sea más sencillo aprender a usarlo, aunque hace
que sea más difícil detectar errores asociados con los tipos de datos.
- Lenguaje multiparadigma: Python permite aplicar diferentes paradigmas de
programación como son la programación orientada a objetos, como Java o C++,
programación imperativa, como C, o programación funcional, como Haskell.
- Interpretado/scripts: otra ventaja es que podemos ejecutar Python de forma
interpretada o usando scripts. Es decir, puedo abrir una consola de Python y
escribir y ejecutar las instrucciones una a una o, por otro lado, puedo crear un
fichero que almacene todo el programa.
- Extensible: por último, Python cuenta con una gran cantidad de módulos y
librerías que podemos instalar para incluir nuevas funcionalidades. Sin embargo,
como Python esta implementado usando C++, podemos crear nuevos módulos en
C++ e incluirlo en Python haciendo que el lenguaje sea extensible a nuevos
módulos.
### Versiones en Python
- Uno de los problemas que tenía una persona que se inicializaba en Python era saber
qué versión tenía que instalar, ya que hasta finales de diciembre de 2019 existían dos versiones activas.

- Como explicamos al principio, la primera versión de Python se publicó en 1991. Desde
entonces se han publicado varias versiones que han seguido siendo más o menos
retrocompatibles. Es decir, podía usar esas versiones en programas que había creado
en versiones anteriores.
- Sin embargo, a finales de 2008 se iba a publicar la versión 3.0. Esta nueva versión era
un cambio radical con respecto las predecesoras y esto hacía que no fuera compatible
con las versiones anteriores de Python. Por este motivo, se publicó la versión 2.6
como soporte para los desarrollos de la versión 2. En la versión 2.6 se incluyeron
nuevas funcionalidades de la versión 3, pero adaptadas a la versión 2. Desde ese
momento Python contaba con 2 versiones y las novedades las tenían que duplicar en
ambas. Por ejemplo, en 2010 publicaron la versión 3.1 y la 2.7 que incluía las nuevas
- funcionalidades, pero adaptadas a la versión 2.
Sin embargo, desde el equipo de Python siempre han explicado que las versiones 2.6
o 2.7 eran un parche y que no iban a ser versiones funcionales en un futuro. Este
hecho se hizo oficial en enero de 2020 cuando se decidió que la versión 2.7 quedaba
descontinuada y que a partir de entonces solo se publicarían nuevas funcionalidades
para la versión 3.

### 1.3. Instalación

- Distribución básica Python
La primera opción que podemos instalar es una distribución básica de Python. Esta
distribución solo incluye los módulos principales que hay en Python. A continuación,
veremos los pasos para instalarlo.
Descargar Python
- La primera opción de instalación es únicamente los módulos principales del lenguaje.
En esta opción tendremos que instalar nuevos módulos si queremos ampliar las
funcionalidades de Python. Para poder descargarnos esta versión, deberemos
acceder a la sección de descargas de la página principal de Python.

- En esta página tenemos una opción para instalar la última versión estable de Python.
En nuestro caso, es la versión 3.8. Para descargarlo, hacemos clic en el botón
download Python 3.X y automáticamente empezará la descarga del paquete de
instalación.
- Instalación Python
Una vez que tenemos el paquete de instalación descargado, podemos iniciar el proceso
de instalación. Para ello, ejecutaremos el fichero python-3.X.exe que hemos ejecutado y,
a continuación, se nos abrirá el asistente de configuración.