&#x20;Simulación Física: Dispara al Mono



&#x20;Descripción del Proyecto



Este proyecto consiste en una simulación interactiva del problema físico conocido como "Dispara al Mono". El objetivo es representar mediante una animación el movimiento de un proyectil y la caída libre de un mono para demostrar cómo actúa la gravedad sobre ambos cuerpos al mismo tiempo.



La simulación fue desarrollada utilizando HTML, CSS y JavaScript, permitiendo modificar diferentes variables iniciales para observar cómo cambian los resultados del experimento.



\---



&#x20;Integrantes



\* Ana Fuentes

\* Kelly Fuentes

\* Mario Grillo

\* Genesis Ramos

\* Allysson Palma



\---



&#x20;Objetivo



Desarrollar una simulación que permita visualizar los conceptos de movimiento parabólico y caída libre, aplicando las ecuaciones de la mecánica clásica y mostrando los resultados en tiempo real.



\---



Funcionamiento de la Simulación



El usuario puede modificar diferentes valores antes de iniciar la simulación:



\* Velocidad inicial del proyectil.

\* Ángulo de disparo.

\* Distancia horizontal del mono.

\* Altura inicial del mono.



Una vez configurados los datos, la simulación calcula continuamente la posición del proyectil y del mono utilizando las ecuaciones físicas correspondientes.



Durante la ejecución también se muestran los valores calculados en tiempo real para facilitar el análisis del comportamiento de ambos objetos.



\---



&#x20;Ecuaciones Utilizadas



&#x20;Posición horizontal del proyectil



x(t) = v₀ · cos(θ) · t



Esta ecuación permite calcular la distancia horizontal recorrida por el proyectil.



&#x20;Posición vertical del proyectil



y(t) = v₀ · sin(θ) · t − ½ · g · t²



Se utiliza para determinar la altura del proyectil en cada instante.



&#x20;Caída libre del mono



yₘ(t) = h − ½ · g · t²



Representa la altura del mono mientras cae debido a la gravedad.



&#x20;Distancia entre ambos objetos



d = √\[(xₘ − x)² + (yₘ − y)²]



Esta ecuación permite determinar si existe una colisión entre el proyectil y el mono.



\---



&#x20;Características del Programa



&#x20;Panel de Control



Permite modificar las variables iniciales mediante controles deslizantes y campos numéricos sincronizados.



&#x20;Área de Simulación



Muestra gráficamente:



\* El cañón.

\* El proyectil.

\* El mono.

\* La trayectoria recorrida por el proyectil.

\* La cuadrícula de referencia.



&#x20;Telemetría



Durante la simulación se muestran:



\* Tiempo transcurrido.

\* Posición horizontal del proyectil.

\* Posición vertical del proyectil.

\* Posición horizontal del mono.

\* Posición vertical del mono.

\* Distancia entre ambos objetos.



&#x20;Detección de Colisiones



El sistema verifica constantemente la distancia entre el proyectil y el mono. Cuando ambos se encuentran dentro del rango de colisión establecido, se muestra un mensaje indicando que ocurrió el impacto.



\---



&#x20;Estructura General del Código



El proyecto está dividido en tres partes principales:



&#x20;HTML



Contiene la estructura de la interfaz, incluyendo controles, paneles informativos y el área de simulación.



&#x20;CSS



Se encarga del diseño visual de la aplicación, los colores, la distribución de los elementos y la adaptación a diferentes tamaños de pantalla.



&#x20;JavaScript



Gestiona toda la lógica de la simulación:



\* Control de variables.

\* Aplicación de fórmulas físicas.

\* Animación de objetos.

\* Detección de colisiones.

\* Actualización de datos en tiempo real.



\---



&#x20;Conclusión



Con este proyecto fue posible aplicar conceptos de física y programación para representar visualmente el movimiento parabólico y la caída libre. Además, permitió integrar cálculos matemáticos, animaciones y elementos interactivos dentro de una aplicación web funcional.



