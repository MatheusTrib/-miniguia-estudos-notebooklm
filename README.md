# 📚 Miniguia de Equilíbrio de Mercado com Apoio de IA

![Status](https://img.shields.io/badge/status-concluído-success)
![Projeto Educacional](https://img.shields.io/badge/foco-educacional-blue)
![Ferramentas](https://img.shields.io/badge/IA-ChatGPT%20%7C%20NotebookLM-purple)
![Licença](https://img.shields.io/badge/licença-MIT-green)

Projeto desenvolvido como exercício de **elaboração de um caderno temático no NotebookLM**, utilizando **Inteligência Artificial Generativa como ferramenta de apoio ao estudo e organização do conhecimento**.

O resultado final é um **miniguia didático sobre o conceito econômico de equilíbrio de mercado**, estruturado a partir de:

- curadoria de fontes
- síntese conceitual
- elaboração didática
- glossário técnico
- documentação metodológica

---

# 📑 Índice

- [Objetivo do Projeto](#-objetivo-do-projeto)
- [Escolha do Tema](#-escolha-do-tema)
- [Fluxo Metodológico](#-fluxo-metodológico)
- [Etapas do Projeto](#-etapas-do-projeto)
  - [1. Curadoria de Fontes](#1-curadoria-de-fontes)
  - [2. Construção no NotebookLM](#2-construção-no-notebooklm)
  - [3. Construção do Glossário](#3-construção-do-glossário)
  - [4. Consolidação do Miniguia](#4-consolidação-do-miniguia)
- [Uso de Inteligência Artificial](#-uso-de-inteligência-artificial)
- [Reprodutibilidade](#-reprodutibilidade)
- [Estrutura do Repositório](#-estrutura-do-repositório)
- [Links do Projeto](#-links-do-projeto)
- [Considerações Finais](#-considerações-finais)

---

# 🎯 Objetivo do Projeto

O presente projeto tem como objetivo **satisfazer o desafio de elaborar um caderno temático no NotebookLM sobre um assunto financeiro introdutório**.

Além disso, o projeto busca demonstrar de forma prática **como ferramentas de IA generativa podem auxiliar no processo de estudo**, apoiando etapas como:

- pesquisa
- síntese de conteúdo
- organização didática
- construção de material educacional

Todo o processo foi **documentado para garantir transparência e reprodutibilidade**.

---

# 🧠 Escolha do Tema

O processo iniciou com uma solicitação ao **ChatGPT** para sugerir possíveis temas dentro da área de **finanças ou economia introdutória**.

Entre as sugestões apresentadas, foi escolhido:

> **Equilíbrio de Mercado**

A escolha ocorreu por se tratar de um **conceito fundamental da microeconomia**, além de ser um tema que sempre despertou interesse durante a graduação.

O equilíbrio de mercado representa o ponto em que:

Quantidade Demandada = Quantidade Ofertada


Esse ponto determina o **preço de equilíbrio** e a **quantidade de equilíbrio** em um mercado competitivo.

---

# ⚙️ Fluxo Metodológico

O processo seguido neste projeto pode ser representado pelo fluxo abaixo:

```mermaid
flowchart TD

A[Escolha do Tema] --> B[Curadoria de Fontes com ChatGPT]
B --> C[Importação das Fontes no NotebookLM]
C --> D[Resumo Estruturado do Tema]
D --> E[Criação de Glossário]
E --> F[Consolidação do Miniguia]
F --> G[Documentação no GitHub]

----------------
🧩 Etapas do Projeto

1. Curadoria de Fontes
Após a definição do tema, foi utilizada a funcionalidade Pesquisa Aprofundada do ChatGPT para realizar uma curadoria inicial de materiais confiáveis sobre o tema.

Foi solicitado que o modelo assumisse a persona de:

Profa. Dra. Sônia — Professora universitária de Introdução à Economia, com pesquisa focada em equilíbrio de mercado

A partir desse prompt, o modelo retornou uma lista de materiais recomendados, contendo:

links

justificativa de relevância

breve resumo conceitual

📄 O retorno completo pode ser consultado em:

Retorno Dra. Sonia.md
Esse material foi utilizado como base para inserção de fontes no NotebookLM.

2. Construção no NotebookLM
Após a curadoria inicial, as fontes selecionadas foram inseridas no NotebookLM, onde foi solicitada a criação de um resumo estruturado do tema.

O objetivo era produzir um conteúdo com características semelhantes a um material de revisão pré-prova, contendo:

conceitos fundamentais

explicações didáticas

exemplos práticos

analogias explicativas

Sempre mantendo uma linguagem acessível e levemente bem-humorada, alinhada à persona utilizada.

3. Construção do Glossário
Para complementar o material de estudo, foi criado um glossário técnico em ordem alfabética.

Inicialmente, tentou-se gerar o glossário junto com o relatório principal. No entanto, foi observado que:

⚠️ Quando o glossário era solicitado junto com o relatório, o modelo limitava os termos apenas aos conceitos mais presentes no próprio texto.

Por esse motivo, o glossário foi solicitado em um prompt separado, o que produziu um resultado mais completo e abrangente, considerando melhor os termos das fontes.

4. Consolidação do Miniguia
Após a produção do resumo e do glossário, foi consolidado o miniguia de estudo, contendo:

introdução ao tema

fundamentos de oferta e demanda

explicação do equilíbrio de mercado

desajustes de mercado

intervenções governamentais

elasticidade

glossário técnico

apêndices metodológicos

📄 O material final pode ser consultado em:

miniguia.md
Nesse documento também estão incluídos os prompts utilizados no processo.

🤖 Uso de Inteligência Artificial
Durante o desenvolvimento deste projeto, ferramentas de IA foram utilizadas como assistentes cognitivos para apoiar o processo de estudo.

As principais contribuições foram:

curadoria inicial de fontes

síntese de conteúdo acadêmico

organização didática de conceitos

auxílio na estruturação textual

No entanto, é importante destacar que:

A IA foi utilizada como ferramenta de apoio, e não como substituta da análise crítica humana.

A curadoria final e organização do material permaneceram sob supervisão humana.

🔁 Reprodutibilidade
Uma das preocupações deste projeto foi permitir a reprodução do processo metodológico.

Por isso foram documentados:

os prompts utilizados

as fontes selecionadas

o fluxo de produção do material

Isso permite que outros estudantes ou pesquisadores possam:

replicar o experimento

adaptar o método para outros temas

utilizar o fluxo como modelo de estudo com IA.

📂 Estrutura do Repositório
.
├── README.md
├── miniguia.md
├── Retorno Dra. Sonia.md
└── materiais/
🔗 Links do Projeto
Notebook utilizado no processo:

📎 NotebookLM
https://notebooklm.google.com/notebook/7a635cb0-6ac9-4be2-858d-1c4bcb51a49c

🎓 Considerações Finais
Este projeto demonstra como ferramentas de Inteligência Artificial podem ser integradas ao processo de estudo e produção de material educacional.

Quando utilizadas de forma estruturada e crítica, essas ferramentas podem contribuir para:

acelerar a pesquisa

organizar conteúdos complexos

facilitar a construção de materiais didáticos

Sem substituir a curadoria e análise humana, que continuam sendo elementos fundamentais no processo educacional.

📘 Projeto desenvolvido como exercício de elaboração de caderno temático no NotebookLM com apoio de IA generativa.


---
