=========================================
 QUESTIONS — Primeros pasos
=========================================

¿QUÉ ES ESTO?

Questions es un juego de preguntas para el aula.
El profesorado prepara las preguntas (en un archivo con extensión CSV ) y el alumnado juega respondiendo, con marcador, cuenta
atrás y distintos modos de juego.

Funciona en local, sin necesidad de conexión a internet para jugar
(la conexión solo se usa para comprobar si existe una nueva versión
y descargarla).

-----------------------------------------
1. PRIMEROS PASOS
-----------------------------------------

- Descomprime la carpeta completa donde quieras tenerla (escritorio,
  pendrive, etc.). No muevas ni borres ninguna de las carpetas que
  van dentro (Images, JSON, etc.): el programa las necesita para funcionar correctamente.

- Haz doble clic en "Question_version_____.exe" para abrir el programa.

- La primera vez que lo abras no habrá ninguna categoría de preguntas
  cargada todavía. Eso es normal: hay que añadir al menos un archivo
  de preguntas antes de poder jugar.


-----------------------------------------
2. AÑADIR CATEGORÍAS DE PREGUNTAS
-----------------------------------------

- En la pantalla principal, pulsa "Configuración".

- Pulsa el botón para añadir categorías y selecciona la carpeta de
  tu ordenador donde tengas guardados los archivos CSV con las
  preguntas (uno por categoría, por ejemplo "matematicas.csv",
  "geografía.csv"...).

- El programa detecta automáticamente todos los CSV de esa carpeta
  y los añade como categorías nuevas (es normal que no veas nada cuando 
  selecciones la carpeta. Solo tienes que estar seguro de haber elegido la
  carpeta correcta)

- Formato de cada archivo CSV (una pregunta por línea):
      pregunta (fila 1-columna 1) , respuesta correcta (fila 1-columna 2) ,
      respuesta2-distractora (fila 1-columna 3), respuesta 3-distractora  (fila 1-columna 4), 
      respuesta 4-distractora (fila 1-columna 5)
   

  La respuesta correcta va SIEMPRE en segundo lugar, justo después
  de la pregunta. Puedes crear estos archivos con Excel o cualquier
  hoja de cálculo, guardándolos como CSV.

- Desde esa misma pantalla puedes también eliminar categorías que
  ya no quieras usar.

-Un aspecto interesante es que una vez importados los CSV se puede prescindir
 de ellos ya que el juego crea sus propios archivos de consulta.

-El juego es autoportable. Es decir, si copias la carpeta donde está el ejecutable 
 y la pegas en otro ordenador todo el contenido que ya habías cargado (los CSV, Estadísticas, etc)
 viaja con esa carepta.

-----------------------------------------
3. JUGAR UNA PARTIDA
-----------------------------------------

- Desde la pantalla principal, pulsa "Jugar".

- Elige color pulsando el botón de color (cada pulsación lo cambia).

- Escribe tu nombre y pulsa Intro.

- Selecciona con qué categorías quieres jugar (puedes marcar varias
  o todas, pero al menos debes elegir una porque si no no habría preguntas para mostrar).

- Elige el modo de juego:
    * Límite de tiempo: te marca los segundos que tienes para responder. Si se acaban la pregunta se cuenta 
 	como fallada.
    * Límite de errores: puedes establecer el máximo de fallos que peudes cometer. Si se superan se acaba la partida.
  
    * También puedes elegir no tener límite de errores o de tiempo.

	- Pulsa "Empezar a jugar" cuando lo tengas todo listo.


-----------------------------------------
4. DURANTE LA PARTIDA
-----------------------------------------

- Verás la pregunta y cuatro posibles respuestas.

- El marcador de arriba muestra tu nombre, aciertos, fallos,
  la categoría actual, cuántas preguntas llevas y el total.

- Si elegiste modo con límite de tiempo, verás una cuenta atrás
  que cambia de color según se vaya agotando el mismo.

- La partida termina automáticamente al agotar las preguntas
  disponibles, o al cumplirse el límite que hayas elegido
  (tiempo o errores). Desde ahí puedes volver al menú principal
  y jugar de nuevo.


-----------------------------------------
5. ACTUALIZACIONES
-----------------------------------------

- Si el ordenador tiene conexión a internet, el programa comprueba
  automáticamente si existe una versión nueva.

- Si la hay, verás un aviso junto al botón de Configuración.
  Pulsa ahí para ver qué ha cambiado en la nueva versión y decidir
  si quieres actualizar.

- Si no hay conexión a internet, el programa funciona con
  normalidad para jugar; simplemente no podrá comprobar si hay
  actualizaciones disponibles.


-----------------------------------------
6. ALGO NO FUNCIONA
-----------------------------------------

- Si el programa no encuentra ninguna categoría al pulsar "Jugar",
  ve a Configuración y añade al menos un archivo CSV de preguntas.

- Si tienes cualquier problema o duda, estaré encantado de ayudar.

  Nota: este es mi primer proyecto de programación y podrás encontrar fallos,
  y elementos que se pueden mejorar. En este momento estoy en 'make it work', y
  espero pasar al modo 'make it nice' en unos meses. Cualquier ayuda o comentario
  será agradecido. 

=========================================
