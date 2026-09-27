# ia-local-starter

Kit mínimo para correr IA local con Ollama + opencode. Gratis, privado, sin nube.

## Requisitos

- Mac, Windows o Linux
- 8 GB RAM mínimo (16 GB recomendado)

## Instalación

```bash
# 1. Instalar opencode
curl -fsSL https://opencode.ai/install | bash

# 2. Instalar Ollama -> https://ollama.com

# 3. Bajar modelo y probar
ollama run llama3.2
```

Luego en la carpeta del proyecto:

```bash
opencode
```

## Skills incluidas (8)

Están en `skills/` y se cargan automático:

- **api-and-interface-design** — diseña APIs/interfaces
- **autonomous-loops** — loops autónomos
- **code-review-and-quality** — revisión de código
- **context-engineering** — configura contexto del agente
- **documentation-and-adrs** — docs y decisiones
- **open-design** — proyectos visuales
- **test-driven-development** — desarrollo con tests
- **using-agent-skills** — invoca skills

Usar: `/skill nombre` dentro de opencode o el agente las llama solo.

## Ejemplo

```bash
opencode
> crea una landing con open-design
```