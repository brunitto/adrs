# AMBIENTE DE DESENVOLVIMENTO

## Contexto

TODO.

## Decisão

- Usar um ambiente de desenvolvimento simples de configurar e replicar.

## Consequências

TODO.

## Implementação

- Usar [Dev Containers](https://containers.dev) para configurar e provisionar ambientes de desenvolvimento com containers.
- Usar [Docker](https://docker.com) como runtime e gerenciador de imagens e containers.
- Usar um container chamado "workspace" para todas as aplicações e bibliotecas.
- Usar containers separados para os serviços e ferramentas.
- Usar a extensão do VS Code ou a CLI do Dev Containers.
- Usar variáveis de ambiente para qualquer configuração, evitar configurações manuais e arquivos de configuração.
- Usar [dotenv](https://www.dotenv.org/) para definir e exportar variáveis de ambiente.
