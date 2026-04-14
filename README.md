#  Caderno Temático: Finanças Sustentáveis e Crédito ESG

**Bootcamp:** Bradesco GenAI & Dados - DIO  
**Desafio:** NotebookLM - Caderno Temático  
**Autor:** Murilo Monzillo Pepineli de Souza  


---

##  Contexto e Objetivos

- Compreender o conceito de Finanças Sustentáveis e sua importância para a transformação ecológica da economia brasileira, entendendo como recursos públicos e privados são direcionados para atividades de baixo carbono .

- Identificar os principais instrumentos de crédito sustentável disponíveis no mercado, com foco na atuação do Bradesco como agente financiador da transição energética e da agricultura sustentável .

- Analisar cases práticos de financiamento verde, como a emissão de debêntures verdes da Neoenergia estruturada pelo Bradesco BBI, entendendo os critérios de elegibilidade e os benefícios ambientais mensuráveis gerados .

- Desenvolver prompts eficazes para extrair informações relevantes sobre crédito ESG, conectando os conceitos estudados a aplicações práticas que poderiam ser integradas à assistente virtual BIA do Bradesco.

---

### Por que este tema?
O Bradesco tem se destacado no mercado brasileiro com metas agressivas de negócios sustentáveis, ultrapassando R$ 334 bilhões em 2024 e mirando R$ 350 bilhões. Compreender como funcionam os instrumentos de crédito verde e as finanças sustentáveis é essencial para profissionais que desejam atuar no setor financeiro alinhado às tendências globais de descarbonização e transição energética.

---

## Curadoria de Fontes:

| 1 | bradesco-relatorio-esg | PDF oficial do banco |
| 2 | negócios sustentáveis - Bradesco | Texto/PDF institucional |
| 3 | finanças sustentáveis - Ministério da Fazenda | PDF governamental |
| 4 | Emissão de R$ 1 bi Neoenergia - Integridade ESG | Artigo/PDF |

---

## Engenharia de Prompts e "Cicatrizes:

### Prompt 1 - Nível Fácil

**Pergunta:** "O que são finanças sustentáveis?"

**Resposta obtida:** As finanças sustentáveis são medidas fiscais, creditícias e regulatórias para direcionar recursos a atividades sustentáveis. Envolve: (1) direcionamento de capital para transição (carbono, taxonomia, Eco Invest Brasil); (2) instrumentos ESG (green bonds, sustainability-linked); (3) gestão de riscos com integração ESG; (4) duplo benefício (retorno financeiro + impacto socioambiental).

**Referências:** Ministério da Fazenda (eixos estratégicos); bradesco-relatorio-esg (gestão de riscos); Integridade ESG (green bonds).

**Dificuldade:** A fonte "negócios sustentáveis - bradesco" não foi utilizada. A IA priorizou fontes mais técnicas. Próximo passo: forçar o uso de todas as 4 fontes explicitamente.

---

### Prompt 2 - Nível Médio 

**Pergunta:** "Quais são os principais instrumentos de crédito ESG disponíveis no mercado brasileiro?"

**Resposta obtida:** O Notebooklm identificou 7 instrumentos ESG: (1) Debêntures Verdes (Neoenergia R$1 bi); (2) Títulos Soberanos Sustentáveis (US$2 bi para Fundo Clima); (3) Sustainability-Linked Bonds/Loans (Bracell US$60 mi); (4) Letras Financeiras Climáticas (Bradesco emissor R$1,2 mi); (5) CPR ESG (Jaepel R$330 mi); (6) Green Loans (Sambazon R$20 mi); (7) Transition Bonds (Bradesco estruturou R$250 mi). O Bradesco atua como coordenador, estruturador, emissor ou operador em todos.

**Referências:** Integridade ESG (debêntures); Ministério da Fazenda (títulos soberanos); relatório ESG Bradesco (SLL, LF, CPR, green loans, transition).

**Dificuldade:** A resposta trouxe instrumentos que não estavam explicitamente nomeados como "crédito ESG" nas fontes (ex: Transition Bonds, CPR ESG).

---

### Prompt 3 - Nível Difícil 

**Pergunta:** "Quais os principais desafios e riscos das finanças sustentáveis no Brasil, e como o Bradesco pode mitigá-los?"

**Resposta obtida:** 3 desafios: (1) Escassez de dados/padronização → mitiga com PCAF; (2) Incertezas regulatórias e geopolíticas → mitiga com cenários e testes de estresse; (3) Riscos físicos/desmatamento → mitiga com georreferenciamento e SARB 026/2023. Priorização: 1º incertezas, 2º dados, 3º físicos.

**Referências:** Relatório ESG Bradesco; Ministério da Fazenda.

**Dificuldade:** A resposta ficou muito longa (mais de 20 linhas). Para o README, precisei resumir bastante. Próxima vez, pedir "resposta em no máximo 10 linhas".

---

##  Miniguia de Estudo

### 1. Resumos Estruturados

#### O que são Finanças Sustentáveis?
As finanças sustentáveis compreendem um conjunto de medidas fiscais, tributárias, creditícias, regulatórias e financeiras que visam incentivar a alocação de recursos públicos e privados em atividades que sejam simultaneamente sustentáveis, inovadoras e inclusivas. O objetivo central é ampliar os investimentos em soluções tecnológicas e atividades econômicas que reduzam o impacto ambiental e os riscos climáticos, promovendo o desenvolvimento sustentável.

**Principais componentes:**
- Direcionamento de capital para transição (carbono, taxonomia, Eco Invest Brasil)
- Instrumentos financeiros rotulados ESG (Green Bonds, Social Bonds, Sustainability-Linked)
- Gestão de riscos e integração ESG na análise de crédito
- Duplo benefício: retorno financeiro + impacto socioambiental

**Dado numérico relevante:** O mercado global de dívida sustentável — que engloba títulos verdes, sociais e de sustentabilidade — atingiu a marca de aproximadamente US$ 6 trilhões em circulação em 2025.

**Importância para o setor financeiro:** As finanças sustentáveis são fundamentais para a gestão de riscos sistêmicos, permitindo a identificação de riscos físicos (eventos climáticos extremos) e de transição (mudanças regulatórias e tecnológicas) que podem afetar a estabilidade das instituições. Além disso, permitem que os bancos atuem como agentes de transformação positiva.

---

#### Instrumentos de Crédito ESG no Brasil

| Debêntures Verdes | Títulos para projetos ambientais | Neoenergia R$ 1 bilhão |
| Títulos Soberanos Sustentáveis | Dívida do governo para metas sustentáveis | US$ 2 bilhões para o Fundo Clima |
| Sustainability-Linked (SLL) | Juros atrelados a metas ESG | Bracell US$ 60 milhões |
| Letras Financeiras Climáticas | Captação bancária para ativos verdes | Bradesco R$ 1,2 milhão |
| CPR ESG | Crédito do agro com critérios sustentáveis | Jaepel R$ 330 milhões |
| Green Loans | Empréstimos para projetos ambientais | Sambazon R$ 20 milhões |
| Transition Bonds | Financiamento para descarbonização | Bradesco R$ 250 milhões |

---

#### Comparativo: Títulos Verdes vs Sustainability-Linked Bonds (SLB)

Com base nos documentos fornecidos, a comparação entre os dois principais instrumentos de captação ESG citados:

| **Diferença principal** | Os recursos captados são obrigatoriamente destinados a projetos com benefícios ambientais específicos e mensuráveis | Os recursos possuem destinação livre, mas o custo da dívida (juros) varia conforme o cumprimento de metas de desempenho ESG (KPIs) |
| **Foco da operação** | Foca no projeto financiado (ex: energia renovável ou transporte limpo) | Foca na estratégia global de sustentabilidade da empresa emissora |
| **Exemplo no Brasil** | Emissão de R$ 1 bilhão pela Neoenergia para modernização de redes e smart grids | Operação de US$ 60 milhões para a Bracell com metas de redução de resíduos e consumo hídrico |
| **Relevância para o Bradesco** | O Bradesco BBI atuou como coordenador exclusivo no caso Neoenergia e o banco captou R$ 1,2 milhão via Letra Financeira Climática própria | Em 2024, o banco estruturou 3 operações de SLBs totalizando R$ 1,7 bilhão para auxiliar a transição de seus clientes |

**Resumo do papel do Bradesco:** A instituição atua como um facilitador estratégico em ambas as frentes. No caso dos títulos verdes, o banco foca na viabilização de infraestrutura de baixo carbono, como o apoio ao Programa Eco Invest. Já nos títulos vinculados à sustentabilidade, o Bradesco utiliza sua equipe especializada para ajudar os clientes a definirem KPIs rigorosos e estruturarem o framework de finanças sustentáveis necessário para atrair investidores.

---

#### Desafios e Riscos das Finanças Sustentáveis

| Escassez de dados e falta de padronização metodológica | Imprecisão no reporte de emissões financiadas | Metodologia PCAF e revisões frequentes |
| Incertezas regulatórias e rebalanço geopolítico | Redução da liquidez no mercado de títulos verdes e aumento do risco de transição | Análise de cenários (Net Zero vs Current Policies) e testes de estresse |
| Riscos físicos extremos e desmatamento ilegal | Aumento da inadimplência no setor agrícola e danos reputacionais | Georreferenciamento, normativo SARB 026/2023 da FEBRABAN |

**Priorização dos desafios (do mais crítico ao menos crítico):**
1. **Incertezas regulatórias e geopolíticas** - Risco sistêmico e externo, afetando captação de recursos e viabilidade dos R$ 350 bilhões em compromissos até 2025
2. **Falta de padronização e dados** - Essencial para integridade do negócio; sem dados confiáveis, o banco fica vulnerável a falhas na transparência
3. **Riscos físicos e desmatamento** - Severos, mas mais endereçáveis via gestão interna de crédito e monitoramento tecnológico direto

**Recomendação executiva:** O Bradesco deve acelerar a integração da Taxonomia Sustentável Brasileira em seus sistemas de risco e fortalecer o engajamento técnico com clientes de alta emissão para mitigar o vácuo de dados, garantindo que a expansão das metas ESG não comprometa a precisão do reporte e a confiança dos investidores internacionais.

---

### 2. Glossário de Conceitos

| **ESG** | Environmental, Social and Governance — critérios ambientais, sociais e de governança |
| **Green Bond (Título Verde)** | Título de dívida cujos recursos são destinados exclusivamente a projetos com benefícios ambientais |
| **Sustainability-Linked Bond (SLB)** | Título com recursos de uso livre, mas juros atrelados ao cumprimento de metas ESG |
| **Sustainability-Linked Loan (SLL)** | Empréstimo com taxas vinculadas a metas de desempenho ESG predefinidas |
| **Taxonomia Sustentável** | Sistema de classificação que define quais atividades econômicas contribuem para objetivos socioambientais |
| **Greenwashing** | Prática de divulgar informações falsas ou enganosas sobre benefícios ambientais |
| **PCAF** | Partnership for Carbon Accounting Financials — metodologia internacional para medir emissões financiadas |
| **Transition Bond** | Título para financiar empresas de setores intensivos em carbono em processo de descarbonização |
| **CPR ESG** | Cédula de Produto Rural com critérios de sustentabilidade no agronegócio |
| **SARB 026/2023** | Normativo da FEBRABAN para monitoramento da cadeia da carne bovina e combate ao desmatamento |
| **Eco Invest Brasil** | Programa governamental para atrair investimentos estrangeiros com proteção cambial para projetos ecológicos |
| **Fundo Clima** | Fundo brasileiro que financia projetos de mitigação e adaptação às mudanças climáticas |

---
