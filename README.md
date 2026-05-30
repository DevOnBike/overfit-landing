# Overfit landing — Bielik update

Static GitHub Pages landing for Overfit.

## Updated positioning

> Private LLMs, Bielik, RAG, C# tool calling and guaranteed JSON inside your .NET app — no Python, no Ollama, no model server, no data egress.

## Files

- `index.html` — main landing with Bielik as visible CTA
- `bielik-dotnet-agent.html` — dedicated Bielik / Polish local agent page
- `enterprise-dotnet-ai-integration.html` — commercial integration page
- `zero-allocation-llm-inference-csharp.html` — technical build-log page
- `privacy.html` — static mailto privacy note
- `robots.txt`, `sitemap.xml`
- `CNAME`

## Primary demo CTA

```bat
cd Demo\LocalAgentAspNetDemo
.\download-bielik.cmd
.\download-embedder.cmd
.\run-bielik.cmd
```

## Wording note

Use "well-formed JSON object" for `/decision/refund` until full field-level JSON Schema enforcement is public.
