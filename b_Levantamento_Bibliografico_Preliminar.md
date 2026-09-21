# Etapa (b) — Levantamento Bibliográfico
---
## 1. Identificação do Grupo
| Campo | Informação |
|---|---|
| Curso / Disciplina | `[Ciências da computação]` |
| Projeto de Pesquisa / IC | `[Análise de Algoritmos e Eficiência Operacional em Sistemas de Inteligência Artificial]` |
| Orientador(a) | `[Andrea Ono Sakai]` |
| Data de entrega desta etapa | `[11/09/2026]` |
| Integrantes do grupo | `[Henrique de Figueiredo Lourenço, Nicolas Silva Rodrigues de Melo, Victor Alexandre Dorea Randis ]` |
| Tema (da etapa "a") | `[qual o custo operacional das diferentes estrategias de recuperação de informaçao utilizadas em uma arquitetura RAG]` |
---
## FASE 1 — Planejamento da Busca

### Passo 1 — Pergunta de pesquisa e palavras-chave
**1.1 Problema/pergunta de pesquisa (versão de trabalho)** 
> `[Qual é o custo computacional das estratégias de recuperação densa e híbrida utilizadas em arquiteturas RAG, considerando aspectos como tempo de recuperação, uso de memória e escalabilidade?]`

**1.2 Conceitos-chave e sinônimos**
| Conceito-chave | Sinônimos / termos relacionados (PT) | Sinônimos / termos relacionados (EN) |
|---|---|---|
| `[RAG]` | `[Geração Aumentada por Recuperação]` | `[Retrieval-Augmented Generation, RAG, retrieval-augmented systems]` |
| `[Escalabilidade]` | `[escalabilidade computacional]` | `[computational scalability]` |
|  `[Custo computacional]` | `[Custo operacional, complexidade computacional, custo de processamento]` | `[Computational cost, computational complexity, processing cost]` |
|  `[Memória]` | `[Uso de memória]` | `[    ]` | 
`[BM25]` | `[Recuperação BM25, Recuperação Esparsa` | `[Best Matching 25, sparse retrieval]` |
`[Recuperação Densa]` | `[Busca Semântica]` | `[Dense Retrieval]` |
`[Recuperação Hibrida]` | `[Busca híbrida]` | `[hybrid Retrieval]` |  
*Responsável por este passo: `[Henrique de Figueiredo Lourenço]`*
---
### Passo 2 — Strings de busca
| Nº | String de busca | Base(s) em que será usada | Elaborada por |
|---|---|---|---|
| 1 | `[("Retrieval-Augmented Generation" OR RAG) AND ("BM25")]` | `[IEEE Xplore, DOAJ, CAPES]` | `[Nicolas]` |
| 2 | `[("Retrieval-Augmented Generation" OR RAG) AND ("Dense Retrieval")]` | `[IEEE Xplore, DOAJ, CAPES]` | `[Henrique]` |
| 3 | `[("Retrieval-Augmented Generation" OR RAG) AND ("Hybrid Retrieval")]` | `[IEEE Xplore, DOAJ, CAPES]` | `[Nicolas]` |
    
--- 
### Passo 3 — Bases de dados escolhidas
| Base de dados | Por que foi escolhida | Responsável pela busca nesta base |
|---|---|---|
| `[IEEE Xplore]` | `[Possui artigos relacionados à Inteligência Artificial, algoritmos e recuperação de informação ]` | `[Victor Alexandre]` |
| `[DOAJ]` | `[É uma das principais fontes de literatura científica em Ciência da Computação e Tecnologia da Informação]` | `[Victor Alexandre]` |
|`[CAPES]` | `[quantidade de artigos relacionados a pesquisas hibridas.]` | `[Victor Alexandre]` |


### Passo 4 — Critérios de inclusão e exclusão

**Critérios de inclusão:**
- `[Artigos publicados nos últimos 10 anos]`
- `[Trabalhos relacionados a arquiteturas RAG;]`
- `[Artigos em português/inglês]`
- `[Trabalhos que apresentem informações sobre custo computacional ou desempenho;]`
- `[Trabalhos que apresentem métricas de recuperação; ]`

**Critérios de exclusão:**
- `[Trabalhos que não tenham relação direta com RAG;]`
- `[Duplicatas]`
- `[Trabalhos que não apresentem informações relacionadas a custo ou desempenho;]`
- `[Trabalhos fora do tema proposto;]`
- `[Trabalhos sem metodologia ou resultados suficientes para comparação.]`

*Definidos em conjunto por: `[Henrique de Figueiredo Lourenço, Nicolas Silva Rodrigues de Melo e Victor Alexandre Dorea Randis.]`*

---

## FASE 2 — Execução da Busca e Triagem

### Passo 5 — Execução das buscas e registro dos resultados

| Base | String usada (nº) | Data da busca | Nº de resultados | Executada por |
|---|---|---|---|---|
| `[IEEE Xplore]` | `[RAG AND BM25]` | `[18/09/2026]` | `[07]` | `[Henrique Lourenço]` |
| `[IEEE Xplore]` | `[RAG AND Dense Retrieval]` | `[18/09/2026]` | `[11]` | `[Henrique Lourenço]` |    
| `[IEEE Xplore]` | `[RAG AND Hybrid Retrieval]` | `[18/09/2026]` | `[31]` | `[Henrique Lourenço]` |
| `[DOAJ]` | `[RAG AND BM25]` | `[18/09/2026]` | `[29]` | `[Victor Alexandre]` |
| `[DOAJ]` | `[RAG AND Dense Retrieval]` | `[18/09/2026]` | `[59]` | `[Victor Alexandre]` |
| `[DOAJ]` | `[RAG AND Hybrid Retrieval]` | `[18/09/2026]` | `[140]` | `[Victor Alexandre]` |
| `[CAPES]` | `[RAG AND BM25]` | `[18/09/2026]` | `[01]` | `[Nicolas Silva]` |
| `[CAPES]` | `[RAG AND Dense Retrieval]` | `[18/09/2026]` | `[02]` | `[Nicolas Silva]` |
| `[CAPES]` | `[RAG AND Hybrid Retrieval]` | `[18/09/2026]` | `[05]` | `[Nicolas Silva]` |

**Total de resultados brutos (soma de todas as buscas):** `[285]`

**Gerenciador de referências utilizado:** `[Zotero]`
**Formato de exportação:** `[RIS]`

---

### Passo 6 — Triagem por título e resumo (1ª filtragem)

*Leia apenas título e resumo de cada resultado. Classifique: incluir / excluir / dúvida. Remova duplicatas entre bases.*

| Item de controle | Quantidade |
|---|---|
| Total de resultados antes da triagem | `[285]` |
| Duplicatas removidas | `[30]` |
| Classificados como "Incluir" | `[05]` |
| Classificados como "Excluir" | `[170]` |
| Classificados como "Dúvida" | `[79]` |

**Como as dúvidas foram resolvidas?**
`[discussão em grupo e pesquisas acerca dos artigos para verificar se é cabivel aos tema do projeto.]`

*Responsável(is) por esta triagem: `[Henrique de Figueiredo, Nicolas Melo]`*

---

### Passo 7 — Triagem por leitura completa (2ª filtragem)

*Para os artigos que passaram na primeira filtragem, leia introdução e conclusão. Aplique os critérios de inclusão/exclusão (passo 4) de forma mais rigorosa.*

| Item de controle | Quantidade |
|---|---|
| Total de artigos que entraram nesta filtragem | `[85]` |
| Aprovados (conjunto definitivo para fichamento) | `[05]` |
| Excluídos nesta etapa | `[79]` |

**Principais motivos de exclusão nesta filtragem:**
- `[Falta de estratégias de recuperação em RAG ]`
- `[Falta de objetificação com a proposta do Artigo. ]`

*Responsável(is) por esta triagem: `[Henrique de Figueiredo, Nicolas Melo]`*

---

## 3. Lista Final de Artigos Selecionados (Conjunto Definitivo)

*Liste aqui os artigos que passaram por todas as filtragens e seguirão para o fichamento (etapa "j"). Referência completa no formato ABNT/APA definido pelo projeto.*

1. [AGUSTIANI, A. D. et al. Evaluating RAG Performance on Small Language Models for Low-Resource Devices through Chunking and Retrieval Methods. **JOIN (Jurnal Online Informatika)**, v. 11, n. 1, p. 243-255, 2026. DOI: 10.15575/join.v11i1.1733.]
2. [MISHRA, S.; NAIK, G. R. Cost-Aware Query Routing in RAG: Empirical Analysis of Retrieval Depth Tradeoffs. **AI**, v. 7, p. 250, 2026. DOI: 10.3390/ai7070250.]
3. [AROMSUK, T.; NETISOPAKUL, P.; NOOTYASKOOL, S. Improved Naive RAG by Integrated Advanced Techniques: A Comprehensive Framework Using Parent-Child Architecture, Hybrid Retrieval, and Contextual Compression. **IEICE Trans. Inf. & Syst.**, v. E109-D, n. 7, p. 1057-1068, 2026. DOI: 10.1587/transinf.2025DAP0003.]
4. [KRAINOVSKIKH, V.; SAMIGULIN, T. Domain-Adapted Retrieval-Augmented Generation for Technical Documentation: Enhancing Reliability and Faithfulness in Technical QA. **IEEE Access**, v. 14, p. 36016-36024, 2026. DOI: 10.1109/ACCESS.2026.366810.]
5. [BUDAKOGLU, G.; EMEKCI, H. Unveiling the Power of Large Language Models: A Comparative Study of Retrieval-Augmented Generation, Fine-Tuning, and Their Synergistic Fusion for Enhanced Performance. **IEEE Access**, v. 13, p. 30936-30951, 2025. DOI: 10.1109/ACCESS.2025.3542334.]


## 4. Contribuição Individual dos Integrantes

> **Importante:** cada integrante deve descrever, com suas próprias palavras, o que efetivamente fez em cada passo desta etapa. Contribuições genéricas como "ajudei em tudo" não serão aceitas. Use verbos de ação e seja específico (ex.: "executei a busca no IEEE Xplore com a string 2 e obtive 84 resultados; fiz a triagem por título/resumo de 40 desses").

### Integrante 1 — `[Henrique de Figueiredo Lourenço]`
- **Passo(s) em que atuou:** `[Passos 1, 2, 5, 6 e 7.]`
- **O que fez em cada passo:** `[Participou da definição da pergunta de pesquisa e dos conceitos relacionados ao tema. Elaborou e executou strings de busca no IEEE Xplore, registrando os resultados encontrados. Também participou da triagem dos artigos por título e resumo e, posteriormente, da leitura de introdução e conclusão dos trabalhos selecionados, contribuindo para a definição dos artigos aprovados para o fichamento.]`
- **Tempo dedicado (aprox.):** `[6h]`
- **Evidência da contribuição** *(print de busca, planilha de triagem, exportação BibTeX, etc.)*: `[https://ieeexplore.ieee.org/search/searchresult.jsp?action=search&matchBoolean=true&queryText=(%22All%20Metadata%22:RAG)%20AND%20(%22All%20Metadata%22:BM25%20OR%20%22All%20Metadata%22:sparse%20retrieval)&highlight=true&returnFacets=ALL&returnType=SEARCH&matchPubs=true&refinements=ContentType:Journals]`

### Integrante 2 — Nicolas Silva Rodrigues de Melo
- **Passo(s) em que atuou:** Passos 2, 4, 6 e 7.
- **O que fez em cada passo:** Participou da elaboração das strings de busca, principalmente relacionadas à recuperação BM25, recuperação esparsa e recuperação híbrida. Contribuiu para a definição dos critérios de inclusão e exclusão. Realizou a triagem dos artigos encontrados por título e resumo e participou da análise dos artigos na segunda filtragem, auxiliando na identificação dos trabalhos que apresentavam relação com o tema da pesquisa.
- **Tempo dedicado (aprox.):** 4h
- **Evidência da contribuição:** https://doaj.org/search/articles?ref=homepage&q=%22Retrieval-Augmented+Generation%22+AND+%22BM25%22

### Integrante 3 — `[Victor Alexandre Dorea Randis]`
- **Passo(s) em que atuou:** `[3 e 5]`
- **O que fez em cada passo:** `[O que fez em cada passo: Participou da definição das bases de dados utilizadas no levantamento bibliográfico e realizou buscas na plataforma CAPES. Auxiliou no levantamento dos resultados relacionados à recuperação híbrida e no registro das referências encontradas para posterior análise pelo grupo.]`
- **Tempo dedicado (aprox.):** `[3h]`
- **Evidência da contribuição:** `[https://www.periodicos.capes.gov.br/index.php/acervo/buscador.html?q=Retrieval-Augmented+Generation+AND+hybrid+search&mode=advanced&source=all&type%5B%5D=type%3D%3DArtigo]`


### 4.1 Quadro-resumo de participação por passox'

| Passo | Responsável(is) | % estimado de participação de cada um |
|---|---|---|
| 1. Pergunta e palavras-chave | `[Henrique)]` | `[100%]` |
| 2. Strings de busca | `[Henrique e Nicolas]` | `[Henrique 50% / Nicolas 50%]` |
| 3. Bases de dados | `[Victor]` | `[100%]` |
| 4. Critérios de inclusão/exclusão | `[Henrique, Nicolas e Victor]` | `[Henrique 30% / Nicolas 30% / Victor 40% ]` |
| 5. Execução das buscas | `[Henrique e Victor]` | `[Henrique 60% / Victor 40%]` |
| 6. Triagem título/resumo | `[Henrique e Nicolas]` | `[Henrique 50% / Nicolas 50%]` |
| 7. Triagem texto completo | `[Henrique e Nicolas]` | `[Henrique 50% / Nicolas 50%]` |

### 4.2 Quadro-resumo geral de participação na etapa

| Integrante | % estimado de participação total nesta etapa |
|---|---|
| `[Henrique de Figueiredo Lourenço]` | `[40%]` |
| `[Nicolas Silva Rodrigues de Melo]` | `[35%]` |
| `[Victor Alexandre Dorea Randis]`   | `[25%]` |

*A soma das porcentagens deve ser igual a 100%. Divergências de percepção sobre a participação devem ser discutidas em grupo antes do envio — o orientador pode solicitar esclarecimentos individuais em caso de disparidade relevante.*

---

## 5. Checklist Final da Etapa

**Fase 1 — Planejamento**
- [x] Pergunta de pesquisa de trabalho definida
- [x] Conceitos-chave e sinônimos (PT/EN) listados
- [x] Strings de busca elaboradas com operadores booleanos
- [x] Bases de dados escolhidas e justificadas
- [x] Critérios de inclusão e exclusão definidos

**Fase 2 — Execução e triagem**
- [X] Buscas executadas e resultados registrados por base/string
- [x] Referências exportadas para o gerenciador de referências
- [x] Triagem por título/resumo concluída (com duplicatas removidas)
- [x] Triagem por texto completo (introdução/conclusão) concluída
- [x] Conjunto definitivo de artigos para fichamento compilado

**Documentação**
- [x] Contribuição individual de cada integrante registrada por passo
- [x] Quadro-resumo de participação preenchido (soma = 100%)

---


