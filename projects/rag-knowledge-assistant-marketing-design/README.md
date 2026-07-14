# RAG Knowledge Assistant for Marketing and Design

## Objetivo

Criar um assistente interno que responde perguntas usando uma base de conhecimento propria, com documentos, FAQs, briefings, textos comerciais, referencias, processos e materiais de projeto.

## Problema

Empresas criativas acumulam conhecimento em documentos, propostas, pastas, conversas e referencias dispersas. Isso dificulta respostas rapidas, consistencia de discurso e reaproveitamento de repertorio.

## Solucao

Um fluxo RAG que:

1. recebe uma pergunta;
2. busca trechos relevantes na base de conhecimento;
3. envia contexto para um modelo de IA;
4. retorna uma resposta com base nos documentos;
5. indica fontes ou trechos usados.

## Ferramentas previstas

- n8n;
- OpenAI/Anthropic/Google AI;
- Supabase, pgvector, Pinecone, Chroma ou banco vetorial similar;
- parser de PDF/documentos;
- Google Drive, Notion, pastas locais ou CMS;
- webhook ou chat interno.

## Casos de uso

- atendimento interno;
- pesquisa de projetos passados;
- apoio comercial;
- criacao de propostas;
- consulta a processos;
- base de perguntas e respostas;
- onboarding de equipe.
