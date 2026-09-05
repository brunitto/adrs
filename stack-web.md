# STACK WEB

## Contexto

- Stacks definem os conjuntos de tecnologia usadas para um objetivo comum.
- Stacks não são certas ou erradas, mas têm prós e contras, e funcionam melhor ou pior dependendo do contexto.
- Desenvolvimento web é baseado em HTTP, navegadores, JavaScript, HTML, CSS, etc.
- Uma stack full inclui frontend (APP) e backend (API).

## Decisão

- Usar uma stack completa, priorizando velocidade e qualidade sobre performance e suporte à processamento assíncrono.

## Consequências

- Prós:
  - Alta velocidade de desenvolvimento, incluindo servidor de desenvolvimento, rotas baseadas em sistema de arquivos, e gerenciamento de banco de dados.
  - Alta qualidade de desenvolvimento, incluindo testes E2E, SSR e otimização de imagens.
- Contras:
  - Baixa performance, alto custo de processamento (Node, Playwright) e armazenamento (npm, Next.js).
  - Limitado para páginas e APIs, excluindo processamento assíncrono com maior volume de dados e latência.

## Implementação

Tecnologias:

- Usar Node como runtime.
- Usar npm como gerenciador de dependências, pacotes e scripts.
- Usar Playwright como ferramenta de testes E2E.
- Usar Next.js como framework web full-stack.
- Usar Prisma como ORM e ferramenta de migrations.
- Usar Tailwind como ferramenta de CSS.
