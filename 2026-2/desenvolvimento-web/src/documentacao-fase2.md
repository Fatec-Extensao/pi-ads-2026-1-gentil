# Fase 2 — Desenvolvimento Web (Issue #7)

## Objetivo

Desenvolver a estrutura semântica HTML5 e a estilização CSS das páginas do **Sistema de Pesquisas de Satisfação**, com suporte a diferentes tamanhos de tela e recursos básicos de acessibilidade.

## Estrutura da entrega

Todos os arquivos desta entrega devem ficar na pasta `2026-2/desenvolvimento-web/src/`.

### Páginas HTML

- `index.html`: página inicial do sistema.
- `login.html`: página de login.
- `main.html`: página principal e navegação.
- `acesso-questionario.html`: acesso à pesquisa.
- `questionario.html`: formulário do questionário.
- `gestor-categorias.html`: gerenciamento de categorias.
- `gestor-perguntas.html`: gerenciamento de perguntas.
- `gestor-participacao.html`: acompanhamento da participação.
- `gestor-relatorios.html`: página de relatórios.
- `gerador-codigos.html`: interface de geração de códigos.

### Outros arquivos

- `style.css`: folha de estilos compartilhada pelas páginas.
- `img.png`: imagem utilizada na página inicial.

## HTML5 semântico

As páginas utilizam elementos como `header`, `nav`, `main`, `section` e `footer` para organizar o conteúdo. Formulários usam `form` e `label` quando aplicável.

## CSS responsivo (Mobile-first)

A folha `style.css` define estilos base para telas menores. A regra `@media (min-width: 768px)` adapta espaçamentos, tipografia e navegação para telas maiores. Imagens usam largura máxima relativa ao contêiner.

## Acessibilidade básica

O código inclui rótulos em campos de formulários, texto alternativo na imagem da página inicial, indicação visual de foco por `:focus-visible` e adaptação do layout.

## Limites da verificação

Esta documentação foi elaborada com base na análise dos arquivos de código. Ainda é recomendável abrir as páginas no navegador, verificar os links e formulários, testar em tela pequena e conferir contraste e navegação por teclado antes de marcar a issue como concluída.
