#JAVA

**Autor:** Gianni Fantelli

## 1. Introducción.

Java fue creado en 1991 por un equipo, liderado por James Gosling, llamado Sun Microsystems. Al principio, el proyecto
se llamó Oak pero, antes de su lanzamiento en 1995, pasó a llamarse Java. Estos nombres vinieron inspirados por el roble (oak)
que tenía a la vista James Gosling desde su ventana pero, debido a conflictos comerciales, decidieron usar el nombre Java
inspirado en el café del mismo nombre, proveniente de la isla de Java... un café muy popular entre los ingenieros del proyecto
durante las fases de desarrollo del mismo. Por eso, también, es que el logo oficial del lenguaje es el de una taza de café
humeante.

A lo largo de los años, Java ha ido implementando diferentes versiones, entre las que destacan: Java 5, que introdujo los genéricos
y anotaciones. Y Java 8, que añadió expresiones lambda y programación funcional. Las versiones más recientes se han concentrado,
sobre todo, en mejorar la gestión de memoria, seguridad y velocidad de ejecución.

En 2010, Oracle adquirió Sun Microsystems, pasando a ser la empresa desarrolladora principal del lenguaje. Desde entonces, 
Java se actualiza de manera regular con varias versiones y mejoras constantes. Pero el objetivo sigue siendo el mismo: desarrollar
un lenguaje único que sirva para ser ejecutado en diferentes plataformas sin necesidad de ser modificado.


## 2. Campo de Aplicación.

Java se utiliza principalmente en el desarrollo de aplicaciones empresariales, sistemas de backend y aplicaciones moviles.
Aunque también tiene su nicho dentro del mundo de los videojuegos, destacando nombres como Minecraft o The Binding of Isaac.
Gracias a su estabiliad, seguridad y capacidad para manejar grandes cantidades de datos y usuarios, es uno de los lenguajes
más utilizados en entornos profesionales y corporativos.

En *aplicaciones empresariales*, Java suele destacar para crear sistemas internos de gestión, plataformas bancarias y aplicaciones
que deben funcionar de manera estable durante muchos años. Por ejemplo, muchas entidades financieras usan sistemas basados en Java
para operaciones bancarias, pagos o bases de datos de clientes.

En el *desarrollo web y servidores*, Java es muy utilizado para el backend, es decir, la parte del software destinada a ejecutar
en servidores y gestionar la lógica de las aplicaciones web. Por ejemplo, grandes plataformas como LinkedIn o Netflix, han 
utilizado Java en diferentes partes de sus sistemas para gestionar datos y usuarios.

En *aplicaciones móviles* destaca el desarrollo de aplicaciones en el sistema operativo de Android, desarrollado actualmente por Google.
Aunque ahora también se usan otros lenguajes como Kotlin, todavía se pueden encontrar importantes aplicaciones desarrolladas
en Java. Por ejemplo: WhatsApp, una de las aplicaciones de mensajería más utilizadas del Mundo y desarrollada por Meta.


## 3. Tipado de Variables, paradigmas y tipo de ejecución.

Java es un lenguaje de tipado estático y fuerte. Esto significa que el tipo de cada variable debe declararse antes de utilizarla
y no puede cambiar durante la ejecución del programa. El compilador comprueba los tipos de datos antes de ejecutar el programa, lo
que ayuda a detectar errores en fases tempranas del desarrollo.

Además, es principalmente un lenguaje de programación orientado a objetos (POO). Esto implica que el código se organiza en clases
y objetos, permitiendo estructurar programas de forma modular y reutilizable. Entre sus paradigmas destacan:
-Orientación a objetos: uso de clases, objetos, herencia, encapsulación y polimorfismo.
-Imperativo: se ejecuta mediante instrucciones que indican paso a paso qué debe hacer el ordenador.
-Programación genérica: que permite crear clases y métodos reutilizables que funcionan con distintos tipos de datos.
-Elementos de programación funciona: desde las versiones más modernas del lenguaje, se pueden utilizar expresiones lambda. Las expresiones 
lambda son una forma de escribir funciones pequeñas y anónimas directamente dentro del código, permitiendo pasar un comportamiento
o lógica como si fuera un valor, haciendo el código más corto y fácil de leer. Además de permitir funciones más flexibles.

Java tiene un modelo de ejecución híbrido, ya que combina compilación e interpretación. El proceso es el siguiente. Primero,
el código fuente escrito se compila mediante el compilador javac. El resultado es un archivo de bytecode que, finalmente, es ejecutado
por la Maquina Virtual de Java (JVM). Gracias a este sistema, el mismo programa puede ejecutarse en distintos OS sin necesidad de
modificar el código, siempre que exista una JVM compatible. Convirtiendolo en uno de los mejores lenguajes para el desarrollo
multiplataforma.


## 4. IDEs para Java.

**IntelliJ Idea:** De la empresa JetBrains. Tiene dos modalidades. La Community Edition gratuita y de codigo abierto basada en Apache 2.0
y la Ultimate Edition, con licencia comercial.

Las características destacables de IntelliJ Idea son:
-Autocompletado inteligente de código.
-Herramientas avanzadas de refactorización.
-Integración con sistemas de control de versiones como Git.
-Soporte para frameworks populares como Spring.
Esto la convierte en una de las IDEs más utilizadas en entornos profesionales.

**Eclipse:** De la empresa Eclipse Foundation, solo tiene la Eclipse Public License de software libre.

Las características destacables de Eclipse son:
-Sistema basado en plugins que permiten añadir nuevas funcionalidades.
-Compatible con muchos lenguajes, además de Java.
Es una de las IDEs mas utilizadas de Java, sobre todo para entornos educativos y proyectos empresariales.

**NetBeans:** de Apache Software Foundation, con licencia Apache 2.0 (igual que IntelliJ Idea) de software libre.

Las características destacables de NetBeans son:
-Muy completo y fácil de usar.
-Buen soporte para Java SE, JavaFX y desarrollo web.
-Integración directa con herramientas como Maven y Gradle.
-Amigable tanto para principiantes como para desarrolladores profesionales con experiencia previa.


## 5. Frameworks para Java.

Los Frameworks son conjuntos de herramientas y bibliotecas que facilitan el desarrollo de aplicaciones al proporcionar estructuras
y funcionalidades ya implementadas.

Las principales y más conocidas son:

**Spring:** Desarrollada por VMware y la comunidad de Spring, tiene licencia Apache License 2.0

Las características destacables son:
-Facilita la creación de APIs y aplicaciones web.
-Utiliza el principio de inyección de dependencias, que mejora la organización del código.
Esto lo convierte en uno de los frameworks más utilizados en desarrollo de backend con java, muy utilizado para desarrollar microservicios
y aplicaciones empresariales.

**Hibernate:** desarrollada por Red Hat, con licencia GNU Lesser General Public License (LGPL)

Las características más destacables son:
-Framework de mapeo objeto-relacional (ORM).
-Permite trabajar con bases de datos utilizando objetos Java en lugar de consultas SQL complejas.
-Reduce la cantidad de código necesario para acceder a datos.
Muy usado en aplicaciones empresariales.

**Jakarta EE:** desarrollado por Eclipse Foundation con diferentes licencias de código abierto según las especificaciones.

Las características más destacables son:
-Conjunto de especificaciones para desarrollar aplicaciones empresariales en Java.
-Herramientas para trabajar en sevlets, APIs web y bases de datos.
Muy utilizado en sistemas corporativos de gran tamaño.
