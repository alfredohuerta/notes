---
id: cfnmdtg5u97o4hy02xbacte
title: Apuntes-GraficasComputacionales
desc: ''
updated: 1676502231359
created: 1676502210691
---
## Rasterización

Reciben las coordenadas de los triángulos para construir los objetos.
Los triángulos son útiles porque todas las figuras prmitivas pueden ser construidas con treiángulos, así como es fácil de conectarse y llevar a cabo interpolación en ellos (la forma en la que obtiene la forma, color e iluminación).

**Triangle coverage:** Cómo se transforma un triángulo a un conjunto de pixeles.

**Oclusión:** Efecto d eun objeto en 3D que está ocupando la vista de otro.

**Muestreo/Sampling:** Tomar las medidas de una señal, señalando las oordenadas en diversos puntos, también llamados _mapas de bits_

**Reconstruction:** dado un conjunto de muestras de una señal cómo se reconstruye la señal original mediante **Constant aproximation** (conectanto los puntos mediante los vértieces de un cuadrado) o **linear aproximation** (uniendo los puntos con líneas rectas). _La Picewise constant es la más precisa._

**Aliasing:** Es el ruido que hay en las señales, cuando se usa el antia-alising, es para "limar" los bordes en las imágenes

Las imágenes también pueden ser consiferadas como un conjunto de señales que se mueven en distintas frecuencias que una vez sumadas dan pie a imágenes de mayor calidad. Algunos filtros seleccionan distintas componentes de la señal.

##### Incrementar la calidad de la imagen

* Incrementar el muestreo de la señal, 
* Hacer supersampling 
* Hacer resampling de la misma imagen una y otra vez

### Transformaciones espaciales

#### Rotaciones
* Origen fijo
* Mantiene las distancia de todos los elementos
* Otro

#### Transformaciones octogonales
* Hace una reflexión de las imágenes

#### Escalamiento
* Mantiene la dirección de tosos los vectores
* Cada vector escala en un múltiplo

#### Shear
Tensión similar a la que tiene un pastel cuando se corta

#### Traslación
Modifica la posición de un obketos

### Transformaciones compuestas
Está basado en multiplicación de matrices. Es cuando se juntan varias de las transformaciones

### Transpolar transformaciones
Sirve para aplicar múltiples transformaciones a una imagen

### Descomponer trasnformaciones
Ayuda para deshacer las transformaciones que se hacen en un objeto y revertur sus procesos aplicacdos

### Instanciamiento
Es cuando tenemos un objeto raíz donde se crean diferentes variaciones de la misma pero que comparte un comportamiento y características generales hasta cierto punto.

