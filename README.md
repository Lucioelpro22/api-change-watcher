# API Change Watcher

Dashboard profesional para monitorear documentación de APIs y detectar cambios en endpoints, schemas, campos y precios antes de que impacten en producción.

## Demo

[Abrir la demo publicada](https://api-change-watcher.lucianohernanleal22.chatgpt.site)

## Funcionalidades

- Resumen operativo de APIs monitoreadas, cambios recientes y uptime.
- Clasificación de cambios por severidad: crítico, warning e informativo.
- Detalle de cambios con una vista de diff.
- Filtros rápidos por severidad.
- Flujo interactivo para agregar nuevos monitores.
- Cobertura de endpoints, schemas, campos, planes y precios.
- Diseño responsive para escritorio y dispositivos móviles.

> Los datos incluidos en esta versión son demostrativos y no representan actividad real de los proveedores mencionados.

## Ejecutar localmente

No requiere build ni dependencias. Serví la carpeta `dist` con cualquier servidor estático:

```bash
python -m http.server 4173 --directory dist
```

Luego abrí `http://localhost:4173`.

## Estructura

```text
dist/
  index.html
  styles.css
  app.js
.openai/
  hosting.json
```

## Stack

HTML5, CSS3 y JavaScript nativo.
