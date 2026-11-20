```text
                         ADS-II
             Projeto Integrador — 2026/2



     Sistema Web para Gestão de
Pesquisas por Questionários
        gEOVANNA CIRIACO, GIULIA GENTIL, ISABELA ERMINIA
      POLIANA BENEDITO, RAFAELA CAVALHEIRO, YARA TORRES



                                                           FATEC LINS
```

```text
Por que desenvolver
   esse sistema?
    Sobre o sistema

         O projeto consiste no desenvolvimento de uma solução web para
    gestão de pesquisas por questionários.

         A proposta é organizar a criação e o gerenciamento de pesquisas,
    possibilitando a estruturação de questionários, o registro de respostas e a
    consulta de resultados.

       O trabalho integra conhecimentos de Desenvolvimento Web, Banco de
    Dados, Engenharia de Software e Segurança da Informação.
```

```text
     Objetivo do projeto
Objetivo geral
Desenvolver a estrutura de um sistema web para gerenciamento de
pesquisas por questionários, integrando conhecimentos das disciplinas
do curso de Análise e Desenvolvimento de Sistemas.

Objetivos específicos
   Estruturar páginas web utilizando HTML5 e CSS3.
   Planejar a organização das pesquisas e dos questionários.
   Modelar um banco de dados relacional.
   Representar os processos do sistema por diagramas UML.
   Identificar riscos relacionados à segurança da informação.
   Considerar princípios da Lei Geral de Proteção de Dados (LGPD).
```

```text
          Visão geral do sistema
Funcionalidades previstas

  O sistema foi planejado para permitir a administração de pesquisas e questionários em um
ambiente web.

Principais funcionalidades:
   Autenticação: disponibilizar uma interface de acesso ao sistema.
   Gestão de pesquisas: organizar pesquisas cadastradas.
   Questionários: estruturar perguntas e categorias.
   Respostas: permitir a coleta e o armazenamento de respostas.
   Resultados: organizar informações para consultas e relatórios.

    O desenvolvimento foi dividido entre a estrutura das páginas, a modelagem dos dados e a
documentação dos processos.

  As funcionalidades descritas representam o escopo planejado; sua implementação completa
depende da integração das diferentes partes do sistema.
```

```text
        Desenvolvimento Web
Estruturação das interfaces com HTML5 e CSS3
    Nesta etapa, foram desenvolvidas páginas que representam a interface do Sistema de
Gestão de Pesquisas de Satisfação.

Tecnologias utilizadas:
   HTML5: estruturação das páginas, formulários, tabelas e elementos semânticos.
   CSS3: estilização visual e organização da apresentação dos conteúdos.
   Git e GitHub: versionamento e armazenamento dos arquivos do projeto.

   O desenvolvimento também considerou aspectos de acessibilidade, como identificação de
campos, organização dos conteúdos e navegação entre páginas.

     Situação atual: a estrutura HTML/CSS foi trabalhada, enquanto a implementação de
interatividade e validações com JavaScript permanece pendente.
```

```text
Banco de Dados
Modelagem e organização das informações
O banco de dados foi estruturado com o objetivo de representar as
informações necessárias ao gerenciamento de pesquisas e questionários.

      Principais entidades trabalhadas:            Conceitos aplicados:
                                                       Modelagem de banco de dados relacional.
         GESTOR: informações relacionadas à            Definição de chaves primárias e
         administração do sistema.                     estrangeiras.
         PESQUISA: identificação das                   Relacionamentos entre tabelas.
         pesquisas cadastradas.                        Comandos SQL para criação e
         CATEGORIA: classificação dos                  manipulação de dados.
         questionários.                                Organização de scripts SQL no GitHub.
         QUESTIONARIO: organização dos
         questionários de pesquisa.                   A modelagem estabelece a base
         PERGUNTA: armazenamento das               necessária para armazenar e relacionar os
         perguntas                                 dados do sistema.
```

```text
Engenharia de Software
Análise, requisitos e modelagem
                                          Artefatos desenvolvidos ou
UML
   A Engenharia de Software foi
                                          trabalhados:
utilizada para organizar a estrutura do
sistema e representar seu                   Levantamento de requisitos: definição das
funcionamento antes da implementação        necessidades e funcionalidades do sistema.
completa.                                   Diagrama de Casos de Uso: representação
                                            das interações dos usuários com o sistema.
                                            Diagrama de Classes: identificação dos
Ferramenta utilizada:                       principais elementos e relacionamentos do
Astah, para elaboração e organização        domínio.
dos diagramas UML.                          Diagrama de Sequência: representação da
                                            ordem das interações em um processo.
A modelagem contribui para a                Diagrama de Atividades: representação dos
documentação, compreensão e                 fluxos de execução.
planejamento da solução.
```

```text
Segurança da Informação e LGPD
 Proteção dos dados e identificação de riscos
 O planejamento de segurança do sistema considera a importância de proteger as informações das pesquisas e reduzir possíveis
 vulnerabilidades.

 Riscos considerados:
    Acesso não autorizado às informações.
    Exposição indevida de dados e respostas.
    Tentativas de injeção de SQL.
    Preenchimentos fraudulentos.
    Armazenamento inadequado de informações.

 Medidas e princípios estudados:
    Confidencialidade, integridade e disponibilidade.
    Controle de acesso e proteção de credenciais.
    Identificação e classificação de riscos.
    Minimização da coleta de dados pessoais.
    Privacidade e anonimato dos respondentes.
    Diretrizes para retenção e exclusão de dados.

 A documentação de segurança tem como objetivo orientar o desenvolvimento de uma aplicação mais segura e alinhada à LGPD.
 Esses itens representam requisitos e medidas planejadas, não uma certificação de conformidade ou implementação integral dos
 controles.
```

```text
        Resultado do projeto:
              Resultados alcançados:

              O Projeto Integrador possibilitou a aplicação prática dos conhecimentos adquiridos
              ao longo do semestre, reunindo diferentes áreas do desenvolvimento de sistemas.




Principais resultados:

   Desenvolvimento de interfaces web utilizando HTML5 e
   CSS3.                                                                             O projeto demonstrou a integração
   Estruturação das funcionalidades e navegação do sistema.                          entre as disciplinas e a importância
   Modelagem do banco de dados e criação de scripts SQL.                            do planejamento, da modelagem e da
   Elaboração de diagramas UML para representação do                                 documentação no desenvolvimento
   sistema.                                                                                      de software.
   Documentação de requisitos de segurança da informação e
   LGPD.
   Organização e versionamento dos arquivos no GitHub.
```

```text
Considerações finais:
    O desenvolvimento do Sistema Web para Gestão de Pesquisas por
Questionários proporcionou a aplicação prática de conceitos estudados
ao longo do semestre.
    A integração entre Desenvolvimento Web, Banco de Dados,
Engenharia de Software e Segurança da Informação permitiu
compreender diferentes etapas da construção de um sistema.
    Além dos conhecimentos técnicos, o projeto contribuiu para o
desenvolvimento de habilidades de organização, documentação, análise
de requisitos e versionamento de arquivos.
    O projeto constitui uma base para a evolução de uma solução web
mais completa, integrada e segura.


                                                        Obrigada!
```
