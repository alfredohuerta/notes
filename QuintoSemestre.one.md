---
id: 8owmqc0denfohpj2sglf601
title: Apuntes Algoritmos
desc: ''
updated: 1676501818869
created: 1676501767608
---
## Antecedentes

### Algoritmos:
Es un procedimiento para resolver un problema particular en un número finito de pasos para una entrada definida.

#### Método de implementación
1. Recursión: 
Se llama a sí mismo una y otra vez hasta que se logra una condición base
2. Iteración: 
Usan bucles y/o estructuras de datos como pilas, colas para resolver cualquier problema.
3. Exacto: 
Algoritmos cepaces de encontroar una solución óptima para cualquier problema
4. Aproximado:
Se utilizan para todos aquellos problemas donde no es posible encontrar la solución más optimizada)
5. Algoritmos en serie o en paralelo o distribuídos
- > Los algoritmos que encuentran el resultado como un resultado medio de los sobresultados de un problema.
- > Cada solución recursiva puede implementarse cmo una solución iterativa y viceversa.
#### Métodos de diseño
1. Divide y vencerás:
Es un enfoque de arriba hacia abajo.
    * Divide un problema original en un conjunto de subproblemas.
    * Resuelve cada subproblema individualmente, de forma recursiva.
    * Combina la solución de los subproblemas.
2. Programación dinámica:
Es un enfoque de abajo hacia arriba, resolvemos todos los pequeños problemas posibles y luego los combinamos para obtener soluciones para problemas mayores
3. Algoritmos ávaros:
En cada ocasión se toma la desición de elegir el óptimo local sin pensar en las consecuencias futuras. El algoritmo codicioso no siempre garantiza la solución óptima, sin embargo, generalmente produce un valor cercano al óptimo
4. Programación lineal:
Existe desigualdades en los términos de entrada  maximixación o minimización de algunas funciones lineales de entradas
5. Reducción (transformar y conquistar)
Resolvemos un problmea dificil transformándolo en un poblema conocido para el cual tenemos una solución óptima
#### Otros
1. Backtraquing:
Intenta cada posibilidad hasta que encuentra la correcta, es una búsqueda de profundidad del conjunto de posibles soluciones- Durante la búsqueda, si una alternativa no funciona, retroceda al punto de elección, el lugar que presentó diferentes alternativas e intente la siguiente alternativa
2. Ramificación y poda:
Un subproblema dado que no puede acotarse, debe dividirse en al menos dos nuevos subrpoblemas restringidos.
3. Aleatorios:
Son algoritmos que toman decisiones aleatorias para soluciones más rápidas.
5. Clasificación por complejidad:
Algoritmos que se clasifican en función del tiempo necesario para obtener una solución a cualquier problema por tamaño de entrada.
6. Por área de investigación:
En Ciencias computacionales cda campo tiene sus propios probelmas y necesita algoritmos eficientes.

## ¿Cómo encontrar un buen algoritmos?
* Analizar el problema
* Pensar una solución viable
* Analizar soluciones existentes
* Pensar en la _eficacia_ y en la _eficiencia_
- > El uso de la intuición no basta
- > ENcontrar o deiseñar un buen algoritmo es un procese formal.
### ¿Cómo sé que mi algoritmo es eficiente?
* Tiempo
* Facilidad de implementación
* Memoria
 - > no se pueden usar medidas relativas para medir la eficiencia, sino que en el número de operaciones elementales que lleva a cabo.
#### Criterios para escoger algoritmos
Orientados a __minimizar el costo de desarrollo__
: Claridad, sencillez, facilidad d eimplantación, depuración y mantenimiento.

Orientados a __disminuir el costo de ejecución__
: tiempo de procesador y cantidad de memoria

### Análosos de algoritmos
#### Tamaño del problema
* Un problema tiene solución algoritmica si además de que el algoritmo existe, se es posible computar en un tiempo factible


Problema | Tamaño
----------
Buscar x en un arreglo | número de elementos del arreglo.
Multipilcar dos matrices | dimensión de las matrices.
Recorrer un árbol | número de nodos.
Resolver un sistema de ecuaciones | número de elementos en ella.

#### Función de complejidad
##### Complejidad espacial

* Cantidad de memoria
* Variables de tipo simple que se usarán
* Celdas de memoria necesarias (dinámica y estática)

##### Complejidad temporal
* Cantidad de trabajo realizado
* Enrtadas proporcionadas
* Calidad del código
* Calidad del equipo en el que se corre

# Algoritmos voraces

* Suelen ser los más fáciles de implementar.
* Tienen un enfoque miope: basándose sólo en la información que tiene de inmediato.
* Se usa típicamente para resolver problemas de optimización.

## Características generales.
Buscan resolver un problema de forma óptima basados en una lista de solución candidatos
A medida que avanza el algoritmo, se van acumulando dos conjuntos: un conjunto con candidadtos rechazados y otro con candidatos seleccionados
FUnción de solución
~ FUnción que comprueba si un cierto conjunto de datos

# Algoritmos de backtracking

Es un algoritmo general que busca todas ao alfunas soluciones.Es especialmente útil en problemas con restricciones. Genera gradualmente candidatos para las soluciones y abandona estastan pronto determina que un candidato no es una solució´n válida. Se considera el contrario al voraz debido a que es altamente einnefiinente y este busca encontrar el mejor caminoa largo plazo, no instantáeamente.

En la entrada cuenta con una matroz de entrada de n x n que cuenta con los caminos disponibles para el algoritmo y otra matriz de salida con el camino que se encontró

Estas matrices cuentan con 1 en el camino disponible:

```Matriz
{1, 0, 0, 0}
{0, 1, 0, 1}
{0, 1, 1, 1}
{0, 0, 0, 1}
```

## Algoritmo de ramificación y poda
El algoritmo recorre un árbol buscando el camino más corto, recordando en cada bifurcación cuánto se ha tardado en recorrer hasta el siguiente nodo, cuando nota que un camino es más corto que otro, elimina de la soluciónel camino más costoso y sigue adelante para comparar los caminos.

# Manejo de strings
- > Tarea de strings, se crea una tabla de un multiplo de 4 de colunas rellena de datos, si no se llenan las tablas se rellenan con el último valor de n, luego se calcula el valor ascii de cada elemento de la tabla y se suma, la respuesta se guarda en un vector donde se almacenan cada resultado