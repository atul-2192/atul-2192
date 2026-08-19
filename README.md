<!--
  ─────────────────────────────────────────────────────────────
  PALETTE (keep consistent everywhere)
  bg      #0D1117   accent  #00FFC6
  text    #8B949E   bright  #C9D1D9
  ─────────────────────────────────────────────────────────────
-->

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=21&pause=1400&duration=3000&color=00FFC6&center=true&vCenter=true&width=620&lines=backend+engineer;distributed+systems+%C2%B7+event-driven+architecture;i+build+things+that+don't+fall+over" />
</p>

<p align="center">
  <a href="https://linkedin.com/in/atulsingh2192"><img src="https://img.shields.io/badge/linkedin-0D1117?style=flat-square&logo=linkedin&logoColor=00FFC6&labelColor=0D1117" /></a>
  <a href="https://leetcode.com/u/atulkumarsingh952"><img src="https://img.shields.io/badge/leetcode-0D1117?style=flat-square&logo=leetcode&logoColor=00FFC6&labelColor=0D1117" /></a>
  <a href="mailto:atulkumarsingh952@gmail.com"><img src="https://img.shields.io/badge/mail-0D1117?style=flat-square&logo=gmail&logoColor=00FFC6&labelColor=0D1117" /></a>
  <img src="https://komarev.com/ghpvc/?username=atul-2192&style=flat-square&color=00FFC6&label=visitors" />
</p>

---

## `$ whoami`

```console
atul@backend:~$ whoami
> Backend Engineer @ Cognizant — building for JP Morgan Chase
> java · spring boot · kafka · postgres · redis · aws

atul@backend:~$ cat interests.txt
> consistency, retries, latency, concurrency, distributed failure
> the boring parts of systems that decide whether they survive
```

<table>
<tr><td><code>system failures</code></td><td>&darr; <b>85%</b></td></tr>
<tr><td><code>api latency (p90)</code></td><td><b>2.6s &rarr; 310ms</b></td></tr>
<tr><td><code>retry throughput</code></td><td>&uarr; <b>15%</b></td></tr>
</table>

---

## `$ cat stack.txt`

<p align="center">
  <img src="https://skillicons.dev/icons?i=java,spring,kafka,postgres,redis,mongodb,aws,docker,nginx,grafana,git,github&theme=dark&perline=12" />
</p>

```yaml
core:      Java 17 · Spring Boot · Spring Cloud · WebFlux · REST
scale:     Kafka · Redis · microservices · event-driven · outbox · idempotency
data:      PostgreSQL · MongoDB · indexing & query tuning
platform:  AWS · Docker · GitHub Actions · Nginx
observe:   Prometheus · Grafana · Loki · Tempo
```

---

## `$ git log --stat`

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=atul-2192&show_icons=true&include_all_commits=true&count_private=true&rank_icon=github&hide_border=true&bg_color=0D1117&title_color=00FFC6&icon_color=00FFC6&text_color=8B949E" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=atul-2192&layout=compact&langs_count=6&hide_border=true&bg_color=0D1117&title_color=00FFC6&text_color=8B949E" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=atul-2192&hide_border=true&background=0D1117&stroke=21262D&ring=00FFC6&fire=00FFC6&currStreakLabel=00FFC6&sideLabels=8B949E&dates=6E7681&currStreakNum=C9D1D9&sideNums=C9D1D9" height="165" />
</p>

<p align="center">
  <img src="https://gh-heat.anishroy.com/api/atul-2192/svg?colors=0d1117,033a2f,006d5b,00b894,00ffc6&darkMode=true&transparent=true&shape=square&radius=2&borderWidth=0&cellSize=11&cellGap=3&padding=8&fontSize=10&textColor=6e7681&showMonthLabels=true&showDayLabels=true&showLegend=true&legendPos=bottom&width=1000" width="100%" alt="contribution heatmap" />
</p>

<!-- optional: activity line graph — uncomment if you want it
<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=atul-2192&bg_color=0D1117&color=00FFC6&line=00FFC6&point=C9D1D9&area=true&hide_border=true" width="100%" />
</p>
-->

---

## `$ leetcode --stats`

<p align="center">
  <img src="https://leetcard.jacoblin.cool/atulkumarsingh952?theme=dark&font=JetBrains%20Mono&ext=heatmap&width=520" width="80%" />
</p>

<p align="center">
  <code>knight · 1844</code> &nbsp;·&nbsp; <code>1500+ solved</code> &nbsp;·&nbsp; <code>900+ gfg</code> &nbsp;·&nbsp; <code>graphs · dp · trees</code>
</p>

---

## `$ ls projects/`

### **switchboard** — distributed microservices platform

7 services behind a gateway, talking over Kafka, fully instrumented. Built to see what actually breaks at scale.

```mermaid
flowchart LR
    C(client) --> G[api gateway]
    G --> A[auth · jwt/oauth2]
    G --> S[7 domain services]
    A --> R[(redis · otp ttl)]
    S --> K{{kafka}}
    K --> W[async workers]
    S --> P[(postgres)]
    S -.metrics/traces.-> O[prometheus · grafana · loki · tempo]
```

`p90 latency −84%` · `jwt + oauth2` · `redis-backed otp` · `github actions ci/cd` · `docker`

<br>

### **lamicons** — assessment & learning platform

8-service EdTech backend with a real-time coding engine on Judge0, Kafka-driven workflows, and Redis caching. Strategy + adapter patterns so new assessment types plug in without touching the core.

`java 17` · `kafka` · `postgres` · `redis` · `mongodb` · `aws`

---

## `$ tail -f now.log`

```console
> designing retry orchestration for long-running workflows
> reading: designing data-intensive applications (again)
> open to: backend / platform / distributed systems roles
```

<p align="center">
  <sub><code>atulkumarsingh952@gmail.com</code> — always up for a conversation about kafka, failure modes, or a hard system design problem.</sub>
</p>
