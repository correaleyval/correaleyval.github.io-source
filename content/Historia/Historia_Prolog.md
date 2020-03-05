Title: Historia de Prolog
Tags: historia, prolog
Date: 2020-03-04 20:07
DatePrev: 2020-03-04
Slug: historia-prolog
Subtitle: Historia de Prolog
Keywords: historia, prolog
Featured_Image: images/featured_images/prolog.png
readingTime: 3
Social_Media_Description: El objetivo de este trabajo es desarrollar un corrector ortográfico para detección de errores por palabras utilizando métodos estadísticos para ordenar las sugerencias. En esta primera parte se muestra: carga de datos, detección de errores non-word, tokenización de las palabras.
IndexPreview: El lenguaje de programación Prolog tuvo sus inicios a principios de los años 70 en la Universidad de Aix-Marseille I ubicada en Marsella, Francia. Los profesores Alain Colmerauer y Philippe Roussel se dieron a la tarea de realizar un proyecto que no tenía como objetivo la implementación de un lenguaje de programación, sino el procesamiento de lenguajes naturales. 
Summary: El lenguaje de programación Prolog tuvo sus inicios a principios de los años 70 en la Universidad de Aix-Marseille I ubicada en Marsella, Francia. Los profesores Alain Colmerauer y Philippe Roussel se dieron a la tarea de realizar un proyecto que no tenía como objetivo la implementación de un lenguaje de programación, sino el procesamiento de lenguajes naturales. 

<img src="/images/featured_images/prolog.png">

El lenguaje de programación **Prolog** tuvo sus inicios a principios de los años 70 en la Universidad de Aix-Marseille I ubicada en Marsella, Francia. Los profesores **Alain Colmerauer** y **Philippe Roussel** se dieron a la tarea de realizar un proyecto que no tenía como objetivo la implementación de un lenguaje de programación, sino el *procesamiento de lenguajes naturales*. **Alain Colmerauer** y **Robert Pasero** trabajaban en la parte del procesado del lenguaje natural y **Jean Trudel** y **Philippe Roussel** en la parte de deducción e inferencia del sistema. Interesado por el método de resolución SL, **Trudel** persuadió a **Robert Kowalski** para que se uniera al proyecto, dando lugar a una versión preliminar del lenguaje **Prolog** a finales de 1971 y apareciendo la versión definitiva en 1972. Esta primera versión de Prolog fue programada en ALGOL W.

En sus inicios se trataba de un lenguaje totalmente interpretado, no fué hasta el año 1983 que **David H.D. Warren** desarrolló un compilador capaz de traducir **Prolog** en un conjunto de instrucciones de una máquina abstracta denominada **Warren Abstract Machine (WAM)**. Desde entonces Prolog se convirtió en un lenguaje semi-interpretado.

Al principio Prolog era un lenguaje de uso reducido, posteriormente con la aparición de intérpretes para microordenadores de 8 bits (ej: micro-PROLOG) y para ordenadores domésticos de 16 bits (ej: Turbo Prolog de Borland, entre otros muchos) a lo largo de la década de 1980 contribuyó notablemente a su popularización. Otro importante factor en su difusión fue la adopción del mismo para el desarrollo del proyecto de la quinta generación de computadoras a principios de la década de los 80, en cuyo contexto se desarrolló la implementación paralelizada del lenguaje llamada KL1 y del que deriva parte del desarrollo moderno de Prolog.

Las primeras versiones del lenguaje diferían, en sus diferentes implementaciones, en muchos aspectos de sus sintaxis, empleándose mayormente como forma normalizada el dialecto propuesto por la Universidad de Edimburgo, hasta que en 1995 se estableció un estándar ISO (ISO/IEC 13211-1), llamado ISO-Prolog.

Prolog se enmarca en el paradigma de los lenguajes lógicos y declarativos, lo que lo diferencia enormemente de otros lenguajes más populares  de la época tales como Fortran, Pascal, C o Java, y de los derivados modernos de estos lenguajes.

En los lenguajes de programación antes mencionados, las instrucciones se ejecutan normalmente en orden secuencial, es decir, una a continuación de otra, en el mismo orden en que están escritas, que sólo varía cuando se alcanza una instrucción de control (un bucle, una instrucción condicional o una transferencia).

Los programas en Prolog se componen de cláusulas de Horn que constituyen reglas del tipo "modus ponendo ponens", es decir, "Si es verdad el antecedente, entonces es verdad el consecuente". No obstante, la forma de escribir las cláusulas de Horn es al contrario de lo habitual. Primero se escribe el consecuente y luego el antecedente. El antecedente puede ser una conjunción de condiciones que se denomina secuencia de objetivos. Cada objetivo se separa con una coma y puede considerarse similar a una instrucción o llamada a procedimiento de los lenguajes imperativos. En Prolog no existen instrucciones de control. Su ejecución se basa en dos conceptos: la unificación y el backtracking.

Gracias a la unificación, cada objetivo determina un subconjunto de cláusulas susceptibles de ser ejecutadas. Cada una de ellas se denomina punto de elección. Prolog selecciona el primer punto de elección y sigue ejecutando el programa hasta determinar si el objetivo es verdadero o falso.

En caso de ser falso entra en juego el backtracking, que consiste en deshacer todo lo ejecutado situando el programa en el mismo estado en el que estaba justo antes de llegar al punto de elección. Entonces se toma el siguiente punto de elección que estaba pendiente y se repite de nuevo el proceso. Todos los objetivos terminan su ejecución bien en éxito ("verdadero"), bien en fracaso ("falso").

### Referencias

---

[Wikipedia: https://es.wikipedia.org/wiki/Prolog](https://es.wikipedia.org/wiki/Prolog)

[Manual Prolog de la Universidad Autónoma de baja California](http://fcqi.tij.uabc.mx/usuarios/ardiaz/material/manual_lab_prolog.pdf)

[Bratko. Ivan. Prolog programming for artificial intelligence](https://silp.iiita.ac.in/wp-content/uploads/PROLOG.pdf)
