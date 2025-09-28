# Visión por computador - Práctica II
## Autores
 - Juan Carlos Rodríguez Ramírez
 - Mohamed O. Haroun Zarkik

## Introducción

## Tarea I
El objetivo de la tarea es realizar el conteo de píxeles blancos por filas en la imagen obtenida tras aplicar el detector de bordes de Canny, en lugar de hacerlo por columnas. Se debe determinar el valor máximo de píxeles blancos por fila (maxfil) y mostrar tanto el número de filas como sus posiciones correspondientes, siempre que el número de píxeles blancos en dichas filas sea mayor o igual al 90% de maxfil. La imagen resultante del operador de Canny contiene únicamente valores 0 o 255. 
Para el cálculo se utiliza la función cv2.reduce, que permite obtener la suma de valores por fila. Posteriormente, la suma se normaliza dividiendo entre el número de columnas de la imagen y el valor máximo de un píxel (255), obteniendo así el número de píxeles blancos por fila en valor normalizado. A partir de este resultado se calcula el umbral correspondiente al 90% de maxfil y se seleccionan las filas cuyo número de píxeles blancos sea igual o superior a dicho valor. 
El programa finalmente muestra una representación gráfica con dos partes: la imagen de Canny en escala de grises original y la respuesta de Canny por filas, donde se representa la evolución del número de píxeles blancos a lo largo de la imagen, lo que permite identificar de forma visual las filas que alcanzan al menos el 90% del máximo detectado.

## Tarea II


## Tarea III
La tarea consiste en realizar un carrusel de modos aprendidos durante la asignatura. Para ello, además de poder visualizar la imagen original de la webcam, el programa debe ofrecer la posibilidad de cambiar de modo e incluir al menos dos procesamientos diferentes utilizando las funciones de OpenCV trabajadas previamente. La implementación desarrollada incorpora cinco modos que pueden seleccionarse mediante clics de ratón: modo normal, donde se muestra la imagen sin alteraciones; modo en escala de grises, que convierte el flujo de vídeo a tonalidades grises; modo de diferencia, que calcula el cambio entre fotogramas consecutivos para destacar el movimiento en la escena; modo de localización de zonas más claras y oscuras, donde se identifican los píxeles de mayor y menor intensidad dibujando círculos de colores sobre ellos; y finalmente, un modo artístico de estilo “Pop Art”, que reduce la resolución de la imagen en celdas, calcula la intensidad promedio en cada una y genera un patrón de círculos coloreados en función de dicha intensidad. En todos los casos, el programa muestra un texto sobre la ventana indicando el modo activo y permite cambiar de uno a otro con un clic izquierdo, volviendo al modo normal con un clic derecho. Además, el sistema asegura la conversión a formato BGR en aquellos modos donde la salida es en escala de grises. Para finalizar la ejecución, se pulsa la tecla ESC. Este demostrador ejemplifica de forma interactiva distintas técnicas de procesamiento de imagen aprendidas en clase y facilita su exhibición de manera visual y atractiva.

## Tarea IV
