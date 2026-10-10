# AGENTS.md — repo `page` (sitio público estático)

> **Lee primero el plan maestro completo:** `../AGENTS.md` (raíz del proyecto). Copia canónica
> versionada: `../test-manager-library-3413974-docs/AGENTS.md`. Este archivo es solo un puntero.

## Reglas duras (resumen; detalle en el maestro §1)
- Sitio **estático**: se abre **sin la API**; no hace llamadas a `/api`.
- Todo con **Docker** (`docker compose build page`).
- Responsive: correcto a 375 px y 1440 px.
- **Commits pequeños** (`page: …`) y **push** al fork `cuchau115/test-manager-library-3413974-page`.
- Toda tarea exige **evidencia** (se abre `index.html` / build ok).

## Tareas de este repo (maestro §9.9)
`PAGE-01`…`PAGE-04`. Modelo: `opencode/deepseek-v4-flash`. **No depende de nada: puede empezar ya.**
