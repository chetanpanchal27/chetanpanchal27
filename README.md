<div align="center">
  <img src="assets/header.svg" width="100%" alt="Chetan Panchal, cloud engineer ii @ amazon web services, toronto" />
</div>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2600&pause=900&color=A78BFA&center=true&vCenter=true&width=720&lines=cloud+engineer+ii+%40+amazon+web+services;i+make+opensearch+clusters+behave;kafka+%C2%B7+kinesis+%C2%B7+streaming+at+scale;terraform+%C2%B7+kubernetes+%C2%B7+observability;building+with+bedrock%2C+claude+%26+mcp+servers" alt="cloud engineer ii @ amazon web services" />
</div>

<p align="center">
  <a href="https://www.linkedin.com/in/chetan2709/"><img src="https://skillicons.dev/icons?i=linkedin" width="44" alt="LinkedIn" /></a>
  &nbsp;&nbsp;
  <a href="mailto:chetan.panchal270999@gmail.com"><img src="https://skillicons.dev/icons?i=gmail" width="44" alt="Email" /></a>
</p>

<br/>

### about

```console
$ whoami
cloud engineer ii @ amazon web services, toronto 🇨🇦
i own the gnarliest opensearch + streaming escalations and make clusters behave

$ cat ~/now.txt
→ tuning opensearch at enterprise scale: shards, jvm heap, circuit breakers, ism / ultrawarm tiers
→ streaming pipelines: kafka (msk) · kinesis · lambda → opensearch ingestion
→ building with amazon bedrock, claude and mcp servers
→ mentoring engineers + writing the runbooks i wish i'd had

$ history | grep -i sre
societe generale (montreal) · splunk (ahmedabad)
```

<div align="center">
  <img src="assets/tiles.svg" width="100%" alt="opensearch sme · 300+ escalated incidents resolved · 98% fewer build failures · petabyte-scale analytics" />
</div>

<br/>

### what i build

```mermaid
flowchart LR
    SRC[apps · services · infra]:::src
    SRC --> MSK[(amazon msk<br/>kafka)]:::stream
    SRC --> KDS[(kinesis<br/>data streams)]:::stream
    MSK --> ING[opensearch ingestion<br/>+ lambda<br/>transform · enrich]:::ing
    KDS --> ING
    ING --> OS[(amazon opensearch<br/>service)]:::os
    OS --> OUT[dashboards · alerts<br/>search · analytics]:::out
    OS -. ism · ultrawarm · cold .-> TIER[(tiered storage)]:::tier
    OS -. cross-cluster replication .-> DR[(dr cluster)]:::tier

    classDef src fill:#0f1629,stroke:#a78bfa,color:#e2e8f0
    classDef stream fill:#0f1629,stroke:#f472b6,color:#e2e8f0
    classDef ing fill:#0f1629,stroke:#a78bfa,color:#e2e8f0
    classDef os fill:#0a0e1a,stroke:#22d3ee,color:#e2e8f0,stroke-width:2px
    classDef out fill:#0f1629,stroke:#34d399,color:#e2e8f0
    classDef tier fill:#0f1629,stroke:#64748b,color:#cbd5e1,stroke-dasharray:4 3
```

<br/>

### stack

<div align="center">
  <img src="assets/aws.svg" width="100%" alt="aws services: opensearch, opensearch ingestion, msk kafka, kinesis, lambda, eks, dynamodb, cloudwatch, s3, ec2, cloudformation, bedrock, amazon q, auto scaling" />
</div>

<div align="center">
  <img src="https://skillicons.dev/icons?i=aws,gcp,azure,kubernetes,docker,terraform,ansible,jenkins,gitlab,grafana,linux,bash,python,java,go,cpp,js,nodejs,react,spring,kafka,elasticsearch,mysql,mongodb,dynamodb,git,postman,selenium,clojure,nginx,maven,vscode,pycharm&theme=dark&perline=11" alt="tech stack icons" />
</div>

<br/>

### where i've been

<div align="center">
  <img src="assets/timeline.svg" width="100%" alt="experience timeline and education" />
</div>

<br/>

### github

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=chetanpanchal27&show_icons=true&hide_border=true&bg_color=0f1629&title_color=a78bfa&icon_color=22d3ee&text_color=cbd5e1&ring_color=f472b6&border_radius=20&include_all_commits=true&count_private=true" height="170" alt="github stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=chetanpanchal27&layout=compact&hide_border=true&bg_color=0f1629&title_color=a78bfa&text_color=cbd5e1&border_radius=20&langs_count=8" height="170" alt="top languages" />
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=chetanpanchal27&hide_border=true&background=0f1629&ring=a78bfa&fire=f472b6&currStreakLabel=a78bfa&sideLabels=cbd5e1&currStreakNum=ffffff&sideNums=ffffff&dates=6b7280&border_radius=20" alt="github streak" />
</div>

<div align="center">
  <img src="https://ghchart.rshah.org/a78bfa/chetanpanchal27" width="100%" alt="contribution graph" />
</div>

<br/>

<div align="center">
  <sub>thanks for scrolling · say hi on <a href="https://www.linkedin.com/in/chetan2709/">linkedin</a></sub>
</div>
