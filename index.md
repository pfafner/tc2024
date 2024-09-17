# Teoría de la Computación 2024

Este es un curso introductorio a la teoría de la computación, la cual se ocupa de determinar cuáles problemas pueden ser resueltos computacionalmente y con qué eficiencia, así como de entender el límite entre los problemas computables y los no-computables, y clasificarlos de acuerdo a su simpleza o dificultad.  

El curso inicia con el estudio de distintos modelos de cómputo, como los autómatas finitos (que son los más sencillos), y sus diferentes tipos y aplicaciones; las máquinas de Turing (que son las computadoras usuales de hoy en día) y las computadoras cuánticas (cuyo funcionamiento no es digital). Una vez formulado un modelo de computación, nos interesa conocer la cantidad de recursos computacionales que es necesario utilizar para resolver un problema. El primero de estos recursos es el tiempo: cuántos pasos o cuántas acciones debemos realizar para resolver el problema. También son importantes el espacio ocupado, la necesidad de utilizar una fuente de números aleatorios, la posibilidad de resolver subproblemas en paralelo, entre otros.

La formalización de un modelo computacional como objeto matemático permite expresar de manera precisa preguntas sobre problemas o algoritmos. En particular, si L es un problema. ¿Puede L ser resuelto por un algoritmo? ¿Puede ser L resuelto de manera eficiente? ¿Cómo podemos construir un algoritmo eficiente para L? ¿Es L un problema para el cual no existe un algoritmo que lo resuelva? Contestaremos a algunas de estas preguntas, mientras que otras se verán en los cursos de Lógica Matemática y en Análisis de Algoritmos.


# Prerrequisitos

Se recomienda que los estudiantes antes del curso estén habituados con los siguientes temas:
* Álgebra lineal (matricial).
* Matemática discreta (conteo, permutaciones, divisibilidad, congruencias).
* Grafos (representaciones, propiedades, algoritmos).
* Cálculo (funciones, límites, derivadas).
* Estructuras y algoritmos (pilas y colas, árboles, grafos).

Bastará con haber cursado una materia de cálculo y una de mátemática discreta. En el caso de programación, conviene conocer muy bien los temas de estructuas de datos y algoritmos.

El curso tiene una carga fuerte en el tema de matemática y estructuras abstractas. Cuando sea conveniente, dedicaremos una parte del curso a cubrir algunos prerrequisitos necesarios en los temas.


# Programa del curso
<div id='id-programa'/>

[Programa del curso](programa/Programa-tc2024.pdf){:target="_blank"}


### Horario
<div id='id-horario'/>

* Lunes de 17:20 a 19:40 G-205, y Miércoles de 19:00 a 20:35 G-205.

### Office Hours
<div id='id-office'/>

* Viernes de 18:00 a 19:00.

# Material del curso
<div id='id-material'/>

**No.**  | **Fecha**    | **Tópicos**                                                               | **Recursos**
-------- | ------------ | ------------------------------------------------------------------------- |  ---------------
01       | 03.07.2024   | Introducción al curso. Aspectos generales de la teoría de la computación. <br/> [Aula 01](aulas/Aula01.pdf){:target="_blank"} | Hopcroft-Ullman, sección 1.1 
02       | 08.07.2024   | Autómatas Finitos Deterministas (AFD). Tabla de transiciones. [Aula 02a](aulas/Aula02a.pdf){:target="_blank"} [Aula 02b](aulas/Aula02b.pdf){:target="_blank"} | Hopcroft-Ullman, secciones 2.1, 2.2 
03       | 10.07.2024   | Operaciones con lenguajes. Expresiones regulares (*regexp*). Abreviaturas para regexp. [Aula 03a](aulas/Aula03a.pdf){:target="_blank"} [Aula 03b](aulas/Aula03b.pdf){:target="_blank"} | Hopcroft-Ullman, Sección 3.1 <br/> [regextutorials.com](http://regextutorials.com/index.html){:target="_blank"}
L1       | 15.07.2024   |  |  [Lab 01](labs/Lab01.pdf){:target="_blank"}
04       | 17.07.2024   | Función de transición extendida. Configuraciones y derivaciones. [Aula 04](aulas/Aula04.pdf){:target="_blank"} | Hopcroft-Ullman, Sección 2.2 
05       | 24.07.2024   | Autómatas Finitos No Deterministas (AFN). [Aula 05](aulas/Aula05.pdf){:target="_blank"} | Hopcroft-Ullman, Sección 2.3 
06       | 29.07.2024   | Conversión de AFN a AFD: Construcción de subconjuntos. | Hopcroft-Ullman, Sección 2.5  
L2       | 29.07.2024   |  |  [Lab 02](labs/Lab02.pdf){:target="_blank"}
07       | 31.07.2024   | Conversión de Regexp a AFN: Algoritmo de Thompson. Algoritmo de Glushkov. [Aula 06a](aulas/Aula06a.pdf){:target="_blank"} [Aula 06b](aulas/Aula06b.pdf){:target="_blank"} | Hopcroft-Ullman, Sección 3.2 
L3       | 05.08.2024   |  |  [Lab 03](labs/Lab03.pdf){:target="_blank"}
08       | 05.08.2024   | Conversión de AFN a Regexp: Algoritmo de Reducción. | Hopcroft-Ullman, Sección 3.2 
09       | 07.08.2024   | Conversión de AFN a Regexp: Método de Arden. [Aula 07](aulas/Aula07.pdf){:target="_blank"} | Hopcroft-Ullman, Sección 3.4 
10       | 14.08.2024   | Propiedades de decisión. Producto de autómatas. [Aula 08](aulas/Aula08.pdf){:target="_blank"} | Hopcroft-Ullman, Sección 3.4 
11       | 19.08.2024   | Minimización de autómatas: Algoritmo de Hopcroft. [Aula 09](aulas/Aula09.pdf){:target="_blank"} | Hopcroft-Ullman, Sección 3.4 
L4       | 19.08.2024   |  |  [Lab 04](labs/Lab04.pdf){:target="_blank"}
12       | 21.08.2024   | Lema de Bombeo (*Pumping Lemma*). <br/> [Aula 10](aulas/Aula10.pdf){:target="_blank"} | Hopcroft-Ullman, Sección 3.4 
C1       | 26.08.2024   | Corto 1.  |  [Corto 01](cortos/Corto01.pdf){:target="_blank"}
13       | 28.08.2024   | Gramáticas libres del contexto.  | Hopcroft-Ullman, Sección 4.1 
15       | 18.09.2024   | Entrega proyecto 1.  | 


# Lecturas complementarias
### (Autores: T. Gálvez, B. Pojoy, P. Mejía y A. Reyes-Figueroa, 2022).
<div id='id-notas'/>

**No.**  | **Fecha**    | **Tópicos**                                                          | **Recursos**
-------- | ------------ | -------------------------------------------------------------------- |  -------------------------------------
01       | 31.07.2024   | Lectura 1 - Expresiones regulares y AFNs.                            | [Lectura 1](lectures/Lectura01.pdf){:target="_blank"}
02       | 31.07.2024   | Lectura 2 - Conversión de AFNs as AFDs.                              | [Lectura 2](lectures/Lectura02.pdf){:target="_blank"}
03       | 19.08.2024   | Lectura 3 - Algoritmo de minimización.                               | [Lectura 3](lectures/Lectura03.pdf){:target="_blank"}


# Proyectos
<div id='id-proyectos'/>

En el curso se desarrollarán tres proyectos.

## Primer Proyecto 

  **No.**  | **Fecha**    | **Tópicos**                                                     | **Recursos**
  -------- | ------------ | --------------------------------------------------------------- |  ---------------------
  1        | 14.08.2024   | Proyecto 1 - Algoritmos sobre AFDs, AFNs y *regexp*.            | [Proyecto 1](proyectos/Proyecto1.pdf){:target="_blank"} <br/> **Fecha de Entrega: 16-20 septiembre.**
  2        | 18.09.2024   | Presentación y revisión del proyecto.
  3        | 20.09.2024   | Entrega del reporte final.

## Horarios presentación Primer Proyecto

**Hora**     | **Equipo**   
------------ | ----------------------------
17:20-17:35  | Grupo 4
17:35-17:50  | Triple Impacto
17:50-18:05  | Los Chepitos
18:10-18:25  | Automata Masters
18:40-18:55  | Grupo 6 
19:00-19:15  | Autómatas Unidos
19:15-19:30  | Grupo 9
19:30-19:45  | Grupo 3
19:45-20:00  | Grupo 8

  
  
# Referencias
<div id='id-ref'/> 

### Textos:

* [J. Hopcroft, R. Motwani, J. Ullman (2006). *Automata Theory, Languages and Computation*.](http://library.lol/main/CAC409C1878AC487AF3A39687C924FFC){:target="_blank"}

* [J. Hopcroft, R. Motwani, J. Ullman (2007). *Teoría de autómatas, lenguajes y computación*.](libros/Hopcroft_Ullman.pdf){:target="_blank"}

### Referencias adicionales:

* [H. Lewis, C. Papadimitriou (1998). *Elements of the Theory of Computation*.](http://library.lol/main/586BEB94A1648CF624F74496477E92DB){:target="_blank"}

* [J. G. Brookshear (1988). *Theory of Computation: Formal Languages, Automata, and Complexity*.](http://library.lol/main/EE4EB25060E76527E13F904C99DE2D98){:target="_blank"}

* [J. G. Brookshear (1993). *Teoría de la Computación, Lenguajes Formales, Autómatas y Complejidad*.](libros/Brookshear.djvu){:target="_blank"}

* [R. de Castro Korgi (2004). *Teoría de la Computación, Lenguajes Autómatas, Gramáticas*.](http://library.lol/main/60501AE7549BF7B67BB11709240CE5B7){:target="_blank"}

* [E. Gaudioso Vásquez *et al.* (2017). *Introducción a la Teoría de Autómatas, Gramáticas y Lenguajes*.](http://library.lol/main/7B969A8129A16B2F3679F4D4A20FFF5D){:target="_blank"}

* [H. Pedrycz (2022). *Automata Theory and Formal Languages*.](http://library.lol/main/AEC2FE8B00CE16488082B14183D31727){:target="_blank"}

### Referencias avanzadas:

* [C. Papadimitriou, K. Steiglitz (1994). *Computational Complexity*.](http://library.lol/main/2E57188472ACBBBB8B5860A1327FBA94){:target="_blank"}

---
