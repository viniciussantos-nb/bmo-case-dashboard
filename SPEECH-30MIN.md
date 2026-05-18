# Speech — Case BMO Ouvidoria
## Processo Seletivo Nubank | 30 minutos (versão final)

---

## ESTRUTURA OTIMIZADA PARA 30 MINUTOS

| Módulo | Tempo | Slides | Foco |
|--------|-------|--------|------|
| Abertura | 2 min | 0-1 | Contexto + Agenda |
| Diagnóstico | 10 min | 2-7 | Problemas + Validação + Pareto |
| Plano de Ação | 6 min | 8-14 | Ações + IA (resumido) |
| **Gestão de Pessoas** | **10 min** | **15-18** | **Foco principal** |
| Fechamento | 2 min | 19 | Síntese |

---

## SPEECH COMPLETO

---

### ABERTURA (2 min)

#### Slide 0: Capa (1 min)

"Bom dia/Boa tarde. Sou Vinícius Santos e vou apresentar o case de BMO Ouvidoria.

**Antes de começar, um contexto:** o case completo foi enviado anteriormente e passou pelo processo de triagem, então vou focar nos **principais pontos e na linha de raciocínio** que usei para chegar nas conclusões. Se em algum momento quiserem que eu aprofunde algum ponto ou tiverem dúvidas, fiquem à vontade para interromper ou anotar para o final.

**A conclusão principal que cheguei:** identifiquei 3 problemas críticos na operação, mas descobri que eles não são independentes. O SLA elevado é a causa raiz que amplifica os outros dois. Minha estratégia é atacar o SLA primeiro — resolvendo um, melhoramos os três."

---

#### Slide 1: Agenda (1 min)

"A apresentação está organizada em 4 módulos:

**Módulo 1 — Diagnóstico:** Os 3 problemas críticos e a validação estatística de que SLA é a causa raiz.

**Módulo 2 — Estratégia de Dados:** Governança com Golden Source e diferença entre dashboards.

**Módulo 3 — Automação:** Oportunidades com IA e análise de ROI.

**Módulo 4 — Gestão de Pessoas:** O plano 30-60-90, framework de priorização e modelo de gestão do time — que é onde vou me aprofundar mais.

Vamos começar."

---

### MÓDULO 1: DIAGNÓSTICO (10 min)

#### Slide 2: 3 Problemas Críticos (2 min 30 seg)

"Analisei **337.614 casos** de janeiro a dezembro de 2025. Os indicadores gerais já mostram o cenário: SLA médio de **6,48 dias**, resolutividade de **35,3%**, taxa de resposta tNPS de **7,2%**.

Identifiquei **3 problemas críticos**:

**1. SLA Elevado (Prioridade Crítica):**
- **46,12%** dos casos excedem 7 dias — mais de 155 mil casos
- O SLA **piorou 65% no ano** — de 4,5 para 7,4 dias
- Risco regulatório direto: BACEN exige 10 dias úteis

**2. Baixa Resolutividade RDR (Prioridade Alta):**
- Apenas **16-19%** de resolução
- São **114 mil casos** com tNPS de **-66**
- Clientes que já escalaram para o BACEN

**3. Baixa Taxa de Resposta tNPS (Prioridade Média):**
- Apenas **7,2%** respondem
- **92,8%** são detratores silenciosos — sem visibilidade para melhoria

**A tese central:** SLA é a causa raiz. Quem é atendido rápido tem problema resolvido e responde mais à pesquisa."

---

#### Slide 3: Validação da Hipótese (2 min 30 seg)

"Fui validar essa hipótese nos dados. Dividi os casos em duas categorias:

**Rápido: 0 a 3 dias** — Escolhi esse corte porque representa atendimentos dentro de uma margem confortável, onde ainda há tempo para eventuais retrabalhos sem estourar o prazo.

**Lento: 4 dias ou mais** — A partir daqui, cada dia adicional consome a margem de segurança até o limite regulatório de 10 dias.

**Os resultados:**

| Categoria | Resolutividade | tNPS |
|-----------|----------------|------|
| Rápido (0-3 dias) | **42%** | **6,1** |
| Lento (4+ dias) | **24,5%** | **4,2** |
| Diferença | **-17,5pp** | **-1,9pts** |

**Por squad, a correlação se mantém:**
- Collections: 45% vs 21% — diferença de 24pp
- CSS: 44% vs 22% — diferença de 22pp

**A conclusão:** a cada dia adicional de SLA, perdemos ~3pp de resolutividade e ~0,5pts de tNPS. Casos até 3 dias têm **71% mais chance** de resolução.

**Por que 7 dias como corte crítico?** Representa 70% do prazo BACEN — margem de segurança antes do limite regulatório."

---

#### Slide 4: Matriz de Impactos (1 min)

"A matriz cruza os 3 problemas com impactos regulatório, reputacional e operacional.

**O ponto mais crítico:** SLA + RDR combinados geram **76 mil casos com 97% de não resposta ao tNPS**. É nosso maior ponto cego — sem feedback para melhorar justamente onde o risco reputacional é maior.

*[Os detalhes estão no slide — avanço para a análise de causa raiz]*"

---

#### Slide 5: Gaps de Dados (30 seg)

"Por transparência: a base tinha gaps. O principal é a **ausência do campo de procedência BACEN** — usei SLA e resolutividade como proxies. Os demais gaps estão documentados no slide e têm impacto menor na análise."

---

#### Slide 6: Análise Pareto (1 min 30 seg)

"Onde está concentrado o problema?

**Por canal:** RDR e Email = **92,95%** dos casos críticos
**Por squad:** **Collections = 44,73%** do problema

O insight: o problema está concentrado. Focando em Collections, ataco quase metade do problema."

---

#### Slide 7: Drill-Down Collections (2 min)

"Dentro de Collections, os reasons por taxa de estouro:

- **SCR:** 91,84% — praticamente todo caso estoura
- **Multidébitos:** 86,7%
- **Cartão de Crédito:** 81,1%
- **Empréstimo em Atraso:** 79,84%
- **Acordo CI:** 49,51%

**Por que esses reasons têm SLA elevado?**

- **SCR** exige consulta ao BACEN/Serasa e análise manual de histórico — processo burocrático
- **Multidébitos** requer análise cruzada de múltiplas dívidas — negociação complexa
- **Cartão de Crédito** envolve disputas e processo de estorno — depende de terceiros

**Acordo CI** tem maior volume (51k casos), mas taxa de 49% indica processo mais controlado.

**Conclusão:** SCR e Multidébitos são os alvos prioritários — processos complexos com >85% de estouro.

SLA médio de Collections: **9,04 dias** — já acima do limite regulatório."

---

### MÓDULO 2: PLANO DE AÇÃO (6 min)

#### Slide 8: Plano de Ação 90 dias (2 min)

"O plano em 3 fases, focando em Collections:

**Fase 1 — 30 dias — Quick Wins:**
- Triagem automatizada por IA
- Templates para os 5 reasons mais frequentes
- Task Force em Collections
- **Meta: SLA ≤ 5,8 dias**

**Fase 2 — 60 dias — Estruturação:**
- Agent IA para respostas simples
- Dashboard de monitoramento
- **Meta: SLA ≤ 4,8 dias**

**Fase 3 — 90 dias — Transformação:**
- IA Generativa para sugestão de respostas
- Feedback loop com Produto
- **Meta: SLA ≤ 3,5 dias**

**Impacto em 90 dias:**
- SLA: 6,5 → 3,5 dias (redução de 46%)
- Casos críticos: 46% → 12% (redução de 74%)
- Resolutividade RDR: 18% → 55%"

---

#### Slide 9: Desenvolvimento do Time (30 seg)

"Para executar, o time precisa de **autonomia com alinhamento**. Três pilares:

1. **Playbook** com critérios claros de análise
2. **Perguntas-guia** para direcionar investigações
3. **Calibração semanal** para ajustes

O objetivo: analistas tomam decisões sem depender do líder para cada passo."

---

#### Slide 10: Golden Source (1 min)

"Sobre consistência de dados — a metodologia **Golden Source**.

**O que é:** Uma arquitetura onde existe uma **única fonte primária de dados** considerada a versão oficial. Todas as outras fontes derivam dela ou são validadas contra ela.

**Por que importa:** Elimina o problema de 'meu número diz X, o seu diz Y'. Quando há divergência, a Golden Source é o árbitro.

**Na prática:** Golden Source alimenta o Framework de Core Metrics — as 5 métricas que importam. Esse framework materializa no Dashboard Operacional, que vira a **fonte única da verdade** para a operação."

---

#### Slide 11: Dashboard Executivo vs Operacional (30 seg)

"Em resumo:
- **Executivo:** 5 KPIs, visão estratégica, decisão de onde investir
- **Operacional:** Drill-down completo, visão tática, ação imediata

São complementares — o executivo direciona, o operacional executa."

---

#### Slide 12: Bot de Triagem (30 seg)

"O bot parado há 3 meses: **retomar com validação técnica**.

Plano de 30 dias: discovery, recalibração, shadow mode.

Critério GO/NO-GO: acurácia ≥ 85%. Se não atingir, não ativa."

---

#### Slide 13: ROI do Bot (30 seg)

"ROI com premissas conservadoras:

**Premissas:**
- Tempo economizado por caso: 3 minutos
- Custo FTE: **R$ 40/hora**
- Volume anual de triagem

**Resultado estimado:** Economia de aproximadamente **R$ 250 mil/ano** e liberação de **3-4 FTEs** para tarefas de maior valor.

*Nota: São estimativas que precisam ser validadas com dados reais de tempo de triagem.*"

---

#### Slide 14: Outros Casos de IA (30 seg)

"Duas oportunidades adicionais de IA:

**1. Agent IA para Respostas Simples:**
- Automatiza casos de baixa complexidade
- **Impacto:** Libera headcount para casos complexos, padroniza comunicação, reduz tempo de primeira resposta

**2. AI CX Analysis Plugin:**
- Analisa conversas e identifica padrões automaticamente
- **Impacto:** Classifica reasons automaticamente, identifica tendências antes que virem problemas, melhora qualidade dos dados

Ambas atacam a raiz do problema: mais eficiência operacional com menos esforço manual."

---

### MÓDULO 4: GESTÃO DE PESSOAS (10 min)

#### Slide 15: Roadmap 4 Semanas (1 min 30 seg)

"Para o Fórum de liderança, estruturei um roadmap de 4 semanas com **2 tracks paralelos**:

**Track 1 — Diagnóstico:**
- Semana 1: Extração e limpeza de dados
- Semana 2: Análise Pareto com suporte de IA
- Semana 3: Validação de hipóteses
- Semana 4: Dashboards operacional e executivo

**Track 2 — Bot de Triagem:**
- Semana 1: Discovery e benchmark
- Semana 2: Requisitos de recalibração
- Semana 3: Shadow mode
- Semana 4: Relatório GO/NO-GO

**Distribuição dos 5 analistas:**
- A1/A2: Dados — extração, limpeza, qualidade
- A3: IA — análise Pareto com Cursor
- A4: Negócio — bot, stakeholders
- A5: Dashboards — operacional e executivo

Os tracks rodam em paralelo porque usam stakeholders diferentes."

---

#### Slide 16: Framework RICE (1 min 30 seg)

"Para priorização autônoma, uso o framework **RICE**:

- **R**each: Quantos casos são impactados
- **I**mpact: Nível de impacto no KPI
- **C**onfidence: Confiança na estimativa
- **E**ffort: Esforço em semanas/pessoa

**Fórmula:** (R × I × C) ÷ E

**Importante: BAU vs Estratégico**

Na priorização, separo as demandas em duas categorias:

- **BAU (Business As Usual):** Atividades rotineiras e operacionais do dia a dia — responder casos, monitorar filas, gerar relatórios recorrentes. São necessárias, mas não transformam.

- **Iniciativas Estratégicas:** Projetos que geram mudança estrutural — implementar IA, criar dashboards, otimizar processos. São o que move os indicadores.

O RICE ajuda a priorizar as iniciativas estratégicas. O BAU tem sua cadência própria. Na Weekly, alinhamos: quanto tempo vai para BAU, quanto vai para estratégico. Se o BAU está consumindo 100% do time, não há transformação."

---

#### Slide 17: Plano 30-60-90 (3 min)

"Agora o plano executivo completo em **30-60-90 dias**:

**30 DIAS — Foco: SLA**
- **Iniciativas:** Dashboard no Fórum, Bot de Triagem validado e ativo, Task Force Collections
- **Stakeholders:** Dados, IA, Engenharia
- **Marco de Sucesso:** Dashboard apresentado + Bot com acurácia ≥ 85%

**60 DIAS — Foco: Resolutividade**
- **Iniciativas:** Fila prioritária RDR, Agent IA em piloto, Dashboard de monitoramento em tempo real
- **Stakeholders:** Produto, Operação
- **Marco de Sucesso:** Resolutividade RDR ≥ 25%

**90 DIAS — Foco: tNPS**
- **Iniciativas:** IA Generativa, Estudo de dimensionamento, Priorização de reasons críticos
- **Stakeholders:** Estratégia, Qualidade
- **Marco de Sucesso:** Taxa resposta tNPS ≥ 12%, SLA ≤ 3,5 dias

**RISCOS DE EXECUÇÃO E MITIGAÇÕES:**

**Risco Regulatório:** BACEN pode escalar casos durante a transição
→ **Mitigação:** Comunicação proativa com compliance, priorização absoluta de RDR, monitoramento diário de casos próximos ao limite

**Risco Operacional:** Backlog pode crescer durante implementação de mudanças
→ **Mitigação:** Task Force temporária com analistas sênior, horas extras controladas no primeiro mês, alocação extra se necessário

**Risco de Pessoas:** Sobrecarga de trabalho durante período de mudança
→ **Mitigação:** Distribuição equilibrada via RICE, monitoramento de carga nas 1:1s, ajuste de escopo se necessário

**Risco Tecnológico:** Bot pode não atingir acurácia esperada
→ **Mitigação:** GO/NO-GO rigoroso em 30 dias, plano B com triagem manual otimizada, não ativar sem validação"

---

#### Slide 18: Gestão de Pessoas (4 min)

"Por fim, e o mais importante para esta avaliação: como pretendo **liderar o time de 5 analistas sênior**.

**TIMELINE SEMANAL DE RITUAIS:**

**Daily (15 min) — Todo dia às 9h:**
- Acompanhamento do progresso das tarefas RICE
- Identificação de bloqueios
- Prioridades do dia
- Formato: standup rápido, cada um fala o que fez, o que vai fazer, e se tem impedimento

**1:1 (45 min) — Individual, sexta-feira:**
- Não é status report — é desenvolvimento
- Conversa sobre carreira, aspirações, feedback
- Revisão de entregas da semana
- PDI: o que a pessoa quer desenvolver, como posso ajudar
- Fundamental para reter talentos e identificar insatisfações cedo

**Weekly (1h) — Time completo, segunda-feira:**
- Revisão da semana anterior: o que funcionou, o que não funcionou
- Planejamento da semana: distribuição de tarefas via RICE
- Alinhamento BAU vs Estratégico: o que é urgente vs o que é importante
- Espaço para o time trazer problemas e sugestões

**Integração Mensal:**
- Atividade fora do contexto de trabalho
- Coffee, almoço de time, team building
- Importante para coesão do grupo

**OS 4 PILARES DE GESTÃO:**

**Pilar 1 — Desenvolvimento Técnico:**
- PDI individualizado por competência — cada analista tem gaps diferentes
- Capacitação em ferramentas: Cursor, SQL, Python, análise de dados
- Mentoria técnica direta — não terceirizo, faço junto
- Objetivo: elevar o nível técnico do time continuamente

**Pilar 2 — Rituais e Acompanhamento:**
- Cadência clara de entregas — todo mundo sabe o que é esperado
- 1:1 focado em desenvolvimento, não em cobrança
- Feedback contínuo, não só em avaliação formal
- Weekly estruturada com pauta definida

**Pilar 3 — Engajamento:**
- **Ownership:** Cada analista é 'dono' de um projeto estratégico — não executor de tarefas
- **Visibilidade:** Reconhecimento em fóruns executivos — quem fez o trabalho apresenta
- **Integração:** Atividades mensais para fortalecer o time como grupo

**Pilar 4 — Liderança Técnica (Meu Diferencial):**
- **Hands-on:** Não sou líder que delega e cobra. Atuo junto ao time em entregas críticas
- **Mentoria em IA:** Tenho experiência com Cursor, automação, análise de dados — posso capacitar o time
- **Contexto de negócio:** Sei traduzir demandas técnicas para linguagem executiva e vice-versa

**CONSTRUÇÃO DE AUTONOMIA:**

O modelo que proponho **não cria dependência do líder**. O objetivo é construir capacidade analítica e decisória no time.

- Framework RICE permite que qualquer analista priorize sem precisar perguntar
- Playbook documenta critérios de decisão
- 1:1 desenvolve, não controla
- Ownership dá responsabilidade real, não tarefas

**TIME ENXUTO, ALTO IMPACTO:**

Com 5 analistas sênior bem direcionados + liderança técnica hands-on, a capacidade é multiplicada sem aumento de headcount. O diferencial está em:
- Processos claros
- Ferramentas certas
- Desenvolvimento contínuo
- Liderança que trabalha junto"

---

### FECHAMENTO (2 min)

#### Slide 19: Encerramento

"Para resumir:

**O problema:** 3 indicadores críticos com uma causa raiz comum — SLA. Comprovado com dados: casos rápidos têm o dobro da resolutividade.

**A estratégia:** Foco em SLA, priorizando Collections que representa 44,73% do problema.

**O plano:** 90 dias com metas progressivas, riscos mapeados, mitigações definidas.

**A gestão:** Time com autonomia via RICE, rituais estruturados, desenvolvimento contínuo, e liderança técnica hands-on.

**Meu diferencial:** Combino capacidade analítica para estruturar problemas, conhecimento técnico para implementar soluções com IA, e experiência de liderança que desenvolve — não controla.

Estou à disposição para perguntas."

---

## RESUMO DE TEMPOS (TOTAL: 30 min)

| Slide | Título | Tempo |
|-------|--------|-------|
| 0 | Capa | 1 min |
| 1 | Agenda | 1 min |
| 2 | 3 Problemas Críticos | 2 min 30 seg |
| 3 | Validação da Hipótese | 2 min 30 seg |
| 4 | Matriz de Impactos | 1 min |
| 5 | Gaps de Dados | 30 seg |
| 6 | Análise Pareto | 1 min 30 seg |
| 7 | Drill-Down Collections | 2 min |
| 8 | Plano de Ação 90 dias | 2 min |
| 9 | Desenvolvimento do Time | 30 seg |
| 10 | Golden Source | 1 min |
| 11 | Dashboard Exec vs Oper | 30 seg |
| 12 | Bot de Triagem | 30 seg |
| 13 | ROI do Bot | 30 seg |
| 14 | Outros Casos de IA | 30 seg |
| 15 | Roadmap 4 Semanas | 1 min 30 seg |
| 16 | Framework RICE | 1 min 30 seg |
| 17 | Plano 30-60-90 | 3 min |
| 18 | **Gestão de Pessoas** | **4 min** |
| 19 | Encerramento | 2 min |
| **TOTAL** | | **30 min** |

---

## SLIDES RESUMIDOS (para compensar tempo)

Os seguintes slides foram **reduzidos** para dar mais tempo à gestão de pessoas:

| Slide | Antes | Depois | Economia |
|-------|-------|--------|----------|
| 4 - Matriz de Impactos | 2 min | 1 min | 1 min |
| 5 - Gaps de Dados | 1 min 30 seg | 30 seg | 1 min |
| 9 - Desenvolvimento | 1 min | 30 seg | 30 seg |
| 11 - Exec vs Oper | 1 min | 30 seg | 30 seg |
| 12 - Bot de Triagem | 1 min 30 seg | 30 seg | 1 min |
| 13 - ROI | 1 min | 30 seg | 30 seg |
| 14 - Outros IA | 1 min | 30 seg | 30 seg |

**Tempo economizado:** ~5 min → Realocado para slides 17 e 18

---

## MENSAGENS-CHAVE

1. **"SLA é a causa raiz"** — atacando um, melhoro três

2. **"Rápido = 0-3 dias, Lento = 4+ dias"** — corte baseado em margem de segurança

3. **"Collections = 44,73%"** — o problema está concentrado

4. **"Golden Source = fonte única da verdade"** — elimina divergência de números

5. **"Autonomia com alinhamento"** — framework RICE, não dependência

6. **"Liderança hands-on"** — não delego e cobro, trabalho junto

---

## POSSÍVEIS PERGUNTAS

**P: Por que 0-3 dias como "Rápido"?**
> "Margem de segurança. Com 3 dias, ainda há tempo para retrabalho sem estourar o prazo. A partir de 4 dias, cada dia consome a margem até o limite de 10."

**P: De onde veio o custo de R$ 40/hora?**
> "Estimativa baseada em custo médio de analista sênior + encargos. É uma premissa que precisaria ser validada com dados reais de RH."

**P: Como você lida com resistência do time?**
> "Começo pelo porquê. Mostro os dados, o impacto. Envolvo na construção. Resistência geralmente vem de não entender o contexto ou não ter sido consultado."

**P: Por que você e não outro candidato?**
> "Três coisas: capacidade analítica — como mostrei no diagnóstico. Conhecimento técnico — IA, Cursor, automação. E liderança que desenvolve — não controlo, construo autonomia."

**P: O que faria diferente com mais tempo?**
> "Entrevistas qualitativas com analistas para entender gargalos que os dados não mostram. E análise de procedência BACEN que era um gap da base."
