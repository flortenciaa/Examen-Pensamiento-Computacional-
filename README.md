# Examen-Pensamiento-Computacional-
# 🎵 Sound Match

## Descripción

**Sound Match** es un juego desarrollado en **p5.js** donde el objetivo es adivinar una canción escuchando solo un fragmento de su melodía.

El juego está dividido en tres niveles. En cada uno aparecen tres portadas de álbumes y, al comenzar la ronda, se reproduce aleatoriamente una de las canciones de ese nivel. El jugador debe elegir cuál de las tres portadas corresponde a la canción que está sonando.

Si la respuesta es correcta, se suma un punto y aparece el botón para continuar. Después de completar las tres canciones de un nivel, el juego pasa automáticamente al siguiente. Al finalizar los tres niveles se muestra el puntaje obtenido y la opción de volver a jugar.

---

## ¿Por qué hice este proyecto?

La idea nació porque me gusta mucho la música y quería hacer un juego donde el sonido fuera el elemento principal, en lugar de centrar todo en lo visual.

Me inspiré en esos videos de YouTube donde hay que adivinar una canción escuchando solo unos segundos. Siempre me han parecido entretenidos, así que pensé que sería buena idea llevar esa dinámica a un juego interactivo.

Las canciones que elegí son temas que personalmente creo que mi círculo cercano puede reconocer fácilmente. Quise ponerlos a prueba y hacer un juego entretenido que también generara un poco de nostalgia. Además, las organicé por géneros o por la vibra que transmiten para darle un poco más de estructura a los niveles.

---

## Objetivos

Con este proyecto busqué crear un juego simple pero entretenido, donde el jugador pudiera poner a prueba cuánto reconoce canciones solo escuchando una parte de ellas.

También quería practicar el uso de arreglos, funciones y estados dentro de p5.js, además de implementar una selección aleatoria para que cada partida fuera un poco diferente.

---

## ¿Cómo funciona?

El juego comienza en una pantalla de inicio donde el usuario presiona el botón **Play**.

Cada nivel contiene tres canciones.

En cada ronda ocurre lo siguiente:

* Se elige aleatoriamente una canción del nivel.
* Se reproduce un fragmento de esa canción.
* Se muestran las tres portadas correspondientes.
* El jugador selecciona la portada que cree correcta.
* Si acierta, gana un punto y puede continuar.
* Si se equivoca, puede volver a intentarlo.

Cuando las tres canciones del nivel ya fueron utilizadas, el juego avanza automáticamente al siguiente nivel.

Al completar los tres niveles aparece una pantalla final con el puntaje obtenido y un botón para volver a jugar.

---

## Aspectos técnicos

Para desarrollar el proyecto utilicé principalmente las funciones de **p5.js**:

* `preload()` para cargar las imágenes y los audios.
* `setup()` para inicializar el juego.
* `draw()` para actualizar continuamente la pantalla.
* `mousePressed()` para detectar las interacciones del jugador.

Además, utilicé:

* Variables para controlar el estado del juego.
* Arreglos para guardar las canciones, imágenes y respuestas.
* Funciones para organizar el código.
* Condicionales para verificar si una respuesta era correcta.
* Ciclos (`for`) para mostrar automáticamente las portadas.
* `random()` para seleccionar la canción que se reproduce en cada ronda.

Una de las partes que más me costó fue lograr que la canción elegida aleatoriamente siempre coincidiera con la respuesta correcta y que no se repitiera dentro del mismo nivel.

---

## Recursos utilizados

* p5.js
* p5.sound
* Archivos de audio en formato MP3.
* Imágenes de las portadas de los álbumes.

---
## Proceso de desarrollo

Antes de comenzar a programar, pensé en la idea principal del juego y decidí que quería hacer un proyecto donde el sonido fuera el protagonista. Después elegí las nueve canciones y las dividí en tres niveles según su género o la vibra que transmiten.

Una vez definida la idea, empecé creando la estructura básica del juego con una pantalla de inicio y un sistema de estados para controlar las distintas pantallas. Luego incorporé las imágenes de las portadas y los archivos de audio.

La parte que más tiempo me tomó fue desarrollar la lógica para que las canciones se reprodujeran de forma aleatoria sin repetirse dentro del mismo nivel y que la respuesta correcta siempre coincidiera con el audio que estaba sonando.

Finalmente agregué detalles visuales como los botones, los cambios de color al responder y la pantalla final con el puntaje obtenido.

### Registro del proceso

Aquí puedes agregar algunas capturas del desarrollo del proyecto.

#### Boceto inicial

![Boceto](imagenes/boceto.png)

#### Primera versión del juego

![Versión inicial](imagenes/version1.png)

#### Juego terminado

![Versión final](imagenes/final.png)

---

## Posibles mejoras

Si siguiera desarrollando este proyecto, me gustaría agregar:

* Más niveles y más canciones.
* Un cronómetro para responder.
* Diferentes niveles de dificultad.
* Efectos de sonido al acertar o equivocarse.
* Animaciones más elaboradas.
* Un sistema para guardar el mejor puntaje.

---

## Reflexión

Este proyecto me permitió practicar la organización de un programa utilizando distintos estados, además de trabajar con arreglos, funciones y reproducción de audio.

Lo que más aprendí fue a estructurar mejor el código para que cada parte cumpliera una función específica y a resolver problemas relacionados con la lógica del juego, especialmente al momento de elegir canciones de manera aleatoria sin afectar el funcionamiento del resto del programa.

En general, quedé conforme con el resultado porque logré la idea que tenía desde el principio: crear un juego simple, entretenido y donde el sonido fuera el protagonista.
