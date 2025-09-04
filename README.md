# Automatizacion-torno
Este código controla un torno automatizado mediante una placa Arduino, una pantalla LCD 16x2 y una shield de botones analógicos. Su objetivo principal es facilitar el proceso de corte de piezas cilíndricas, permitiendo al usuario seleccionar distintas configuraciones de corte a través de un menú interactivo.

Este código está diseñado para controlar un **torno automatizado** utilizando un **Arduino** con una **pantalla LCD 16x2** y una **shield de botones analógicos**. Su objetivo principal es permitir al usuario seleccionar, desde un menú interactivo, distintos programas de corte para mecanizar piezas con precisión, eligiendo entre **longitudes de corte (4mm a 7mm)** y **direcciones de giro (derecha o izquierda)**.

El sistema cuenta con un menú que despliega opciones al usuario, permitiéndole navegar con botones y ejecutar rutinas específicas de corte. Cada rutina mueve dos motores paso a paso: uno controla el **avance del cabezal** para realizar el corte, y el otro **gira la pieza** (manivela del torno) en la dirección deseada. El número de cortes varía según la longitud seleccionada, y cada rutina realiza automáticamente todos los pasos requeridos para completar el proceso.

Además, incluye una opción de **repetición de prueba**, útil para validaciones rápidas. La interfaz muestra en todo momento información clara del progreso, como el número de corte actual y el total.

En resumen, este código automatiza el proceso de corte en un torno, mejorando la **precisión**, **consistencia** y **facilidad de uso**, especialmente útil en tareas repetitivas dentro de un entorno de mecanizado.
