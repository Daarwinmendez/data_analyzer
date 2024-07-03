# Análisis Dinámico de Datos con NLP

Este proyecto proporciona una herramienta para analizar datos dinámicamente a partir de archivos en formato CSV o Excel (xlsx). Utiliza técnicas de estadística descriptiva y tiene la intención de incorporar procesamiento de lenguaje natural (NLP) en el futuro para generar insights a partir de los datos proporcionados por el usuario.

## Descripción del Proyecto

El objetivo principal de esta herramienta es permitir a los usuarios cargar sus propios conjuntos de datos y obtener un análisis detallado, incluyendo medidas de centralización, tablas de distribución, y gráficos relevantes. En futuras versiones, se planea escalar la funcionalidad para incluir análisis de NLP, permitiendo a los usuarios extraer información valiosa de textos y otros datos no estructurados.

### Características

- **Lectura de Datos**: Soporta la carga de archivos CSV y Excel.
- **Análisis Estadístico**: Calcula medidas de centralización (media, mediana, moda) y genera tablas de distribución.
- **Visualización de Datos**: Crea gráficos de barras y pasteles para representar visualmente los resultados.
- **Integración de NLP**: Próximamente, se implementará análisis de texto utilizando técnicas de NLP.

### Contexto del Programa

Para fines técnicos y de demostración, el programa incluye una matriz aleatoria de tamaño treinta. Esto permite que los usuarios vean un ejemplo funcional del análisis antes de cargar sus propios datos. En futuras versiones, se implementará soporte para archivos CSV y otras extensiones adicionales para proporcionar mayor flexibilidad en la entrada de datos.

## Diagrama de Flujo

A continuación se muestra un diagrama de flujo del proceso general del proyecto:

```mermaid
graph TD;
    A[Usuario] --> B[Análisis de Datos]
    B --> C[Backend]
    C --> D[Procesamiento de Datos]
    D --> E[Análisis Numérico]
    E --> F[Generación de Resultados]
    F --> G[Visualización de Resultados]
