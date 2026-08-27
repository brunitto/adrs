# MONOREPO

## Contexto

- Todo código de um sistema de software é armazenado em um ou mais repositórios.
- A quantidade de repositórios impacta o processo de dependências e mudanças do sistema.
- Usar vários repositórios (polyrepo) cria autonomia para os times mas aumenta a complexidade para gerenciar dependências e fazer mudanças no sistema.
- Usar apenas um repositório (monorepo) reduz a complexidade para gerenciar dependências e mudanças mas adiciona complexidade no gerenciamento do repositório.

## Decisão

Usar apenas um repositório (monorepo) para sistemas de software, para reduzir a complexidade de dependências e mudanças do sistema.

## Consequências

Prós:

- Reduz a complexidade para gerenciar dependências e mudanças no sistema.
- Aumenta o contexto das pessoas e agentes de IA no desenvolvimento.

Contras:

- Aumenta a complexidade no gerenciamento do repositório, principalmente no processo de _build_ e uso de tecnologias diferentes.

## Implementação

- Um sistema deve usar um único repositório (monorepo).
- O monorepo deve ser estruturado para diferentes projetos (aplicações, bibliotecas, serviços, ferramentas, etc).
- O README deve conter informações sobre como usar o monorepo.
- O uso do monorepo deve ser 100% automatizado a partir de scripts.

Exemplo de monorepo:

```plaintext
monorepo/
  apps/              # Aplicações.
    api/
    web/
    worker/
  config/            # Configurações.
    .env.example
    .env.development
    .env.test
  docs/              # Documentação.
    adrs/
    handbook/
    system/
  infra/            # Infraestrutura.
    cache/
    database/
    stream/
  libs/             # Bibliotecas.
    core/
    security/
    observability/
  specs/            # Especificações.
  README.md
  LICENSE
  ...
```

Exemplos de comandos:

- `build`: compila todo o sistema.
- `test`: testa todo o sistema.
- `lint`: analisa o código de todo o sistema.
- `start`: inicia o ambiente de desenvolvimento.
- `stop`: pára o ambiente de desenvolvimento.
- `restart`: reinicia o ambiente de desenvolvimento.
- `create`: cria o ambiente de desenvolvimento.
- `destroy`: destrói o ambiente de desenvolvimento.
- `reset`: destrói e cria o ambiente de desenvolvimento.
