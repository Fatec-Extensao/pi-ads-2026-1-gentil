# Banco de Dados — Fase 2

## Issue #4 — Modelagem Lógica e Script DDL de Criação

### Normalização

O mapeamento atual está normalizado. Justificativa apresentada:

1. **Primeira Forma Normal (1FN):** Todos os atributos são monovalorados e atômicos.
2. **Segunda Forma Normal (2FN):** Os campos não chave dependem da chave primária.
3. **Terceira Forma Normal (3FN):** Não existem atributos não chave que dependem de outros atributos não chave.

> **Observação:** Esta é a justificativa de normalização fornecida para o projeto; a comprovação formal depende da análise das dependências funcionais e das regras de negócio.

### Modelo lógico — tabelas

O script DDL fornecido apresenta as tabelas `GESTOR`, `PESQUISA`, `CATEGORIA`, `QUESTIONARIO`, `PERGUNTA`, `ALTERNATIVA`, `CODIGO_ANONIMO`, `SUBMISSAO` e `RESPOSTA`.

Cada tabela possui sua chave primária. As relações estão declaradas por chaves estrangeiras no script. A tabela `CODIGO_ANONIMO` também possui uma restrição de unicidade para `hash_codigo` e uma verificação de valor para `utilizado`.
