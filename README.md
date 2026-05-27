# ImportCalc Brasil 🌍

**Simulador profissional de custos de importação para o Brasil**

> Acesse: `https://seu-usuario.github.io/importcalc-brasil`

---

## Funcionalidades

- ✅ **Landed Cost completo** — CIF + II + IPI + PIS + COFINS + AFRMM + ICMS + DUIMP
- ✅ **11 Incoterms® 2020** com campos dinâmicos por incoterm
- ✅ **Autocomplete NCM** via BrasilAPI + Portal Único SISCOMEX (RF)
- ✅ **Cotações automáticas** USD, EUR, GBP, CNY, JPY, ARS (ExchangeRate-API)
- ✅ **Regimes tributários** — Integral, Redução, Suspensão (Drawback), Isenção, Não Incidência
- ✅ **Reforma Tributária EC 132/2023** — simulação CBS + IBS com fases de transição 2026→2033
- ✅ **Frete de Referência** estimado por modal e origem (marítimo/aéreo/rodoviário)
- ✅ **Seguro** por valor fixo ou percentual sobre invoice+frete
- ✅ **Mapa de rota** interativo (Leaflet + OpenStreetMap)
- ✅ **Painel BI** com 8 gráficos (Chart.js)
- ✅ **Exportação PDF** e **Excel** (SheetJS — 3 abas)
- ✅ **Manual de preenchimento** integrado
- ✅ **Todas as moedas do mundo** nos selects de moeda

---

## Abas

| Aba | Descrição |
|---|---|
| ⚙ Operação | Incoterm, modal, origem, câmbio, frete, seguro, mapa de rota |
| 📦 Carga | Itens com NCM autocomplete, regimes tributários, alíquotas |
| 🧾 Despesas | Despesas operacionais por modal com taxa individual |
| 🧮 Custo Detalhado | Resultado completo em tempo real |
| 📄 Custo Final | Relatório profissional para PDF/Excel |
| ⚡ Reforma Trib. | Simulação EC 132/2023 CBS+IBS com comparativo |
| 📊 Gráficos | Painel BI executivo |

---

## Metodologia de Cálculo

| Tributo | Base Legal |
|---|---|
| II — Imposto de Importação | Art. 20 CTN · Dec.-Lei 37/1966 |
| IPI | Art. 47 CTN · Dec. 11.158/2022 |
| PIS-Importação | Lei 10.865/2004 art. 7º I |
| COFINS-Importação | Lei 10.865/2004 art. 7º I |
| AFRMM (modal marítimo) | Lei 10.893/2004 art. 6º — 8% s/ frete |
| ICMS — cálculo por dentro | LC 87/1996 art. 13 §1º II "a" |
| Taxa DUIMP/SISCOMEX | Portaria ME 4.131/2021 |
| Valoração Aduaneira | Decreto 6.759/2009 — Acordo GATT/OMC |
| CBS (Reforma) | EC 132/2023 — substitui PIS+COFINS |
| IBS (Reforma) | EC 132/2023 — substitui ICMS+ISS |

---

## Como Publicar no GitHub Pages

1. Crie um repositório público no GitHub
2. Faça upload de `index.html` e `README.md` na raiz
3. Vá em **Settings → Pages → Source → Deploy from branch → main → / (root)**
4. Aguarde ~1 minuto → acesse `https://seu-usuario.github.io/nome-do-repositorio`

---

## Dependências (CDN — sem instalação)

| Biblioteca | Uso |
|---|---|
| [Chart.js 4.4.1](https://www.chartjs.org/) | Gráficos BI |
| [SheetJS 0.18.5](https://sheetjs.com/) | Exportação Excel |
| [Leaflet.js 1.9.4](https://leafletjs.com/) | Mapa de rota |
| [Tabler Icons 3.7](https://tabler.io/icons) | Ícones |
| [Google Fonts](https://fonts.google.com/) | Tipografia DM Sans/Serif |
| [ExchangeRate-API](https://www.exchangerate-api.com/) | Cotações automáticas |
| [BrasilAPI NCM](https://brasilapi.com.br/) | Autocomplete NCM + alíquotas |
| [Portal Único SISCOMEX](https://portalunico.siscomex.gov.br/) | NCM oficial RF |

Todas gratuitas, sem chave de API, com fallback offline.

---

## Licença

MIT — uso livre para fins comerciais e educacionais.

---

*ImportCalc Brasil · 2025 · Desenvolvido com Claude (Anthropic)*
