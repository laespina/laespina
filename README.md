<div align="center">

# Alexander Martins La Espina

**Serial founder · AI · Govtech**
**Juiz de Fora, MG 🇧🇷 · multilingual 🇧🇷 🇺🇸 🇳🇱**

Building [**Licinexus**](https://licinexus.com.br) — proprietary AI for Brazilian public procurement.
Founder of [**LLMwiz**](https://licinexus.com.br) and [**TuriVerde**](https://www.linkedin.com/in/laespina/).
Previously sold [**Licitei**](https://foundersclub.com.br/cases/licitei-e-founders-club/) for **R$ 6,25M**, 5 months after MVP.

<br/>

<a href="https://licinexus.com.br"><img alt="Website" src="https://img.shields.io/badge/licinexus.com.br-050816?style=for-the-badge&logo=googlechrome&logoColor=00d4ff" /></a>
<a href="https://linkedin.com/in/laespina"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://x.com/licinexus"><img alt="X" src="https://img.shields.io/badge/@licinexus-000000?style=for-the-badge&logo=x&logoColor=white" /></a>
<a href="https://www.youtube.com/watch?v=2sU-egdmaAk"><img alt="YouTube" src="https://img.shields.io/badge/YouTube-ff0000?style=for-the-badge&logo=youtube&logoColor=white" /></a>
<a href="mailto:alex@licinexus.com.br"><img alt="Email" src="https://img.shields.io/badge/alex@licinexus.com.br-ea4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>

</div>

---

### 👋 About

I build proprietary AI for a market most engineers ignore: **R$ 1,5 trillion/year in Brazilian public procurement**. Public data lives shattered across 1,000+ federal, state and municipal APIs — each with its own schema, uptime and way to break. My work is the layer that turns this mess into decisions.

**Now**
- 🏗 Founder & CEO of [**Licinexus**](https://licinexus.com.br) — building 7 proprietary AI models (Catálogo, Previsor, Auditor, Leitor, Reader-Full, OCR, STT) on top of open public data, with a free permanent tier. Open-sourcing what's commodity, keeping intelligence proprietary.
- 🧪 Founder of [**LLMwiz**](https://licinexus.com.br) — applied LLM tooling lab.

**Then**
- 💼 Founder of [**Licitei**](https://foundersclub.com.br/cases/licitei-e-founders-club/) — exit at **R$ 6,25M** only 5 months post-MVP, with 2k users and R$ 15k MRR. Pre-exit raised **R$ 3,5M** led by Thompson Participações. Backed by **Microsoft for Startups Founders Hub** and **TecHolding**. Incubated at [**Critt UFJF**](https://www2.ufjf.br/critt/) (Incubadora de Base Tecnológica).
- 🌱 Founder of [**TuriVerde**](https://www.linkedin.com/in/laespina/) — sustainable tourism platform unifying the travel chain (travelers, agencies, accommodations, transport). Also incubated at [**Critt UFJF**](https://www2.ufjf.br/critt/) (second incubation, after Licitei) and selected for [**Adapta Summit 2025**](https://mg.agenciasebrae.com.br/inovacao-e-tecnologia/startups-juiz-foranas-marcam-presenca-no-adapta-summit-2025/) (Sebrae Minas × Critt).

**Recognition**
- 🏆 **TOP 10 Startup Awards 2024**
- 🏆 **TOP 1000 Sebrae Startup Awards 2024**
- 🗺️ Featured on **[Mapa GovTech 2024](https://www2.ufjf.br/critt/2024/03/26/startup-juizforana-tem-tecnologia-destacada-no-mapa-govtech-2024-elaborado-pelo-brazillab-em-parceria-com-a-oracle/)** by BrazilLAB × Oracle
- 💼 **[Founders Club](https://foundersclub.com.br/cases/licitei-e-founders-club/)** portfolio
- 🌎 **[Startup Summit 2023](https://www2.ufjf.br/critt/2023/07/18/conheca-os-representantes-de-juiz-de-fora-no-startup-summit-2023/)** Juiz de Fora representative

---

### 🤖 The Licinexus AI family

Free open data + proprietary intelligence on top. The 7 models I'm shipping:

| Model | What it does | Status |
|---|---|---|
| **Catálogo** | Understands CATMAT/CATSER better than any generic LLM — bi-encoder + cross-encoder fine-tuned on 848k pairs | 🟢 PROD |
| **Previsor** | Predicts winning price + win-probability per bid (LightGBM, quantile regression on 1.48M outcomes) | 🟢 PROD |
| **OCR** | Tesseract pipeline at US$ 60 vs US$ 48k of Textract for 32M pages | 🟢 PROD |
| **Leitor** | LLM that turns any bid PDF into structured JSON (60+ fields) — Qwen2.5 fine-tune | 🟡 BUILD |
| **Reader-Full** | Full edital PDF → complete analysis (after OCR) | 🟡 BUILD |
| **Auditor** | Detects directional clauses, restrictive requirements, TCU jurisprudence risk | 🟡 BUILD |
| **STT** | Whisper-Large-V3 internal pipeline replacing paid third-party transcription | 🟡 BUILD |

Full family → [**licinexus.com.br/ai**](https://licinexus.com.br/ai) · Org on GitHub → [**Licinexus**](https://github.com/Licinexus)

---

### 🔥 Open source

🇧🇷 **[Licinexus/licinexus-mcp](https://github.com/Licinexus/licinexus-mcp)** — first Brazilian Model Context Protocol server for public procurement. Connects Claude Desktop, Cursor, Cline and any MCP client to PNCP, BrasilAPI, Receita Federal and IBGE in one line:

```bash
npx -y @licinexusbr/mcp
```

[![npm](https://img.shields.io/npm/v/@licinexusbr/mcp?style=flat-square&logo=npm&color=cb3837&label=npm)](https://www.npmjs.com/package/@licinexusbr/mcp)
[![Downloads](https://img.shields.io/npm/dw/@licinexusbr/mcp?style=flat-square&logo=npm&color=10b981&label=downloads%2Fweek)](https://www.npmjs.com/package/@licinexusbr/mcp)
[![Stars](https://img.shields.io/github/stars/Licinexus/licinexus-mcp?style=flat-square&logo=github&color=2968ed&label=stars)](https://github.com/Licinexus/licinexus-mcp/stargazers)
[![Forks](https://img.shields.io/github/forks/Licinexus/licinexus-mcp?style=flat-square&logo=github&color=2968ed&label=forks)](https://github.com/Licinexus/licinexus-mcp/network/members)
[![MIT](https://img.shields.io/github/license/Licinexus/licinexus-mcp?style=flat-square&color=000000&label=license)](https://github.com/Licinexus/licinexus-mcp/blob/main/LICENSE)

**18 tools · 4 prompts · MIT.** Live in the [Official MCP Registry](https://registry.modelcontextprotocol.io). Shipped 11 May 2026.

---

### 🛠 Stack

<p>
<img alt="TypeScript" src="https://img.shields.io/badge/-TypeScript-3178c6?style=flat-square&logo=typescript&logoColor=white" />
<img alt="Node.js" src="https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white" />
<img alt="Python" src="https://img.shields.io/badge/-Python-3776ab?style=flat-square&logo=python&logoColor=white" />
<img alt="PyTorch" src="https://img.shields.io/badge/-PyTorch-ee4c2c?style=flat-square&logo=pytorch&logoColor=white" />
<img alt="Hugging Face" src="https://img.shields.io/badge/-Hugging%20Face-fbbf24?style=flat-square&logo=huggingface&logoColor=black" />
<img alt="LightGBM" src="https://img.shields.io/badge/-LightGBM-9caf88?style=flat-square" />
<img alt="React" src="https://img.shields.io/badge/-React-61dafb?style=flat-square&logo=react&logoColor=black" />
<img alt="React Native" src="https://img.shields.io/badge/-React%20Native-61dafb?style=flat-square&logo=react&logoColor=black" />
<img alt="PostgreSQL" src="https://img.shields.io/badge/-PostgreSQL-4169e1?style=flat-square&logo=postgresql&logoColor=white" />
<img alt="pgvector" src="https://img.shields.io/badge/-pgvector-336791?style=flat-square&logo=postgresql&logoColor=white" />
<img alt="AWS" src="https://img.shields.io/badge/-AWS-232f3e?style=flat-square&logo=amazonwebservices&logoColor=ff9900" />
<img alt="SageMaker" src="https://img.shields.io/badge/-SageMaker-ff9900?style=flat-square&logo=amazonaws&logoColor=white" />
<img alt="Anthropic" src="https://img.shields.io/badge/-Anthropic-d97757?style=flat-square&logo=anthropic&logoColor=white" />
<img alt="MCP" src="https://img.shields.io/badge/-MCP-000000?style=flat-square&logo=anthropic&logoColor=white" />
<img alt="Remotion" src="https://img.shields.io/badge/-Remotion-000000?style=flat-square" />
</p>

---

### 📰 In the press

- 📺 **[MGTV / Rede Globo](https://globoplay.globo.com/v/12019826/)** — open broadcast TV interview (1)
- 📺 **[MGTV / Rede Globo](https://globoplay.globo.com/v/12488467/)** — open broadcast TV interview (2)
- 📰 **[Founders Club](https://foundersclub.com.br/cases/licitei-e-founders-club/)** — *"Licitei faz exit 5 meses após MVP com apoio do Founders Club"*
- 📰 **[Startupi](https://startupi.com.br/licitei-recebe-aporte-de-r35-milhoes/)** — *"Licitei, que simplifica licitações para PMEs, recebe aporte de R$ 3,5 milhões"*
- 📰 **[UFJF — Notícias](https://www2.ufjf.br/noticias/2024/02/19/startup-lanca-sistema-gratuito-com-ia-para-agilizar-licitacoes-publicas/)** — *"Startup lança sistema gratuito com IA para agilizar licitações públicas"*
- 📰 **[Critt UFJF](https://www2.ufjf.br/critt/2024/02/22/startup-juizforana-lanca-novo-sistema-gratuito-com-inteligencia-artificial-para-agilizar-licitacoes-publicas/)** — *"Startup juizforana lança novo sistema gratuito com IA para agilizar licitações públicas"*
- 📰 **[Critt UFJF](https://www2.ufjf.br/critt/2024/03/26/startup-juizforana-tem-tecnologia-destacada-no-mapa-govtech-2024-elaborado-pelo-brazillab-em-parceria-com-a-oracle/)** — *"Tecnologia destacada no Mapa GovTech 2024 (BrazilLAB × Oracle)"*
- 📰 **[UFJF — Notícias](https://www2.ufjf.br/noticias/2024/03/25/startup-incubada-no-critt-e-destaque-em-estudo-nacional/)** — *"Startup incubada no Critt é destaque em estudo nacional"*
- 📰 **[Acessa.com](https://www.acessa.com/economia/2023/08/167376-juiz-de-fora-e-representada-por-tres-empresas-de-solucoes-tecnologicas-na-startup-summit-2023.html)** — *"Juiz de Fora é representada por três empresas de soluções tecnológicas na Startup Summit 2023"*
- 📰 **[Critt UFJF](https://www2.ufjf.br/critt/2025/11/11/critt-e-sebrae-minas-organizam-rodada-de-negocios-com-empresas-de-juiz-de-fora/)** — *"Critt e Sebrae Minas organizam Rodada de Negócios com empresas de Juiz de Fora"* (TuriVerde)
- 📰 **[ASN Sebrae Minas](https://mg.agenciasebrae.com.br/inovacao-e-tecnologia/startups-juiz-foranas-marcam-presenca-no-adapta-summit-2025/)** — *"Startups juiz-foranas marcam presença no Adapta Summit 2025"* (TuriVerde)
- 📰 **[Zero40](https://zero40.com.br/startups/licitei/)** — Comunidade de Empreendedorismo Inovador
- 🎙️ **[VoxLab Podcast](https://www.youtube.com/watch?v=HnGbFidWO4g)** — interview
- 🎙️ **[Além do Mais Podcast](https://www.youtube.com/watch?v=22FVWz5ui3I)** — interview
- 📰 Diário do Comércio · Economia SC · Critt UFJF Startup Summit 2023

---

### 💭 Philosophy

> **Open source what's commodity. Keep the intelligence where the moat lives.**
>
> Public data should be accessible to everyone — not just engineers with API tokens. Three years of fine-tuned models, gold datasets and an integrated platform is where the unfair advantage compounds. We give away what any competitor could rebuild in 3 months, to stay focused on what takes 3 years.

Joel Spolsky called it *commoditizing your complement*. Worked for IBM with Linux, for Google with Android. Betting it works for us too.

---

### 📬 Let's talk

If you cover govtech, work in public-sector technology, do data journalism, are an investor in B2B AI for emerging markets, or want to build with AI applied to real Brazilian problems — reach out.

**[alex@licinexus.com.br](mailto:alex@licinexus.com.br)** · [licinexus.com.br](https://licinexus.com.br) · [LinkedIn](https://linkedin.com/in/laespina) · [@licinexus](https://x.com/licinexus)

<sub>📍 Juiz de Fora, MG · 🌍 Multilingual: PT 🇧🇷 · EN 🇺🇸 · NL 🇳🇱 (moved to the Netherlands at age 12, lived there into adulthood)</sub>
