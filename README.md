<!-- ╔══════════════════════════════════════════════════════════════╗
     ║              DIEGO LIAL — GITHUB PROFILE README             ║
     ╚══════════════════════════════════════════════════════════════╝ -->

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:00d9ff,100:0d1117&height=180&section=header&text=Diego%20Lial&fontSize=42&fontColor=ffffff&fontAlignY=35&desc=Full%20Stack%20Developer%20%E2%80%A2%20Automa%C3%A7%C3%A3o%20%E2%80%A2%20Seguran%C3%A7a%20P%C3%BAblica%20%E2%80%A2%20Cripto&descSize=16&descColor=00d9ff&descAlignY=55&animation=fadeIn" />

<!-- ═══════════════ AI INTELLIGENCE ANALYST ═══════════════ -->
<div align="center">
  <img src="./assets/ai-analyst.svg" alt="AI Intelligence Analyst System" width="100%"/>
</div>

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=800&color=00D9FF&center=true&vCenter=true&multiline=true&repeat=true&width=700&height=80&lines=%24+whoami;Diego+Lial+%E2%80%94+building+systems+that+matter+%F0%9F%9B%A1%EF%B8%8F" alt="Terminal Typing" />
</div>

<p align="center">
  <a href="https://github.com/DiegoLial?tab=followers">
    <img src="https://img.shields.io/github/followers/DiegoLial?label=Seguidores&style=for-the-badge&color=00D9FF&labelColor=0d1117" />
  </a>&nbsp;
  <a href="https://github.com/DiegoLial?tab=repositories">
    <img src="https://img.shields.io/badge/Repos-Explorar-00D9FF?style=for-the-badge&labelColor=0d1117&logo=github" />
  </a>&nbsp;
  <a href="https://t.me/DiegoLial">
    <img src="https://img.shields.io/badge/Telegram-DiegoLial-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white&labelColor=0d1117" />
  </a>&nbsp;
  <img src="https://komarev.com/ghpvc/?username=DiegoLial&style=for-the-badge&color=00d9ff&label=Views&labelColor=0d1117" />
</p>

<!-- ═══════════════ NAVEGAÇÃO ═══════════════ -->

<p align="center">
  <a href="#-sobre-mim">Sobre</a> · 
  <a href="#%EF%B8%8F-segurança-pública--govtech">Segurança Pública</a> · 
  <a href="#-o-que-eu-construo">O que construo</a> · 
  <a href="#-projetos-públicos">Projetos</a> · 
  <a href="#-case-studies-privados">Cases privados</a> · 
  <a href="#-stack-tecnológica">Stack</a> · 
  <a href="#-métricas-github">Métricas</a> · 
  <a href="#-contato">Contato</a>
</p>

---

## 🧑‍💻 Sobre mim

```python
class DiegoLial:
    role       = "Full Stack Developer"
    location   = "Manaus, AM 🇧🇷"
    languages  = ["pt-BR", "en"]
    
    focus = [
        "Sistemas completos (front → back → deploy → observabilidade)",
        "Segurança Pública: inteligência, auditoria, gestão operacional",
        "Automação: bots, pipelines, integrações, webhooks",
        "Cripto: análise técnica, alertas e monitoramento via API",
    ]
    
    currently = "Construindo produtos que rodam em produção e resolvem problemas reais."
```

---

## 🛡️ Segurança Pública · GovTech

<table>
<tr>
<td width="80" align="center">🏛️</td>
<td>

Desenvolvo e mantenho **sistemas de missão crítica** para órgãos de segurança pública, com foco em:

</td>
</tr>
</table>

<div align="center">

| Domínio | O que entrego |
|:---:|:---|
| 🔐 **Controle de Acesso** | RBAC multi-nível, RLS por tabela, segregação de dados, aprovação de usuários |
| 🧾 **Auditoria & Compliance** | Logs imutáveis, trilhas de auditoria, rastreabilidade de ações (quem/quando/o quê) |
| 📊 **Dashboards Operacionais** | KPIs em tempo real, métricas de produtividade, rankings e gamificação |
| 🗺️ **Geointeligência** | Mapas interativos, geocodificação, clusters, territórios e organogramas |
| 📄 **Relatórios & Documentos** | Geração automatizada de PDF/TXT, ofícios com numeração, exportação padronizada |
| 🔗 **Integrações Institucionais** | APIs externas (BACEN, ViaCEP, Nominatim), consultas financeiras, processamento de filas |
| ⚙️ **Módulos de Gestão** | Investigação, cartório, produtividade, operações, inquéritos, apreensões |

</div>

> **⚠️ Repositórios e detalhes técnicos são privados** por motivos de segurança e confidencialidade institucional.  
> Abaixo estão descrições de alto nível sem exposição de dados sensíveis.

<details>
<summary><b>📌 Sistema de Gestão Policial — 4 módulos integrados</b></summary>
<br/>

- **Cartório**: dashboards estatísticos, entrada de dados, relatórios com comparativo anual
- **Investigação**: operações, investigados, diligências, inquéritos, apreensões, presos, mapa com Mapbox, organograma de facções
- **Produtividade**: metas, tarefas (kanban), pontuação/gamificação com triggers automáticos
- **Ofícios**: geração com numeração automática por setor, banco de 400+ contatos
- **Segurança**: RLS em 42 tabelas, 5 roles, aprovação de usuários, edge functions
- Stack: `React` · `Vite` · `TypeScript` · `Supabase` · `Mapbox` · `PWA`

</details>

<details>
<summary><b>📌 Sistema de Inteligência — NestJS enterprise-grade</b></summary>
<br/>

- Gestão de investigados, facções, relacionamentos complexos e vínculos criminais
- Análise de redes (grafos com D3.js/React Flow), mapas com Leaflet/PostGIS
- RBAC 4 níveis (Admin → Delegado → Supervisor → Operador), WebSockets, auditoria imutável
- Monitoramento com Prometheus + Grafana, backup criptografado
- Stack: `React` · `NestJS` · `Prisma` · `PostgreSQL/PostGIS` · `Redis` · `Docker`

</details>

<details>
<summary><b>📌 Consultas Financeiras e Relatórios (BACEN)</b></summary>
<br/>

- Consultas PIX e CCS integradas ao Banco Central via API
- Gestão de operações investigativas com alvos e vinculações
- Auditoria completa (IP, user-agent, CPF consultado, busca reversa)
- Dashboard com métricas globais (admin) ou individuais por perfil
- Stack: `Next.js` · `Prisma` · `PostgreSQL` · `Docker` · `JWT/HttpOnly`

</details>

<details>
<summary><b>📌 Análise Telemática — Interceptação e Inteligência</b></summary>
<br/>

- Processamento de dados de interceptação WhatsApp (mensagens + chamadas + grupos)
- Lógica de análise baseada em Qlik Sense (sentido, interlocutores, estatísticas)
- WHOIS/geolocalização com múltiplas fontes, cache inteligente, mapa interativo
- Stack: `Python` · `Flask` · `SQLite` · `APIs (WHOIS/Nominatim)`

</details>

---

## 🔧 O que eu construo

<div align="center">

```
┌─────────────────────────────────────────────────────────────────────┐
│                                                                     │
│   FRONT-END          BACK-END            INFRA & OPS               │
│   ─────────          ────────            ──────────                 │
│   React / Next.js    Node.js / NestJS    Docker / Compose          │
│   TypeScript         Supabase (Auth/DB)  Ansible / Tailscale       │
│   Vite / Tailwind    Prisma / Postgres   CI/CD (Actions)           │
│   PWA / Offline      Edge Functions      Prometheus / Grafana      │
│   shadcn/ui          Stripe / Webhooks   Backup / Recovery         │
│   Mapbox / Leaflet   JWT / RLS / RBAC    Nginx / SSL               │
│                                                                     │
│   AUTOMAÇÃO          DADOS & IA          CRIPTO                    │
│   ─────────          ─────────           ──────                    │
│   Telegram Bots      PostgreSQL/PostGIS  Binance API               │
│   WhatsApp (WAHA)    Redis / Queues      CoinMarketCap API         │
│   Webhooks / Cron    Gemini AI           TradingView               │
│   Pipelines          MediaPipe Vision    Análise Técnica (TA)      │
│                      PDF / Relatórios    Indicadores (RSI/MACD/…)  │
│                                                                     │
└─────────────────────────────────────────────────────────────────────┘
```

</div>

---

## 🚀 Projetos públicos

<div align="center">
<table>
<tr>
<td align="center" width="50%">

### ⭐ Crypto Telegram BOT
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=DiegoLial&repo=Crypto-Telegram-BOT&theme=tokyonight&hide_border=true&bg_color=0d1117)](https://github.com/DiegoLial/Crypto-Telegram-BOT)

**35+ Stars · 14+ Forks**  
Bot completo de análise técnica de cripto  
`Python` · `Telegram Bot API` · `SQLite`

</td>
<td align="center" width="50%">

### 💹 Crypto Trading App
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=DiegoLial&repo=crypto&theme=tokyonight&hide_border=true&bg_color=0d1117)](https://github.com/DiegoLial/crypto)

Automação de operações de trading  
`TypeScript` · `Node.js`

</td>
</tr>
<tr>
<td align="center" width="50%">

### 🤖 Clawdbot Ansible
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=DiegoLial&repo=clawdbot-ansible&theme=tokyonight&hide_border=true&bg_color=0d1117)](https://github.com/DiegoLial/clawdbot-ansible)

Deploy automatizado e hardened  
`Shell` · `Ansible` · `Tailscale` · `Docker`

</td>
<td align="center" width="50%">

### 🔍 WhatsAnalyze
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=DiegoLial&repo=whatsanalyze&theme=tokyonight&hide_border=true&bg_color=0d1117)](https://github.com/DiegoLial/whatsanalyze)

Análise de chat WhatsApp no browser  
100% local · `Vue.js`

</td>
</tr>
</table>
</div>

<details>
<summary><b>📦 Mais repos públicos</b></summary>
<br/>

| Repo | Descrição | Tech |
|------|-----------|------|
| [molthub](https://github.com/DiegoLial/molthub) | Skill Directory for moltbot | TypeScript |
| [TelegramBotBR](https://github.com/DiegoLial/TelegramBotBR) | Bot Telegram + PIX via Mercado Pago | Python |
| [botPixTelegramMercadoPago](https://github.com/DiegoLial/botPixTelegramMercadoPago) | Bot PIX com servidor Flask | Python |
| [bolt.diy](https://github.com/DiegoLial/bolt.diy) | Deploy full-stack apps com qualquer LLM | TypeScript |
| [gameplay](https://github.com/DiegoLial/gameplay) | App React Native (NLW #06) | TypeScript |

</details>

---

## 🔒 Case studies (privados)

> Projetos privados com resumo técnico — sem exposição de código ou dados sensíveis.

<details>
<summary><b>🏋️ SaaS para Personal Trainers — PWA completo (v1.6)</b></summary>
<br/>

- **47 páginas**, ~120 componentes, 50 hooks, 32 edge functions
- CRM (leads/deals com links rastreáveis), chat realtime, agenda Google Calendar/Meet
- Simetrógrafo com IA (MediaPipe Pose: 33 landmarks, quality gate, radar chart)
- Marketplace de coaches, SEO (JSON-LD, sitemap dinâmico), landing pages drag-and-drop
- Billing com Stripe, planos/assinaturas, notificações push, PWA offline com IndexedDB
- Stack: `React` · `Vite` · `Supabase` · `Stripe` · `MediaPipe` · `Gemini AI`

</details>

<details>
<summary><b>🎰 Gerador inteligente de jogos (Mega da Virada)</b></summary>
<br/>

- 5 estratégias de geração anti-padrão usando Google Gemini AI
- Análise estatística de 2.954 sorteios históricos em tempo real
- Autenticação (Email OTP, Google, Apple), pagamento Stripe, export PDF
- Stack: `React 19` · `Vite 6` · `Supabase` · `Stripe` · `Gemini`

</details>

<details>
<summary><b>🤖 Monitoramento WhatsApp (Evolution API)</b></summary>
<br/>

- Monitoramento automatizado de status, foto e nome de exibição
- Processamento em lotes com fallback individual, cache de evidências
- Stack: `Node.js` · `Electron` · `Evolution API`

</details>

<details>
<summary><b>📚 Plataforma de Estudos com IA (flashcards + simulados)</b></summary>
<br/>

- Flashcards com repetição espaçada, simulados adaptativos, gamificação
- IA: geração de cards (CardMind™), sumarização (SynthBrain™), RAG (MemoryMesh™)
- Stack: `React` · `TypeScript` · `Vite` · `Clerk` · `HuggingFace`

</details>

---

## 🧰 Stack tecnológica

<div align="center">

<!-- Linguagens -->
<img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=000" />
<img src="https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Shell-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" />

<br/>

<!-- Frontend -->
<img src="https://img.shields.io/badge/React-0d1117?style=for-the-badge&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/Next.js-0d1117?style=for-the-badge&logo=nextdotjs&logoColor=white" />
<img src="https://img.shields.io/badge/Vite-0d1117?style=for-the-badge&logo=vite&logoColor=BD34FE" />
<img src="https://img.shields.io/badge/Tailwind-0d1117?style=for-the-badge&logo=tailwindcss&logoColor=38BDF8" />
<img src="https://img.shields.io/badge/Vue.js-0d1117?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D" />

<br/>

<!-- Backend -->
<img src="https://img.shields.io/badge/Node.js-0d1117?style=for-the-badge&logo=nodedotjs&logoColor=5FA04E" />
<img src="https://img.shields.io/badge/NestJS-0d1117?style=for-the-badge&logo=nestjs&logoColor=E0234E" />
<img src="https://img.shields.io/badge/Supabase-0d1117?style=for-the-badge&logo=supabase&logoColor=3ECF8E" />
<img src="https://img.shields.io/badge/Prisma-0d1117?style=for-the-badge&logo=prisma&logoColor=white" />
<img src="https://img.shields.io/badge/Flask-0d1117?style=for-the-badge&logo=flask&logoColor=white" />

<br/>

<!-- Infra -->
<img src="https://img.shields.io/badge/Docker-0d1117?style=for-the-badge&logo=docker&logoColor=2496ED" />
<img src="https://img.shields.io/badge/PostgreSQL-0d1117?style=for-the-badge&logo=postgresql&logoColor=4169E1" />
<img src="https://img.shields.io/badge/Redis-0d1117?style=for-the-badge&logo=redis&logoColor=DC382D" />
<img src="https://img.shields.io/badge/Nginx-0d1117?style=for-the-badge&logo=nginx&logoColor=009639" />
<img src="https://img.shields.io/badge/Linux-0d1117?style=for-the-badge&logo=linux&logoColor=FCC624" />

<br/>

<!-- Integrações -->
<img src="https://img.shields.io/badge/Stripe-0d1117?style=for-the-badge&logo=stripe&logoColor=635BFF" />
<img src="https://img.shields.io/badge/Telegram-0d1117?style=for-the-badge&logo=telegram&logoColor=26A5E4" />
<img src="https://img.shields.io/badge/Binance-0d1117?style=for-the-badge&logo=binance&logoColor=F0B90B" />
<img src="https://img.shields.io/badge/Mapbox-0d1117?style=for-the-badge&logo=mapbox&logoColor=white" />
<img src="https://img.shields.io/badge/Google_AI-0d1117?style=for-the-badge&logo=googlegemini&logoColor=8E75B2" />

</div>

---

## 📊 Métricas GitHub

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=DiegoLial&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&bg_color=0d1117&title_color=00d9ff&icon_color=00d9ff&text_color=c9d1d9" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=DiegoLial&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00d9ff&text_color=c9d1d9&langs_count=8" />

</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=DiegoLial&theme=tokyonight&hide_border=true&background=0d1117&stroke=00d9ff&ring=00d9ff&fire=ffd700&currStreakLabel=00d9ff&sideLabels=c9d1d9&dates=666666" />
</div>

<!-- ═══════════════ GRÁFICO DE ATIVIDADE ═══════════════ -->

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=DiegoLial&theme=tokyo-night&hide_border=true&bg_color=0d1117&color=00d9ff&line=00d9ff&point=ffd700&area=true&area_color=00d9ff" />
</div>

---

## 🏆 Troféus

<div align="center">
  <img src="https://github-trophies.vercel.app/?username=DiegoLial&theme=algolia&no-frame=true&no-bg=true&column=4&margin-w=15&margin-h=15" />
</div>

---

## 📫 Contato

<div align="center">

<a href="https://github.com/DiegoLial">
  <img src="https://img.shields.io/badge/GitHub-DiegoLial-0d1117?style=for-the-badge&logo=github&logoColor=white" />
</a>&nbsp;
<a href="https://t.me/DiegoLial">
  <img src="https://img.shields.io/badge/Telegram-DiegoLial-0d1117?style=for-the-badge&logo=telegram&logoColor=26A5E4" />
</a>

</div>

---

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:00d9ff,100:0d1117&height=100&section=footer" />

<div align="center">
  <sub><b>Código limpo · Segurança consistente · Automação inteligente · Impacto real</b></sub>
</div>
