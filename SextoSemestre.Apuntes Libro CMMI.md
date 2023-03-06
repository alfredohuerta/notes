---
id: 25za8mu9p4gyib06u0a5j6q
title: Apuntes Libro CMMI
desc: ''
updated: 1678079298620
created: 1676647824808
---
# Primera parte: Acerca de CMMI para desarrollo
## Capítulo 2: Componentes del área de procesos
### Componentes requeridos, esperados e informativos
#### Requeridos
Son escenciales para lograr a mejora de procesos en un área y su implementación debe ser visible en la organización

#### Esperados
Describen las actividades que son importantes para lograr un componente. Orientan a quienes implementan las mejoras o realizan las evaluaciones. **Son prácticas específicas y genéricas**.

#### Informativos
Ayudan a los usuarios del modelo a comprender los componentes requeridos y esperados.

> Ejemplos en un recuadro, explicaciones detalladas u otras informaciones útiles. Las subprácticas, las notas, las referencias, los títulos de metas, los títulos de prácticas, las fuentes, los ejemplos de productos de trabajo y las elaboraciones de prácticas genéricas

### Componentes asociados con la Segunda Parte
#### Áreas de proceso
Grupo de prácticas relacionadas dentro de un áres que satidface un conjunto de metas consideradas importantes para mejorar

![](/assets/CMMI/AreaProcesos.png)

#### Declaraciones del propósito
Describe la finalidad del área de proceso y es un [componente informativo](#informativos).

#### Notas introductorias
Describe los conceptos principales cubiertos por el área de proceso y es un [componente informativo](#informativos)

#### Áreas de proceso relacionadas
Enumera las referencias a áreas de proceso relacionadas y refleja las relaciones de alto nivel entre las áreas de proceso. Es un [componente informativo](#informativos)

#### Metas específicas
Describe las características únicas que deben estar presentes para satisfacer el área de proceo. Es un componente requerido del CMMI y se utiliza en las evaluaciones para ayudar a determinar si se satisface un área de proceso.

Solo la declaración de la meta es un [componente requerido](#requeridos). El título, el número y las notas asociadas son considerados [componentes informativos](#informativos)

#### Metas genéricas
Son llamadas así porque la misma declaración de la meta se aplica a múltimes áreas de proceso. Describe las características que deben estar presentes para institucionalizar los procesos que implementan un área de proceso. Es un [componente requerido](#requeridos) y se utiliza en las evaluaciones para determinar si se satisface un área de proceso.

Solo la declaración de la meta es un [componente requerido](#requeridos). El título, el número y las notas asociadas son considerados [componentes informativos](#informativos).

#### Resúmenes de metas y prácticas específicas
Proporciona un resumen de alto nivel de las metas específicas y de las prácticas específicas. Es un [componente informativo](#informativos).

#### Prácticas específicas
Es la descripción de una actividad que se considera importante para lograr la meta específica asociada. Las prácticas específicas describen las actividades que se espera que produzcan el logro de las metas específicas de un área de proceso. Es un [componente esperado](#esperados) del modelo.

Solo la declaración de la meta es un [componente requerido](#requeridos). El título, el número y las notas asociadas son considerados [componentes informativos](#informativos).

#### Ejemplos de productos de trabajo
Son las evidencias que marcan el cumplimiento de una [práctica específica](#prácticas-específicas)

#### Subprácticas
Descripción detallada que proporciona orientación para interpretar e implementar una práctica específica o genérica. Son un componente informativo indicado sólo para proporcionar ideas que puedan ser útiles para la mejora de los procesos.

#### Prácticas genéricas
Se denomina genérica porque se aplica a múltiples áreas de proceso, describen las actividades que se consideran importantes para lograr la meta genérica y contribuir a la institucionalización de los procesos asociados con el área.

Solo la declaración de la meta es un [componente requerido](#requeridos). El título, el número y las notas asociadas son considerados [componentes informativos](#informativos).

##### Elaboración de la práctica genérica
Aparecen después de las prácticas genéricas para orientar  la forma en que pueden aplicarse las [prácticas genéricas](#prácticas-genéricas) a las [áreas de proceso](#áreas-de-proceso-relacionadas)

> Por ejemplo, una elaboración de práctica genérica de la práctica genérica
“Establecer y mantener una política de la organización para planificar
y realizar el proceso” en el área de proceso Planificación del Proyecto
es “Esta política establece las expectativas de la organización para estimar
los parámetros de la planificación, para definir compromisos internos
y externos, y para desarrollar un plan para gestionar el proyecto”.

#### Extenciones
Son componentes del modelo claramente visibles que contienen información de interés para usuarios particulares. Pueden ser material informativo, una práctica, meta específica o un área de proceso que amplía el alcance de un modelo.

---

### Componentes informativos de soporte
#### Notas
Texto que puede acompañar casi a cualquier otro componete del modelo. Puede proporcionar detalles, antecedentes o un análisis razonado. Es un [componente informativo](#informativos)

#### Ejemplos
Texto y, a menudo una lista de elementos, puede amopañar a casi cualquier otro componente y proporciona uno o más ejemplos para clarificar un concepto o una actividad descrita. Es un [componente informativo del modelo](#informativos)

#### Referencias
Es un enlace adicional o más detallado en las áreas de proceso relacionadas y puede acompañar otro componente del modelo.

---

### Esquema de numeración
Las metas específicas y genéricas se numeran secuencialmente

Nombre | Abreviación | Ejemplo
----|----|----
Meta específica | SG # de meta | SG 1
Meta genérica | GG # de meta | GG 1
Prácica específica | SP # de la meta a la que pertenece . # de  secuencia de la práctica para la meta | SP 1.1
Prácica genérica | GP # de la meta a la que pertenece . # de  secuencia de la práctica para la meta | GP 1.1

---

## Capítulo 3: Uniéndolo todo
### Comprendiendo los niveles de capacidad
Se alcanza un nivel de capacidad para un área cuando **se satisfacen todas las metas genéricas hasta ese nivel**. Los niveles de capacidad 2 y 3 usan los mismo términos que las metas genéricas 2 y 3  porque refleja el significado de os niveles de capacidad de las metas y prácticas.

#### Niveles de capacidad
##### Nivel de capacidad 0: Incompleto
Es un proceso que no se realiza o se hace parcialmente. Al menos una de las [metas específicas](#metas-específicas) del [área de proceso](#áreas-de-proceso) y no existen metas genéricas para este nivel.

##### Nivel de capacidad 1: Realizado
Lleva a cabo el trabajo necesario para producir productos de trabajo. Se satisfacen las [metas específicas](#metas-específicas) del [área de proceso](#áreas-de-proceso).

Las mejoras del nivel 1 pueden perderse con el tiempo si no se institucionalizan.

##### Nivel de capacidad 2: Gestionado
Es un proceso realizado que se planifica y efecuta de acuerdo con la política. Es empleado por las personas capacitadas para el proceso, así como contando con los recursos adecuados para dar resultados controlados. Además de involucrar a las partes interesadas, se monitorea, controla y revisa para asegurar la adherencia a su descripción.

La diciplina que se regleja en el nivel ayuda a segurar que las prácticas de mantienen en momentos de mayor presión.

##### Nivel de capacidad 3: Definido
Tiene una descripción de proceso que s emantiene y que contribuye a los activos de proceso de la organización con experiencias relativas al proceso.

###### Diferencias Nivel 2 y 3
Nivel 2 | Nivel 3
----|----
Los estándares, descripciones y procedimientos son **muy diferentes entre proyectos** | Los estándares, descripciones y procedimientos para un proyecto son **más consistentes entre proyectos**
Los procesos se **describen de forma vaga y poco consisa**. | Los procesos se **describen rigurosamente**.
Los procesos se trabajan como **instancias aisladas** de sus productos y otros procesos. | Los procesos se gestiona más proactivamente a través de la **comprensión de las relaciones** entre actividades del proceso, las medidas detalladas y sus productos de trabajo.

##### Cómo alcanzar cada nivel
Nivel 1 | Realizar los procesos
----|----
Nivel 2 | Se planifica y monitoriza el cumplimiento de los procesos.
Nivel 3 | Los procesos se definen y aplican de forma más consistente debido a que hay procesos estandar que se adaptan en la organización.

#### Niveles de madurez
##### Nivel de madurez VS Nivel de capacidad
Nivel de madurez | Nivel de capacidad
----|----
Se utilizan para caracterizar la mejora de la organización relativa a un conjunto de áreas de proceso | Caracterizan la mejora de la organización relatica a un área de proceso individual
Mejora colectiva/en área | Mejora en un proceso individual

#### Niveles de madurez 1 a 3

Nivel 1 (Inicial) | Nivel 2 (Gestionado) | Nivel 3 (Definido)
----|----|----
No proporciona un entorno estable para dar soporte a los procesos | Garantiza que en los proyectos los procesos se planifican y ejecutan de acuerdo con las políticas | Los procesos están bien caracterizados y comprendidos
Depende de que unos pocos salven el proyecto | Emplean personal cualificado y con recursos ara producir resultados | Se describen en estándares, procedimientos, herramientas y métodos
Producen productos y servicios que exceden el presupuesto y los plazos planificados | Se involucran los interesados relevantes | El conjunto de procesos estándar de la organización se establece y mejora a lo largo del tiempo 
Se comprometen en exceso | Se monitorizan, controlan y revisan los procesos | Los procesos estandar se utilizan para establecer la integridad de toda la organización 
Abandonan los procesos en momentos de crisis | Se evalúa cuánto se apegan a sus descripciones de proceso | Los proyectos personalizan los procesos estándar a través de guías de adaptación 
No repiten los éxitos | Son diciplinados y aseguran que la prácticas se mantienen en momentos de presión | Se usan como base procedimientos, guías, etc. estándar que se modifican para cada proyecto de acuerdo a sus necesidades
-- | Los proyectos se realizan y gestionan de acuerdo a sus planes documentados | Los procesos se gestionan a través de cómo interactúan los unos con los otros, así como con las distintas medidas, productos de trabajo y servicios
-- | El estado de los productos es visible, así como su dirección en puntos definidos (ej. hitos) | Los procesos son contínuamente evaluados y mejorados en la organización
-- | Establecen compromisos entre las partes interesadas y se modifican de ser necesario | - 
-- | Los productos de trabajo se controlan de forma apropiada | -
-- | Los productos de trabajo y servicios satisfacen sus descripciones de proceso, estándares y procesdimientos especificados | -

### Áreas de proceso
![](/assets/CMMI/AreasCMMI.png)

## Capítulo 4: Relaciones entre áreas de proceso
