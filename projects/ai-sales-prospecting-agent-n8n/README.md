# AI Sales Prospecting Agent - n8n

## Objetivo

Automatizar parte do processo de prospeccao comercial B2B usando IA para pesquisar uma conta, entender contexto, sugerir dores provaveis e gerar uma mensagem personalizada de abordagem.

## Problema

Times comerciais e criativos gastam muito tempo pesquisando empresas, organizando contexto e criando mensagens personalizadas. O resultado muitas vezes fica disperso em abas, planilhas, notas e conversas.

## Solucao

Um fluxo no n8n recebe dados basicos de uma conta e gera uma ficha de prospeccao com:

- resumo da empresa;
- possivel contexto de negocio;
- dores ou oportunidades provaveis;
- angulo de abordagem;
- mensagem curta para LinkedIn;
- e-mail inicial;
- sugestao de follow-up;
- registro em planilha/CRM.

## Ferramentas previstas

- n8n;
- OpenAI API, Anthropic API ou Google AI Studio;
- HTTP Request para APIs externas;
- Google Sheets, Airtable, Notion ou CRM;
- webhooks;
- e-mail ou Slack/WhatsApp para notificacao.

## Fluxo resumido

1. Entrada via webhook ou formulario.
2. Normalizacao dos dados da empresa.
3. Enriquecimento com pesquisa/API.
4. Analise com IA.
5. Geracao de mensagem personalizada.
6. Registro em planilha/CRM.
7. Notificacao do responsavel.

## Como demonstrar

Use `examples/input.json` como entrada e compare com `examples/output.md`.

O arquivo `workflow.json` serve como template importavel/adaptavel no n8n.
