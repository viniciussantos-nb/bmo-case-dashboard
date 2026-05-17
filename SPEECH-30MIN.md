# Speech — Case BMO Ouvidoria
## Processo Seletivo Nubank | 30 minutos (versão revisada)

---

## ESTRUTURA DA APRESENTAÇÃO

| Módulo | Tempo | Slides |
|--------|-------|--------|
| 1. Abertura | 2 min | 0-1 |
| 2. Diagnóstico | 12 min | 2-7 |
| 3. Plano de Ação | 8 min | 8-14 |
| 4. Gestão de Pessoas | 6 min | 15-18 |
| 5. Fechamento | 2 min | 19 |

---

## SPEECH COMPLETO

---

### ABERTURA (2 min)

#### Slide 0: Capa (30 seg)

"Bom dia/Boa tarde. Sou Vinícius Santos e vou apresentar minha análise do case de BMO Ouvidoria.

Antes de começar, quero compartilhar a conclusão principal — assim vocês podem acompanhar meu raciocínio sabendo onde vou chegar:

**Identifiquei 3 problemas críticos na operação, mas descobri que eles não são independentes. O SLA elevado é a causa raiz que amplifica os outros dois. Portanto, minha estratégia é atacar o SLA primeiro — resolvendo um, melhoramos os três.**"

---

#### Slide 1: Agenda (1 min 30 seg)

"Organizei a apresentação em 4 módulos:

**Módulo 1 — Diagnóstico:** Como cheguei nos 3 problemas críticos e por que priorizei o SLA. Vou mostrar a validação estatística dessa hipótese.

**Módulo 2 — Estratégia de Dados:** Como garantir consistência nas métricas e construir dashboards que gerem ação — executivo e operacional.

**Módulo 3 — Automação e IA:** Oportunidades de escala com tecnologia, incluindo a decisão sobre o bot de triagem e análise de ROI.

**Módulo 4 — Gestão de Pessoas:** Como estruturar o time de 5 analistas, o framework de priorização RICE, e o plano 30-60-90 dias.

Ao longo da apresentação, vou explicar **por que fiz cada escolha** — não apenas o que fiz."

---

### MÓDULO 1: DIAGNÓSTICO (12 min)

#### Slide 2: 3 Problemas Críticos (3 min)

"Recebi uma base com **337.614 casos** de janeiro a dezembro de 2025. Meu primeiro passo foi entender: qual é o problema que mais importa resolver?

Os números gerais já indicam o cenário: SLA médio de **6,48 dias**, resolutividade geral de **35,3%**, e taxa de resposta tNPS de apenas **7,2%**.

Analisando mais a fundo, identifiquei **3 problemas críticos** — e os priorizei nessa ordem:

**Primeiro — Prioridade Crítica — SLA Elevado:**
- **46,12%** dos casos excedem 7 dias de atendimento — são mais de 155 mil casos
- O BACEN exige resposta em até 10 dias úteis
- Pior: o SLA **piorou 65% ao longo do ano** — de 4,5 para 7,4 dias
- É a causa raiz dos demais problemas — vou demonstrar isso no próximo slide

**Segundo — Prioridade Alta — Baixa Resolutividade no RDR:**
- Apenas **16-19%** de resolução neste canal
- São **34% da base — 114 mil casos** — e o tNPS é de **-66**
- Clientes que chegam no RDR já escalaram para o BACEN. Cada caso não resolvido é impacto reputacional direto

**Terceiro — Prioridade Média — Baixa Taxa de Resposta tNPS:**
- Apenas **7,2%** respondem à pesquisa
- Os outros **92,8%** são detratores silenciosos
- Sem dados, CompSol não consegue gerar insights confiáveis para melhoria

**A tese central que defendo:** SLA é a causa raiz. Resolver SLA melhora resolutividade — porque cliente atendido rápido tem problema resolvido. E aumenta taxa de resposta — quem responde tem SLA de 4,6 dias versus 6,6 dias de quem não responde."

---

#### Slide 3: Validação da Hipótese (2 min 30 seg)

"Essa não é uma opinião — é uma correlação comprovada nos dados. Fui validar a hipótese de que SLA é o driver dos demais problemas.

**Teste 1 — SLA vs Resolutividade:**
- Casos atendidos em até 3 dias: **42% de resolutividade**
- Casos com 4+ dias: **24,5% de resolutividade**
- É uma queda de **17,5 pontos percentuais** — praticamente o dobro

**Teste 2 — SLA vs tNPS:**
- Atendimento rápido (0-3 dias): tNPS de **6,1**
- Atendimento lento (4+ dias): tNPS de **4,2**
- A diferença é consistente em todos os squads

**Comprovação por squad:**
- Collections: Rápido 45% vs Lento 21% — diferença de 24pp
- CSS: Rápido 44% vs Lento 22% — diferença de 22pp
- A correlação se mantém independente do squad

**O detalhamento por faixa de SLA é ainda mais revelador:**
- 0-1 dias: 55,6% de resolutividade, tNPS 7,5
- 2-3 dias: 47,5% de resolutividade, tNPS 7,2
- A partir de 4 dias começa a degradação
- 11+ dias: apenas 29,7% de resolutividade, tNPS 3,5

**A conclusão é clara:** a cada dia adicional de SLA, perdemos aproximadamente 3 pontos percentuais de resolutividade e 0,5 pontos de tNPS. Casos resolvidos em até 3 dias têm **71% mais chance** de ter o problema resolvido.

**Por que 7 dias como corte crítico?** Duas razões:
1. **Regulatório:** Prazo BACEN é 10 dias úteis — 7 dias corridos dá margem de segurança
2. **Empírico:** Os dados mostram que a partir de 7 dias há degradação significativa — resolutividade cai de 30,9% para 28,7%"

---

#### Slide 4: Matriz de Impactos (2 min)

"Agora quero mostrar a matriz de impactos cruzando os 3 problemas com as dimensões regulatória, reputacional e operacional.

**Problema 1 — SLA Elevado:**
- **Impacto Regulatório: CRÍTICO** — BACEN exige 10 dias úteis. Com 46% acima de 7 dias, operamos no limite. Risco de multas e sanções
- **Impacto Reputacional: ALTO** — Cliente em Ouvidoria já é um escalation. SLA longo aumenta risco de escalation adicional para Procon, Reclame Aqui
- **Impacto Operacional: CRÍTICO** — Demora gera recontato em outras plataformas, multiplicando volume. É um efeito cascata: mais casos gera mais pressão, que gera mais erros

**Problema 2 — Baixa Resolutividade RDR:**
- **Impacto Regulatório: CRÍTICO** — RDR são demandas que chegaram via BACEN. 80%+ saem sem solução
- **Impacto Reputacional: CRÍTICO** — São 114 mil casos com tNPS de -66. Cada caso não resolvido é um detrator público potencial
- **Impacto Operacional: ALTO** — Aqui está um dado importante: **RDR + Collections concentra 76 mil casos com 97% de não resposta ao tNPS**. Não temos visibilidade operacional desse segmento

**Problema 3 — Baixa Taxa de Resposta tNPS:**
- **Impacto Regulatório: MÉDIO** — Com 7% de resposta, decisões ficam baseadas em amostra enviesada
- **Impacto Reputacional: ALTO** — 90% dos detratores não têm problema resolvido — e não sabemos quem são os 93% que não respondem
- **Impacto Operacional: MÉDIO** — CompSol não consegue gerar relatórios confiáveis

**O ponto crítico que conecta com o próximo slide:** esses 76 mil casos de RDR em Collections com 97% de não resposta são nosso maior ponto cego. Não temos feedback para melhorar esse segmento — e é justamente onde está o maior risco reputacional."

---

#### Slide 5: Gaps de Dados (1 min 30 seg)

"Por transparência, preciso pontuar os gaps que encontrei na base. Isso aumenta credibilidade da análise.

**Gap 1 — Procedência Ausente (Impacto Alto):**
- Base não contém campo de procedência/improcedência
- Case menciona taxa de 19% de casos procedentes, mas não consegui analisar os motivos
- Mitigação: usei SLA e resolutividade como proxies de qualidade

**Gap 2 — Receiving Method em Branco (Impacto Médio):**
- **171.638 casos — 50,84% da base** — sem receiving method classificado
- Mitigação: utilizei coluna Channel como alternativa

**Gap 3 — Reason em Branco (Impacto Baixo):**
- Apenas 4.210 casos (1,25%) sem motivo. Em Collections: apenas 0,25%
- Impacto mínimo nas análises de Pareto

**Gap 4 — IDs Repetidos (Impacto Médio):**
- 1.131 IDs aparecem mais de uma vez
- 92% têm squads diferentes, 97% têm reasons diferentes
- Pode ser recontato ou problema de chave — não identificado padrão

**Na seção de dados adicionais**, listo o que precisaríamos consultar para aprofundar: procedência RDR detalhada, classificação de causa raiz NOK, métricas consolidadas do QuickSight, e histórico de atendimento pré-RDR.

**Por que mostro isso?** Porque em ambiente real, dados nunca são perfeitos. O importante é saber trabalhar com o que tem e ser transparente sobre as limitações."

---

#### Slide 6: Análise Pareto (1 min 30 seg)

"Com o problema definido — SLA elevado — fui fazer análise de causa raiz usando Pareto. A pergunta é: onde está concentrado o problema?

**Por Canal:**
- RDR e Email concentram **92,95%** dos casos críticos de SLA
- Apenas 2 de 7 canais

**Por Squad:**
- **Collections sozinho representa 44,73%** do problema
- CSS vem em segundo com 27,62%
- Os 5 maiores squads concentram 78% dos casos críticos

**O insight é claro:** o problema está concentrado. Não preciso resolver tudo — se eu focar em Collections e RDR, ataco quase metade do problema com recursos direcionados.

Isso guiou minha priorização: **Collections primeiro**. Vou fazer o drill-down."

---

#### Slide 7: Drill-Down Collections (1 min 30 seg)

"Dentro de Collections, identifiquei os reasons mais críticos ordenados por taxa de estouro:

**SCR:** 91,84% de estouro de SLA — praticamente todo caso estoura
**Multidébitos:** 86,7%
**Cartão de Crédito:** 81,1%
**Acordo com Atraso:** 74,98%
**Acordo CI:** 49,51%

Uma observação importante: **Acordo CI tem o maior volume absoluto**, mas a taxa de estouro é de 49% — mais controlada. Por isso não é a prioridade número 1 em urgência.

Já **SCR e Multidébitos** têm taxas acima de 85% — são os alvos prioritários. Com fila prioritária e templates padronizados para esses reasons, já geramos impacto significativo no SLA de Collections.

O SLA médio de Collections é de **9,04 dias** — acima do limite regulatório. Precisa de ação imediata."

---

### MÓDULO 2: PLANO DE AÇÃO (8 min)

#### Slide 8: Plano de Ação 90 dias (3 min)

"Com o diagnóstico completo, agora o plano de ação. Estruturei em 3 fases com metas progressivas, focando em Collections que representa 44,73% do problema.

**Fase 1 — 30 dias — Quick Wins:**
- Triagem automatizada por IA para classificar casos por complexidade
- Templates de resposta para os 5 reasons mais frequentes
- Task Force temporária em Collections para zerar backlog
- **Meta: SLA ≤ 5,8 dias**

**Fase 2 — 60 dias — Estruturação:**
- Agent IA para respostas de casos simples
- Dashboard de monitoramento em tempo real com alertas
- Priorização de reasons críticos (SCR, Multidébitos)
- **Meta: SLA ≤ 4,8 dias**

**Fase 3 — 90 dias — Transformação:**
- IA Generativa para sugestão de respostas
- Feedback loop com Produto
- Estudo de dimensionamento baseado em dados
- **Meta: SLA ≤ 3,5 dias**

**Impacto esperado em 90 dias:**
- SLA Médio: de 6,5 para **3,5 dias** — redução de 46%
- Casos > 7 dias: de 46% para **12%** — redução de 74%
- Resolutividade RDR: de 18% para **55%** — aumento de 206%
- Taxa de resposta tNPS: de 7% para **18%** — aumento de 157%
- tNPS RDR: de -66 para **+5** — saindo da zona crítica

**Por que essas metas são factíveis?** Usei P75 como referência — se 25% dos casos já atingem esse SLA, é factível para os demais com as ações corretas."

---

#### Slide 9: Desenvolvimento do Time (1 min)

"Para executar esse plano, o time precisa de **autonomia com alinhamento**.

Estruturei em 3 pilares:

**1. Playbook Estruturado:**
- Definição clara de causa raiz: concentração em squads/reasons específicos
- Metodologia: Pareto por canal, squad, reason + drill-down
- Critérios de decisão documentados

**2. Perguntas-Guia:**
- Onde está concentrado o problema?
- Qual a correlação com outros indicadores?
- O que muda se resolvermos isso?

**3. Calibração Contínua:**
- Revisão semanal de análises
- Feedback estruturado
- Ajuste de abordagem conforme achados

O objetivo: analistas tomam decisões de forma autônoma, sem depender do líder para cada passo."

---

#### Slide 10: Golden Source (1 min 30 seg)

"Uma pergunta do case era sobre consistência de dados entre fontes diferentes. Como garantir que os números batem?

Minha resposta: **arquitetura de Golden Source**.

O fluxo é: Golden Source → Framework de Core Metrics → Dashboard Operacional

**Golden Source:** Uma fonte primária de dados com governança clara. Princípios MECE — mutuamente exclusivo, coletivamente exaustivo.

**Framework de Core Metrics:** As 5 métricas que importam:
1. SLA Médio
2. Casos > 7 dias
3. Resolutividade
4. tNPS
5. Taxa de Resposta tNPS

**Dashboard Operacional:** Materializa o framework e vira a **fonte única da verdade**. Qualquer discussão de número parte dali.

Isso elimina o problema de 'meu número diz X, o seu diz Y'. O Dashboard Operacional é a referência para toda a operação."

---

#### Slide 11: Dashboard Executivo vs Operacional (1 min)

"Outra pergunta do case: qual a diferença entre dashboard executivo e operacional?

**Dashboard Executivo:**
- Audiência: Diretoria, C-Level
- Frequência: Semanal/Mensal
- Métricas: 5 KPIs principais
- Pergunta que responde: 'Onde investir recursos?'
- Drill-down: Mínimo — só tendência temporal

**Dashboard Operacional:**
- Audiência: Supervisores, Analistas
- Frequência: Diária/Tempo real
- Métricas: Todas as métricas operacionais
- Pergunta que responde: 'Por que o SLA de Collections subiu esta semana?'
- Drill-down: Máximo — por squad, canal, reason, período

São complementares. O executivo direciona estratégia, o operacional executa tática."

---

#### Slide 12: Bot de Triagem (1 min 30 seg)

"O case perguntava sobre um bot de triagem que está parado há 3 meses. Minha recomendação: **retomar, mas com validação técnica prévia**.

Na matriz de priorização:
- Impacto: **Alto** — triagem automatizada libera headcount para casos complexos
- Esforço: **Médio** — já existe, precisa recalibrar
- Risco: **Médio-Alto** — se a acurácia for baixa, gera retrabalho

**Plano de execução em 30 dias:**

**Semanas 1-2:** Discovery técnico
- Benchmark de alternativas
- Requisitos de recalibração
- Definição de métricas de sucesso

**Semanas 2-3:** Recalibração
- Treinar com dados recentes
- Ajustar regras de classificação

**Semanas 3-4:** Validação
- Shadow mode: bot classifica, humano valida
- Relatório de acurácia

**Critério GO/NO-GO:** Acurácia ≥ 85%. Se não atingir, não ativa.

Por que esse approach? Prefiro transparência a risco operacional. Bot com baixa acurácia gera mais problema do que resolve."

---

#### Slide 13: ROI do Bot (1 min)

"Fiz a conta de ROI com premissas conservadoras:

**Premissas:**
- 30% dos casos são triagem simples (101.284 casos/ano)
- 3 minutos economizados por caso
- Custo FTE: R$ 5.800/mês (R$ 35/hora)

**Cálculo:**
- Horas economizadas: 5.064 horas/ano
- Economia: R$ 177.240/ano só em triagem
- FTEs liberados: 3,4 analistas para tarefas de maior valor

**Resultado Total:** Economia estimada de **R$ 236 mil/ano**.

**Importante:** São estimativas. Deixei documentado que precisaria validar o tempo médio de triagem manual com dados reais. A nota de FTE explica que é Full-Time Equivalent — 1 FTE = 1 pessoa trabalhando 40h/semana.

Transparência sobre premissas é fundamental para credibilidade."

---

#### Slide 14: Outros Casos de IA (1 min)

"Identifiquei mais 2 oportunidades de IA que podem acelerar os resultados:

**1. Agent IA para Respostas Simples:**
- O que é: Automatiza respostas de baixa complexidade — solicitação de documentos, confirmação de dados, status de processo
- Impacto: Libera headcount para casos complexos que precisam de análise humana
- Gaps que resolve: Reduz tempo de resposta, padroniza comunicação

**2. AI CX Analysis Plugin:**
- O que é: Analisa conversas e identifica padrões automaticamente usando LLM
- Impacto: Classifica reasons automaticamente, identifica tendências, sugere melhorias
- Gaps que resolve: IDs repetidos (identifica recontatos), receiving method em branco (classifica automaticamente), inconsistência de reasons

Ambas são prototipáveis com dados existentes e entram no roadmap de 60-90 dias."

---

### MÓDULO 4: GESTÃO DE PESSOAS (6 min)

#### Slide 15: Roadmap 4 Semanas (1 min 30 seg)

"Para preparar o diagnóstico completo para o Fórum de liderança, estruturei um roadmap de 4 semanas com 2 tracks paralelos.

**Track 1 — Diagnóstico:**
- Semana 1: Extração e limpeza de dados
- Semana 2: Análise Pareto com suporte de IA
- Semana 3: Validação de hipóteses e correlações
- Semana 4: Dashboards operacional e executivo

**Track 2 — Bot de Triagem:**
- Semana 1: Discovery e benchmark
- Semana 2: Requisitos de recalibração
- Semana 3: Shadow mode
- Semana 4: Relatório GO/NO-GO

**Distribuição dos 5 analistas por skill:**
- A1/A2: Foco em dados — extração, limpeza, qualidade
- A3: Foco em IA — análise Pareto com Cursor
- A4: Foco em negócio — bot de triagem, stakeholders
- A5: Foco em dashboards — operacional e executivo

Os tracks rodam em paralelo porque usam stakeholders diferentes — não competem por recurso."

---

#### Slide 16: Framework RICE (1 min)

"Para o time priorizar de forma autônoma, implemento o framework RICE.

**R — Reach:** Quantos casos são impactados? (escala 1-5)
**I — Impact:** Qual o nível de impacto no KPI? (0.25 a 3)
**C — Confidence:** Qual a confiança na estimativa? (20% a 100%)
**E — Effort:** Quantas semanas/pessoa? (número absoluto)

**Fórmula:** (R × I × C) ÷ E = Score

**Exemplo prático com ações do case:**
1. Task Force Collections: Score 36 — Prioridade 1
2. Templates de Resposta: Score 20 — Prioridade 2
3. Triagem por IA: Score 15 — Prioridade 3
4. Dashboard SLA: Score 12 — Prioridade 4
5. Feedback Loop Produto: Score 6 — Prioridade 5

Por que RICE? É simples, quantificável e amplamente usado em produto. Permite que qualquer analista proponha uma ação e calcule prioridade objetivamente."

---

#### Slide 17: Plano 30-60-90 (2 min)

"O plano executivo consolidado em 30-60-90 dias:

**30 DIAS — Foco: SLA (Vermelho)**
Iniciativas:
- Dashboard apresentado no Fórum
- Retomada Bot Triagem (validação completa)
- Task Force Collections
Stakeholders: Dados, IA, Engenharia
Marco de Sucesso: Dashboard no Fórum + Bot ativo com acurácia ≥ 85%

**60 DIAS — Foco: Resolutividade (Laranja)**
Iniciativas:
- Fila prioritária RDR
- Agent IA em piloto
- Dashboard monitoramento em tempo real
Stakeholders: Produto, Operação
Marco de Sucesso: Resolutividade RDR ≥ 25%

**90 DIAS — Foco: tNPS (Amarelo)**
Iniciativas:
- IA Generativa para sugestão de respostas
- Estudo de dimensionamento
- Priorização de reasons críticos (SCR, Multidébitos)
Stakeholders: Estratégia, Qualidade
Marco de Sucesso: Taxa resposta tNPS ≥ 12%, SLA ≤ 3,5 dias

**Riscos de Execução e Mitigações:**
- **Regulatório:** BACEN pode escalar casos → Comunicação proativa, priorização RDR
- **Operacional:** Backlog pode crescer durante transição → Task Force temporária, alocação extra
- **Pessoas:** Sobrecarga de trabalho → Distribuição equilibrada, monitoramento de carga
- **Tecnológico:** Bot pode não atingir acurácia → GO/NO-GO rigoroso, plano B manual"

---

#### Slide 18: Gestão de Pessoas (1 min 30 seg)

"Por fim, como pretendo liderar o time de 5 analistas sênior.

**Timeline Semanal de Rituais:**
- **Daily (15 min):** Acompanhamento RICE, desbloqueios, prioridades do dia — todo dia às 9h
- **1:1 (45 min):** Individual com cada analista — carreira, entregas, feedback — sexta-feira
- **Weekly (1h):** Alinhamento do time — revisão da semana, planejamento da próxima — segunda-feira

**4 Pilares de Gestão:**

**01 — Desenvolvimento Técnico:**
- PDI individualizado por competência
- Capacitação em ferramentas (Cursor, SQL, Python)
- Mentoria técnica direta

**02 — Rituais e Acompanhamento:**
- Cadência clara de entregas
- 1:1 focado em desenvolvimento
- Feedback contínuo, não só em avaliação

**03 — Engajamento:**
- Ownership: cada analista 'dono' de um projeto estratégico
- Visibilidade em fóruns executivos
- Integração mensal do time

**04 — Liderança Técnica (Meu Diferencial):**
- Hands-on: atuo junto ao time em entregas críticas
- Mentoria em IA, Cursor e análise de dados
- Contexto de negócio: traduzo demandas técnicas para linguagem executiva

O modelo não cria dependência do líder — constrói autonomia no time."

---

### FECHAMENTO (2 min)

#### Slide 19: Encerramento

"Para resumir:

**O problema:** 3 indicadores críticos que parecem independentes, mas têm uma causa raiz comum — SLA. Comprovei com dados: casos rápidos têm o dobro da resolutividade e tNPS significativamente maior.

**A estratégia:** Foco em SLA primeiro, priorizando Collections que representa 44,73% do problema. Atacando um ponto, melhoramos os três indicadores.

**O plano:** 90 dias com metas progressivas:
- SLA de 6,5 para 3,5 dias
- Casos críticos de 46% para 12%
- Resolutividade RDR de 18% para 55%

**A gestão:** Time com autonomia via framework RICE, rituais estruturados, e modelo de liderança que não cria dependência.

**Meu diferencial:** Combino visão analítica para estruturar problemas complexos, conhecimento técnico para implementar soluções com IA, e experiência de liderança para desenvolver o time. Não só planejo — executo junto.

Estou à disposição para perguntas."

---

## RESUMO DE TEMPOS (REVISADO)

| Slide | Título | Tempo |
|-------|--------|-------|
| 0 | Capa | 30 seg |
| 1 | Agenda | 1 min 30 seg |
| 2 | 3 Problemas Críticos | 3 min |
| 3 | Validação da Hipótese | 2 min 30 seg |
| 4 | Matriz de Impactos | 2 min |
| 5 | Gaps de Dados | 1 min 30 seg |
| 6 | Análise Pareto | 1 min 30 seg |
| 7 | Drill-Down Collections | 1 min 30 seg |
| 8 | Plano de Ação 90 dias | 3 min |
| 9 | Desenvolvimento do Time | 1 min |
| 10 | Golden Source | 1 min 30 seg |
| 11 | Dashboard Exec vs Oper | 1 min |
| 12 | Bot de Triagem | 1 min 30 seg |
| 13 | ROI do Bot | 1 min |
| 14 | Outros Casos de IA | 1 min |
| 15 | Roadmap 4 Semanas | 1 min 30 seg |
| 16 | Framework RICE | 1 min |
| 17 | Plano 30-60-90 | 2 min |
| 18 | Gestão de Pessoas | 1 min 30 seg |
| 19 | Encerramento | 2 min |
| **TOTAL** | | **~32 min** |

*Nota: Tempo ligeiramente acima de 30 min para ter margem de corte. Na prática, alguns slides podem ser mais rápidos.*

---

## DICAS PARA O DIA

### Pontos de Corte (se precisar reduzir tempo)
- Slide 5 (Gaps): Pode resumir em 45 seg mencionando só o principal
- Slide 9 (Desenvolvimento do Time): Pode pular se tempo estiver curto
- Slide 13 (ROI): Pode dar só o número final sem detalhar premissas

### Pontos para Enfatizar
- Slide 3: A validação estatística é seu diferencial — não pule
- Slide 4: O dado dos 76k casos com 97% não resposta é impactante — use
- Slide 8: Os números de impacto são ambiciosos e mostram domínio — destaque

### Linguagem
- Use "eu identifiquei", "minha análise mostrou", "minha recomendação é"
- Evite passivo: "foi identificado", "os dados mostram"
- Mostre ownership em cada decisão

### Se der branco
- Volte para: "O ponto principal é que SLA é a causa raiz"
- Ou: "O problema está concentrado em Collections — 44,73%"

---

## POSSÍVEIS PERGUNTAS E RESPOSTAS

**P: Por que você escolheu 7 dias como corte?**
> "Duas razões: regulatória — 70% do prazo BACEN dá margem de segurança. E empírica — os dados mostram degradação significativa de resolutividade e tNPS a partir de 7 dias."

**P: Como você validaria se o bot realmente funciona?**
> "Shadow mode por 2 semanas: o bot classifica, mas humano valida. Comparo acurácia. Se menor que 85%, não ativo e investigo o que está errando."

**P: De onde veio a meta de 55% de resolutividade em RDR?**
> "Benchmark interno. Os squads com melhor performance já atingem esse patamar. Se alguns conseguem, é factível para os demais com as ações corretas."

**P: E se o time resistir às mudanças?**
> "Começo pelo porquê. Mostro os dados, o impacto nos indicadores. Envolvo na construção da solução. Resistência geralmente vem de não entender o contexto ou não ter sido consultado."

**P: Por que você e não outro candidato?**
> "Combino três coisas: capacidade analítica para estruturar problemas — como mostrei na validação de hipótese. Conhecimento técnico para implementar soluções com IA — como o plano de automação. E experiência de liderança hands-on — não só planejo, executo junto com o time."

**P: O que você faria diferente se tivesse mais tempo?**
> "Aprofundaria a análise de procedência BACEN — era um gap da base. E faria entrevistas qualitativas com analistas para entender gargalos que os dados não mostram — às vezes o problema é processo, não volume."

**P: Esses números de impacto são realistas?**
> "Usei P75 como referência — se 25% dos casos já atingem esse SLA, é factível para os demais. E as ações são progressivas em 3 fases justamente para validar antes de escalar."

---

## MENSAGENS-CHAVE (MEMORIZE)

1. **"SLA é a causa raiz"** — atacando um, melhoro três. Comprovado com dados.

2. **"O problema está concentrado"** — Collections = 44,73%. Foco gera impacto.

3. **"76k casos RDR sem feedback"** — 97% não respondem tNPS. Ponto cego crítico.

4. **"46% → 12% em 90 dias"** — redução de 74% nos casos críticos.

5. **"Autonomia com alinhamento"** — framework RICE, não dependência do líder.

6. **"Meu diferencial é execução"** — não só planejo, trabalho junto com o time.
