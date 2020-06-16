# Informe-3

#  ANÁLISIS DE NODOS.

## OBJETIVOS

Comprobar experimentalmente el Análisis de Nodos.

**Objetivos específicos:** 
 - Identificar los Nodos del circuito  
 -  Demostrar si se cumple el análisis de Nodos tanto en los valores analíticos y en los
   simulados.    
 - Comprobar los resultados y los datos necesarios  del  circuito    
   propuesto, demostrando el análisis de nodos.    
 - Comparar los resultados obtenidos tanto del  análisis teórico como
   simulado y sacar conclusiones.       
       
## MARCO TEÓRICO

El inicio de este estudio no puede darse si no se tiene el conocimiento necesario de las leyes de Kirchhoff tanto la de corriente como la de voltaje de la misma forma la ley de ohm, ya que estas son un pilar fundamental para el análisis de circuitos y ayudan con nuevos métodos que lo facilitan aún más como, en este caso, el análisis de mallas.

Antes de poder dar una definición de malla se debe conocer lo que es una trayectoria, trayectoria cerrada o lazo.

“Un punto en el cual dos o más elementos tienen una conexión común se llama nodo” (William H. Hayt, Kemmerly, & Durbin, 2012). Es una fácil definición de nodo, en otras palabras, es donde se conectan varios elementos.

“Si no encontramos un nodo más de una vez, entonces el conjunto de nodos y elementos a través de los cuales pasamos se define como una trayectoria” (William H. Hayt, Kemmerly, & Durbin, 2012). Para mejor entendimiento es el sentido que puede tomar un circuito. Claro pasando por los nodos correspondientes. La diferencia entre trayectoria y trayectoria cerrada es que esta ultima termina en el mismo lugar done comienza ya también se la conoce como lazo.

Ya con todo este conocimiento y junto a la ley de Kirchhoff de voltajes podemos dar inicio al conocimiento del análisis de mayas.

**Análisis de mallas**

Así como la ley de Kirchhoff de corriente se utiliza en los nodos para encontrar los valores que se necesitan, pues con la ley de voltajes de Kirchhoff se puede hacer algo muy parecido solo que en este en vez de utilizar nodos utilizamos lazos, y el hecho de hacer eso se lo conoce como Análisis de mallas, se tiene como restricción el poder hacerse solo en circuitos planos, pero comparado con el análisis de nodos este resulta mas complicado en determinados casos, se considera circuito plano el que al representarse en 2d no se superponen ramas, siempre se tienen que analizar bastante bien los circuitos porque a veces pueden parecer no planos y si serlo.

<section>
      <div class="container mt-5 mb-5">
        <img src="img/lab1.PNG"
          alt=""
          height="150"
          style ="float-left ml-4"
        />           
   </div>
   </section>
   
*Ilustración 1,Ejemplos de circuitos planos y no planos.*


“La malla es una propiedad de un circuito de forma plana y no se define para un circuito de forma no plana, sino como un lazo que no contiene ningún otro lazo dentro de él” (William H. Hayt, Kemmerly, & Durbin, 2012). Puede confundir un poco que significa una malla al principio pero viendo un grafico se entiende bien, que quiere decir que si una trayectoria cerrada tiene una rama dentro de él, entonces, no se considera una malla, en cambio si esta libre de cualquier elemento dentro de la trayectoria cerrada entonces si se puede llamar malla.

 <section>
      <div class="container mt-5 mb-5">
        <img src="img/lab 2.PNG"
          alt=""
          height="150"
          style ="float-left ml-4"
        />           
   </div>
   </section>
   
*Ilustración 2, Circuito que no es y si es malla respectivamente.*

La forma de poder trabajar con las mallas es aplicando la LKV en dicha malla obteniendo ecuaciones para poder calcular los datos que nos falten, se puede hacer con todas las mallas y aplicar un sistema de ecuaciones para poder resolver las incógnitas. Al nombrar las mallas suelen acogerse al nombre de la intensidad de corriente que pasa por las ramas adyacentes.

# **DESCRIPCIÓN DE LOS EQUIPOS Y MATERIALES**

Descripción de los equipos y materiales**

**Fuente de voltaje C.D.** Es de donde conseguir electricidad para el circuito
<section>
      <div class="container mt-5 mb-5">
        <img src="img/lab3.PNG"
          alt=""
          height="98"
          style ="float-left ml-4"
        />           
   </div>
   </section> 
   
 *Ilustración 3, Fuente C.D*
   
**Multímetro digital**. Nos ayudara para poder hacer las mediciones de la practica

</section>
      <div class="container mt-5 mb-5">
        <img src="img/lab4.PNG"
          alt=""
          height="98"
          style ="float-left ml-4"
        />           
   </div>
   </section>


**Resistores** de 1kΩ, 2.2kΩ, 1.kΩ, 390Ω y 820Ω. Los utilizaremos para crear el circuito que vamos a medir

</section>
      <div class="container mt-5 mb-5">
        <img src="img/lab5.PNG"
          alt=""
          height="98"
          style ="float-left ml-4"
        />           
   </div>
   </section>

**Protoboard.** Es la base en la cual se va a formar el circuito con los elementos de este.
</section>
      <div class="container mt-5 mb-5">
        <img src="img/lab6.PNG"
          alt=""
          height="98"
          style ="float-left ml-4"
        />           
   </div>
   </section>
   

# **PROCEDIMIENTO**

Arme el circuito que se muestra en la figura 3.1.
</section>
      <div class="container mt-5 mb-5">
        <img src="https://cdn.glitch.com/a7d4561e-bb3e-4916-95fd-cc07aab571ec%2Fb55b21e87e81b79c1b8a18acf92e443f.jpg?v=1590115958949"
          alt=""
          height="200"
          style ="float-left ml-4"
        />           
   </div>
   </section>


Mida cada uno de los voltajes de nodo y anote los resultados en la tabla 3.1.
 3.5.3. Simule en el software Multisim, Proteus, o cualquier otro simulador, el circuito de la figura 3.1, obteniendo los valores de los voltajes de nodo. Anote los resultados en la tabla

***Tabla 3.1. Resultados obtenidos para el circuito de la figura 3.1.***
|NODO   |RESULTADOS ANALÍTICOS| RESULTADOS SIMULADOS|
|------------|-----------------|---------------------|
|**Nodo B**  |2.81[V]          |2.82[V]|
|**Nodo C**  |4.81[V]          |4.80[V]|
|**Nodo R**  |0[V]             |0[V]|


## **DIAGRAMAS**
</section>
      <div class="container mt-5 mb-5">
        <img src="img/lap10.PNG"
          alt=""
          height="300"
          style ="float-left ml-4"
        />           
   </div>
   </section>
   
## **MAPA DE VARIABLES**


   **Resistores**: de 1.8(kΩ), 2.2(kΩ), 1.5(kΩ), 470(Ω) y 3.90(kΩ). 
   
   **Fuentes**: de 12[V] y 8[V].
    
## **DESCRIPCIÓN**
Crear una cuenta de Tinkercad y generar la simulación de la practica 3


## **LISTA DE COMPONENTES**

 </section>
      <div class="container mt-5 mb-5">
        <img src="img/lab7.PNG"
          alt="listado de todos los componentes utilizados para el circuito"
          height="300"
          style ="float-left ml-4"
        />           
   </div>
   </section>
   


## **CONCLUSIONES**

Con esta práctica se pudo adquirir los conocimientos teóricos de lo que el abalisis de nodos,su tipo y su clasificación de acuerdo al circuito montado.

Deducimos según ley de Kirchhoff que expone que cuando en un circuito intervienen dos o más fuentes de voltaje, además de ramificaciones estamos en presencia de una red eléctrica. Para que resolvamos una red eléctrica es necesario realizar un proceso en el cual calculamos las tensiones que circulan por cada nodo.

El método del voltaje en los nodos es un método organizado para analizar un circuito, que está basado en la ley de Kirchhoff de la corriente.

Es muy importante conocer el flujo de corriente en un circuito electrico puesto que este analisis se basa en elflujo de corriente para poder plantear las ecuaciones basadas en las mismas.

Las leyes de Kirchhoff han sido una gran ayuda para la innovación tecnológica ya que han permitido medir con exactitud ciertas características eléctricas necesarias para que el invento funcione óptima mente.

## **RECOMENDACIONES**

Para mejorar un poco la forma de realizar los laboratorios, ayudaria el poder implementar un tiempo de desarrollo de las guias durante la hora de clase.

Para un comprension  total de todo lo impartido en fundamentos de circuitos electricos, las clases teoricas y los laboratorios podrian ir mas de la mano con los temas para que no existan confunciones a la hora de realizar cualquier tipo de actividad.


## **CRONOGRAMA**

 </section>
      <div class="container mt-5 mb-5">
        <img src="img/lab8.PNG"
          alt="Cronograma de actividades del informe"
          height="300"
          style ="float-left ml-4"
        />           
   </div>
   </section> 

  

# **BIBLIOGRÁFICA**

William H. Hayt, J., Kemmerly, J. E., & Durbin, S. M. (2012). Análisis de circuitos en ingenieria. Buffalo: Mc Graw Hill.


Ricárdez, A., Bastién Montoya, M., Hernández, B., & H. S., R. S. (2017). Estrategias para Resolver Problemas de Introducción a la Electrostática y Magnetostática. Ciudad de Mexico.


## **ANEXOS**

https://github.com/attoala/Informe-lab2/tree/master/anexos
