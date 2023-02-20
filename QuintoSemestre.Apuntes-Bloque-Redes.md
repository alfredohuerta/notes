---
id: vyz3m3u9uhak8n11724nhsz
title: Apuntes-Bloque-Redes
desc: ''
updated: 1676502077006
created: 1676502053864
---
# Configurar rutas estáticas
Para sumarizar las redes primero hay que transformar en binario las redes en el byte que cambia

```
172.20.0.0 = 172.00010100.0.0
172.21.0.0 = 172.00010101.0.0
172.22.0.0 = 172.00010110.0.0
172.23.0.0 = 172.00010111.0.0
```
Encontrar dónde empiezan a cambiar los binarios

```
172.20.0.0 = 172.000101|00.0.0
172.21.0.0 = 172.000101|01.0.0
172.22.0.0 = 172.000101|10.0.0
172.23.0.0 = 172.000101|11.0.0
```
A partir de donde comienzan los cambios, llenar con ceros y convertir de vuelta a decimal con todo y máscara.

```
172.000101|00.0.0
172.20.0.0/14 255.252.0.0
```
# Introducción a OSPF
Es un protocolo de estado de enlace multi area dinámico. EL protocolo manda la información a todos los nodos a su alrededor y ellos lo mismo para poder compartir los estados de conexión.

## Paquetes
* Adjacency Database - Todos los nodos que estén directamente conectados al router.
* Link-state Database - Topología de la red que almacena todos los caminos necesarios para navegarla, así como la velocidad entre ellas para calcular la ruta más corta de un sitio a otro. Aquí se almacenan las rutas flotantes.
* Forwarding Database

## Multiarea OSPF
Cuando dos o más áreas de OSPF se conectan entre ellas y comparten información. Cada nueva área recibe un número de área y el área entre cada red recibe el número 0, de esta forma se puede segmentar una red gigantesca sin tener problemas de conexión entre ellas cuando una se caigan. El área 0 funciona como backbone de la red.

## Tipos de paquete
* Hello -> encontrar vecinos y establecer una topología. Cuando se establece la conexión, se mandan constantemente los Keep Alive para mantener viva la conexión, cuando se pierde llegan a Death Interval que es el tiempo que está dispuesto a esperar el router para matar o reestablecer la conexión.
