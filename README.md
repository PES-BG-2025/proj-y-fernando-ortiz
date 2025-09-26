[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/7IRjtlNy)

# Resumen del Proyecto:

Este proyecto es un simulador del Dilema del Prisionero Iterado hecho en Python. La idea es enfrentar distintas estrategias de juego entre sí, ver cómo se comportan a lo largo de varias rondas y luego comparar cuál funciona mejor según los pagos definidos.

# Lo que hace

Hace que cada estrategia juegue contra todas las demás en partidas de n rondas.

Usa una matriz de pagos (cooperar o traicionar) para calcular los puntos en cada enfrentamiento.

Guarda los resultados en una matriz M, donde se ven los promedios obtenidos contra cada rival.

Al final, saca un puntaje promedio por estrategia y arma un ranking.

# Estructura

Hay una clase base llamada Estrategia y a partir de ella se programan las distintas formas de jugar (ejemplo: Siempre cooperar, Siempre traicionar, Ojo por ojo, Ojo por dos ojos, incluso un jugador que traiciona cada cierto número de turnos).

Se puede ajustar el número de rondas, los valores de los pagos, e incluso meterle un poco de “ruido” para que de vez en cuando una acción se cambie al azar.

# Aporte

El programa sirve para probar y comparar estrategias, ver cuáles sobreviven mejor en distintos escenarios, y entender cómo cambia el resultado cuando se modifican las reglas del juego. También deja la base para proponer en el futuro simulaciones más avanzadas, como poblaciones que evolucionan o estrategias que se van extinguiendo con el tiempo.





# Presentación final del curso de Programación I

Este repositorio tiene como propósito servir de contenedor para los archivos de la presentación final del curso. Se deben guardar todos los archivos utilizados para la presentación (vea las condiciones de entrega más adelante). 

*Banco de Guatemala*  
*Maestría en Economía y Finanzas Aplicadas*  
*Programación I*  
*Fecha: Septiembre de 2025*

## Objetivos

El presente proyecto tiene como objetivo que el estudiante conozca nuevos paquetes del lenguaje de Python o que desarrolle lógica de programación necesaria para realizar alguna aplicación interesante utilizando programación científica o métodos de simulación de Monte Carlo. 


## Rúbrica de evaluación 

| Aspecto a evaluar                                                                             |  Punteo |
|:----------------------------------------------------------------------------------------------|--------:|
| Definición y delimitación del proyecto                                                        |      10 |
| El proyecto requiere conocimientos/esfuerzo adicional al ganado/realizado en el curso         |      10 |
| Participantes del grupo colaboraron cada uno con confirmaciones (*commits*) en el repositorio |      10 |
| Exposición clara, interacción con el público y manejo de los límites de tiempo (5-10 minutos) |      20 |
| El proyecto utiliza conceptos, paquetes, algoritmos o herramientas no vistas en clase         |      20 |
| Dominio del código y manejo de preguntas de los estudiantes o del profesor                    |      30 |
| **Total**                                                                                     | **100** |


## Formato de entrega 

- El proyecto debe entregarse utilizando la plataforma de GitHub, a través de las confirmaciones (*commits*) necesarios por los miembros de cada equipo. 
  - Tomar en cuenta que el repositorio será público. Evitar compartir datos personales, contraseñas u otra información sensible. Los repositorios pueden ser visitados nuevamente en el sitio de la organización `PES-BG-2025` para futuras consultas de parte de todos los estudiantes. 
- Los archivos finales del proyecto se pueden guardar en el directorio raíz del repositorio utilizando cualquier estructura deseada. Sin embargo, si se utilizan archivos de prueba que puedan servir como muestra del procedimiento realizado, pero que no formen parte del proyecto final, se deben guardar en un directorio especial denominado `deprecated`. 
- No cargar archivos al repositorio que sean demasiado grandes (>10MB) como fotografías o vídeos. Utilizar recursos o plataformas web específicamente diseñadas para estos propósitos. La única excepción a esta regla es para el archivo de presentación. 
- Un archivo de presentación es opcional. Si se utiliza una presentación en PowerPoint o PDF, esta debe ser adjuntada en la raíz del proyecto. 
- Al final de la presentación, se dará un tiempo para realizar preguntas, tanto del profesor o de los estudiantes.
- Atender a otras indicaciones adicionales por parte del instructor al inicio y durante la presentación. 
- La fecha de entrega máxima para realizar las confirmaciones será el **jueves 25 de septiembre de 2025 a las 23:59 horas**.

- ## Uso de inteligencia artificial

- En cada presentación, los profesores medirán un índice de uso de inteligencia artifical (IA) de 0 a 10 con base en el dominio del código y preguntas que puedan surgir. 
- Si se detecta el uso de ChatGPT o chatbots para realizar partes significativas del código, se aplicará un factor de descuento con base en este índice:

| Índice de uso (0 - 10)    |  % descuento |
|:-------|--------:|
| 0 - 3  |      0% |
| 4 - 6  |     30% |
| 7 - 8  |     60% |
| 9 - 10 |     90% |

**El uso de IA está permitido, pero su mal uso está prohibido.**

- Ejemplos de buen uso:
  - Explicación de piezas de código o sentencias del lenguaje.
  - Depuración de errores.
  - Elaboración de casos de pruebas.
  - Generación de ideas o mejoras en un programa.
  - Elaborar los docstrings de las funciones.
  - Consulta sobre flujos de trabajo en VSCode, GitHub, etc.
  - Pedir ejemplos sobre cómo utilizar una librería en Python. 
 
- Ejemplos de mal uso: 
  - Pedir a los chatbots que elaboren funciones o clases completas.
  - No entender el código brindado por los chatbots (uso ciego).
  - No entender la organización del código porque todo fue elaborado por el chatbot.

