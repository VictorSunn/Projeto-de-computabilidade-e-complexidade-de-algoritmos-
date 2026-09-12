# Etapa (b) — Levantamento Bibliográfico

> **Como preencher:** este documento deve ser preenchido **em conjunto pelo grupo**, mas com registro individualizado da contribuição de cada integrante em cada passo. Substitua os campos entre `[ ]` pelas informações do seu grupo. Não apague as instruções em itálico — elas ajudam na avaliação do orientador.

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
*Ainda não precisa ser a versão final (isso vem na etapa "c"), mas deve orientar a busca desta fase.*

> `[Qual é o custo computacional das estratégias de recuperação densa e híbrida utilizadas em arquiteturas RAG, considerando aspectos como tempo de recuperação, uso de memória e escalabilidade?]`

**1.2 Conceitos-chave e sinônimos**
*Liste os conceitos centrais da pergunta e seus sinônimos, em português e inglês.*

| Conceito-chave | Sinônimos / termos relacionados (PT) | Sinônimos / termos relacionados (EN) |
|---|---|---|
| `[RAG]` | `[Geração Aumentada por Recuperação]` | `[Retrieval-Augmented Generation, RAG, retrieval-augmented systems]` |
| `[BM25]` | `[Recuperação BM25  ` | `[Best Matching 25. ]` |
| `[Custo computacional]` | `[Custo operacional, complexidade computacional, custo de processamento]` | `[Computational cost, computational complexity, processing cost ]` |
`[Memória]` | `[Uso de memória]` | `[Memory usage]` |
`[Escalabilidade]` | `[escalabilidade computacional]` | `[computational scalability]` |
`[Métricas de recuperação]` | `[Métricas de avaliação, desempenho da recuperação]` | `[Retrieval metrics, evaluation metrics]` |
`[Recuperação híbrida]` | `[busca híbrida]` | `[hybrid search]` |
`[Busca vetorial]` | `[busca semântica]` | `[semantic search]` |  

*Responsável por este passo: `[Henrique de Figueiredo Lourenço]`*

---

### Passo 2 — Strings de busca

*Combine os termos do passo 1 com operadores booleanos (`AND`, `OR`, `NOT`). Use aspas para termos compostos e truncamento (`*`) quando a base permitir.*

| Nº | String de busca | Base(s) em que será usada | Elaborada por |
|---|---|---|---|
| 1 | `[("Retrieval-Augmented Generation" OR RAG) AND (BM25 OR "sparse retrieval")]` | `[IEEE Xplore]` | `[Nicolas]` |
| 2 | `[("Retrieval-Augmented Generation" OR RAG) AND ("vector search")]` | `[IEEE Xplore]` | `[Henrique]` |
| 3 | `[("Retrieval-Augmented Generation" OR RAG) AND ("hybrid retrieval" OR "hybrid search")]` | `[ACM Digital Library]` | `[Nicolas]` |

---

### Passo 3 — Bases de dados escolhidas

*Selecione de 2 a 4 bases relevantes ao tema. Registre a justificativa — isso vai para a seção de metodologia do artigo/relatório de IC.*

| Base de dados | Por que foi escolhida | Responsável pela busca nesta base |
|---|---|---|
| `[IEEE Xplore]` | `[Possui artigos relacionados à Inteligência Artificial, algoritmos e recuperação de informação ]` | `[Victor Alexandre]` |
| `[CAPES]` | `[quantidade de artigos relacionados a pesquisas hibridas.]` | `[Victor Alexandre]` |

---

### Passo 4 — Critérios de inclusão e exclusão

**Critérios de inclusão:**
- `[Artigos publicados nos últimos 10 anos]`
- `[Trabalhos relacionados a arquiteturas RAG;]`
- `[Artigos em português/inglês]`
- `[Trabalhos que apresentem informações sobre custo computacional ou desempenho;]`
- `[Trabalhos que apresentem métricas de recuperação; ]`

**Critérios de exclusão:**
- `[Trabalhos que não tenham relação direta com RAG;]`
- `[duplicatas]`
- `[Trabalhos que não apresentem informações relacionadas a custo ou desempenho;]`
- `[Trabalhos fora do tema proposto;]`
- `[trabalhos sem metodologia ou resultados suficientes para comparação.]`

*Definidos em conjunto por: `[Henrique de Figueiredo Lourenço, Nicolas Silva Rodrigues de Melo e Victor Alexandre Dorea Randis.]`*

---

## FASE 2 — Execução da Busca e Triagem

### Passo 5 — Execução das buscas e registro dos resultados

*Anote quantos resultados cada string trouxe em cada base (útil para o fluxograma tipo PRISMA, se o projeto exigir). Exporte as referências (BibTeX, RIS, CSV) para um gerenciador de referências.*

| Base | String usada (nº) | Data da busca | Nº de resultados | Executada por |
|---|---|---|---|---|
| `[IEEE Xplore]` | `[RAG AND BM25 OR sparse retrieval]` | `[11/09/2026]` | `[18]` | `[Henrique Lourenço]` |
| `[IEEE Xplore ]` | `[RAG AND vector search]` | `[11/09/2026]` | `[38]` | `[Henrique Lourenço]` |    
| `[CAPES ]` | `[Retrieval-Augmented Generation AND hybrid search ]` | `[11/09/2026]` | `[4]` | `[Victor Alexandre]` |
| `[IEEE Xplore ]` | `[Retrieval-Augmented Generation AND hybrid search]` | `[11/09/2026]` | `[25]` | `[Henrique Lourenço]` |   

**Total de resultados brutos (soma de todas as buscas):** `[85]`

**Gerenciador de referências utilizado:** `[Zotero]`
**Formato de exportação:** `[RIS]`

---

### Passo 6 — Triagem por título e resumo (1ª filtragem)

*Leia apenas título e resumo de cada resultado. Classifique: incluir / excluir / dúvida. Remova duplicatas entre bases.*

| Item de controle | Quantidade |
|---|---|
| Total de resultados antes da triagem | `[85]` |
| Duplicatas removidas | `[13]` |
| Classificados como "Incluir" | `[39]` |
| Classificados como "Excluir" | `[26]` |
| Classificados como "Dúvida" | `[7]` |

*A triagem detalhada, artigo por artigo, deve ser registrada na planilha de controle do projeto (aba "Triagem de Artigos"). Aqui, registre apenas o resumo quantitativo.*

**Como as dúvidas foram resolvidas?** *(ex.: discussão em grupo, consulta ao orientador)*
`[discussão em grupo e pesquisas acerca dos artigos para verificar se é cabivel aos tema do projeto.]`

*Responsável(is) por esta triagem: `[Henrique de Figueiredo, Nicolas Melo]`*

---

### Passo 7 — Triagem por leitura completa (2ª filtragem)

*Para os artigos que passaram na primeira filtragem, leia introdução e conclusão. Aplique os critérios de inclusão/exclusão (passo 4) de forma mais rigorosa.*

| Item de controle | Quantidade |
|---|---|
| Total de artigos que entraram nesta filtragem | `[39]` |
| Aprovados (conjunto definitivo para fichamento) | `[27]` |
| Excluídos nesta etapa | `[12]` |

**Principais motivos de exclusão nesta filtragem:**
- `[Falta de estratégias de recupeççao em RAG ]`
- `[Falta de objetificação com a proposta do Artigo. ]`

*Responsável(is) por esta triagem: `[Henrique de Figueiredo, Nicolas Melo]`*

---

## 3. Lista Final de Artigos Selecionados (Conjunto Definitivo)

*Liste aqui os artigos que passaram por todas as filtragens e seguirão para o fichamento (etapa "j"). Referência completa no formato ABNT/APA definido pelo projeto.*

1. `[HU, R.; LIU, S.; QI, P.; LIU, J.; LI, F. ICCA-RAG: Intelligent Customs Clearance Assistant Using Retrieval-Augmented Generation (RAG). IEEE Access, v. 13, p. 39711-39726, 2025. DOI: 10.1109/ACCESS.2025.3544408.]`
2. `[HUANG, T. et al. ParaVul: A Parallel Large Language Model and Retrieval-Augmented Framework for Smart Contract Vulnerability Detection. IEEE Transactions on Information Forensics and Security, v. 21, p. 5017-5030, 2026. DOI: 10.1109/TIFS.2026.3694661.]`
3. `[ERSOY, P.; ERŞAHIN, M. A Comparative Evaluation of RAG Architectures for Cross-Domain LLM Applications: Design, Implementation, and Assessment. IEEE Access, v. 13, p. 194185-194196, 2025. DOI: 10.1109/ACCESS.2025.3632404.]`
4. `[PRANEETH, B. et al. Optimization of Customer Feedback Summarization Using Large Language Models (LLM) and Advanced Retrieval-Augmented Generation. IEEE Access, v. 13, p. 124319-124332, 2025. DOI: 10.1109/ACCESS.2025.3588337]`
5. `[ANTAL, G.; ÉRTEKES, L.; SZOLNOKI, N.; HEGEDŰS, P. Evaluating Retrieval-Augmented Generation for LLM-Based Vulnerability Detection: An Empirical Study on Real-World Java Vulnerabilities. IEEE Access, v. 14, p. 50878-50891, 2026. DOI: 10.1109/ACCESS.2026.3676577.  ]`
6. `[KHAN, T. F. et al. UQA-RAG: Enhancing Urdu Question-Answer Retrieval With Semantic Similarity and LLMs. IEEE Access, v. 14, p. 2868-2882, 2026. DOI: 10.1109/ACCESS.2025.3649743.]`
7. `[KHAN, M. Z. et al. RFSensingGPT: A Multi-Modal RAG-Enhanced Framework for Integrated Sensing and Communications Intelligence in 6G Networks. IEEE Transactions on Cognitive Communications and Networking, v. 12, p. 298-311, 2026. DOI: 10.1109/TCCN.2025.3558069.]`
8. `[AMAL, S.; NIRANJAN, A. R.; THUSHARA, M. G. EduRAG: A Multimodal Explainable RAG System With Deterministic Token Grounding. IEEE Access, v. 14, p. 90849-90859, 2026. DOI: 10.1109/ACCESS.2026.3704123.]`
9. `[CHO, S. Q-VESA: Accelerating Quantization-Aware Vector Search for Fast Retrieval in Prompt Engineering. IEEE Transactions on Computers, v. 75, n. 3, p. 1028-1042, 2025. DOI: 10.1109/TC.2025.3644935.]`
10. `[RAHMAN, M. A. et al. Semantic Skyline: Multi-Embedding Skyline Query Processing for RAG Workloads in Vector Databases. IEEE Access, 2026. DOI: 10.1109/ACCESS.2026.3724578.]`
11. `[KO, S. et al. Cosmos: A CXL-Based Full In-Memory System for Approximate Nearest Neighbor Search. IEEE Computer Architecture Letters, v. 24, n. 1, p. 173-176, 2025. DOI: 10.1109/LCA.2025.3570235.]`
12. `[ELKIRAN, H.; RASHEED, J. EvaRAG: Evaluating Advanced RAG Techniques With Indexing and Distance Metrics. IEEE Access, v. 13, p. 215724-215747, 2025. DOI: 10.1109/ACCESS.2025.3646665.]`
13. `[KIM, J. et al. Performance Analysis and CXL Memory Optimization in Cluster-Based RAG Systems. IEEE Transactions on Computers, v. 75, n. 4, p. 1323-1334, 2026. DOI: 10.1109/TC.2025.3643434.]`
14. `[SONG, M. Enhancing RAG Performance by Representing Hierarchical Nodes in Headers for Tabular Data. IEEE Access, v. 13, p. 85072-85083, 2025. DOI: 10.1109/ACCESS.2025.3569872.]`
15. `[CEJAS, O. A.; GUO, Y.; TANG, Q. From Retrieval to Response: Tracing the Impact of Embedding Quality in RAG Systems. IEEE Access, v. 13, p. 212773-212781, 2025. DOI: 10.1109/ACCESS.2025.3644595.]`
16. `[CHAI, H.; CHEN, R.; ZHU, H. RAG-Based Language Model with Enhanced Indexing Optimization for Financial Intelligent Customer Service Application. Big Data Mining and Analytics, v. 9, n. 4, p. 1046-1060, 2026. DOI: 10.26599/BDMA.2025.9020111.]`
17. `[ELKIRAN, H.; RASHEED, J. An Empirical Evaluation of Retrieval, Reranking, and Similarity for a Q&A-Based Retrieval Augmented Generation System. IEEE Access, v. 14, p. 26053-26066, 2026. DOI: 10.1109/ACCESS.2026.3664852.]`
18. `[PESL, R. D. et al. Retrieval-Augmented Generation for Service Discovery: Chunking Strategies and Benchmarking. IEEE Transactions on Services Computing, v. 19, n. 2, p. 1520-1534, 2026. DOI: 10.1109/TSC.2026.3665441.]`
19. `[CHANG, J.-S. et al. Hybrid Retrieval-Augmented Generation for Interpretable Traffic Forecasting in Urban ITS. IEEE Canadian Journal of Electrical and Computer Engineering, v. 49, n. 3, p. 333-343, 2026. DOI: 10.1109/ICJECE.2026.3691315.]`
20. `[LECU, A. et al. Reducing Hallucinations in Medical AI: A Knowledge Graph-Augmented Retrieval System for Evidence-Based Age-Related Macular Degeneration Information. IEEE Access, v. 13, p. 210624-210639, 2025. DOI: 10.1109/ACCESS.2025.3643370.]`
21. `[BORNEA, A.-L. et al. Telco-oRAG: Optimizing Retrieval-Augmented Generation for Telecom Queries via Hybrid Retrieval and Neural Routing. IEEE Journal on Selected Areas in Communications, v. 44, p. 2334-2347, 2026. DOI: 10.1109/JSAC.2025.3641573.]`
22. `[KOŠPRDIĆ, M. et al. VerifAI: A Verifiable Open-Source Search Engine for Biomedical Question Answering. IEEE Access, v. 14, p. 45129-45147, 2026. DOI: 10.1109/ACCESS.2026.3676985.]`
23. `[AN, J. et al. ADRAG: Avionics Diagnostic Retrieval-Augmented Generation by Fusing Hierarchical Semantic Trees and Knowledge Graphs. IEEE Transactions on Reliability, v. 75, p. 2523-2535, 2026. DOI: 10.1109/TR.2026.3704165.]`
24. `[ALABBASI, N. et al. TeleOracle: Fine-Tuned Retrieval-Augmented Generation With Long-Context Support for Networks. IEEE Internet of Things Journal, v. 12, n. 10, p. 13170-13182, 2025. DOI: 10.1109/JIOT.2025.3553161.]`
25. `[MENSCHIKOV, M. et al. PersonalAI: A Systematic Comparison of Knowledge Graph Storage and Retrieval Approaches for Personalized LLM Agents. IEEE Access, v. 14, p. 58262-58281, 2026. DOI: 10.1109/ACCESS.2026.3682941.]`
26. `[WANKHADE, A.; SHAHADE, A. K. Cost-Aware Structured Content Generation Using Hybrid Retrieval-Augmented Generation and Adaptive Compute Routing. International Journal of Networked and Distributed Computing, v. 14, art. 26, 2026. DOI: 10.1007/s44227-026-00105-3.]`
27. `[KIM, S.; YOON, J. VAIV bio-discovery service using transformer model and retrieval augmented generation. BMC Bioinformatics, v. 25, art. 273, 2024. DOI: 10.1186/s12859-024-05903-6.]`

---

## 4. Contribuição Individual dos Integrantes

> **Importante:** cada integrante deve descrever, com suas próprias palavras, o que efetivamente fez em cada passo desta etapa. Contribuições genéricas como "ajudei em tudo" não serão aceitas. Use verbos de ação e seja específico (ex.: "executei a busca no IEEE Xplore com a string 2 e obtive 84 resultados; fiz a triagem por título/resumo de 40 desses").

### Integrante 1 — `[Henrique de Figueiredo Lourenço]`
- **Passo(s) em que atuou:** `[Passos 1, 2, 5, 6 e 7.]`
- **O que fez em cada passo:** `[Participou da definição da pergunta de pesquisa e dos conceitos relacionados ao tema. Elaborou e executou strings de busca no IEEE Xplore, registrando os resultados encontrados. Também participou da triagem dos artigos por título e resumo e, posteriormente, da leitura de introdução e conclusão dos trabalhos selecionados, contribuindo para a definição dos artigos aprovados para o fichamento.]`
- **Tempo dedicado (aprox.):** `[6h]`
- **Evidência da contribuição** *(print de busca, planilha de triagem, exportação BibTeX, etc.)*: `[https://ieeexplore.ieee.org/search/searchresult.jsp?action=search&matchBoolean=true&queryText=(%22All%20Metadata%22:RAG)%20AND%20(%22All%20Metadata%22:BM25%20OR%20%22All%20Metadata%22:sparse%20retrieval)&highlight=true&returnFacets=ALL&returnType=SEARCH&matchPubs=true&refinements=ContentType:Journals]`

### Integrante 2 — `[Nicolas Silva Rodrigues de Melo]`
- **Passo(s) em que atuou:** `[Passos 2, 4, 6 e 7.]`
- **O que fez em cada passo:** `[Participou da elaboração das strings de busca, principalmente relacionadas à recuperação BM25, recuperação esparsa e recuperação híbrida. Contribuiu para a definição dos critérios de inclusão e exclusão. Realizou a triagem dos artigos encontrados por título e resumo e participou da análise dos artigos na segunda filtragem, auxiliando na identificação dos trabalhos que apresentavam relação com o tema da pesquisa ]`
- **Tempo dedicado (aprox.):** `[4h]`
- **Evidência da contribuição:** `[link ou descrição]`

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


