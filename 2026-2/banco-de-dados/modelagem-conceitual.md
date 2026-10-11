# Banco de Dados — Modelagem Conceitual e Mapeamento de Entidades

**Projeto:** Sistema de Pesquisas Institucionais  
**Disciplina:** Banco de Dados  
**Origem:** `entidades-mapeamento.pdf`

## 1. Entidades identificadas

- GESTOR
- CATEGORIA
- PERGUNTA
- ALTERNATIVA
- QUESTIONÁRIO
- CÓDIGO_ANÔNIMO
- PESQUISA
- SUBMISSÃO
- RESPOSTA

## 2. Observação sobre o anonimato

Aluno não é uma entidade porque o sistema foi pensado para não identificar quem responde ao questionário. O aluno é um **ator** que interage com o sistema.

## 3. Mapeamento apresentado no trabalho

A tabela abaixo reproduz o mapeamento textual do documento original. A notação `*` indica o identificador e `--` é mantida conforme a representação de referências no trabalho.

| Nome usado no mapeamento | Atributos apresentados |
| --- | --- |
| Gestor | `*id_gestor`, `nome`, `e-mail`, `senha` |
| Pesquisa | `*id_pesquisa`, `titulo`, `data_inicio`, `data_fim`, `--id_gestor` |
| Categoria | `*id_categoria`, `nome`, `descricao` |
| Questionário | `*id_questionario`, `--id_pesquisa`, `--id_categoria` |
| Pergunta | `*id_pergunta`, `enunciado`, `tipo_resposta`, `--id_questionario` |
| Alternativa | `*id_alternativa`, `texto`, `--id_pergunta` |
| Participante | `*id_codigo`, `hash_codigo`, `utilizador (boolean)`, `--id_questionario` |
| Resposta | `*id_resposta`, `--id_pergunta`, `--id_alternativa` |

## 4. Diagrama Entidade-Relacionamento (DER)

Imagem extraída do diagrama incluído no documento original:

![Diagrama Entidade-Relacionamento do sistema de pesquisas institucionais](diagramas/diagrama-der.png)


