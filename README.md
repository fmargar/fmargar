## Fernando Máximo Martínez García

**Desarrollador Full Stack** · IA en producción · agentes de IA · Python · Laravel · Docker — Marbella (Málaga)

Llevo la IA a producción con criterio de ingeniería: un LLM que propone y una persona que aprueba antes de publicar nada.
Dirijo varios agentes de IA en paralelo sobre mi propio servidor y con ellos construyo y despliego productos completos.
Que una IA escriba el código no lo hace apto para producción: lo hace el sistema de alrededor (diseño por escrito, tests, CI obligatoria y revisión).
Uso IA a diario desde principios de 2026, y de forma muy intensiva con Claude Code desde julio.

*I build production software with AI agents, and the guardrails that make it shippable.*

### Proyectos

| | |
|---|---|
| **[Adivinadle](https://adivinadle.com)** | Juegos diarios de adivinar personajes de videojuegos: 9 juegos, 4 modos y casi 1.800 personajes. Laravel 13 + Octane, PostgreSQL, Redis, Astro y Svelte con contrato OpenAPI. CI con PHPStan al máximo, Pest, Vitest y Playwright en móvil y escritorio, con axe y Lighthouse. Construido dirigiendo agentes de IA. |
| **[Wardux](https://wardux.com)** | Web de guías, pruebas de IA y hardware explicado, en producción. Astro + Laravel, con su propio panel, analítica sin cookies y una redacción asistida por agentes con revisión antes de publicar. |
| **[Equipo de agentes en paralelo](https://fmargar.es/work/agentes-ia)** | Un agente por proyecto y un supervisor que los arranca, vigila y reanuda. El estado vive en una hoja de ruta versionada: al 30 % de contexto, relevo a un agente nuevo que solo lee ese fichero. La máquina se reparte por presión real de CPU y memoria (PSI de Linux). |
| **[LLM en el ERP](https://fmargar.es/work/uniformes-bahia)** | Módulo de Odoo que redacta la descripción de cada producto desde su ficha técnica con la API de OpenAI. Entra como borrador, con autoría registrada, y un responsable lo aprueba antes de publicarlo (*human-in-the-loop*). |
| **[Visión en local](https://fmargar.es/work/vision-local)** | Qwen3-VL-4B cuantizado a 4 bits (NF4) en 2,7 GB de VRAM para automatizar interfaces por visión. Evaluado con un conjunto de prueba antes de decidir entrenarlo: 6/6 pantallas y 15/15 clics, sin entrenar. |
| **[Infraestructura propia](https://fmargar.es/work/homelab)** | Servidor Linux con más de 100 contenedores, Tailscale, Cloudflare Tunnels y Access, logs centralizados y copias cifradas fuera de casa. Orquestador en Node.js + PostgreSQL que sustituyó 28 temporizadores sueltos. |
| **[Gestión de vados · Ayto. de Marbella](https://fmargar.es/work/sistema-vados-marbella)** | Laravel 12, React 18, Inertia y PostgreSQL: importadores de datos heredados, cinco roles con alcance territorial y auditoría de cada cambio. |
| **[Marbella Fácil](https://marbellafacil.com)** | Mi TFG (10, Matrícula de Honor): plataforma publicada de turismo y ciudad con Laravel 12, React 19, MySQL, Docker y pagos con Stripe. |

### Stack

- **IA y LLM:** Claude Code, Codex y Gemini en el día a día; OpenAI integrado por API en producción; servidores MCP, coordinación multiagente, *context engineering*, modelos en local (Qwen3-VL, bitsandbytes), evaluación con conjunto de prueba
- **Lenguajes:** Python, PHP, TypeScript, JavaScript, SQL
- **Backend y datos:** Laravel, Node.js, PostgreSQL, MySQL, Redis, OpenAPI, ETL, Odoo
- **Frontend:** Astro, Svelte, React, Next.js, Tailwind CSS
- **DevOps y calidad:** Docker, Linux, GitHub Actions, Playwright, PHPStan, Pest, Vitest, Nginx, Caddy, Cloudflare, Tailscale

### Contacto

[fmargar.es](https://fmargar.es) · [LinkedIn](https://www.linkedin.com/in/fernando-maximo-martinez-garcia) · [fmargardeveloper@gmail.com](mailto:fmargardeveloper@gmail.com) · [CV en PDF](https://fmargar.es/cv/fernando-martinez-cv.pdf)
