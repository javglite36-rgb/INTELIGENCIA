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

## Instalar las 10 skills en tu ordenador (para usarlas en cualquier carpeta)

1. Descarga el repo (botón verde **Code → Download ZIP** en GitHub) y descomprímelo.
2. Abre **PowerShell** dentro de la carpeta descomprimida y pega:

```powershell
New-Item -ItemType Directory -Force "$HOME\.claude\skills" | Out-Null
Get-ChildItem "skills-adri-y-juanpe\*\.claude\skills\*" -Directory | Copy-Item -Destination "$HOME\.claude\skills" -Recurse -Force
```

3. Cierra y vuelve a abrir Claude Code. Escribe `/` y verás las skills en la lista.

(En Mac/Linux: `mkdir -p ~/.claude/skills && cp -r skills-adri-y-juanpe/*/.claude/skills/* ~/.claude/skills/`)
