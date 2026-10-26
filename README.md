<!-- ═══════════════════════════ HEADER ═══════════════════════════ -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=230&color=0:0f1020,45:24283b,100:7aa2f7&text=Chetan%20Panchal&fontColor=ffffff&fontSize=62&fontAlignY=36&desc=Cloud%20Engineer%20II%20%40%20Amazon%20Web%20Services%20%C2%B7%20OpenSearch%20%26%20Streaming&descAlignY=58&descSize=18&animation=fadeIn" width="100%" alt="Chetan Panchal" />
</div>

<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2800&pause=900&color=7AA2F7&center=true&vCenter=true&width=640&lines=Cloud+Engineer+II+%40+Amazon+Web+Services;Amazon+OpenSearch+Service+Subject+Matter+Expert;Kafka+%C2%B7+Kinesis+%C2%B7+real-time+streaming+pipelines;Terraform+%C2%B7+Kubernetes+%C2%B7+observability+at+scale;Building+with+Bedrock%2C+Claude+%26+MCP+servers" alt="Typing SVG" />
  </a>
</div>

<br/>

<div align="center">
  <a href="https://www.linkedin.com/in/chetan2709/"><img src="https://img.shields.io/badge/LinkedIn-chetan2709-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  &nbsp;
  <a href="mailto:chetan.panchal270999@gmail.com"><img src="https://img.shields.io/badge/Email-Say%20hello-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  &nbsp;
  <a href="https://twitter.com/chetanoic"><img src="https://img.shields.io/badge/X-%40chetanoic-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>
  &nbsp;
  <a href="https://instagram.com/chetanoic"><img src="https://img.shields.io/badge/Instagram-%40chetanoic-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" /></a>
  &nbsp;
  <img src="https://komarev.com/ghpvc/?username=chetanpanchal27&style=for-the-badge&color=7aa2f7&label=Profile+views" alt="Profile views" />
</div>

<br/>

<!-- ═══════════════════════════ ABOUT ═══════════════════════════ -->
## 👋 About me

I'm a **Cloud Engineer II at Amazon Web Services** in Toronto 🇨🇦, where I own the hardest enterprise escalations and architecture engagements for **Amazon OpenSearch Service** and streaming workloads.

Day to day that means shard and allocation strategy, JVM heap and circuit-breaker tuning, **ISM / UltraWarm / cold-tier** lifecycle design for petabyte-scale log analytics, **cross-cluster replication** for DR, and end-to-end pipelines on **Amazon MSK (Kafka)**, **Kinesis**, **Lambda** and **OpenSearch Ingestion**.

Before AWS I was an SRE at **Societe Generale** and **Splunk**, so I think in SLOs, runbooks and root-cause analyses. Lately I'm building with **Amazon Bedrock**, **Anthropic Claude**, **MCP servers** and AI agents.

<div align="center">
  <img src="https://img.shields.io/badge/🏆_OpenSearch-Subject_Matter_Expert-7aa2f7?style=for-the-badge" alt="OpenSearch SME" />
  <img src="https://img.shields.io/badge/📈_Build_failures-cut_by_98%25-9ece6a?style=for-the-badge" alt="98% fewer build failures" />
  <img src="https://img.shields.io/badge/🚨_Escalated_incidents-300%2B_resolved-f7768e?style=for-the-badge" alt="300+ incidents" />
  <img src="https://img.shields.io/badge/🗄️_Log_analytics-petabyte_scale-bb9af7?style=for-the-badge" alt="Petabyte scale" />
</div>

<br/>

<!-- ═══════════════════════════ WHAT I BUILD ═══════════════════════════ -->
## 🧭 What I build

A typical platform I design and stabilize: high-volume logs, metrics and events streamed in, transformed in flight, indexed in OpenSearch, and tiered for cost.

```mermaid
flowchart LR
    SRC[Apps · Services · Infra]:::src
    SRC --> MSK[(Amazon MSK<br/>Kafka)]:::stream
    SRC --> KDS[(Kinesis<br/>Data Streams)]:::stream
    MSK --> ING[OpenSearch Ingestion<br/>+ Lambda<br/>transform · enrich]:::ing
    KDS --> ING
    ING --> OS[(Amazon OpenSearch<br/>Service)]:::os
    OS --> DASH[Dashboards · Alerts<br/>Search · Analytics]:::out
    OS -. ISM · UltraWarm · Cold .-> TIER[(Tiered storage)]:::tier
    OS -. cross-cluster replication .-> DR[(DR cluster)]:::tier

    classDef src fill:#24283b,stroke:#7aa2f7,color:#c0caf5
    classDef stream fill:#1f2335,stroke:#ff9e64,color:#c0caf5
    classDef ing fill:#1f2335,stroke:#bb9af7,color:#c0caf5
    classDef os fill:#1a1b27,stroke:#9ece6a,color:#c0caf5,stroke-width:2px
    classDef out fill:#24283b,stroke:#7dcfff,color:#c0caf5
    classDef tier fill:#1f2335,stroke:#565f89,color:#a9b1d6,stroke-dasharray:4 3
```

<br/>

<!-- ═══════════════════════════ TECH STACK ═══════════════════════════ -->
## 🛠️ Tech stack

<table align="center">
  <tr>
    <td align="right"><b>☁️ Cloud</b></td>
    <td>
      <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=FF9900" alt="AWS" />
      <img src="https://img.shields.io/badge/EKS-FF9900?style=for-the-badge&logo=amazoneks&logoColor=white" alt="EKS" />
      <img src="https://img.shields.io/badge/Lambda-FF9900?style=for-the-badge&logo=awslambda&logoColor=white" alt="Lambda" />
      <img src="https://img.shields.io/badge/EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white" alt="EC2" />
      <img src="https://img.shields.io/badge/S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white" alt="S3" />
      <img src="https://img.shields.io/badge/DynamoDB-4053D6?style=for-the-badge&logo=amazondynamodb&logoColor=white" alt="DynamoDB" />
      <img src="https://img.shields.io/badge/Google%20Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" alt="GCP" />
      <img src="https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logoColor=white" alt="Azure" />
    </td>
  </tr>
  <tr>
    <td align="right"><b>🔎 Search &amp; streaming</b></td>
    <td>
      <img src="https://img.shields.io/badge/OpenSearch-005EB8?style=for-the-badge&logo=opensearch&logoColor=white" alt="OpenSearch" />
      <img src="https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white" alt="Elasticsearch" />
      <img src="https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" alt="Kafka" />
      <img src="https://img.shields.io/badge/Amazon%20MSK-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="MSK" />
      <img src="https://img.shields.io/badge/Kinesis-8C4FFF?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="Kinesis" />
    </td>
  </tr>
  <tr>
    <td align="right"><b>⚙️ DevOps &amp; IaC</b></td>
    <td>
      <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" alt="Terraform" />
      <img src="https://img.shields.io/badge/CloudFormation-FF4F8B?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="CloudFormation" />
      <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes" />
      <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
      <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white" alt="Jenkins" />
      <img src="https://img.shields.io/badge/GitLab%20CI-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white" alt="GitLab CI" />
      <img src="https://img.shields.io/badge/Argo%20CD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white" alt="Argo CD" />
      <img src="https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white" alt="Ansible" />
      <img src="https://img.shields.io/badge/Puppet-FFAE1A?style=for-the-badge&logo=puppet&logoColor=black" alt="Puppet" />
      <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
    </td>
  </tr>
  <tr>
    <td align="right"><b>📡 Observability</b></td>
    <td>
      <img src="https://img.shields.io/badge/CloudWatch-FF4F8B?style=for-the-badge&logo=amazoncloudwatch&logoColor=white" alt="CloudWatch" />
      <img src="https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white" alt="Splunk" />
      <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" alt="Grafana" />
      <img src="https://img.shields.io/badge/Nagios-000000?style=for-the-badge&logo=nagios&logoColor=white" alt="Nagios" />
      <img src="https://img.shields.io/badge/Dynatrace-1496FF?style=for-the-badge&logo=dynatrace&logoColor=white" alt="Dynatrace" />
    </td>
  </tr>
  <tr>
    <td align="right"><b>🤖 AI &amp; GenAI</b></td>
    <td>
      <img src="https://img.shields.io/badge/Amazon%20Bedrock-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="Bedrock" />
      <img src="https://img.shields.io/badge/Amazon%20Q-8C4FFF?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="Amazon Q" />
      <img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=claude&logoColor=white" alt="Claude" />
      <img src="https://img.shields.io/badge/MCP%20servers-000000?style=for-the-badge&logo=modelcontextprotocol&logoColor=white" alt="MCP" />
      <img src="https://img.shields.io/badge/RAG%20%C2%B7%20Agents-24283b?style=for-the-badge" alt="RAG and agents" />
      <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face" />
    </td>
  </tr>
  <tr>
    <td align="right"><b>💻 Languages</b></td>
    <td>
      <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
      <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
      <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go" />
      <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++" />
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
      <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" alt="Bash" />
      <img src="https://img.shields.io/badge/Clojure-5881D8?style=for-the-badge&logo=clojure&logoColor=white" alt="Clojure" />
      <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
      <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
    </td>
  </tr>
  <tr>
    <td align="right"><b>🧰 Frameworks &amp; tools</b></td>
    <td>
      <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot" />
      <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
      <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
      <img src="https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white" alt="Selenium" />
      <img src="https://img.shields.io/badge/Cucumber-23D96C?style=for-the-badge&logo=cucumber&logoColor=white" alt="Cucumber" />
      <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Postman" />
      <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
      <img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white" alt="Jira" />
    </td>
  </tr>
</table>

<br/>

<!-- ═══════════════════════════ EXPERIENCE ═══════════════════════════ -->
## 💼 Experience

| | Role | Company | When |
|:-:|:--|:--|:--|
| 🟠 | **Cloud Engineer II** | Amazon Web Services · Toronto | Aug 2026 – Present |
| 🟠 | **Cloud Engineer I** · OpenSearch SME | Amazon Web Services · Toronto | Nov 2024 – Aug 2026 |
| 🔴 | **Site Reliability Engineer** | Societe Generale · Montreal | Jul 2024 – Nov 2024 |
| 🟢 | **DevOps Engineer** (part-time) | VCare Networks · Remote | Jan 2024 – Jun 2024 |
| 🔵 | **DevOps Engineer Intern** | Tecsys · Montreal | Sep 2023 – Dec 2023 |
| 🟣 | **Site Reliability Engineer** | Splunk · Ahmedabad | Dec 2020 – Aug 2022 |

<details>
<summary><b>Highlights by role</b> (click to expand)</summary>
<br/>

**Amazon Web Services**
- Promoted to Cloud Engineer II for depth in Amazon OpenSearch Service and streaming architectures; own the most complex enterprise escalations.
- Built end-to-end ingestion pipelines (Kafka, Kinesis, Lambda, OpenSearch Ingestion) with in-flight transformation and enrichment.
- Led OpenSearch performance engineering: shard sizing and allocation, JVM heap and circuit breakers, segment merge policies.
- Designed ISM / UltraWarm / cold-tier lifecycle architectures that cut storage cost for petabyte-scale log analytics.
- Architected cross-cluster replication and multi-AZ domains for DR and read scaling.
- Deployed EKS microservices infrastructure with Terraform; partnered with TAMs on on-prem to AWS migrations.
- Mentor engineers on OpenSearch and Kafka troubleshooting; author internal runbooks.

**Societe Generale**
- Release management and deployments for the Border (US) and Maple (Canada) projects with Jenkins, Argo CD and GitHub.
- Monitoring with Dynatrace, AppDynamics, Grafana and Splunk; scheduling with Autosys; automation in Ansible, Python and Bash.

**Tecsys**
- GitLab pipelines for Kubernetes microservice deployments; cut infrastructure-related build failures by 98%.

**Splunk**
- Ran large indexer and search-head clusters; onboarded data sources, wrote SPL, dashboards and alerts.
- On-call for escalated incidents (300+ debugged); incident response, RCAs and preventive automation.

</details>

<br/>

<!-- ═══════════════════════════ EDUCATION ═══════════════════════════ -->
## 🎓 Education

| | Degree | School | When |
|:-:|:--|:--|:--|
| 🎓 | **Master of Software Engineering** | Concordia University · Montreal | 2022 – 2024 |
| 🎓 | **B.Tech, Information Technology** | Dharmsinh Desai University · Nadiad | 2017 – 2021 |

<br/>

<!-- ═══════════════════════════ GITHUB STATS ═══════════════════════════ -->
## 📊 GitHub

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=chetanpanchal27&show_icons=true&theme=tokyonight&hide_border=true&bg_color=1a1b27&include_all_commits=true&count_private=true&rank_icon=github" height="170" alt="GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=chetanpanchal27&layout=compact&theme=tokyonight&hide_border=true&bg_color=1a1b27&langs_count=8" height="170" alt="Top languages" />
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=chetanpanchal27&theme=tokyonight&hide_border=true&background=1a1b27" alt="GitHub streak" />
</div>

<div align="center">
  <img src="https://ghchart.rshah.org/7aa2f7/chetanpanchal27" width="100%" alt="Contribution graph" />
</div>

<div align="center">
  <img src="https://github-trophies.vercel.app/?username=chetanpanchal27&theme=tokyonight&no-frame=true&no-bg=true&margin-w=8&column=7" alt="Trophies" />
</div>

<br/>

<!-- ═══════════════════════════ FOOTER ═══════════════════════════ -->
<div align="center">
  <i>Open to conversations about OpenSearch, Kafka, observability and GenAI on AWS. Say hi on <a href="https://www.linkedin.com/in/chetan2709/">LinkedIn</a>.</i>
</div>

<img src="https://capsule-render.vercel.app/api?type=waving&height=120&color=0:7aa2f7,55:24283b,100:0f1020&section=footer" width="100%" alt="" />
