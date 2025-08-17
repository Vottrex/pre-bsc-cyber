# pre-bsc-cybersec

**Purpose:** public portfolio & research-ready workspace preparing me for the BSc in Cybersecurity — reproducible labs, a Dockerized honeypot project, polished CTF/HTB writeups, and study notes aligned to first-year modules. The objective for this is to go alonside certification aquisition to structure my preparation.

**Highlights**
- ✅ Reproducible demo: `projects/honeypot` — Dockerized, one-line run, sample dataset + analysis notebook.  
- ✅ Weekly micro-labs in `/labs` (pcap, Linux, networking) — each lab includes artifacts and a 1–2 page analysis.  
- ✅ Polished evidence in `/writeups` — clear TL;DR, commands, redacted outputs, and lessons-learned for each exercise.

**Quick demo**
```bash
git clone https://github.com/<your-username>/pre-bsc-cybersec.git
cd pre-bsc-cybersec/projects/honeypot
docker-compose up --build --detach
# then open projects/honeypot/experiments/analysis.ipynb or http://localhost:8080
