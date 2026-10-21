# apecamp

Skills de Claude Code. Al abrir este repositorio en una sesión de Claude Code, las skills de `.claude/skills/` se cargan solas.

Ver [SKILLS.md](SKILLS.md) para el inventario completo de skills.

Contenido actual (commits de origen en `SOURCE`):

- Las 19 skills oficiales de [anthropics/skills](https://github.com/anthropics/skills). Cada skill conserva su propio archivo de licencia.
- Las 45 skills de [OmniRoute](https://github.com/diegosouzapw/OmniRoute) (`omni-*`, `cli-*`, `config-codex-cli`), licencia MIT en `licenses/LICENSE-OmniRoute`.

## Levantar el servidor OmniRoute

Las skills de OmniRoute necesitan el servidor corriendo. Requiere Node.js ≥ 22.22.2 o ≥ 24.

```bash
npm install -g omniroute
omniroute serve --no-open --headless --no-tray   # API en http://localhost:20128/v1
omniroute doctor
```
