# Instruções para agentes de IA neste repositório

## Sobre o projeto

- Documentação pública da **Veronica IA**, publicada pelo [Mintlify](https://mintlify.com).
- Páginas em MDX com frontmatter YAML; configuração em `docs.json`.
- A referência da API é gerada de `api/openapi.json`.
- Todo push na `main` publica em produção.

## Público

- Aba **Guias**: clientes (empresas) que usam o painel. Linguagem simples, sem jargão técnico.
- Aba **API**: desenvolvedores que integram sistemas.

## Terminologia

- "Funcionário IA" ou "agente". Nunca "bot" ou "chatbot".
- "Empresa", não "tenant", nos guias.
- "Conector" para integrações.
- "Chave de IA" para a chave do provedor (BYOK).
- Não existem créditos de IA: o cliente paga o provedor direto e a Veronica IA cobra por vaga de agente.
- Nunca citar OpenClaw, MCP, MongoDB, Qdrant ou nomes internos de infraestrutura.

## Estilo

- Português do Brasil, com acentuação correta.
- Segunda pessoa ("você"), voz ativa, uma ideia por frase.
- Nomes de botões e telas em **negrito**, exatamente como aparecem no painel.

## Segurança

O repositório é público. Nunca incluir segredos, tokens, IDs reais de agentes ou empresas, URLs internas ou detalhes de endpoints administrativos.
