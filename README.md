# Evidencia: Seguimiento de Mariquitas (ESP32-S3)

Este repositorio contiene los videos de validación del sistema embebido TinyML (arquitectura FOMO) ejecutado físicamente en la ESP32-S3. La evidencia está organizada según la resolución de entrada del modelo evaluado:

## 📁 96x96
Modelos entrenados y ejecutados a una resolución de 96x96 píxeles.
* **Video 1:** Prueba en fondo con alto contraste y sin oclusiones. Mantiene rastreo ininterrumpido (10/10 aciertos, 100% confianza).
* **Video 2:** Prueba en entorno de mayor complejidad (follaje denso, oclusiones parciales y mayor velocidad de desplazamiento del insecto). Registra interrupciones por baja resolución espacial (6/10 aciertos, 85.00% confianza).

## 📁 128x128
Modelos entrenados y ejecutados a una resolución de 128x128 píxeles.
* **Video 1:** Prueba en fondo con alto contraste y sin oclusiones. Mantiene rastreo ininterrumpido (10/10 aciertos, 98.00% confianza).
* **Video 2:** Prueba en entorno de mayor complejidad (follaje denso, oclusiones parciales y mayor velocidad de desplazamiento del insecto). Demuestra una retención superior a través del follaje (8/10 aciertos, 96.25% confianza).
