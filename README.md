# NEXO — Sitio web

Sitio de **NEXO Centro de Exámenes** (nexoexamenes.com) — centro de exámenes no invasivos de alta precisión, especializado en elastografía hepática.

## Qué es esto

Sitio estático (HTML + assets). Mantiene el diseño aprobado y corrige los datos de relleno que traía la plantilla original:

- Preguntas frecuentes con las respuestas reales
- Credenciales ARDMS
- Dirección, teléfono y correo reales, con enlaces
- Horario unificado

## Estructura

- `index.html` — el sitio
- `assets/` — imágenes, estilos y scripts

## Publicar

Desplegado en Vercel. Cada push a `main` publica automáticamente una vez conectado el repo.

Deploy manual desde esta carpeta:

```
npx vercel deploy --prod
```

## Pendientes

- Pista para el médico derivador (hoy el sitio es 100% paciente)
- Testimonios y fotos reales
- Blog (todavía con textos de ejemplo)
