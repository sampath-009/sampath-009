![header](https://capsule-render.vercel.app/api?type=waving\&height=220\&text=Sai%20Sampath%20Chinthapalli\&fontSize=36\&fontAlign=50\&fontAlignY=36\&color=0:06B6D4,100:7C3AED\&fontColor=ffffff\&animation=twinkling)

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1100&center=true&vCenter=true&width=900&lines=Backend+SDE+%E2%80%A2+Event%E2%80%91Driven+Systems+%E2%80%A2+AI%2FML;FastAPI+%7C+PostgreSQL+%7C+Redis+%7C+Docker+%7C+AWS;Next.js+%7C+TypeScript+%7C+Tailwind;Idempotent+events%2C+observability%2C+developer+experience" alt="Typing intro" />
</p>

<p align="center">
  <!-- Replace with your own GIF stored in this repo (e.g., /assets/hero.gif) -->
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExazRyaWFyN3ZuaGlqY3Z5M3Fxb2tocHV5bXl2cGh6b2VobmFieGFtbiZjdD1n/WUlplcMpOCEmTGBtBW/giphy.gif" width="680" alt="hero animation" />
</p>

---

### About me

I turn messy requirements into dependable services and polished experiences. I care about correctness (transactions, constraints, schema evolution), speed (caches, queues), and developer experience (docs, health checks, simple rollbacks).

* MS CS (AI/ML), University at Buffalo (2024–2025)
* Present: **Saayam For All** (React + Express + Postgres + Redis on ECS/Terraform)
* Previous: **Kalam Dream Labs** (Spring Boot, MySQL → DynamoDB, Airflow, SQS, CI/CD), **Phoenix Global** (ML with PyTorch/Transformers)
* AWS Certified Solutions Architect – Associate (2025)

---

### Impact highlights

* Brought **p95 API latency to \~200ms** and **99.8% uptime** with indexing, pagination, task tuning, and CloudWatch runbooks
* Migrated **500k+ records** MySQL → DynamoDB via **Airflow DAGs**, feature‑flag cutover, and checksum validation
* Cut **deploy time from 60 → 25 min**; enabled **daily releases** with CodePipeline/CodeBuild + K8s/Kubernetes
* Reduced **invalid submissions by 25%** using a rules‑engine validator; **‑15% support escalations** via SQS dedupe + DLQ redrive
* ML: **+38% precision\@5** and **+15% completions** for a quiz recommender (A/B test); **0.8 corr.** DistilBERT auto‑grading

---

### Tech I enjoy

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,fastapi,flask,postgres,redis,docker,aws,terraform,airflow,linux,git,githubactions,java,spring,ts,nodejs,express,nextjs,react,tailwind,prisma,pytorch,sklearn,pandas,numpy&perline=12" alt="skills" />
</p>

---

### What I'm building / exploring

* Event‑driven microservices with **idempotent contracts** and replay‑safe pipelines
* **FastAPI** + **Next.js** full‑stack patterns, CI/CD, and observability
* **RAG** and voice‑first agents (Whisper STT, LangChain, FAISS)

<p align="center">
  <!-- Optional secondary GIF (replace path with an asset in your repo) -->
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExb2k4Z2h3aHFxYzZzM3k2M3c2bXBwdXBjMGNwN2RyZmw2bmVrbzQxeSZjdD1n/coxQHKASG60HrHtvkt/giphy.gif" width="520" alt="coding animation" />
</p>

---

## 📊 Live widgets (toggle on/off)

<div align="center">

<!-- GitHub Stats -->

<img src="https://github-readme-stats.vercel.app/api?username=sampath-009&show_icons=true&rank_icon=github&hide_border=true" alt="stats" />

<!-- Streak -->

<img src="https://github-readme-streak-stats.herokuapp.com/?user=sampath-009&hide_border=true" alt="streak" />

<!-- Languages -->

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sampath-009&layout=compact&hide_border=true" alt="top langs" />

<!-- Activity Graph -->

<img src="https://github-readme-activity-graph.vercel.app/graph?username=sampath-009&hide_border=true&custom_title=Contribution%20Graph" alt="activity graph" />

</div>

> Tip: If you prefer a cleaner look, keep **stats + top‑langs** and comment out the others.

---

## 🎛️ Optional fancy add‑ons

### 1) 3D contribution landscape (SVG)

<p align="center"><img src="./profile-3d-contrib/profile-night-rainbow.svg" alt="3D contributions" /></p>

<details>
<summary>Enable the 3D graph (copy this workflow)</summary>

```yaml
name: 3D Contributions
on:
  schedule:
    - cron: "0 2 * * *"  # daily at 02:00 UTC
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: yoshi389111/github-profile-3d-contrib@v3
        with:
          USERNAME: sampath-009
      - name: Commit & push
        run: |
          git config user.name "github-actions[bot]"
          git config user.email "41898282+github-actions[bot]@users.noreply.github.com"
          git add -A
          git commit -m "Generate 3D profile (auto)" || echo "No changes"
          git push
```

</details>

### 2) Metrics dashboard (lowlighter)

<p align="center"><img src="./metrics.svg" alt="Metrics" /></p>

<details>
<summary>Enable metrics (copy this workflow)</summary>

> Create a classic Personal Access Token named **METRICS\_TOKEN** with `read:user` and `repo` scopes and add it in **Settings → Secrets → Actions**.

```yaml
name: Metrics
on:
  schedule:
    - cron: "0 3 * * *"  # daily at 03:00 UTC
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: lowlighter/metrics@latest
        with:
          token: ${{ secrets.METRICS_TOKEN }}
          user: sampath-009
          template: classic
          base: header, activity, community, repositories, metadata
          config_timezone: America/New_York
          plugin_isocalendar: yes
          plugin_isocalendar_duration: full-year
          plugin_languages: yes
          plugin_languages_sections: most-used
          plugin_languages_indepth: yes
          plugin_achievements: yes
          plugin_habits: yes
```

</details>

### 3) Quote/Joke widgets (fun)

<p align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=light" alt="quote" />
</p>
<p align="center">
  <img src="https://readme-jokes.vercel.app/api?hideBorder&bgColor=ffffff00" alt="joke" />
</p>

<!-- Snake animation is intentionally omitted by default; can be added later if desired. -->

---

### Contact

<p align="center">
  <!-- Replace # with your actual links -->
  <a href="#"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white" /></a>
  <a href="mailto:your.name@email.com"><img src="https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white" /></a>
  <a href="#"><img src="https://img.shields.io/badge/X-000000?logo=x&logoColor=white" /></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=sampath-009&style=flat" alt="views" />
</p>

---

<!-- Implementation notes (not visible on profile):
1) Repo must be named exactly your username: sampath-009. Put this text in README.md at repo root.
2) For GIFs, add files under /assets and update the <img src> paths accordingly.
3) To keep it link‑free, avoid adding direct project links; pin repos instead via Profile → Customize your pins.
4) Tweak colors by changing the capsule-render color gradient and the typing SVG lines.
-->
