# INTELIGENCIA
skills varias

## Estructura

### `kits/` — kits completos (abrir cada carpeta con Claude Code y lanzar `/setup`)
| Kit | Qué hace |
|---|---|
| `01-kit-cazador-webs` | Encuentra negocios con webs mejorables y prepara una propuesta/rediseño |
| `02-kit-agente-whatsapp` | Agente de WhatsApp (Next.js) con prompts de negocio, dashboard y deploy |
| `05-kit-editor-video` | Editor de vídeo vertical: cortes, subtítulos, sonido y rótulos |
| `07-kit-analisis-ecommerce` | Análisis/auditoría de tiendas online |

Cada kit trae su propio `EMPIEZA-AQUI.md` y `README.md`.

### `skills-adri-y-juanpe/` — las 10 skills de Adri y Juanpe
`kit-web-scrolling`, `kit-instagram-web`, `kit-dashboard-facturas`, `kit-auditoria-seo`,
`kit-automatizaciones-n8n`, `kit-prospeccion`, `kit-auditoria-negocio`, `kit-auditoria-meta-ads`,
`kit-extension-chrome`, `kit-skill-creator`. Cada una incluye `INSTRUCCIONES.md`.

> **n8n:** en `skills-adri-y-juanpe/kit-automatizaciones-n8n/.mcp.json` hay que poner tu URL
> y tu API key de n8n (vienen con valores de ejemplo).

## Cómo usar las 10 skills (sin instalar nada en el PC)

- **Claude Code en el navegador (claude.ai/code):** abre una sesión sobre este repo. Las 10 skills
  están en `.claude/skills/` de la raíz, así que se cargan solas. Pide por ejemplo
  "audita el SEO de esta web".
- **claude.ai (el chat normal):** Ajustes → Capacidades → Skills → *Subir skill*, y sube el `.zip`
  de cada skill (una carpeta con su `SKILL.md`).

Las copias originales siguen dentro de cada kit en `skills-adri-y-juanpe/`.
