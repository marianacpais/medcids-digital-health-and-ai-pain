# Digital Health Strategies in Pain Management

> **🇵🇹 Sessão de 3 horas · 8 de maio de 2026 · FMUP**
> **🇬🇧 3-hour session · 8 May 2026 · FMUP**

🔗 **[Página de selecção · Landing page →](https://marianacpais.github.io/fmup-digital-health-and-ai-in-pain-medicine/)** — escolher entre as duas versões disponíveis.

---

## 🇵🇹 Português

Slides de uma sessão de **3 horas** lecionada no âmbito da **[Pós-Graduação em Medicina da Dor](https://sigarra.up.pt/fmup/pt/cur_geral.cur_view?pv_curso_id=1129)** (PGMDOR) da Faculdade de Medicina da Universidade do Porto.

### Duas versões da apresentação

Este repositório guarda **dois recortes** distintos da mesma sessão:

| Versão | Acesso | O que tem |
|---|---|---|
| **Versão completa** | [`full.html`](https://marianacpais.github.io/fmup-digital-health-and-ai-in-pain-medicine/full.html) — 130 secções | Os 3 blocos como foram desenhados: fundamentos de dados, RWD/RWE, e IA. |
| **Versão apresentada** | [`abridged.html`](https://marianacpais.github.io/fmup-digital-health-and-ai-in-pain-medicine/abridged.html) — 111 secções · também em [`abridged.pdf`](abridged.pdf) | O recorte efectivamente apresentado no dia. Por restrições de tempo, a parte sobre **RWD/RWE foi omitida**; ficaram **2 blocos** (fundamentos de dados + IA), re-numerados como **Bloco I** e **Bloco II** dentro do próprio deck. |

Ambas as versões partilham os mesmos `assets/` (CSS, imagens, logos) e a página `index.html` é um seletor visual entre as duas.

### Conteúdo — versão completa (3 blocos)

A sessão integral percorre, do concreto da prática clínica para o panorama regulatório:

- **Bloco I — Fundamentos de dados em medicina da dor.** Que dados capturamos sobre doentes com dor, estrutura do registo eletrónico, *Patient-Reported Outcomes*, wearables e biomarcadores digitais, fontes de dados para além da clínica.
- **Bloco I.5 — Padronização e interoperabilidade.** O problema da fragmentação, a necessidade de standards (HL7 FHIR, SNOMED CT, ICD, openEHR, OHDSI/OMOP), qualidade dos dados, geração de evidência, OMOP CDM em detalhe, EHDS (European Health Data Space), princípios FAIR, análise federada, governance.
- **Bloco II — De dados a evidência em investigação na dor.** RWD vs RWE, RCTs vs estudos observacionais, fenotipagem, definição de coortes, *small data* vs *big data*, desafios da RWE, STaRT-RWE. *— omitido na versão apresentada.*
- **Bloco III A — IA, fundamentos.** O que é IA, contexto histórico, AI ⊃ ML ⊃ DL ⊃ LLMs, paradigmas de aprendizagem, redes neuronais, anatomia de um LLM, multimodalidade, escala dos modelos, IA generativa, limites (escopo, viés, caixa preta).
- **Bloco III B — IA na prática.** *Reality check* sobre dispositivos médicos com IA aprovados pela FDA (1 357 ao todo, dos quais 23 em "anestesiologia"), AI Act, três reflexões sobre o papel do clínico, considerações éticas.

A apresentação está construída em **Reveal.js** com a especificação visual **FMUP** (amarelo `#FED517`, preto, *Inter*) — definida em [`didactica/designs/fmup/`](https://github.com/marianacpais/didactica/tree/main/designs/fmup) 🔒 *repo privado*.

### Pré-visualização local

```sh
python3 -m http.server 8765
# abrir http://localhost:8765/
```

### Estrutura do repositório

| Caminho | Descrição |
|---|---|
| `index.html` | **Página de selecção** — cartões para escolher entre versão completa e versão apresentada |
| `full.html` | Reveal.js, **deck completo** (130 secções: Blocos I + II + III) |
| `abridged.html` | Reveal.js, **versão apresentada** (111 secções, 2 blocos — re-numerados como I + II dentro do deck) |
| `abridged.pdf` | Export PDF da versão apresentada (1 página por slide) |
| `assets/styles.css` | Tema FMUP — partilhado por ambas as versões dos slides |
| `assets/*.png` `*.jpg` | Imagens, logos, screenshots |
| `assets/mariana-photo.png` | Retrato (slide *Who am I?*) |
| `.github/workflows/deploy-pages.yml` | Deploy automático para GitHub Pages a cada push em `main` |

---

## 🇬🇧 English

Slides for a **3-hour session** delivered as part of the **[Postgraduate Programme in Pain Medicine](https://sigarra.up.pt/fmup/pt/cur_geral.cur_view?pv_curso_id=1129)** (PGMDOR) at the Faculty of Medicine of the University of Porto (FMUP).

### Two versions of the deck

This repo keeps **two cuts** of the same session, plus a landing page to choose between them:

| Version | Where | What it contains |
|---|---|---|
| **Full version** | [`full.html`](https://marianacpais.github.io/fmup-digital-health-and-ai-in-pain-medicine/full.html) — 130 sections | All 3 blocks as designed: data foundations, RWD/RWE, AI. |
| **Delivered version** | [`abridged.html`](https://marianacpais.github.io/fmup-digital-health-and-ai-in-pain-medicine/abridged.html) — 111 sections · PDF at [`abridged.pdf`](abridged.pdf) | The cut actually delivered on the day. The **RWD/RWE block was dropped** for time; what remained is **2 blocks** (data foundations + AI), re-numbered internally as **Block I** and **Block II**. |

Both versions share the same `assets/`, and `index.html` is a visual chooser between them.

### Full session content (3 blocks)

The session moves from concrete clinical practice to the regulatory landscape:

- **Block I — Data foundations in pain medicine.** What data we capture on pain patients, EHR structure, Patient-Reported Outcomes, wearables and digital biomarkers, data sources beyond the clinic.
- **Block I.5 — Standardisation & interoperability.** Fragmentation, the need for standards (HL7 FHIR, SNOMED CT, ICD, openEHR, OHDSI/OMOP), data quality, evidence generation, OMOP CDM in depth, EHDS (European Health Data Space), FAIR principles, federated analysis, governance.
- **Block II — From data to evidence in pain research.** RWD vs RWE, RCTs vs observational studies, phenotyping, cohort definition, small vs big data, RWE challenges, STaRT-RWE. *— dropped in the delivered version.*
- **Block III A — AI fundamentals.** What is AI, historical context, AI ⊃ ML ⊃ DL ⊃ LLMs, learning paradigms, neural networks, anatomy of an LLM, multimodality, model scaling, generative AI, limits (scope, bias, black box).
- **Block III B — AI in practice.** Reality check on FDA-approved AI medical devices (1,357 in total, of which 23 in "anesthesiology"), AI Act, three reflections on the clinician's role, ethical considerations.

Built in **Reveal.js** using the **FMUP visual spec** (yellow `#FED517`, black, *Inter*) — defined in [`didactica/designs/fmup/`](https://github.com/marianacpais/didactica/tree/main/designs/fmup) 🔒 *private repo*.

### Local preview

```sh
python3 -m http.server 8765
# open http://localhost:8765/
```

---

## License & attribution

Slides © Mariana Canelas Pais, 2026. Embedded screenshots, charts and figures retain their original sources — credited in-slide where applicable.

The visual identity (FMUP design system) is defined in the parent repository [`mcp-personal-headquarters`](https://github.com/marianacpais/mcp-personal-headquarters) 🔒 *private repo — internal source of truth*.
