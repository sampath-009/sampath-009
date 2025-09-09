![header](https://capsule-render.vercel.app/api?type=waving\&height=200\&text=Sai%20Sampath%20%F0%9F%91%8B\&fontSize=42\&color=0:06B6D4,100:7C3AED\&fontColor=ffffff\&animation=fadeIn)

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1200&center=true&vCenter=true&width=800&lines=SDE+who+loves+backend+systems%2C+DX%2C+and+delightful+UIs;FastAPI+%7C+PostgreSQL+%7C+Redis+%7C+Kafka+%7C+Docker+%7C+AWS;Next.js+%7C+TypeScript+%7C+Tailwind+%7C+shadcn%2Fui+%7C+Framer+Motion;Event%E2%80%91driven+design%2C+idempotency%2C+observability" alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=sampath-009&style=flat" alt="Profile views" />
</p>

---

### About me

I turn messy requirements into dependable services and polished experiences. I care about correctness (transactions, constraints, schema evolution), speed (caches, queues), and developer experience (docs, health checks, simple rollbacks).

---

### Tech I enjoy

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" />
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white" />
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white" />
  <img alt="Redis" src="https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white" />
  <img alt="Kafka" src="https://img.shields.io/badge/Kafka-231F20?logo=apachekafka&logoColor=white" />
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white" />
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white" />
  <img alt="AWS EC2" src="https://img.shields.io/badge/AWS%20EC2-FF9900?logo=amazonaws&logoColor=white" />
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white" />
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white" />
  <img alt="React" src="https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB" />
  <img alt="Tailwind" src="https://img.shields.io/badge/Tailwind-06B6D4?logo=tailwindcss&logoColor=white" />
  <img alt="Prisma" src="https://img.shields.io/badge/Prisma-2D3748?logo=prisma&logoColor=white" />
  <img alt="Clerk" src="https://img.shields.io/badge/Clerk-3D3D3D?logo=clerk&logoColor=white" />
  <img alt="Sanity" src="https://img.shields.io/badge/Sanity-F03E2F?logo=sanity&logoColor=white" />
  <img alt="OpenAI" src="https://img.shields.io/badge/OpenAI-412991?logo=openai&logoColor=white" />
  <img alt="Tesseract" src="https://img.shields.io/badge/Tesseract-5D2F86" />
</p>

---

### GitHub at a glance

<div align="center">

  <img src="https://github-readme-stats.vercel.app/api?username=sampath-009&show_icons=true&rank_icon=github&hide_title=true&hide_border=true" alt="stats" />

  <img src="https://github-readme-streak-stats.herokuapp.com/?user=sampath-009&hide_border=true" alt="streak" />

  <img src="https://github-readme-activity-graph.vercel.app/graph?username=sampath-009&hide_border=true&custom_title=Contribution%20Graph" alt="activity graph" />
</div>

---

### Highlights (no links)

* Appointment scheduling microservice with conflict‑free booking, idempotent events, and health‑gated deploys
* Full‑stack Reddit‑style app with modern UI, auth, content, and search
* Minesweeper desktop helper that OCRs the board and asks an LLM for the next move

---

### Fancy: animated contribution snake

> This draws a 🐍 across your contribution grid and updates automatically.

<p align="center">
  <img src="https://raw.githubusercontent.com/sampath-009/sampath-009/output/github-contribution-grid-snake.svg" alt="snake animation" />
</p>

<details>
<summary>How to enable the snake (copy this workflow)</summary>

1. Create folder: `.github/workflows/`
2. Add file: `snake.yml` with the content below
3. Commit and push. The action will create/update the animation on the `output` branch and your README will show it.

```yaml
name: Generate Snake
on:
  schedule:
    - cron: "0 0 * * *"  # every day at 00:00 UTC
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: sampath-009
          outputs: |
            dist/github-contribution-grid-snake.svg
      - uses: actions/upload-artifact@v4
        with:
          name: snake
          path: dist/github-contribution-grid-snake.svg
      - name: Push to output branch
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

</details>

---

### Fancy: 3D contribution landscape

<p align="center">
  <img src="./profile-3d-contrib/profile-night-rainbow.svg" alt="3D contributions" />
</p>

<details>
<summary>Enable the 3D graph (copy this workflow)</summary>

```yaml
name: 3D Contributions
on:
  schedule:
    - cron: "0 2 * * *"  # every day at 02:00 UTC
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

---

### Fancy: Metrics dashboard

<p align="center">
  <img src="./metrics.svg" alt="Metrics" />
</p>

<details>
<summary>Enable metrics (copy this workflow)</summary>

> Create a classic Personal Access Token named **METRICS\_TOKEN** with `read:user` and `repo` scopes and add it in **Settings → Secrets → Actions**.

```yaml
name: Metrics
on:
  schedule:
    - cron: "0 3 * * *"  # every day at 03:00 UTC
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

---

### Fun: rotating quote / joke (toggle on/off)

<p align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=light" alt="quote" />
</p>
<p align="center">
  <img src="https://readme-jokes.vercel.app/api?hideBorder&bgColor=ffffff00" alt="joke" />
</p>

---

### Bonus: trophies (toggle on/off)

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=sampath-009&margin-w=10&margin-h=10&no-bg=true&no-frame=true" alt="trophies" />
</p>

---

> Want a custom banner, different colors, or dark‑mode tweaks? Ping me the vibe and I'll swap the assets + settings.
