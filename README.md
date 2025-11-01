# Herramientas y Procedimientos Estadísticos - Tesis Doctoral

Esta aplicación web interactiva sirve como un anexo pedagógico a una tesis doctoral sobre educación ambiental. Su principal objetivo es desglosar y hacer comprensible el andamiaje metodológico y el proceso de análisis de datos de la investigación.

La herramienta está diseñada para estudiantes, colegas investigadores y cualquier persona interesada en comprender no solo *qué* herramientas estadísticas se utilizaron, sino *por qué* se tomaron esas decisiones y *cómo* se conectan entre sí.

## Ver la Aplicación en Vivo

[**https://su-usuario.github.io/su-repositorio/herramientas-y-procedimientos.html**](https://su-usuario.github.io/su-repositorio/herramientas-y-procedimientos.html)

*(**Nota:** Por favor, reemplace `su-usuario` y `su-repositorio` con los datos correspondientes de su perfil y repositorio en GitHub).*

## Características Clave

-   **Organización por Fases:** El contenido se estructura siguiendo el flujo natural de la investigación: Análisis Descriptivo, Validación del Instrumento y Análisis No Paramétrico.
-   **Ruta de Análisis Narrativa:** Cada herramienta clave incluye una sección de "Conexiones Metodológicas" que explica su rol dentro de la secuencia de análisis, basándose en el diagrama de flujo metodológico de la tesis.
-   **Interactividad:** La información de cada herramienta se presenta en modales detallados que se activan al hacer clic, manteniendo la interfaz limpia y enfocada.
-   **Búsqueda en Tiempo Real:** Permite encontrar rápidamente cualquier herramienta o procedimiento por su nombre.
-   **Diseño Adaptable:** La interfaz es completamente funcional en dispositivos de escritorio y móviles.

## Flujo Metodológico Destacado

La aplicación visualiza la lógica detrás de la selección de pruebas no paramétricas, cubriendo el siguiente proceso:

1.  **Diagnóstico de Supuestos:** Uso de la **Prueba de Shapiro-Wilk** para evaluar la normalidad de los datos.
2.  **Selección de Prueba Principal:** Elección de `Mann-Whitney U` (para grupos independientes), `Wilcoxon` (para muestras relacionadas) o `Kruskal-Wallis` (para 3+ grupos) basándose en los resultados del diagnóstico.
3.  **Cuantificación del Impacto:** Cálculo del **Tamaño del Efecto** con medidas apropiadas como `r de Rosenthal` o `Épsilon Cuadrado (ε²)` para determinar la relevancia práctica de los hallazgos.
4.  **Análisis Post-Hoc:** Explicación del rol condicional de la `Prueba de Dunn` tras un resultado significativo en Kruskal-Wallis.

## Ecosistema del Proyecto

Esta aplicación es una de las tres piezas que componen el ecosistema de divulgación de la investigación:

-   **App de Conceptos y Hallazgos:** Explora los resultados y la narrativa de la tesis.
-   **Tesis Doctoral (PDF):** El documento de investigación completo.

## Tecnologías

-   HTML5
-   CSS3
-   JavaScript Vanilla
-   GitHub Pages para despliegue