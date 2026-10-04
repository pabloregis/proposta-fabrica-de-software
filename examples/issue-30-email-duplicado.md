# Exemplo — validação de e-mail duplicado

Este arquivo existe apenas para demonstrar o fluxo Issue → branch → Pull Request → review → merge no GitHub Project.

## Issue relacionada

#30 — Validar e-mail duplicado no cadastro

## Comportamento esperado

- impedir cadastro quando o e-mail já existir;
- retornar `409 Conflict`;
- permitir que o frontend identifique o erro;
- exibir uma mensagem clara ao usuário;
- cobrir o cenário com teste automatizado.

## Observação

Não representa implementação real do ATENA. É apenas uma alteração de demonstração para a proposta da Fábrica de Software.
