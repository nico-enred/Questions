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
  y los añade como categorías nuevas (Solo tienes que estar seguro de haber elegido la
  carpeta correcta)

- Formato de cada archivo CSV (una pregunta por línea):
      pregunta (fila 1-columna 1) 
      respuesta correcta (fila 1-columna 2) 
      respuesta2-distractora (fila 1-columna 3)
      respuesta 3-distractora  (fila 1-columna 4)
      respuesta 4-distractora (fila 1-columna 5)

  Ejemplo:  ¿Cuál es la capital de Francia?  París  Londres  Roma  Berlín
			¿Cuánto es 2+2?  4  3  5  6
			¿Quién pintó la Mona Lisa?  Leonardo da Vinci  Picasso  Velázquez  Goya

  IMPORTANTE:
  
  En caso de utilizar LIbreOffice para crear el CSV desmarcar la casilla de "Tabulador" en el diálogo inicial si abrimos un CSV   existente. Y dejar marcado las comas como separadores.
  Si lo estamos creando desde cero:
  Al guardar: usa Archivo > Guardar como > Texto CSV, marca la casilla "Editar configuración de filtro", y en el diálogo selecciona Coma como delimitador (o separador) de campo. Desmarca Tabulador (si apareciera la opción).

  Si usas Excel en Windows:

    Asegúrate de que el separador de listas de Windows está configurado como coma (,). Se cambia en Panel de Control > Región >  	Configuración adicional > Separador de listas.

    Al guardar, usa la opción "CSV UTF-8 (delimitado por comas)" si está disponible.
  

- Desde esa misma pantalla puedes también eliminar categorías que
  ya no quieras usar.

-Una vez importados, los CSV ya no son necesarios: el juego guarda su propia copia interna de las preguntas. Puedes mover o borrar los CSV originales sin afectar al juego.

-El juego es portable. Es decir, si copias la carpeta donde está el ejecutable 
 y la pegas en otro ordenador todo el contenido que ya habías cargado (los CSV, Estadísticas, etc)
 viaja con esa carpeta.

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
    * Límite de errores: puedes establecer el máximo de fallos que puedes cometer. Si se superan se acaba la partida.
  
    * También puedes elegir no tener límite de errores o de tiempo.

	- Pulsa "Empezar a jugar" cuando lo tengas todo listo.


-----------------------------------------
4. DURANTE LA PARTIDA
-----------------------------------------

- Verás la pregunta y cuatro posibles respuestas.

- El marcador de arriba muestra tu nombre, aciertos, fallos,
  la categoría actual, cuántas preguntas llevas y el total.

- Si elegiste modo con límite de tiempo, verás una cuenta atrás
  que cambia de color según se vaya agotando.

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

  Nota: este es mi primer proyecto de programación y podrás encontrar fallos,
  y elementos que se pueden mejorar. En este momento estoy en 'make it work', y
  espero pasar al modo 'make it nice' en unos meses. 
=========================================
