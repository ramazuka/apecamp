# Skills instaladas

Inventario de las skills disponibles en la sesión de Claude Code (21-10-2026), con su habilidad y uso común. En total son unas 125.

## 1. Skills oficiales de Anthropic (instaladas desde anthropics/skills, incluidas en este repositorio)

| Skill | Habilidad | Uso común |
|---|---|---|
| `academy-guide` | Recomienda cursos de Claude Academy | Aprender a usar Claude, proyectos, MCP o plugins |
| `algorithmic-art` | Arte generativo con p5.js | Campos de flujo, partículas, arte con código |
| `brand-guidelines` | Aplica colores y tipografía de Anthropic | Dar estilo de marca a un entregable |
| `canvas-design` | Diseño visual estático en PNG o PDF | Afiches, portadas, piezas gráficas |
| `claude-api` | Referencia de la API de Claude | Programar apps con Claude: modelos, precios, herramientas, caché |
| `discernment-nudge` | Agrega 2 o 3 preguntas de verificación | Revisar supuestos de un consejo, plan o análisis |
| `doc-coauthoring` | Flujo guiado para escribir documentos | Propuestas, especificaciones técnicas, documentos de decisión |
| `docx` | Crear y editar Word | Informes, cartas, plantillas, control de cambios |
| `frontend-design` | Dirección visual para interfaces | Hacer que una web o app no parezca plantilla |
| `internal-comms` | Comunicaciones internas | Reportes de estado, boletines, informes de incidentes |
| `mcp-builder` | Construir servidores MCP | Conectar Claude a una API externa (Python o TypeScript) |
| `pdf` | Manipular PDF | Unir, dividir, extraer texto y tablas, OCR, formularios |
| `pptx` | Crear y editar PowerPoint | Presentaciones, pitch decks, extraer contenido de láminas |
| `skill-creator` | Crear y evaluar skills | Hacer tus propias skills y medir su desempeño |
| `slack-gif-creator` | GIFs animados para Slack | Reacciones y animaciones cortas |
| `theme-factory` | 10 temas de color y tipografía | Dar estilo a láminas, documentos o páginas |
| `web-artifacts-builder` | Apps web complejas (React, Tailwind, shadcn) | Artifacts con estado, rutas y componentes |
| `webapp-testing` | Pruebas web con Playwright | Probar interfaces, capturas de pantalla, depurar |
| `xlsx` | Crear y editar Excel o CSV | Fórmulas, limpieza de datos, gráficos en planillas |

## 2. OmniRoute (45 skills, instaladas desde diegosouzapw/OmniRoute, incluidas en este repositorio)

Sirven para operar el servidor OmniRoute, un gateway que enruta peticiones a varios proveedores de IA (por defecto en `localhost:20128`).

| Skill | Habilidad | Uso común |
|---|---|---|
| `omni-auth` | Autenticación con tokens y sesiones | **Punto de partida** para usar la API |
| `omni-providers` / `cli-providers` | Conexiones a proveedores de IA | Agregar OpenAI, Anthropic u otros y probar sus keys |
| `omni-models` / `cli-models` | Catálogo de modelos | Listar modelos y resolver alias |
| `omni-combos-routing` / `cli-routing` | Combos de enrutamiento (19 estrategias) | Definir modelos de respaldo y balancear carga |
| `omni-inference` / `cli-chat` | Inferencia compatible con OpenAI | Chat, embeddings, imágenes, audio |
| `omni-api-keys` / `cli-keys` | Claves de API de OmniRoute | Crear, rotar o revocar claves con límites |
| `omni-budget` | Presupuestos y límites de uso | Controlar el gasto por clave |
| `omni-usage-logs` / `cli-cost-usage` | Registros y costos | Ver consumo de tokens y gasto por proveedor |
| `omni-cache` | Caché de respuestas | Ahorrar costos con respuestas repetidas |
| `omni-compression` / `cli-compression` | Compresión de prompts | Reducir tokens entre 60 % y 90 % |
| `omni-context-rtk` / `cli-contexts` | Ingeniería de contexto | Filtros RTK y manejo de sesiones |
| `omni-resilience` / `cli-resilience` | Salud y cortes automáticos por fallas | Detectar proveedores caídos o lentos |
| `cli-health` | Estado del servidor | Monitoreo rápido desde la terminal |
| `omni-settings` / `cli-setup` | Configuración global | Asistente de instalación, variables de entorno |
| `cli-serve` | Ciclo de vida del servidor | Iniciar, detener o reiniciar OmniRoute |
| `omni-proxies` | Proxies de salida | Enviar el tráfico por HTTP o SOCKS |
| `omni-tunnels` / `cli-tunnel` | Túneles (ngrok, Cloudflare) | Exponer OmniRoute a internet |
| `omni-mcp` / `cli-mcp` | Servidor MCP con 110 herramientas | Conectar agentes por MCP |
| `omni-agents-a2a` / `cli-a2a` | Protocolo entre agentes (A2A) | Orquestar agentes |
| `omni-webhooks` | Webhooks | Avisos de errores o presupuesto excedido |
| `omni-db-backups` / `cli-backup-sync` / `omni-sync-cloud` | Respaldos y sincronización | Respaldar y restaurar la configuración |
| `omni-version-manager` | Servicios embebidos | Instalar y actualizar 9Router y CLIProxyAPI |
| `omni-cli-tools` / `cli-plugins-skills` | Plugins, skills y memoria | Extender OmniRoute |
| `omni-github-skills` / `cli-skill-collector` | Descubrir skills en GitHub | Buscar e importar skills de la comunidad |
| `cli-policy-audit` | Auditoría y políticas | Cumplimiento normativo, historial de accesos |
| `cli-batches` | Trabajos en lote | Inferencia masiva |
| `cli-eval` | Evaluaciones | Comparar el rendimiento de modelos |
| `config-codex-cli` | Configurar Codex CLI | Usar OmniRoute como backend de Codex |

## 3. Plugin `data`

| Skill | Habilidad | Uso común |
|---|---|---|
| `data:analyze` | Análisis de datos completo | Investigar por qué cayó una métrica |
| `data:build-dashboard` | Dashboards HTML interactivos | Resúmenes ejecutivos con KPIs |
| `data:create-viz` / `data:data-visualization` | Gráficos con Python | Gráficos para informes |
| `data:explore-data` | Perfilado de datasets | Revisar nulos, duplicados y distribuciones |
| `data:sql-queries` / `data:write-query` | Escribir SQL | Consultas para Snowflake, BigQuery o Postgres |
| `data:statistical-analysis` | Estadística | Tendencias, valores atípicos, pruebas de hipótesis |
| `data:validate-data` | Control de calidad de análisis | Revisar un análisis antes de presentarlo |
| `data:data-context-extractor` | Skill con el contexto de tu empresa | Documentar tablas y métricas propias |

## 4. Plugin `engineering`

| Skill | Habilidad | Uso común |
|---|---|---|
| `engineering:architecture` | Registros de decisiones de arquitectura (ADR) | Elegir entre tecnologías |
| `engineering:code-review` | Revisión de código | Seguridad, rendimiento, errores |
| `engineering:debug` | Depuración estructurada | Analizar un error o traza de pila |
| `engineering:deploy-checklist` | Checklist de despliegue | Antes de salir a producción |
| `engineering:documentation` | Documentación técnica | READMEs, runbooks, documentación de APIs |
| `engineering:incident-response` | Manejo de incidentes | Producción caída, postmortem |
| `engineering:standup` | Resumen para la daily | Qué hice, qué haré, bloqueos |
| `engineering:system-design` | Diseño de sistemas | APIs, modelos de datos, servicios |
| `engineering:tech-debt` | Deuda técnica | Priorizar refactorizaciones |
| `engineering:testing-strategy` | Estrategia de pruebas | Planes de testing y cobertura |

## 5. Documentos, LinkedIn y otras (`anthropic-skills:*`)

| Skill | Habilidad | Uso común |
|---|---|---|
| `docs` | Documentos editables en Claude Docs | Informes y propuestas para compartir |
| `docx` / `pdf` / `pptx` / `xlsx` | Archivos de Office y PDF | Igual que las oficiales (están duplicadas) |
| `google-workspace` | Google Docs, Sheets y Slides | Editar archivos en tu Drive |
| `revision-memorias-calculo` | Revisa memorias de cálculo chilenas | Contrastarlas con NCh, OGUC, RIC y RIDAA, con informe en Excel |
| `ponytail` | Modo "senior dev perezoso" | La solución más simple que funciona |
| `morning` | Brief matutino | Resumen diario de agenda y correos |
| `import-memory` | Importar memoria de otro asistente | Migrar desde ChatGPT u otros |
| `skill-creator` | Crear skills | Igual que la oficial (está duplicada) |
| `li-post` / `li-carousel` | Posts y carruseles de LinkedIn | Publicar contenido |
| `li-comment` / `li-reply` | Comentarios y respuestas | Interactuar en el feed |
| `li-dm` / `li-inbox` | Mensajes y bandeja de entrada | Prospección, solicitudes de conexión |
| `li-profile` / `li-audit` | Perfil y analítica | Mejorar el perfil, ver qué funciona |
| `li-plan` / `li-repurpose` | Planificación y reciclaje de contenido | Calendario semanal, convertir un video en posts |
| `li-human` | Hace que un texto suene humano | Quitar marcas típicas de texto escrito por IA |

## 6. Integradas de Claude Code

| Skill | Habilidad | Uso común |
|---|---|---|
| `code-review` / `simplify` / `security-review` | Revisar cambios | Bugs, limpieza de código, seguridad |
| `init` | Crear CLAUDE.md | Documentar un repositorio para Claude |
| `run` | Ejecutar la app | Ver un cambio funcionando |
| `loop` | Tareas recurrentes | "Revisa el deploy cada 5 minutos" |
| `update-config` / `keybindings-help` / `fewer-permission-prompts` | Configuración | Permisos, hooks, atajos de teclado |
| `session-start-hook` | Hook de inicio de sesión | Preparar un repositorio para sesiones en la nube |
| `workflow-authoring` / `plugin-authoring` | Workflows y mods | Orquestar agentes, extender la interfaz |
| `artifact-design` / `artifact-diagramming` / `artifact-capabilities` / `dataviz` | Páginas y gráficos publicados | Dashboards, diagramas, páginas para compartir |

> Nota: `docx`, `pdf`, `pptx`, `xlsx` y `skill-creator` existen tanto en la versión oficial como en `anthropic-skills:*`, y `claude-api` duplica la integrada.
