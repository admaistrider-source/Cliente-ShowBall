# ShowBall

Projeto do cliente ShowBall, desenvolvido pela AI Strider.

## Stack
<!-- Preencher: linguagem, framework backend, framework frontend, banco de dados, hospedagem. -->
A definir.

## Comandos
<!-- Preencher quando o projeto existir. -->
- Instalar: 
- Rodar local: 
- Lint / typecheck: 
- Testes: 

## Grupo de agentes de desenvolvimento
Os agentes ficam em `.claude/agents/`. Fluxo padrão para cada funcionalidade:

1. **arquiteto** planeja: critérios de aceite, modelo de dados, contrato de API e divisão de tarefas.
2. **backend** e **frontend** implementam em paralelo, seguindo o contrato combinado.
3. **qa-testes** valida os critérios de aceite e completa os testes automatizados.
4. **revisor-codigo** revisa o diff antes do PR; itens bloqueantes voltam para quem implementou.
5. **devops** cuida de CI, ambientes e deploy (deploy em produção só com aprovação).

Para bugs: **qa-testes** reproduz, **backend** ou **frontend** corrige, **revisor-codigo** revisa.

## Convenções
- Código e nomes técnicos em inglês; textos da interface, commits e documentação em português.
- Uma branch por tarefa e PR pequeno com descrição "Antes / Depois / Como testar".
- Decisões de arquitetura em `docs/decisoes/`.
