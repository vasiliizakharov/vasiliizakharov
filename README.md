<div align="center">

[![Header](https://capsule-render.vercel.app/api?type=waving&color=0:1a1d27,100:4f8ef7&height=180&section=header&text=Vasilii%20Zakharov&fontSize=46&fontColor=ffffff&fontAlignY=38&desc=Lead%20SRE%20%E2%80%A2%20AI%20Infrastructure%20Architect&descSize=16&descAlignY=62)](https://github.com/vasiliizakharov)

[![Typing](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=20&duration=3500&pause=800&color=4F8EF7&center=true&vCenter=true&width=780&lines=Lead+SRE+%7C+AI+Infrastructure+Architect;Sovereign+LLMOps+%7C+480B%2B+on-premise+inference;2.7M%2B+DAU+%E2%80%A2+SLA+%E2%89%A599.95%25+%E2%80%A2+MTTR+%3C+5+min)](https://github.com/vasiliizakharov)

[![Profile views](https://komarev.com/ghpvc/?username=vasiliizakharov&label=Profile%20views&color=4f8ef7&style=flat&base=2257)](https://github.com/vasiliizakharov)
[![Followers](https://img.shields.io/github/followers/vasiliizakharov?label=Follow&style=social)](https://github.com/vasiliizakharov)

</div>

> **Q2 2026 — open-sourced production-tested tooling** distilled from years of operating high-load infrastructure on-premise.

---

## What I do

- **Sovereign LLMOps** — on-premise inference of 480B+ open-weight models (Qwen3 Coder 480B-A35B / GPT-OSS 120B / NVIDIA Nemotron 3 Super) via vLLM / Aphrodite Engine
- **AIOps & self-healing** — auto-remediation pipelines covering 90%+ of incidents; MTTR < 5 min
- **High-load SRE** — SLA ≥ 99.95% across multi-DC clusters, 2.7M+ DAU, eBPF + OpenTelemetry observability
- **Security-first infra** — age encryption, threat modeling, IP allow-lists, PCI-DSS technical controls
- **Databases** — PostgreSQL & MariaDB (replication, performance tuning, PITR, schema migrations); ClickHouse / VictoriaMetrics / Redis hot paths

## Sovereign AI Strategy &amp; Omni

Designed and deployed the core of a multimodal **Omni** platform — a cluster of sovereign open-weight models orchestrated by complexity:

- **Qwen3 Coder 480B-A35B-Instruct** ([HF](https://huggingface.co/Qwen/Qwen3-Coder-480B-A35B-Instruct)) — code generation
- **GPT-OSS 120B** — general reasoning
- **NVIDIA Nemotron 3 Super** — high-precision SRE analysis
- **Gemma family** as L1 query-router agents — **40% latency reduction** on simple intents

On-premise inference of 480B+ weights via distributed sharding with **vLLM** / **Aphrodite Engine**.

## AIOps &amp; Highload

- 2000+ auto-remediation scenarios (Python / Bash); **90% of incidents resolved without human**
- **MTTR < 5 min** → 60% engineering team time freed
- **GRIB2** processing via Asyncio + Byte-Range fetch — **50× reduction** in parasitic traffic
- **Cross-AI Consult** — automated security-audit pipeline through delegated AI executor

## Tech stack

### LLMOps &amp; AI Models
<p>
<img src="https://img.shields.io/badge/Qwen3%20Coder%20480B-FF6A00?style=for-the-badge&logo=alibabacloud&logoColor=white" />
<img src="https://img.shields.io/badge/GPT--OSS%20120B-412991?style=for-the-badge&logo=openai&logoColor=white" />
<img src="https://img.shields.io/badge/Nemotron%203%20Super-76B900?style=for-the-badge&logo=nvidia&logoColor=white" />
<img src="https://img.shields.io/badge/Llama--3-0668E1?style=for-the-badge&logo=meta&logoColor=white" />
<img src="https://img.shields.io/badge/Gemma--4-4285F4?style=for-the-badge&logo=google&logoColor=white" />
<img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white" />
<img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" />
<img src="https://img.shields.io/badge/DeepSeek-4D6BFE?style=for-the-badge&logo=deepseek&logoColor=white" />
<img src="https://img.shields.io/badge/vLLM-FFD43B?style=for-the-badge&logo=python&logoColor=black" />
<img src="https://img.shields.io/badge/TensorRT--LLM-76B900?style=for-the-badge&logo=nvidia&logoColor=white" />
<img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" />
<img src="https://img.shields.io/badge/Qdrant-DC382D?style=for-the-badge&logo=qdrant&logoColor=white" />
<img src="https://img.shields.io/badge/PGVector-336791?style=for-the-badge&logo=postgresql&logoColor=white" />
</p>

### SRE &amp; Observability
<p>
<img src="https://img.shields.io/badge/Zabbix%207-D40000?style=for-the-badge&logo=zabbix&logoColor=white" />
<img src="https://img.shields.io/badge/eBPF-4F8EF7?style=for-the-badge&logo=linux&logoColor=white" />
<img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" />
<img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" />
<img src="https://img.shields.io/badge/OpenTelemetry-425CC7?style=for-the-badge&logo=opentelemetry&logoColor=white" />
<img src="https://img.shields.io/badge/ELK-005571?style=for-the-badge&logo=elastic&logoColor=white" />
</p>

### Data &amp; Platform
<p>
<img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white" />
<img src="https://img.shields.io/badge/ClickHouse-FFCC01?style=for-the-badge&logo=clickhouse&logoColor=black" />
<img src="https://img.shields.io/badge/VictoriaMetrics-5C95FF?style=for-the-badge&logo=victoriametrics&logoColor=white" />
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
<img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" />
<img src="https://img.shields.io/badge/ZFS-1A1A1A?style=for-the-badge&logo=openzfs&logoColor=white" />
</p>
<p>
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
<img src="https://img.shields.io/badge/FreeBSD-AB2B28?style=for-the-badge&logo=freebsd&logoColor=white" />
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" />
<img src="https://img.shields.io/badge/Proxmox-E57000?style=for-the-badge&logo=proxmox&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" />
<img src="https://img.shields.io/badge/HAProxy-7B68EE?style=for-the-badge&logo=haproxy&logoColor=white" />
</p>

### Dev &amp; IaC
<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" />
<img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" />
<img src="https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white" />
<img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
<img src="https://img.shields.io/badge/GitLab%20CI-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white" />
</p>

### Also familiar with
<p>
<img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" />
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
<img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" />
<img src="https://img.shields.io/badge/Swift-FA7343?style=for-the-badge&logo=swift&logoColor=white" />
</p>

## Featured projects

| Repo | What it does |
|---|---|
| [**ai-multi-expert-ui**](https://github.com/vasiliizakharov/ai-multi-expert-ui) | Self-hosted multi-persona AI CLI web UI — 9 expert personas, multimodal (text/image/audio/video), thread persistence. |
| [**crm-template**](https://github.com/vasiliizakharov/crm-template) | Production-ready field-service CRM (FastAPI + React + PostgreSQL) — orders FSM, RBAC, salaries, finance. |
| [**zabbix-postgresql-monitoring**](https://github.com/vasiliizakharov/zabbix-postgresql-monitoring) | Zabbix 7 template via `pg_monitor` role — replication slot LLD, cache hit-rate, RDS/CloudSQL compatible. |
| [**zabbix-bind-dns-monitoring**](https://github.com/vasiliizakharov/zabbix-bind-dns-monitoring) | BIND9 stats-channel JSON parser; multi-view aggregation; serial via `rndc` + SOA fallback. |
| [**observability-stack-docker**](https://github.com/vasiliizakharov/observability-stack-docker) | Prometheus + Grafana + Loki + Alertmanager + Promtail one-shot compose. |
| [**weewx-rp5**](https://github.com/vasiliizakharov/weewx-rp5) | Modernized 7-year-old WeeWX driver — silent API bug fix, CI Python 3.8-3.12. |

→ **[All 16 repos →](https://github.com/vasiliizakharov?tab=repositories&type=source)** (incl. 11 more Zabbix integrations)

## Activity

<div align="center">

[![Streak](https://streak-stats.demolab.com?user=vasiliizakharov&theme=tokyonight&hide_border=true&background=0f1117&stroke=2e3250&ring=4f8ef7&fire=4caf7d&currStreakLabel=4f8ef7&sideLabels=7ec8e3&dates=8088a8)](https://git.io/streak-stats)

</div>

## Contact

- **Email** — vasiliiazakharov@gmail.com
- **Telegram** — [@vasilii_zakharov](https://t.me/vasilii_zakharov)
- **Location** — Russia, remote OK
- **Format** — project-based engagements only · 2 days per week

---

<div align="center">

*Open to **Lead SRE** / **AI Infrastructure Architect** roles.*

</div>
