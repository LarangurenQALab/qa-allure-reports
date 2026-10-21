# QA Allure Reports

Repositorio dedicado a alojar reportes Allure de QA. Cada carpeta en la raíz es un proyecto distinto con su propio reporte estático generado por `allure generate`.

## Estructura

```
qa-allure-reports/
├── index.html              <- landing page con el listado de proyectos
├── qa-dashboard-demo/      <- reporte Allure del proyecto demo
└── <otro-proyecto>/        <- un folder nuevo por cada proyecto futuro
```

## Cómo agregar un reporte nuevo

1. Generar el reporte estático del proyecto: `npx allure generate allure-results --clean -o allure-report`.
2. Copiar el contenido de `allure-report/` a una carpeta nueva en la raíz de este repo, con el nombre del proyecto.
3. Agregar un link a esa carpeta en `index.html`.
4. Commit + push.

Publicado vía GitHub Pages.
