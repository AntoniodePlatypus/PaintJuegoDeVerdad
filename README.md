# Actividad: Paint con Turtle

Este repositorio contiene la implementación interactiva del juego de dibujo **Paint** utilizando Python y las librerías `turtle` y `freegames`. 

El objetivo del proyecto es adaptar el código base para extender sus capacidades mediante la adición de nuevas herramientas de dibujo y opciones de color, organizando el desarrollo en ramas independientes por cada integrante del equipo.

---

## 📄 Descripción del Repositorio

El proyecto contiene el archivo principal `paint.py`, el cual inicializa un lienzo interactivo de $420 \times 420$ píxeles. Permite seleccionar puntos con el ratón para trazar figuras geométricas y alternar entre colores mediante comandos de teclado.

---

## 🛠️ Cambios Realizados por Actividad y Rama

### Rama `main` (Código Base)
* Estructura inicial del lienzo con `freegames`.
* Soporte para trazado de líneas (`l`) y cuadrados (`s`).
* Configuración de colores primarios: Negro (`K`), Blanco (`W`), Verde (`G`), Azul (`B`) y Rojo (`R`).
* Funcionalidad para deshacer la última acción (`u`).

---

### Rama `integrante1-circulo y color` (Integrante 1)
* **Inclusión de la figura Círculo:** Se implementó la función `circle_shape(start, end)`, permitiendo calcular dinámicamente el radio mediante la distancia euclidiana entre el punto inicial de clic y el punto final:
  $$r = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2}$$
  Mapeado a la tecla **`c`**.
* **Adición del color Naranja:** Se añadió la selección de color naranja mapeada a la tecla **`O`** (`orange`).

---

### Rama `integrante2-figuras` (Integrante 2)
* **Inclusión de la figura Rectángulo:** Se implementó la función `rectangle(start, end)`, la cual calcula el ancho ($\Delta x$) y alto ($\Delta y$) para trazar los 4 lados mediante un bucle de 2 repeticiones. Mapeado a la tecla **`r`**.
* **Inclusión de la figura Triángulo:** Se implementó la función `triangle(start, end)`, dibujando un triángulo equilátero mediante giros de $120^\circ$ basándose en la distancia horizontal ($\Delta x$). Mapeado a la tecla **`t`**.

---

## 🚀 Instrucciones de Ejecución

1. Clonar el repositorio:
   ```bash
   git clone [https://github.com/AntoniodePlatypus/PaintJuegoDeVerdad.git](https://github.com/AntoniodePlatypus/PaintJuegoDeVerdad.git)
   cd PaintJuegoDeVerdad
