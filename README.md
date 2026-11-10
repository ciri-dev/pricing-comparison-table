# Pricing Comparison Table - roadmap.sh

Una página web estática de una sola página que presenta una tabla comparativa de planes de suscripción totalmente accesible y estructurada con HTML semántico. Este proyecto forma parte de los proyectos prácticos de [roadmap.sh](https://roadmap.sh/projects/pricing-comparison-table).

## Descripción del Proyecto

El objetivo principal de este proyecto es aprender a mostrar datos estructurados utilizando tablas HTML reales y accesibles (`<table>`), garantizando una correcta jerarquía de encabezados, uso de leyendas (`<caption>`) y alcances (`scope`) para lectores de pantalla. En esta fase inicial, **no se incluye CSS** para enfocar todos los esfuerzos puramente en la semántica y la estructura del marcado.

## Características y Requisitos Implementados

- **Estructura Semántica de la Página:** Uso de etiquetas contenedoras principales como `<header>`, `<main>` y `<footer>`.
- **Tabla HTML Robusta:** Empleo explícito de `<thead>` y `<tbody>` para separar las filas de encabezado de las filas de datos.
- **Leyenda Descriptiva (`<caption>`):** Posicionado como el primer hijo de la tabla para nombrar claramente el propósito de los datos comparados.
- **Accesibilidad con Alcances (`scope`):**
  - `scope="col"` en los encabezados de columna.
  - `scope="row"` en las celdas que identifican el nombre de cada plan de suscripción.
- **Celdas Combinadas (`colspan` / `rowspan`):** Implementación de `colspan` en una fila inferior para abarcar información relevante que aplica a todos los planes ("All plans include SSL and daily backups").
- **Metadatos en el Head:** Configuración correcta de `<title>`, `<meta charset="UTF-8">` y `<meta name="viewport">`.

## Tecnologías Utilizadas

- **HTML5** (Semántica y Accesibilidad WAI-ARIA / Estándar)

Desarrollado como parte de las rutas de aprendizaje de [roadmap.sh](https://roadmap.sh/).