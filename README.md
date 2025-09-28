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

## Tarea IV
