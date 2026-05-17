# Speech — Case BMO Ouvidoria
## Processo Seletivo Nubank | 30 minutos

---

## DIFERENÇAS DE UM CASE PARA PROCESSO SELETIVO

| Apresentação Executiva | Case Processo Seletivo |
|------------------------|------------------------|
| Foco no conteúdo | Foco em **como você pensa** |
| Resultado final | **Processo de raciocínio** |
| "O problema é X" | "**Eu identifiquei** que o problema é X" |
| Dados falam por si | **Você explica suas escolhas** |
| Assumir contexto | **Contextualizar para quem não conhece** |

**O que estão avaliando:**
- Capacidade analítica (estruturação, priorização)
- Tomada de decisão com dados incompletos
- Comunicação clara e objetiva
- Visão de liderança e gestão de pessoas
- Fit cultural (customer-centric, autonomia, ownership)

---

## ESTRUTURA RECOMENDADA

```
1. ABERTURA (2 min)
   → Contexto + Objetivo + Spoiler da conclusão

2. DIAGNÓSTICO (10 min)
   → Metodologia + Descobertas + Validação

3. SOLUÇÃO (10 min)
   → Plano de ação + Governança + Automação

4. GESTÃO DE PESSOAS (6 min)
   → Priorização + Roadmap + Modelo de liderança

5. FECHAMENTO (2 min)
   → Síntese + Diferencial + Abertura para perguntas
```

---

## SPEECH COMPLETO

---

### ABERTURA (2 min)

#### Slide 0: Capa (30 seg)

> "Bom dia/Boa tarde. Sou Vinícius Santos e vou apresentar minha análise do case de BMO Ouvidoria.
>
> Antes de começar, quero compartilhar a conclusão principal que cheguei — assim vocês podem acompanhar meu raciocínio sabendo onde vou chegar:
>
> **Identifiquei 3 problemas críticos na operação, mas descobri que eles não são independentes. O SLA elevado é a causa raiz que amplifica os outros dois. Portanto, minha estratégia é atacar o SLA primeiro — resolvendo um, melhoramos os três.**"

*[Por que isso funciona: Dar o spoiler no início mostra confiança e ajuda o avaliador a seguir sua lógica]*

---

#### Slide 1: Agenda (1 min 30 seg)

> "Organizei a apresentação em 4 módulos:
>
> **Módulo 1 — Diagnóstico:** Como cheguei nos 3 problemas críticos e por que priorizei o SLA.
>
> **Módulo 2 — Estratégia de Dados:** Como garantir consistência nas métricas e construir dashboards que gerem ação.
>
> **Módulo 3 — Automação e IA:** Oportunidades de escala com tecnologia, incluindo análise de ROI.
>
> **Módulo 4 — Gestão de Pessoas:** Como estruturar o time de 5 analistas e o plano 30-60-90 dias.
>
> Ao longo da apresentação, vou explicar **por que fiz cada escolha** — não apenas o que fiz."

---

### MÓDULO 1: DIAGNÓSTICO (10 min)

#### Slide 2: 3 Problemas Críticos (3 min)

> "Recebi uma base com 337 mil casos de janeiro a dezembro de 2025. Meu primeiro passo foi entender: **qual é o problema que mais importa resolver?**
>
> Analisando os dados, identifiquei 3 problemas críticos:
>
> **Primeiro: SLA elevado.** 46% dos casos — mais de 155 mil — excedem 7 dias. Por que 7 dias? Porque o BACEN estabelece 10 dias úteis como limite. 7 dias representa 70% desse prazo — é uma margem de segurança operacional. Passar disso significa risco regulatório real.
>
> **Segundo: Baixa resolutividade no RDR.** Apenas 18% dos casos escalados para o BACEN são resolvidos. Ou seja, 82% dos clientes que escalam saem sem solução. Isso tem impacto reputacional direto.
>
> **Terceiro: Baixa taxa de resposta do tNPS.** Apenas 7,2% respondem à pesquisa. Os outros 93% são o que chamo de 'detratores silenciosos' — não temos visibilidade para melhorar.
>
> **Mas aqui está o insight que mudou minha abordagem:** esses problemas não são independentes. Quando cruzei os dados, descobri uma correlação forte entre eles. E isso me levou a uma hipótese."

---

#### Slide 3: Validação da Hipótese (2 min 30 seg)

> "Minha hipótese era: **SLA é o driver dos outros dois problemas.** Se isso fosse verdade, eu não precisaria atacar três frentes — bastaria focar em uma.
>
> Fui validar nos dados:
>
> **Teste 1 — SLA vs Resolutividade:** Casos atendidos em até 3 dias têm 42% de resolutividade. Acima de 4 dias, cai para 24,5%. É praticamente o dobro.
>
> **Teste 2 — SLA vs tNPS:** Clientes com atendimento rápido têm tNPS de -8. Com SLA longo, -45. A diferença é de 37 pontos.
>
> **Teste 3 — SLA vs Taxa de Resposta:** Clientes satisfeitos respondem mais. Se o SLA melhora, a taxa de resposta também melhora.
>
> **Conclusão:** A hipótese se confirmou. SLA é a causa raiz. **Por isso minha estratégia é concentrar esforços no SLA primeiro** — os outros indicadores melhoram como consequência.
>
> Isso é importante porque, com recursos limitados, precisamos escolher onde focar. Atacar três problemas ao mesmo tempo dilui o impacto."

---

#### Slide 4: Matriz de Impactos (1 min)

> "Aqui está a matriz cruzando os 3 problemas com impactos regulatório, operacional e reputacional.
>
> O ponto que quero destacar: quando combinamos SLA alto com baixa resolutividade no RDR, temos **76 mil casos com 97% de não resposta ao tNPS**. Não temos visibilidade operacional desse segmento. É um ponto cego crítico que precisa de atenção.
>
> *[Avançar — este slide é suporte visual, não precisa detalhar cada célula]*"

---

#### Slide 5: Gaps de Dados (1 min)

> "Uma coisa que aprendi em análise de dados: **transparência sobre limitações aumenta credibilidade.**
>
> A base tinha gaps. O mais relevante: não tinha o campo de procedência BACEN que o case menciona. Usei SLA e resolutividade como proxies.
>
> Outros gaps menores — receiving method em branco, IDs repetidos — estão documentados aqui. Na seção de dados adicionais, listei o que precisaríamos consultar para aprofundar.
>
> **Por que mostro isso?** Porque em ambiente real, dados nunca são perfeitos. O importante é saber trabalhar com o que tem e ser transparente sobre as limitações."

---

#### Slide 6: Análise Pareto (1 min 30 seg)

> "Com o problema definido — SLA elevado — fui fazer análise de causa raiz usando Pareto.
>
> **Por canal:** RDR e Email concentram 92,95% dos casos críticos. Apenas 2 de 7 canais.
>
> **Por squad:** Collections sozinho representa 44,73% do problema.
>
> **O insight:** O problema está concentrado. Não preciso resolver tudo — se eu focar em Collections e RDR, ataco quase metade do problema.
>
> Isso guiou minha priorização: Collections primeiro."

---

#### Slide 7: Drill-Down Collections (1 min)

> "Dentro de Collections, identifiquei os reasons mais críticos:
>
> - **SCR:** 91,84% de estouro
> - **Multidébitos:** 86,7%
> - **Cartão de Crédito:** 81,1%
>
> Esses são os alvos do plano de ação. SCR e Multidébitos com fila prioritária e templates padronizados já geram impacto significativo."

---

### MÓDULO 2: SOLUÇÃO (10 min)

#### Slide 8: Plano de Ação 90 dias (3 min)

> "Agora, como resolver. Estruturei um plano em 3 fases com metas progressivas.
>
> **Fase 1 — 30 dias — Quick Wins:**
> - Triagem automatizada por IA
> - Templates para os 5 reasons mais frequentes
> - Task Force em Collections
> - **Meta: SLA ≤ 5,8 dias**
>
> **Fase 2 — 60 dias — Estruturação:**
> - Agent IA para respostas simples
> - Dashboard de monitoramento com alertas
> - Revisão de roteamento
> - **Meta: SLA ≤ 4,8 dias**
>
> **Fase 3 — 90 dias — Transformação:**
> - IA Generativa para sugestão de respostas
> - Feedback loop com Produto
> - Estudo de dimensionamento
> - **Meta: SLA ≤ 3,5 dias**
>
> **Impacto esperado em 90 dias:**
> - SLA: 6,5 → 3,5 dias (redução de 46%)
> - Casos críticos: 46% → 12% (redução de 74%)
> - Resolutividade RDR: 18% → 55%
> - Taxa tNPS: 7% → 18%
>
> **Por que essas metas?** Usei P75 como referência — ou seja, se 25% dos casos já atingem esse SLA, é factível para os demais."

---

#### Slide 9: Desenvolvimento do Time (1 min)

> "Para executar, o time precisa de **autonomia com alinhamento**.
>
> Estruturei em 3 pilares:
> 1. Playbook com critérios claros
> 2. Perguntas-guia para análises independentes
> 3. Calibração semanal
>
> O objetivo: analistas tomam decisões sem depender do líder para cada passo."

---

#### Slide 10: Golden Source (1 min 30 seg)

> "Uma pergunta do case era sobre consistência de dados entre fontes diferentes.
>
> Minha resposta: **arquitetura de Golden Source.**
>
> Uma fonte primária alimenta um Framework de Core Metrics — 5 métricas que importam: SLA, Resolutividade, tNPS, Volume, Taxa de Resposta.
>
> Esse framework materializa no Dashboard Operacional, que vira a **fonte única da verdade**. Qualquer discussão de número parte dali.
>
> Isso elimina o problema de 'meu número diz X, o seu diz Y'."

---

#### Slide 11: Dashboard Executivo vs Operacional (1 min)

> "Outra pergunta do case: diferença entre dashboard executivo e operacional.
>
> **Executivo:** 5 KPIs, visão estratégica, responde 'onde investir recursos?'
>
> **Operacional:** drill-down por squad, canal, reason, período. Responde 'por que o SLA de Collections subiu esta semana?'
>
> São complementares. O executivo decide, o operacional executa."

---

#### Slide 12: Bot de Triagem (1 min 30 seg)

> "O case perguntava sobre um bot de triagem parado há 3 meses.
>
> **Minha recomendação: retomar, mas com validação técnica.**
>
> Na matriz de priorização: impacto alto, esforço médio, risco médio-alto.
>
> **Plano de 30 dias:**
> - Semanas 1-2: Discovery e benchmark
> - Semanas 2-3: Recalibração com dados recentes
> - Semanas 3-4: Shadow mode com validação humana
>
> **Critério GO/NO-GO:** acurácia ≥ 85%. Se não atingir, não ativa.
>
> Por que esse approach? Prefiro transparência a risco operacional. Bot com baixa acurácia gera retrabalho."

---

#### Slide 13: ROI do Bot (1 min)

> "Fiz a conta de ROI com premissas conservadoras:
>
> - 30% dos casos são triagem simples
> - 3 minutos economizados por caso
> - R$ 35/hora por FTE
>
> **Resultado:** R$ 236 mil/ano de economia, 3,4 FTEs liberados.
>
> Importante: são estimativas. Deixei documentado que precisaria validar o tempo de triagem manual com dados reais. **Transparência sobre premissas é fundamental.**"

---

#### Slide 14: Outros Casos de IA (1 min)

> "Identifiquei mais 2 oportunidades de IA:
>
> **Agent IA para Respostas Simples:** automatiza casos de baixa complexidade.
>
> **AI CX Analysis Plugin:** analisa conversas e identifica padrões. Resolve gaps de dados que mencionei.
>
> Ambas entram no roadmap de 60-90 dias."

---

### MÓDULO 4: GESTÃO DE PESSOAS (6 min)

#### Slide 15: Roadmap 4 Semanas (1 min 30 seg)

> "Para preparar o Fórum de liderança, estruturei um roadmap de 4 semanas com 2 tracks paralelos.
>
> **Track 1 — Diagnóstico:** extração, Pareto, dashboards
> **Track 2 — Bot:** discovery, requisitos, shadow mode
>
> Distribuí os 5 analistas por skill:
> - A1/A2: Dados
> - A3: IA e Pareto
> - A4: Negócio
> - A5: Dashboards
>
> Os tracks rodam em paralelo porque usam stakeholders diferentes."

---

#### Slide 16: Framework RICE (1 min)

> "Para o time priorizar de forma autônoma, implemento o framework RICE.
>
> **Reach** × **Impact** × **Confidence** ÷ **Effort**
>
> Isso permite que qualquer analista proponha uma ação e calcule prioridade objetivamente, sem depender de percepção.
>
> **Por que RICE e não outro?** É simples, quantificável e amplamente usado em produto. Facilita alinhamento com outras áreas."

---

#### Slide 17: Plano 30-60-90 (2 min)

> "O plano consolidado:
>
> **30 dias — Foco em SLA:**
> - Dashboard no Fórum
> - Bot ativo (acurácia ≥ 85%)
> - Task Force Collections
>
> **60 dias — Foco em Resolutividade:**
> - Fila prioritária RDR
> - Agent IA em piloto
>
> **90 dias — Foco em tNPS:**
> - IA Generativa
> - Feedback loop com Produto
>
> **Riscos mapeados:** regulatório, operacional, pessoas, tecnológico. Cada um com mitigação.
>
> Por que mapeei riscos? Porque plano sem risco mapeado é wishful thinking. Prefiro antecipar problemas."

---

#### Slide 18: Gestão de Pessoas (1 min 30 seg)

> "Por fim, como pretendo liderar o time de 5 analistas sênior.
>
> **Rituais:**
> - Daily 15 min
> - 1:1 semanal
> - Weekly de alinhamento
> - Integração mensal
>
> **4 pilares:** Desenvolvimento técnico, rituais estruturados, engajamento via ownership, e liderança técnica.
>
> **Meu diferencial como líder:** Atuo hands-on. Não delego e cobro — trabalho junto. Tenho experiência com IA e ferramentas como Cursor, que posso usar para mentoria do time. E sei traduzir demandas técnicas para linguagem executiva.
>
> O modelo não cria dependência — constrói autonomia."

---

### FECHAMENTO (2 min)

#### Slide 19: Encerramento

> "Para resumir:
>
> **O problema:** 3 indicadores críticos que parecem independentes, mas têm uma causa raiz comum — SLA.
>
> **A estratégia:** Foco em SLA primeiro. Atacando um, melhoramos os três.
>
> **O plano:** 90 dias com metas progressivas, ROI calculado, riscos mapeados.
>
> **A gestão:** Time com autonomia, frameworks para priorização, rituais estruturados.
>
> **Meu diferencial:** Combino visão analítica com capacidade de execução. Sei estruturar problemas complexos, mas também sei colocar a mão na massa com o time.
>
> Estou à disposição para perguntas."

---

## RESUMO DE TEMPOS

| Módulo | Tempo | O que avalia |
|--------|-------|--------------|
| Abertura | 2 min | Comunicação, síntese |
| Diagnóstico | 10 min | Capacidade analítica |
| Solução | 10 min | Tomada de decisão |
| Gestão | 6 min | Liderança |
| Fechamento | 2 min | Síntese, confiança |
| **Total** | **30 min** | |

---

## DICAS PARA O DIA

### Linguagem
- Use **"eu identifiquei"**, **"minha análise mostrou"**, **"minha recomendação é"**
- Evite passivo: "foi identificado", "os dados mostram"
- Mostre ownership

### Ritmo
- Não corra nos slides de diagnóstico — é onde você mostra raciocínio
- Slides de suporte (matriz, gaps) podem ser mais rápidos
- Pause antes de insights importantes

### Se der branco
- Volte para a mensagem principal: "O ponto aqui é que SLA é a causa raiz"
- Você sabe o conteúdo — o speech é guia, não script decorado

### Perguntas difíceis
- "Não tenho essa informação na base, mas faria X para descobrir"
- "Essa é uma boa pergunta — minha hipótese seria Y, e validaria assim"
- Nunca invente dados

---

## POSSÍVEIS PERGUNTAS E RESPOSTAS

**P: Por que você escolheu 7 dias como corte?**
> "70% do prazo BACEN. É uma margem de segurança — se eu usar 10 dias, já estou no limite regulatório sem margem de manobra."

**P: Como você validaria se o bot realmente funciona?**
> "Shadow mode por 2 semanas: o bot classifica, mas humano valida. Comparo acurácia. Se < 85%, não ativo e investigo o que está errando."

**P: E se o time resistir às mudanças?**
> "Começo pelo porquê. Mostro os dados, o impacto nos indicadores. Envolvo na construção da solução. Resistência geralmente vem de não entender o contexto."

**P: Por que você e não outro candidato?**
> "Combino três coisas: capacidade analítica para estruturar problemas, conhecimento técnico para implementar soluções com IA, e experiência de liderança para desenvolver o time. Não só planejo — executo junto."

**P: O que você faria diferente se tivesse mais tempo?**
> "Aprofundaria a análise de procedência BACEN — era um gap da base. E faria entrevistas qualitativas com analistas para entender gargalos que os dados não mostram."

**P: Como você lida com pressão por resultados rápidos?**
> "Divido em quick wins e transformação. Quick wins geram credibilidade em 30 dias. Isso compra tempo para mudanças estruturais de 60-90 dias. O segredo é mostrar progresso contínuo."

---

## MENSAGENS-CHAVE (MEMORIZE)

1. **"SLA é a causa raiz"** — atacando um, melhoro três

2. **"O problema está concentrado"** — Collections = 44,73% do problema

3. **"Correlação comprovada nos dados"** — não é opinião, é evidência

4. **"46% → 12% em 90 dias"** — redução de 74% nos casos críticos

5. **"Autonomia com alinhamento"** — o time decide com framework, não com dependência

6. **"Meu diferencial é execução"** — não só planejo, trabalho junto com o time
