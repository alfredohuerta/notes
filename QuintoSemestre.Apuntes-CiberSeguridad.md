---
id: 3n50qb0irlce7hrkid6kuz4
title: Apuntes-CiberSeguridad
desc: ''
updated: 1676502189433
created: 1676502170053
---
## Industria 4.0

Es la conjunción de los artefactos físicos con las tecnologías de la información donde las líneas entre los artículos electrónicos y el internet están interconectados y comunicados en todo momento.
La ciberseguridad busca proteger la información digital de los sistemas interconectados. De acuerdo con la ISACA, la ciberseguridad busca la protección de los **activos de información**, a través del tratamiento de amenazas que ponen en riesgo _la información que es procesada, almacenada y transportada por los sistemas de información que se encuentran._

#### **Actividad colaborativa: ¿Por qué es importante que yo aprenda ciberseguridad?**

- Porque es una herramienta universal y necesaria para todos los sistemas basados en software.
- Porque la información personal y crítica de todas las personas están almacenadas en algún sistema de software y es necesario hacer todo lo posible para protegerla.
- Porque muchos sistemas críticos para mantener el estilo de vida actual están soportados por software y perder el control de ellos sería tan dañino como privarle el agua a alguien.
  El conjunto de políticas y mecanismos que nos permiten garantizar la confidencialidad, la integridad y la disponibilidad de los recursos de un sistema. También llamada Tríada CIA.

# Dimensiones de la seguridad

### Procesos

- Diseñar pensando en la seguridad.
- Roles y responsabilidades.
- Auditar, dar seguimiento y rastrear.
- Mantenerse al día con el desarrollo de seguridad.

### Gente

- Falta de conocimiento
- Falta de compromiso
- Falla humana

### Infraestructura

- Los productos no cuentan con funciones de seguridad
- Demasiado difícil mantenerse al día
- Muchos problemas no se ven abordados por estándares técnicos.

## Panorama organizacional de la seguridad informática

- Lo primero que hay que ver es la legislación del país donde te encuentras
- Recurrir a los estándares de seguridad como el ISO
- Gestión y operación de procedimientos y políticas
- Diseño de topologías, arquitecturas y servicios
- Sistemas de seguridad

### Los 3 niveles de inseguridad en una infraestructura tecnológica

1. Nivel de la infraestructura tecnológica: hardware y nivel físico de acceso e instalaciones.
2. Nivel lógico: software, errores en el diseño y configuración
3. Nivel humano: riesgos por el mal uso de los factores anteriores y por falta de conocimiento de los empleados de las políticas de seguridad.

### Dominios de la seguridad informática

La seguridad del perímetro: protección frente ataques del exterior generalmente basada en cortafuegos. Sin embargo ahora con las tecnologías de la nube se ha difuminado el perímetro debido a que ya no hay tanto hardware que protege la información.

La seguridad en el canal: donde hay que proteger los datos frente a escuchas mediante el cifrado de información.

Seguridad de acceso: donde se contemplan la identificación del usuario, la autorización del acceso y la auditoría de las operaciones.

Adicionalmente la seguridad interna debe incluir monitorización y seguridad en los servidores, aplicaciones y procesos.

#### Seguridad de perímetro

- Cortafuegos en routers dedicados en cada dispositivos.
- IPS: ala entrada de toda red
- IDS

### Seguridad en el canal

- Encriptación de accesos
- Uso de HTTPS y SSH

### Seguridad de acceso

- Utilizar técnicas de autenticación robustas en los clientes o shells seguros
- Autenticación biométrica
- Firmas digitales
- Asignación de privilegios adecuada.

### Passwords

Herramienta para probar [contraseñas](https://password.kaspersky.com/es/)

P = el tiempo que se tomaría alguien en romper una contraseña por fuerza bruta.

        P = (LR)/S

L = tiempo de vida del password

R = es el número de intentos por unidad de tiempo que es posible realizar para descifrar un password.

S = es el espacio de passwords: el número total de passwords únicos disponibles donde es:

         S = A ^ m

A = el número total de caracteres en el alfabeto más los caracteres especiales (se cuentan mayúsculas y minúsculas como caracteres diferentes.

M = longitud del password.

La técnica de autenticación más robusta se logra al combinar algo que se es (biométrico), con algo que se sabe (contraseña) y con algo que se tiene (objeto - tarjeta inteligente). De igual forma hay una tendencia a utilizar autenticación multifactor para prevenir ataques de phishing y el acceso a sistemas. Este tipo de control de accesos son implementados en lugares que demandan alta seguridad.

Los **biométricos** deben ser: _universales_, _únicos_, _permanentes_, _colectable_ ( presentable a un sensor y es fácilmente cuantificable), con _desempeño aceptable_ y _confiable_ (que no presente falsos negativos).

# Actividad 1: Ataques de fuerza bruta

[Actividad aquí](https://docs.google.com/document/d/1UjFP9gDlAw41TZh4D0e99hZLpuDFFXP29TeeLH8K6Lg/edit)

# Ley Federal de Protección de Datos Personales

### Diferencias entre dato sensible y personal

|            | Dato Sensible                                                                                          | Dato Personal                                                                  |
| ---------- | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ |
| Definición | Datos que bajo ciertas circunstancias o sociedades nos pueda presentar algún peligro o daño a nosotros | Aquella información que permita identificar a una persona sobre otro individuo |
| Ejemplo    | Edad, creencias religiosas, enfermedades o preferencias sexuales                                       | CURP, RFC, Número de identificación social                                     |

### Regla para trabajar con los datos sensibles y personales

Datos sentibles + Datos personales deben estar cifrados, en reposo y en trasmición

Siempre hay que actuar tomando en cuenta que la información será robada en algún punto, por lo que siempre hay que encriptarla para reducir su valor o hacerlos indeseables de poseer.

## Principio de la LFPDD

- Licitud -> Apegado a la ley
- Información
- Finalidad
- Proporcionalidad
- Consentimiento -> El usuario deberá permitir el almacenamiento de estos datos.
- Calidad
- Lealtad
- Responsabilidad

Los datos personales y sensibles deben contener lo siguiente:

- Confidencialidad
- Seguridad

Los encargados de la base de dato deberán sen responsables de brindar estas facilidades

### Dibulgación y almacenamiento de la ley

|            | Remisión                                                                                          | Transferencia |
| ---------- | ------------------------------------------------------------------------------------------------- | ------------- |
| Definición | Cuando el **responsable** de los datos se los entrega a alguien para que se **encargue** de elloa | C1            |

Los responsables de estos datos deben estar seguros de que no han dejado ningún punto ciego en las defensas, así como

# Criptografía

## Métodos de cifra moderna

### Cifrado en flujo

- Telefonía móvil, Internet y WLAN.

El mensaje se convierte en bits y se le aplica un proceso a través de una compuerta lógica XOR con una clave, los bits se envían, después se le vuelve a aplicar el XOR con la clave y se vuelve a tener la información íntegra.

### Cifrado en bloque

El mensaje e agrupa en bloque, de 8 a 16 bytes, antes de aplicar el algoritmo de cifra a cada bloque de forma indemendiente con la misma clave. Cifrado con clave secreta.

- DES -> Aplicaciones bancarias
- IDEA, CAST -> e-mail.
- Triple DES -> comercio electrónico
- Nuevo estandas -> AES Rijndael

#### Clave pública

##### Exponenciación

- RSA: ElGamal
  Uso en el intercambio de clave y en firmas digitales

##### Suma/producto

- Curvas elípticas
  ~ Intercambio y firmas digitales.
- Mochilas
  ~

### Clave secreta

### Clave privada

Un número, que sólo es conocido por el que conoce la información en particular

#### Texto cifrado

Se origina de cifrar el texto plano con una clave mediante un algoritmo de cifrado.

**Criptografía**
~ Arte de construir códigos secretos

**Criptoanálisis**
~ Técnicas para recuperar la información cifrada.

## Criptosistemas

Es el conjunto de procedimientos que garantizan la seguridad de la información que utlilizan técnicas de criptofráfía

El elemento más importante a cuidar es la **llave**, que es lo que permite descifrar el código.

Fuerza del cifrado simétrico

1. Robustés del algoritmo
   ~ Qué tan bien diseñado está y usa mecanismos de **difusión** y **confusión** haciendo uso de operaciones de transposición, sustitución, +, x y XOR. Siempre y cuando estas sean reversibles.

- Difusión
  : **Oculta la relación entre el texto claro y el texto cifrado.** Se logra usando permutación, totación y transposición. Cada bit del texto plano y de la clave influyen todos los bits del texto cifrado con lo que se logra.

- Confusión
  : **Oculta la relación entre el texto plano y la clave secreta.** Se logra usando alternativamente otras operaciones como +, x y

2. Longitud de clave.

## DES (Cifrado de Datos Estándar)

Longitud de clave es de 56 bits para cifrar bloques de 64 bits.

Tienen un fuerte efecto de avalancha debido a que el cifrado de cada bloque depende del anterior.

Quedó obsoleto tras haber sido hackeado por ataques de fuerza bruta

## IDEA (Algoritmo de Cifrado de Datos Internacional)

Usa una clave de 128 bits para cifrar bloques de 64 bits

No ha sido hackeado

## Blowfish

Es el mejor para hardware

Usa los ciclos del reloj interno para crear el cifrado

La longitud de clave puede llegar hasta los 448 bits, pero esto puede bajar debido a que la seguridad puede meterse en proceso de la eficiencia.

Utiliza sólo adición y operaciones XOR

## AES

Tamaño de bloque fijo de 128 bits y tamaños de llave de 128 bits, realizando 10 rondas, 192 bits (realizando 12 rondas) o 256 bits (realizando 14 rondas), todas las claves son múltiplos de 32 bits y cada ronda encripta el bloque y la clave con cada paso.

Opera con una matríz de 4x4 bytes llamada **state** dependiendo de la longitud de claves es el número de rondas que se ejecutan para el cifrado de la información.

Cada ronda o vuelta usa una subclave generada a partir de la clave maestra.

Para generar cada subclave se utiliza una función de expansión que hace uso de rotación de palabras de la clave, uso de la función subBytes y de la función XOR.

WPA, los protocolos de enlace de datos, SSL, etc. usan cifrados AES o derivados de AES.

# Criptografía Asimétrica

Nace con el fin de solicionar el problema de la criptiografía simétrica como lo es la distribicuón de claves y para generar firmas digitales.

Puede ser usado para cifrar o para autentica. Con lo cual puede ofrecer confidencialidad, autenticación e uncluso una firma digital.

Consite en generar un texto cifrado a partir de un testo plano y una clave (que se toma deun par de claves). La información original se obtiene aplicando al texto cifrado el inverso del algoritmo mediante la clave complementaria

Clave pública: un número asocado con una clave privada de una autoridad particular. Una clave pública se pretende dar a conocer a todos aquellos que necesitan tener interacciones con aquella entidad.

Certificado: una declaración formada digitalmente de una entidad, diciendo que la clave pública de alguna otra entidad tiene un valor particular. SI se confía en la entidad que firmó el certificado, entocnes se da acceso a la información.

Las seguridad del sistema reside en la dificultad computacional de descubrir la clave privada a partir de la pública. Para ello se usan funciones matemáticas de un solo sentido y número primos muy grandes.

El otro elemento que determina la intensidad de cifrado es el tamaño de la clave, que debe ser lo suficientemente larga para que sea imposible encontrar su clave complementaria con todo el poder de cómputo de una red de computadoras de la épica de un tiempo relativamente corto (2 años, que es lo que dura la validez del certificado, después tiene que revalidarse)

Las claves públicas son para que todos las conozcan, pero las claves privadas son públicas para cada individuo.

Además de permitir tener confidencialidad en las comunicaciones, también permite mantener la integridad de los mensajes enviados a través del sistema.

## Diffie-Hellman (**BUSCAR POR MI LADO**)

En los trabajos iniciales de la criptografía de dos claves se sugiere la exponenciación de algún módulo de un primo p para el intercambio de claves públicos, la complejidad de esto algoritmo radica en la dificultad de hacer ingeniería inversa al valor, por lo que la única forma verdadera de deshacer la encriptación es sabiendo el valor real.

Una de los aspectos fuertes de DH es que no se necesita de un certificado digital, sin embargo, RSA es uno de los más usados sobre DH debido a que permite certificar las llaves y asegurarse de que son enviadas a la persona correcta. DH es usado en ambientes como VPN's

## Filosofía S3 (Security By)

### By design

Considerar la seguridad desde el diseño

Repetar el diseño y convenicones deprogamación

Las convenciones de programacióndeberían ecoluvionarcon las tendencias de seguidad actuales.

Código viego y funcionalidades obsoletas deben ser omitidas

Realizar pentesting

Planear la ehecución de la app con privilegios mínimos

La organización debería de tener un experto en seguirad al que consultar.

Los empleados deben ser capacitados periódicamente en temas de seguirdad

### By Default

La instalación por default debe se la más segura

No instalar todas la funconalidades de seguridad por default

Asegurar todos los recursos que representen datos sensibles, pues estos pueden ser objetivo de ataque.

Otorgar la menor cantidad de privilegios posibles.

### By Deployment

Deben existit una configuración de seguridad

Corregir los bugs y aplicar los parches de seguridad inmediateamente tras detectar una vulnerabilidad

Dar suficiente informaciónal usuario para que puedan usar la aplicación de forma segura. DOcumentación, instrucciones de uso y también mensajes de error.
