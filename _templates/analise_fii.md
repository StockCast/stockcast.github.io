gerar post para publicação no Jekyll utilizando o seguinte template:

---
layout: post
title: "TICKER (TICKR11) — Análise de Resultados Mês/Ano"
date: YYYY-MM-DD
author: João Eduardo F. Bertacchi (para StockCast)
categories: [analise, fii, segmento]
tags: [TICKR11, NomeDoFundo, segmento, resultados, Mês/Ano]
excerpt: "Uma frase sobre o resultado principal: sustentabilidade do provento e momento operacional do fundo."
---

Parágrafo introdutório: o que o resultado do mês revela sobre o fundo? O provento está lastreado? Houve mudança relevante no portfólio ou na carteira? Contexto em 2-3 frases.

> **Fontes:** [Relatório Gerencial, Mês/Ano], [Informe Mensal Estruturado CVM, Mês/Ano] e [Fatos Relevantes, se houver].

## Sumário Executivo

| Indicador | Mês/Ano | Mês Anterior | Var. |
|---|---|---|---|
| Provento por cota | R$ X,XX | R$ Y,YY | **±Z%** |
| Resultado caixa por cota | R$ X,XX | R$ Y,YY | **±Z%** |
| Resultado recorrente por cota | R$ X,XX | R$ Y,YY | **±Z%** |
| Reserva acumulada por cota | R$ X,XX | R$ Y,YY | — |
| Vacância física / Inadimplência¹ | X% | Y% | **±Xpp** |
| Vacância financeira / PDD¹ | X% | Y% | **±Xpp** |
| Valor patrimonial por cota | R$ X,XX | R$ Y,YY | **±Z%** |
| Nº de cotistas | X.XXX | Y.YYY | **±Z%** |
| Patrimônio líquido | R$ X mi | R$ Y mi | **±Z%** |

<!-- ¹ Usar vacância para tijolo; inadimplência/PDD para papel -->

## 1. Resultado do Mês

### Caixa vs. Competência

<!-- Este é o ponto central da análise. O provento está coberto pelo caixa recorrente? -->

| Métrica | R$/cota |
|---|---|
| Resultado — regime de caixa | R$ X,XX |
| Resultado — regime de competência | R$ X,XX |
| Resultado recorrente (caixa, s/ não recorrentes) | R$ X,XX |
| Provento distribuído | R$ X,XX |
| Cobertura (recorrente / provento) | X,XXx |

<!-- Se cobertura < 1,0x → alerta obrigatório -->

> ⚠️ **Atenção:** [Se aplicável: o provento excede o resultado recorrente em R$ X,XX/cota. A diferença foi coberta por [reserva/ganho de capital/venda de ativo]. Saldo de reserva restante: R$ X,XX/cota.]

### Composição da Receita

| Origem | R$ mil | % do Total |
|---|---|---|
| Receita recorrente (aluguel / juros CRI / rendimento cotas) | X.XXX | X% |
| Receita não recorrente (ganho de capital, multas, etc.) | X.XXX | X% |
| Receita financeira do caixa | X.XXX | X% |
| **Total** | **X.XXX** | **100%** |

<!-- Se receita recorrente < 80% do total, explicar o motivo -->

### Despesas e Eficiência

| Despesa | R$ mil | % s/ PL (a.a.) |
|---|---|---|
| Taxa de administração + gestão | X.XXX | X,XX% |
| Despesas extraordinárias | X.XXX | — |
| Custo da dívida (se aplicável) | X.XXX | CDI + X,X% |

> 💬 *"[Citação da gestora sobre resultado ou movimentação relevante]"* — Relatório Gerencial

## 2. Portfólio / Carteira

<!-- Aplicar a seção correspondente ao segmento do fundo. Remover as demais. -->

### [Se Tijolo] Imóveis e Locações

**Vacância:**

| | Mês/Ano | Mês Anterior | Var. |
|---|---|---|---|
| Vacância física | X% | Y% | **±Xpp** |
| Vacância financeira | X% | Y% | **±Xpp** |

<!-- Carências: quando terminam e impacto esperado na receita -->

**Contratos:**

| Métrica | Valor |
|---|---|
| WAULT (prazo médio ponderado) | X anos |
| Receita com vencimento em 12 meses | X% |
| Mix típico / atípico | X% / Y% |
| Indexador predominante | IPCA (X%) / IGP-M (Y%) |
| Maior inquilino (% receita) | Nome — X% |
| Top 5 inquilinos (% receita) | X% |

<!-- Se maior inquilino > 20% da receita → risco de concentração -->

**Ativos:**

<!-- Classe construtiva, localização, estado de conservação, capex/retrofit -->
<!-- Para shoppings: vendas/m², NOI/m², custo de ocupação, same-store sales -->
<!-- Para logística: last mile, especificações técnicas -->

### [Se Papel] Carteira de CRIs

| Métrica | Valor |
|---|---|
| Composição: % IPCA | X% |
| Composição: % CDI | X% |
| Composição: % IGP-M / Pré / Outros | X% |
| Spread médio sobre indexador | IPCA + X,X% / CDI + Y,Y% |
| Duration média | X anos |
| LTV médio ponderado | X% |
| Subordinação predominante | Sênior / Mezanino |

**Qualidade de crédito:**

| Métrica | Valor |
|---|---|
| Inadimplência / PDD | R$ X mi (X% do PL) |
| Eventos de crédito no mês | [Descrever ou "Nenhum"] |
| Concentração: top 10 CRIs (% PL) | X% |
| Perfil | Pulverizado / Corporativo |

**Sensibilidade:**

<!-- Impacto de deflação (há piso?), impacto de variação na Selic -->

> 💡 **Destaque:** [Insight sobre sensibilidade — ex: "X% da carteira é CDI+, o que protege o rendimento em cenário de Selic elevada."]

### [Se FoF] Carteira de Fundos

| Métrica | Valor |
|---|---|
| Desconto/ágio sobre VP agregado | X% |
| Custo total efetivo (FoF + fundos investidos) | X,XX% a.a. |
| Giro da carteira no mês | X% do PL |
| Concentração: top 10 fundos (% PL) | X% |

<!-- Trades relevantes: geraram alfa vs. IFIX? -->

## 3. Alavancagem

<!-- Omitir esta seção inteira se o fundo não possui dívida -->

| Métrica | Mês/Ano | Mês Anterior |
|---|---|---|
| Dívida bruta | R$ X mi | R$ Y mi |
| Caixa | R$ X mi | R$ Y mi |
| Dívida líquida | R$ X mi | R$ Y mi |
| LTV (dív. líquida / ativos) | X% | Y% |
| Custo médio da dívida | CDI + X,X% | — |

<!-- LTV ≤30%: saudável | 30-40%: atenção | >40%: alerta -->
<!-- Vencimentos concentrados em curto prazo? -->

> ⚠️ **Atenção:** [Se LTV > 30%: descrever risco e cronograma de amortização]

## 4. Faixas de Referência

<!-- Valores calculados a partir dos fundamentos — sem cotação de mercado -->

| Referência | Valor | Cálculo |
|---|---|---|
| Provento recorrente mensal | R$ X,XX/cota | [mostrar conta] |
| Provento recorrente anualizado | R$ X,XX/cota | × 12 |
| Preço-teto (DY mín. X% a.a.) | R$ XX,XX | prov. anual / X% |
| Preço-piso (DY máx. Y% a.a.) | R$ XX,XX | prov. anual / Y% |
| Valor patrimonial por cota | R$ XX,XX | fonte: informe mensal |
| Cap rate implícito (tijolo) | X,X% a.a. | NOI anual / valor imóveis |
| Prêmio s/ renda fixa se NTN-B < | X,X% a.a. | DY recorrente − spread |

> 📌 **Leitura:** Com base no provento recorrente de R$ X,XX/cota/mês, a faixa de preço atrativa situa-se entre **R$ [piso]** e **R$ [teto]**, correspondendo a um DY entre X% e Y% a.a. Compras abaixo de R$ [VP] representam desconto patrimonial.

## 5. Sensibilidade Macroeconômica

<!-- Extrair referências macro dos próprios documentos. Não buscar dados externos. -->
<!-- Declarar sensibilidade qualitativa + quantificar se possível -->

Este fundo **se beneficia de** [cenário: Selic alta / inflação alta / etc.] e **é prejudicado por** [cenário oposto].

<!-- Se possível: "Uma variação de 1 p.p. na Selic impacta o resultado em ~R$ X,XX/cota/mês." -->

## 6. Riscos e Pontos de Atenção

| Risco | Severidade | Impacto potencial |
|---|---|---|
| [Risco 1 — o mais grave] | 🔴 Crítico | [consequência se materializar] |
| [Risco 2] | 🟠 Alto | [consequência] |
| [Risco 3] | 🟡 Médio | [consequência] |
| [Risco 4] | 🟢 Baixo | [consequência] |

<!-- Incluir como risco dados relevantes que os documentos omitiram -->

### O que acompanhar no próximo mês

- **[Evento/métrica 1]** — [por que importa]
- **[Evento/métrica 2]** — [por que importa]
- **[Evento/métrica 3]** — [por que importa]

## 7. Conclusão

<!-- Síntese: o provento é sustentável? O fundo está melhorando ou piorando? -->
<!-- Veredito: Positivo / Neutro / Negativo + justificativa em 2-3 frases -->

**Veredito: [Positivo / Neutro / Negativo]**

[Justificativa em 2-3 frases.]

> 💡 **Investidor com tolerância ao risco:** [condições em que a entrada faz sentido, considerando as faixas de referência].

> 📌 **Investidor conservador:** [o que precisa melhorar antes de considerar posição].

---

> *Análise elaborada com base em [fontes]. Não constitui recomendação de investimento.*
