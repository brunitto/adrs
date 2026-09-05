# ADRS

## Contexto

- Projetos e sistemas de softwares são impactados pela qualidade das decisões de arquitetura e tecnologia.
- As decisões são tomadas dentro de um contexto e têm consequências (prós e contras). Entender este contexto e ter consciência sobre as consequências é essencial para tomar boas decisões.
- Com o tempo, as pessoas e agentes de IA esquecem das decisões e podem tomar ou ignorar decisões sem contexto.

## Decisão

- Usar ADRs para registrar decisões de arquitetura e tecnologia importantes para os projetos e sistemas de software.

## Consequências

Prós:

- As pessoas e agentes de IA conseguem recuperar o contexto e avaliar as consequências das decisões tomadas.
- As pessoas e agentes de IA investem mais tempo alinhando o contexto e avaliando as consequências antes de tomar decisões.
- As ADRs podem ser usadas como parte da camada de _feedforward_ da arquitetura Harness.

Contras:

- Trabalho adicional para escrever e manter as ADRs atualizadas.

## Implementação

- Esta ADR deve ser usada como modelo para outras ADRs.
- Toda decisão importante de arquitetura ou tecnologia deve ser registrada como uma ADR.
- Cada ADR é estruturada como um arquivo Markdown usando o padrão de nome `<titulo-adr>.md`.
- As ADRs não precisam de ID nem status. O título da ADR é o seu ID. Todas ADRs na _branch_ `main` estão aprovadas.
- As ADRs devem incluir as seções:
  - Contexto: lista de fatos e limitações relacionados à decisão.
  - Decisão: a decisão definida em um parágrafo.
  - Consequências: lista de prós e contras da decisão.
  - Implementação: detalhes sobre como implementar a decisão, incluindo regras e exemplos.
 
