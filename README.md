```python
class Pantelis:
    def __init__(self):
        self.role = "CS & Telecom @ NKUA"
        self.currently = "figuring it out on the way"
        self.hackathons = 5
        self.podiums = 3
        self.sleep = "theoretically possible"

    def build(self, idea: str) -> str:
        if self.feels_ready():
            return "waiting..."
        return ship(idea)  # always takes this branch

    def feels_ready(self) -> bool:
        return False  # has never returned True, probably never will
```

I build systems where AI decisions are trustworthy enough to act on; agents with audit trails, optimizers with validated metrics, infrastructure that keeps humans in the loop where it matters.

The other half is C — schedulers, job runners, kernels. Nothing exposes whether you actually understood a system like having to implement it without a garbage collector.

---

## Work

**[ATLAS](https://github.com/galactica-labs/project-atlas)** &nbsp; *2nd place · Panathēnea × Florent VC Hackathon 2026*

Agentic OS for mission-critical physical infrastructure. Five-agent ensemble over a declarative HITL policy gateway on Azure Durable Functions. Live asset graph on Apache AGE/PostgreSQL, MILP technician dispatch via PuLP/CBC, voice-first field workflow on OpenAI Realtime API. Every agent decision written to a tamper-evident audit trail.

**[LogicVolt](https://github.com/panteliskts/Agent404_ETW)** &nbsp; *3rd place · Engineering the World by Metlen 2026*

BESS dispatch optimization for the Greek Day-Ahead Market. LightGBM quantile ensemble with conformal calibration, dynamic-horizon MPC MILP scheduler, FastAPI/Next.js stack with enterprise security. 87.4% capture vs. perfect foresight. €551k backtested 30-day revenue in leakage-free walk-forward validation.

**[HITL Gateway](https://github.com/panteliskts/HITL-Gateway)** &nbsp; *3rd place · ThinkBiz 2026 · Microsoft Azure Challenge*

AI agent governance middleware on Azure Durable Functions. Multi-tenant isolation, multi-stage SLA escalation across Telegram/Twilio/Resend, real-time React orchestration dashboard. HMAC-SHA256, replay prevention, immutable audit log. 91 passing tests.

**[INFORM](https://github.com/panteliskts/makethon-2026-Merge_Conflicts-INFORM)** &nbsp; *Makeathon 2026*

Invoice intelligence that highlights the exact bounding box on the source PDF behind every answer. FastAPI + PyMuPDF semantic chunking, ChromaDB, Gemini-powered RAG with two-pass self-check grounding, PDF.js canvas overlay on the Next.js frontend.

**[POSIX Job Management Systems](https://github.com/panteliskts/posix-job-management-system)** &nbsp; *Systems Programming · NKUA 2026*

Two C execution engines. A process-pool scheduler where console, coordinator and worker pools talk over named pipes, multiplexed with `poll` and SIGCHLD self-pipe handling. A [concurrent TCP job server](https://github.com/panteliskts/concurrent-job-management-server) with detached handler threads and a mutex/condvar-guarded growing queue feeding a fixed pthread pool. Both fork/exec the real jobs, capture per-job output, and ship with end-to-end smoke tests.

**[MLFQ Scheduler](https://github.com/panteliskts/MLFQ_Scheduler_in_xv6-riscv) & B+ Tree Engine** &nbsp; *NKUA 2025*

Extended xv6-riscv with a 4-level MLFQ scheduler (timeslice demotion, anti-starvation boost, custom `getpinfo()` syscall). Disk-based B+ tree in C over a 512-byte block library with correct splitting, rebalancing, and leaf-chain traversal across 400+ records.

**[panteliskotsas.com](https://panteliskotsas.com)** &nbsp; *live*

React/TypeScript/Vite over a Hono API, Drizzle and PostgreSQL, with presigned S3 uploads, deployed on a Cloudflare Worker. The only thing on this list that isn't a hackathon or a course project, and the only one I keep running.

**Also:** [Agentic Clarity](https://github.com/panteliskts/agentic-response-clarity-pipeline) — four-stage Qwen3.5 pipeline with schema contracts, repair paths, deterministic fallbacks and bootstrap comparisons · [Evasion Classifier](https://github.com/panteliskts/political-evasion-classifier) — TF-IDF and Word2Vec baselines against DistilBERT and DeBERTa-v3 on QEvasion · [Multimodal Music Analysis](https://github.com/panteliskts/multimodal-music-analysis) — audio and lyric fusion across 52,105 Music4All songs

---

## Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**ML & AI**

![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=flat-square&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)

**Systems**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![POSIX](https://img.shields.io/badge/POSIX%20IPC-4B275F?style=flat-square&logoColor=white)
![pthreads](https://img.shields.io/badge/pthreads-6E4C13?style=flat-square&logoColor=white)
![RISC-V](https://img.shields.io/badge/RISC--V-283272?style=flat-square&logo=riscv&logoColor=white)

**Backend & Web**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232a?style=flat-square&logo=react&logoColor=61DAFB)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-6DA55F?style=flat-square&logo=node.js&logoColor=white)

**Data & Infra**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0072C6?style=flat-square&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-0db7ed?style=flat-square&logo=docker&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-039BE5?style=flat-square&logo=firebase)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)

---

## Stats

![](https://github-readme-stats.shion.dev/api?username=Panteliskts&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true)&nbsp;
![](https://github-readme-stats.shion.dev/api/top-langs/?username=Panteliskts&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true&layout=compact)

---

[![Portfolio](https://img.shields.io/badge/Portfolio-245E76?style=flat-square&logo=googlechrome&logoColor=white)](https://panteliskotsas.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pantelis-kotsas-46861a299/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:contact@panteliskotsas.com)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://instagram.com/panteliskotsas)
