# Digital Health Strategies in Pain Management

> **🇵🇹 Apresentação · 8 de maio de 2026 · FMUP / MEDCIDS**
> **🇬🇧 Lecture · 8 May 2026 · FMUP / MEDCIDS**

🔗 **[Ver apresentação · View slides →](https://marianacpais.github.io/medcids-digital-health-and-ai-pain/)**

---

## 🇵🇹 Português

Sessão de **três horas** preparada para a unidade curricular **["Digital Health Strategies in Pain Management"](https://sigarra.up.pt/fmup/pt/cur_geral.cur_view?pv_curso_id=1129)**, leccionada na Faculdade de Medicina da Universidade do Porto (FMUP), no âmbito do MEDCIDS — Departamento de Medicina da Comunidade, Informação e Decisão em Saúde.

A sessão percorre, do concreto da prática clínica para o panorama regulatório:

- **Bloco I — Fundamentos de dados em medicina da dor.** Que dados capturamos sobre doentes com dor, estrutura do registo electrónico, *Patient-Reported Outcomes*, wearables e biomarcadores digitais, fontes de dados para além da clínica.
- **Bloco I.5 — Padronização e interoperabilidade.** O problema da fragmentação, a necessidade de standards (HL7 FHIR, SNOMED CT, ICD, openEHR, OHDSI/OMOP), qualidade dos dados, geração de evidência, OMOP CDM em detalhe, EHDS (European Health Data Space), princípios FAIR, análise federada, governance.
- **Bloco II — De dados a evidência em investigação na dor.** RWD vs RWE, RCTs vs estudos observacionais, fenotipagem, definição de coortes, *small data* vs *big data*, desafios da RWE, STaRT-RWE.
- **Bloco III A — IA, fundamentos.** O que é IA, contexto histórico, AI ⊃ ML ⊃ DL ⊃ LLMs, paradigmas de aprendizagem, redes neuronais, anatomia de um LLM, multimodalidade, escala dos modelos, IA generativa, limites (escopo, viés, caixa preta).
- **Bloco III B — IA na prática.** *Reality check* sobre dispositivos médicos com IA aprovados pela FDA (1 357 ao todo, dos quais 23 em "anestesiologia"), AI Act, três reflexões sobre o papel do clínico, considerações éticas.

A apresentação está construída em **Reveal.js** com a especificação visual **[FMUP](https://github.com/marianacpais/mcp-personal-headquarters/tree/main/claude/design-md/fmup)** (amarelo `#FED517`, preto, *Inter*).

### Pré-visualização local

```sh
python3 -m http.server 8765
# abrir http://localhost:8765/
```

### Estrutura do repositório

| Caminho | Descrição |
|---|---|
| `index.html` | Reveal.js, deck completo (130 secções) |
| `assets/styles.css` | Tema FMUP |
| `assets/*.png` `*.jpg` | Imagens, logos, screenshots |
| `assets/mariana-photo.png` | Retrato (slide *Who am I?*) |

---

## 🇬🇧 English

**Three-hour session** prepared for the course **["Digital Health Strategies in Pain Management"](https://sigarra.up.pt/fmup/pt/cur_geral.cur_view?pv_curso_id=1129)**, taught at the Faculty of Medicine of the University of Porto (FMUP), within MEDCIDS — Department of Community Medicine, Information and Health Decision Sciences.

The session moves from concrete clinical practice to the regulatory landscape:

- **Block I — Data foundations in pain medicine.** What data we capture on pain patients, EHR structure, Patient-Reported Outcomes, wearables and digital biomarkers, data sources beyond the clinic.
- **Block I.5 — Standardisation & interoperability.** Fragmentation, the need for standards (HL7 FHIR, SNOMED CT, ICD, openEHR, OHDSI/OMOP), data quality, evidence generation, OMOP CDM in depth, EHDS (European Health Data Space), FAIR principles, federated analysis, governance.
- **Block II — From data to evidence in pain research.** RWD vs RWE, RCTs vs observational studies, phenotyping, cohort definition, small vs big data, RWE challenges, STaRT-RWE.
- **Block III A — AI fundamentals.** What is AI, historical context, AI ⊃ ML ⊃ DL ⊃ LLMs, learning paradigms, neural networks, anatomy of an LLM, multimodality, model scaling, generative AI, limits (scope, bias, black box).
- **Block III B — AI in practice.** Reality check on FDA-approved AI medical devices (1,357 in total, of which 23 in "anesthesiology"), AI Act, three reflections on the clinician's role, ethical considerations.

Built in **Reveal.js** using the **[FMUP visual spec](https://github.com/marianacpais/mcp-personal-headquarters/tree/main/claude/design-md/fmup)** (yellow `#FED517`, black, *Inter*).

### Local preview

```sh
python3 -m http.server 8765
# open http://localhost:8765/
```

---

## License & attribution

Slides © Mariana Canelas Pais, 2026. Embedded screenshots, charts and figures retain their original sources — credited in-slide where applicable.

The visual identity (FMUP design system) is defined in the parent repository [`mcp-personal-headquarters`](https://github.com/marianacpais/mcp-personal-headquarters).
