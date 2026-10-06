# Documentação da Veronica IA

Documentação pública da Veronica IA, publicada com [Mintlify](https://mintlify.com).

## Estrutura

| Pasta | Conteúdo |
|---|---|
| `index.mdx`, `primeiros-passos.mdx`, `conceitos.mdx` | Comece aqui |
| `agentes/` | Contratar, configurar, prompts, playground, rotinas, colaboração |
| `canais/` | WhatsApp, Canal Web, Slack |
| `conhecimento/`, `conectores/` | Base de conhecimento e integrações |
| `vendas/` | Leads e campanhas |
| `conta/` | Chaves de IA, usuários, planos |
| `api/` | Guias da API e `openapi.json` (referência gerada automaticamente) |

A navegação fica em `docs.json`.

## Rodar localmente

```bash
npm i -g mint
mint dev
```

Abra http://localhost:3000.

## Publicar

Todo push na `main` publica automaticamente pelo app do Mintlify no GitHub. Antes de subir:

```bash
mint broken-links
```
