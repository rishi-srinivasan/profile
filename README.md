<p align="center">
  <img src="assets/banner.svg" alt="Terminal window: Rishi Srinivasan, Cloud Site Reliability Engineer. Focus: reliability, observability, LLM platforms, FinOps." width="900">
</p>

<p align="center">
  <a href="https://linkedin.com/in/rishi-srinivasan">LinkedIn</a> ·
  <a href="mailto:rishi.srinivasan95@gmail.com">Email</a> ·
  <a href="https://rsrinivasan.de">Portfolio</a> ·
  <a href="https://medium.com/@rishi.srinivasan95">Writing</a>
</p>

## About

I keep platforms reliable, and ship the LLM systems that run on them. Eight years across machine learning, backend and cloud, in regulated environments: online banking, insurance, healthcare.

At **Scalable Capital** (Berlin) I own the Datadog platform and the company's LLM gateway. Before that I owned a production Azure OpenAI application for 1000+ users at **OEV** and delivered cloud and ML work for Bank of Montreal, Equinor, Transgrid and JERA at **Tata Consultancy Services**.

German permanent residence · open to relocating to Munich · English, German (B1), French (A2)

## Results

Share left of the starting point, indexed to 100.

| What | Where | Before → after | |
|---|---|---|---|
| Datadog spend | Scalable Capital | `█████░░░░░░░░░░░░░░░` | **−74%** |
| AWS spend | OEV | `███████████░░░░░░░░░` | **−43%** |
| Manual release effort | OEV, CI/CD standardisation | `████░░░░░░░░░░░░░░░░` | **−80%** |
| False-positive classifications | OEV, Azure OpenAI app, via evals with the customer | `█░░░░░░░░░░░░░░░░░░░` | **−94%** |

Also: about 24 hours a month of manual cost reporting replaced by a scheduled Codex workflow on the Datadog MCP server, and 200+ multipage insurance documents processed in 3 months by a TypeScript service.

## Experience

**Cloud Site Reliability Engineer II · [Scalable Capital](https://www.scalable.capital)** · Jul 2026 – now · Berlin
- Led a 3-month proof of concept of Dash0 as a Datadog replacement: set the success criteria, integrated 5 core services, ran governance and permissions, onboarded 15+ engineers in 3 workshops, and turned developer feedback into feature requests with Dash0's product teams.
- Automated Datadog cost reporting with scheduled Codex tasks on the Datadog MCP server, publishing weekly and monthly slides for the VP Engineering and CTO.
- Operate Bifrost, the LLM gateway: cost, latency and token tracking across teams, MCP connectors, budgets, rate limits and alerts.
- Own the Datadog platform; cut its cost by 74% while keeping observability intact.

**DevOps Engineer · OEV (Sparkasse Versicherung Group)** · Nov 2022 – Jun 2026 · Berlin
- Owned a production Azure OpenAI app (Python, LangChain, LangGraph) end to end for a healthcare customer, classifying rehabilitation case documents for 1000+ users. Built evals with the customer and cut false positives by 94%.
- Designed and ran its Azure infrastructure: containers, CI/CD, guardrails, observability, cost controls.
- Built a TypeScript document service on Azure Document Intelligence that pre-fills policy forms from insurance certificates, and a market-monitoring pipeline that summarises competitor pricing changes with Azure OpenAI and Slack alerts.
- Migrated 20+ microservices from on-premises to Azure (AKS, ACI, Terraform) with zero downtime; standardised CI/CD in GitHub Actions and GitLab CI.
- Started as Associate DevOps Engineer and cut AWS costs by 43%.

**Data Scientist, then Associate Systems Engineer · Tata Consultancy Services** · Sep 2017 – Sep 2021 · Chennai
- Shipped an end-to-end ML pipeline predicting coal properties for JERA, working directly with their engineers.
- Delivered backend and cloud work for Bank of Montreal, Equinor and Transgrid, including a Windows banking monolith moved to cloud-native C# microservices on AWS CDK.

## Projects and writing

**Local-model evals with Codex CLI.** Open-source models served through Ollama, scored on a 6-task coding set over repeated runs. Qwen2.5-Coder 7B produced malformed tool calls in 67% of runs against 11% for Qwen3 8B, a gap I traced to the missing reasoning ability. A second comparison of GLM 5.3 flash against Luna 5.6 (low reasoning) found similar pass rates but less time and fewer tokens per task for GLM on the same harness.

**Articles**
- 2025-11 · [Building Enterprise-Grade Cloud Infrastructure: A Deep Dive into OOP and Reusable Components with Pulumi](https://medium.com/@rishi.srinivasan95/building-enterprise-grade-cloud-infrastructure-a-deep-dive-into-oop-and-reusable-components-with-e3441b89168e) · Medium
- 2025-03 · [Building Zero-Downtime Deployment Pipelines](https://medium.com/@rishi.srinivasan95) · Substack, also on Medium

**Teaching.** Guest lecturer for the Cloud Computing module of the M.Sc. Professional IT Business and Digitalisation at HTW Berlin, Summer 2027; administrator of the programme's AWS accounts.

## Stack

| | |
|---|---|
| **LLM systems** | Azure OpenAI, OpenAI API, Codex (CLI, MCP, plugins, scheduled tasks), LLM gateways, evals, tool calling, guardrails, RAG, LangChain, LangGraph, Ollama |
| **Observability** | Datadog, Dash0, OpenTelemetry, Prometheus, Grafana, CloudWatch, SLI/SLO design, load testing |
| **Cloud** | AWS (ECS, EKS, Lambda), Azure (Foundry, AKS, Functions, Entra ID), Kubernetes, Docker |
| **IaC and CI/CD** | Terraform, Pulumi, AWS CDK, GitHub Actions, GitLab CI, Jenkins, AWS CodePipeline |
| **Languages** | Python, TypeScript, C# |
| **Security and FinOps** | Least-privilege IAM, secrets management, cost optimisation, LLM token and rate limiting |

## Education

M.Sc. Professional IT Business and Digitalisation, HTW Berlin (GPA 1.58) · B.Tech Mechanical Engineering, SASTRA University

## Contact

[rishi.srinivasan95@gmail.com](mailto:rishi.srinivasan95@gmail.com) · [LinkedIn](https://linkedin.com/in/rishi-srinivasan) · [rsrinivasan.de](https://rsrinivasan.de)
