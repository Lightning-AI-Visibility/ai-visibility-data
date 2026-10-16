<p align="center"><img src="icono.png" width="96" alt="Lightning"></p>

# Lightning · AI Visibility Data

**How ChatGPT, Gemini and Claude answer people, for any region and industry:** which brands they recommend, in what order, with what arguments and which sources they cite. Built on custom-designed universes of AI interactions and AI journeys of both humans and agents. Each catalog study is sold whole, for **USD 0.99**, to AI agents and developers.

**Cómo responden ChatGPT, Gemini y Claude, para cualquier región e industria:** qué marcas recomiendan, en qué orden, con qué argumentos y qué fuentes citan. Cada estudio parte de un diseño a medida del universo de interacciones IA y de journeys IA de humanos y de agentes. Cada estudio del catálogo se vende completo, a **USD 0,99**, a agentes de IA y desarrolladores.

> This repository has no code. It describes the service and holds its MCP Registry entry.
> Este repositorio no tiene código: describe el servicio y contiene su ficha para el registro de MCP.

## What's in a study / Qué trae cada estudio

- **Question-universe design:** what was asked and why / diseño del universo de preguntas.
- **Every raw model answer,** with date, model and cited sources / todas las respuestas crudas.
- **Analysis tables** with Lightning metrics: AI Prominence, Mention, Average Position, Top1, Citation, HHI, Variability, Survival and Tone / tablas de análisis con métricas Lightning.
- **Findings** with numeric backing and evidence / hallazgos con respaldo.
- **Formats:** JSON for agents; Excel and PDF reports for people / JSON para agentes, Excel y PDF para personas.

Current catalog (live) / catálogo actual: **[api.lightningeo.com/catalogo](https://api.lightningeo.com/catalogo)**. Today's studies were run in Argentina and the Southern Cone, in Spanish / los estudios de hoy se hicieron en Argentina y el Cono Sur, en español. They cover banking, car insurance, cosmetics, pharma and OTC brands, atopic dermatitis, rheumatology, running retail, hotel chains and tourism.

## Custom studies, any region or industry / Estudios a medida, cualquier región o industria

We design the universe of AI interactions for your market: what people and agents ask, in which language, with which personas and intents. We also design complete AI journeys of humans and of AI agents, from first question to purchase. Then we run and analyze them with the same Lightning metrics. Write to delivery@lightningeo.com.

Diseñamos el universo de interacciones IA de tu mercado: qué preguntan personas y agentes, en qué idioma, con qué perfiles e intenciones. También diseñamos journeys IA completos de humanos y de agentes, desde la primera pregunta hasta la compra. Después los corremos y analizamos con las mismas métricas Lightning. Escribinos a delivery@lightningeo.com.

## Connect via MCP / Conectar por MCP

| Server | URL | What it does |
|---|---|---|
| Catalog only (free, read-only) | `https://api.lightningeo.com/mcp/catalogo` | List and search studies, free study sheets, metric definitions. No payments. |
| Full | `https://api.lightningeo.com/mcp` | Same, plus `comprar_estudio`: pays USD 0.99 via x402 (needs an x402-capable client with a wallet). |

Add either URL as a custom connector in Claude, ChatGPT, Cursor or any MCP client. No account or API key.

## Buy over HTTP with x402 / Comprar por HTTP con x402

1. `GET https://api.lightningeo.com/estudio/{slug}` → HTTP 402 with price and payment details.
2. Sign the USDC payment on **Base** with any x402 client (for example `@x402/fetch`).
3. Retry with the `PAYMENT-SIGNATURE` header → the full study plus 7-day download links.

Each study costs USD 0.99, within the default USD 1 per-payment cap of official x402 clients. You are not charged if the study isn't delivered.

## Links

- Service and docs: [api.lightningeo.com](https://api.lightningeo.com)
- For agents: [llms.txt](https://api.lightningeo.com/llms.txt) · [OpenAPI](https://api.lightningeo.com/openapi.json) · [x402 manifest](https://api.lightningeo.com/.well-known/x402)
- Privacy: [api.lightningeo.com/privacidad](https://api.lightningeo.com/privacidad)
- Contact: delivery@lightningeo.com · [lightningeo.com](https://lightningeo.com)

Made by **Lightning**, a GEO / AI-visibility consultancy in Buenos Aires.
