#  CyberSystems // Audio Intelligence Dashboard

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Status](https://img.shields.io/badge/status-8th_Semester_Engineering-neon)

Un reproductor de música de alto rendimiento con estética **Cyberpunk/Glassmorphism**, diseñado para demostrar la integración de procesamiento de señales de audio en tiempo real mediante la **Web Audio API**.

##  Características Técnicas (Core)

* **Procesamiento de Señal en Tiempo Real:** Implementación de un `AnalyserNode` para la extracción de datos de frecuencia (FFT) a 60 FPS.
* **Visualización Reactiva:** Interfaz dinámica impulsada por algoritmos de normalización de bajos y escala logarítmica para el "baile" del núcleo visual.
* **Arquitectura Dashboard:** Diseño basado en micro-ventanas utilizando **CSS Grid** y **Flexbox** para una gestión eficiente del espacio de trabajo.
* **Audio Engine Blindado:** Sistema de manejo de promesas asíncronas para evitar bloqueos de seguridad del navegador (CORS & Autoplay Policy).

##  Stack Tecnológico

* **Frontend:** HTML5 (Semántico), CSS3 (Custom Properties & Back-drop Filters).
* **Lógica:** JavaScript ES6+ (Event-Driven Architecture).
* **API:** Web Audio API (AudioContext, Analyser, MediaElementSource).

##  Arquitectura de Visualización

El sistema procesa el flujo de audio dividiéndolo en dos ramas principales:
1.  **Rama de Salida:** Conexión directa al `AudioDestination` (altavoces).
2.  **Rama de Análisis:** Extracción de bytes de frecuencia para manipular el DOM y el elemento `<canvas>` de forma reactiva.



## Instalación y Despliegue Local

Para visualizar este proyecto en tu entorno local (recomendado usar Manjaro Linux):

1. Clona el repositorio:
   ```bash
   git clone [https://github.com/TU_USUARIO/wow-player.git](https://github.com/TU_USUARIO/wow-player.git)
