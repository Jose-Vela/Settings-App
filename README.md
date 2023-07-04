# Settings-App

# Introducción
Pantalla de ajustes para activar el __Modo Oscuro, Bluetooth, Volumen y Vibración para llamadas__. En este proyecto hacemos uso de la __Persistencia de Datos con DataStore__.

Es una de las prácticas propuestas en el curso de [ANDROID CON KOTLIN de AristiDevs](https://youtu.be/vJapzH_46a8) el cual es gratis y si prefieres consumir más de su contenido, puedes visitar su [canal de YouTube:](https://www.youtube.com/@AristiDevs)

# Tecnologías Utilizadas

- Kotlin
- DataStore
- Persistencia de Datos
- Flow
- Coroutines (Corrutinas)
- Data Class
- Diseño basado en XML
  - Linear Layout

# Funcionalidad

1. __Vista principal:__ Solo es una vista, la cual contiene los controles para activar, desactivar o ajustar el __Modo oscuro__, __Bluetooth__, __Nivel de volumen__ y __Vibrar en las llamadas__.

<p align="center">
      <img width="35%" src="https://i.postimg.cc/zGr1Fqjn/Screenshot-01.png">
      <img width="35%" src="https://i.postimg.cc/K8Dh9CqC/Screenshot-02.png">
  </p>

La aplicación es capaz de persistir o "recordar" los ajustes que se dejaron antes de cerrarla, es decir, que opciones se dejaron activadas/desactivadas y el nivel de volumen establecido, esto gracias a que la información se guarda en una __Base de Datos local__ en el dispositivo. La primera vez que se ejecuta la aplicación, mostrará ajustes establecidos por defecto.

La finalidad de este pequeño proyecto es mostrar la __Persistencia de Datos__, por lo cual la única opción que realmente funciona es la primera, __Modo Oscuro__, que al activarla o desactivarla, los colores del fondo, textos e iconos de la aplicación cambian. El resto de las opciones son solo demostrativas.

# Enlaces

- [ANDROID CON KOTLIN de AristiDevs](https://youtu.be/vJapzH_46a8)
- [Canal de YouTube de AristiDevs](https://www.youtube.com/@AristiDevs)

### Extras

- [Postimages: Almacenamiento gratuito de imágenes](https://postimages.org/es/)