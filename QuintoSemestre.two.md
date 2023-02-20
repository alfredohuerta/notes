---
id: eofe951b3vkwdu1whziehzi
title: Apuntes-Bloque-DesarrolloMovil
desc: ''
updated: 1676502019912
created: 1676501916284
---
# Calidad Movil
* Resistencia a fallos
* Cumplir las espectativas del mercado
* Tener un funcionamiento correcto con los recursos que se tienen.

## Usuarios
* Son los que califican la calidad de nuestro software
* Su juicio afecta la persepción de la calidad.
* Determinan el nivel de satisfacción.

## Ambiente
* Dispositivos objetivos, redes móviles
* Condiciones, restricciones y particularidades de ejecución
* Determinan que tan adecuado es tu producto.

## Tiendas
* Tiene que cumplir las condiciones de la tienda para entrar en el mercado.

## Responsividad
* Algunas app stores sugieren un máximo de milisegundos de respuesta.
* Si la aplicación está tardando mucho en cargar, agregar una barra de progreso para reducir la ansiedad del usuario

## Energy management
* Evitar usar demasiados recursos como la batería.

## Seguridad
* Usar protocolos de seguridad
* Criptografía
* API's de identificación
* No exponer los datos del usuario.

## Diseño de la GUI
* Se ajusta a distintos tamaños de pantallas
* Respeta las guías de las GUI
* La apariencia visual es agradable

## Análisis de sentimiento
* Análisis cualitativo que regresa la probabilidad de qué sentimiento representa un comentario.

## Análisis de métricas
* Marco de trabajo que analiza cuánto se usa una aplicación por un usuario

## Elementos que marcan la calidad de una aplicación movil
* Lo que el __usuario__ quiere
* Lo que el __ambiente__ permite.
* Lo que el __mercado__ permite.

# Kotlin

```Código de Kotlin
class MainActivity : AppCompatActivity() {
    los : significan herencia
    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        setContentView(R.layout.activity_main)
    }
}
R es un objeto automáticamente creado por android
```

## Aplicaciones que pueden servir
* Android debugg bridge
* Vysor
* Android emulator Goldfish

## Activity lifecycle callbacks
* onPause() cuando se cambia la actividad 

# Kotlin basics, the return

