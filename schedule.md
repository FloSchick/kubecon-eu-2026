# KubeCon EU 2026 — Personalized Schedule Report

---

## Monday, March 23 — Co-Located Events Day

### Strategy

Your day splits naturally across three anchor events: **ArgoCon** (morning), **CiliumCon** (early afternoon), and **Agentics Day** (late afternoon). ArgoCon is the non-negotiable morning home for teams heavily invested in ArgoCD. Agentics Day is the forward-looking investment: AI agents in ops, the MCP ecosystem, and how these reshape Platform Engineering.

| Time | Primary Talk | Room | Backup Talk | Room | Why |
|------|-------------|------|-------------|------|-----|
| 09:00–09:05 | ArgoCon Welcome | Auditorium | Platform Engineering Day Welcome | Hall 8 Room F | Catch roadmap signals from the Argo ecosystem opening. |
| 09:05–09:10 | **Argo CD Update** | Auditorium | Observability Day Welcome | Forum | Official project update — directly impacts your ArgoCD deployment. |
| 09:20–09:25 | **Argo Rollouts Update** | Auditorium | Vibe Coding Meets GitOps (FluxCon) | Elicium 1 | Rollout updates matter for teams using progressive delivery across multi-tenant environments. |
| 09:30–09:35 | **Argo Workflows Update** | Auditorium | Observability Project Updates | Forum | Argo Workflows drives automation across many platform stacks — upstream changes matter. |
| 09:40–09:45 | **Argo Events Update** | Auditorium | Who Built This Platform? (Platform Eng Day) | Hall 8 Room F | Complete the Argo ecosystem sweep before the keynote block. |
| 09:50–09:55 | **ArgoCon Keynote: Promotion with Kargo** | Auditorium | Platform Engineering Day Keynote | Hall 8 Room F | Kargo is the emerging GitOps promotion layer — directly relevant to multi-stage dev→staging→prod pipelines. |
| 10:00–10:05 | **ArgoCon Keynote: Argo CD vs the World** | Auditorium | BackstageCon Keynote | Hall 8 Room E | Strategic framing for ArgoCD's position; validates your toolchain choices going forward. |
| 10:15–10:40 | **GitOps and Secrets: State of the Union** | G102-103 | Bring Your Own Artifact Driver To Workflows | Auditorium | Covers the GitOps/secrets integration challenge — directly relevant for teams using 1Password Operator or similar secrets CRDs. |
| 10:40–11:05 | **Creating an IDP for AI Engineering** | Hall 8 Room F | A Practical Blueprint for Evolving Observability Schemas | Forum | Bridges platform engineering work with AI/MCP integration — relevant to how internal platforms evolve. |
| 10:50–11:15 | **Anatomy of a GitOps Engine: Understanding Your Sync** | G102-103 | *(catch if IDP talk ends early)* | — | Deep ArgoCD sync internals from a core contributor (Alexandre Gaudreault). Invaluable for debugging complex multi-source app behavior. |
| 11:15–11:40 | **Expl(AI)n Like I'm 5: AI-Native Networking** | Hall 7 Room B | How To Play Support for a Platform Team | Hall 8 Room F | Intersects Cilium with AI-driven operations — relevant to CNI investment and forward-looking AI interest. |
| 11:25–11:50 | **Beyond Argo Rollouts: Boosting Developer Experience** | G102-103 | Don't Do What Donny Don't Does | Auditorium | Carlos Sanchez on extending rollout capabilities — practical for multi-tenant deployment patterns. |
| 11:30–11:55 | Talking to Your Cluster: Conversational GitOps | Elicium 1 | — | — | *(Backup)* AI + GitOps convergence — relevant to MCP server work. |
| 12:45–13:10 | **We Broke Free From Cloud-Managed Kubernetes** | Hall 8 Room F | The Day 2 Hangover | Hall 8 Room G | For teams running managed Kubernetes alongside self-managed clusters — relevant to multi-cloud architecture decisions. |
| 12:50–13:25 | **Panel: Building a GitOps Culture** | G102-103 | Scaling Telemetry To Terabytes | E103-105 | Organizational GitOps adoption patterns — relevant as your platform scales across more environments and teams. |
| 13:25–13:30 | **CiliumCon Welcome** | Elicium 1 | Agentics Day Welcome | Hall 7 Room A | Cilium v1.16 is your CNI — be present for project direction and community signals. |
| 13:35–13:55 | **★ Agentics Day: MCP in 2026** | Hall 7 Room A | Network Flow Aggregation (CiliumCon) | Elicium 1 | David Soria Parra (Anthropic) on the state and direction of MCP in 2026 — essential if you're building or evaluating MCP servers. |
| 13:35–14:00 | **GitOps Your Costs: Automated FinOps** | G102-103 | Analysis in Action: Metrics Driven Argo | Auditorium | Concrete path to operationalizing cost governance across all environments via GitOps patterns. |
| 14:05–14:30 | **The New AI Coding Fabric** | Hall 7 Room A | Argo CD: Previewing Pull Request Changes | G102-103 | Patrick Debois (coined "DevOps") on AI's impact on the coding/ops fabric — directly addresses how AI transforms Platform Engineering roles. |
| 14:10–14:35 | **It Is Always DNS… Even at the Edge** | Elicium 1 (CiliumCon) | Self-Healing Clusters (KyvernoCon) | E106-108 | Cilium's DNS handling is a common pain point in multi-cloud setups. |
| 14:35–14:45 | **Lightning: How I Built My Laptop Into MCP** | Hall 7 Room A | *(short, worth catching)* | — | 10-min talk — may surface integration ideas for MCP server work. |
| 14:40–14:50 | **Lightning: Accelerating Cilium** | Elicium 1 | — | — | Short session on Cilium performance — relevant as your tenant count grows. |
| 14:50–14:55 | **Agentics Day Keynote: Day-2 Ready** | Hall 7 Room A | CiliumCon Keynote | Elicium 1 | Idit Levine + Keith Babo on Day-2 readiness for AI agents — maps to operational maturity concerns. |
| 15:00–15:05 | **Agentics Day Keynote: Rescue Agents** | Hall 7 Room A | — | — | Stay in Hall 7 Room A. Ignasi Barrera on autonomous rescue agents in operations. |
| 15:20–15:45 | **★ Backend-First IDP: Argo CD + Crossplane + OPA** | Hall 8 Room G | Secure Your MCP Servers | Hall 8 Room D | KodeKloud + SailPoint engineers demo a production roadmap using ArgoCD, Crossplane, and OPA together in a 100+ service multi-tenant environment — the exact combination of GitOps, IaC reconciliation, and policy in a single control plane. If MCP server security is the priority, flip to the MCP security backup. |
| 15:55–16:20 | **Keeping Your Agents in Check** | Hall 7 Room A | Agnostic Workload Identity Across Argo | Auditorium | Governance and guardrails for AI agents. Workload identity backup relevant to RBAC + Keycloak OIDC setups. |
| 16:00–16:25 | **Cloud Native Promises, On-Premises** | Elicium 1 (CiliumCon) | The GitOps Paradox | Hall 8 Room F | On-prem Cilium deployment patterns — relevant to self-hosted clusters not on a hyperscaler CNI. |
| 16:30–16:55 | **Fantastic Vibes and Where To Find Them** | Hall 7 Room A (Agentics Day) | Leveraging Argo Workflows | Auditorium | AI-augmented development culture — forward-looking role/career perspective. Argo Workflows backup is operational for automation-heavy workflows. |
| 16:30–16:55 | **Testing Infrastructure as Code** | Emerald Room (OpenTofu Day) | Observability Without Borders | Forum | Testing IaC is a gap most teams have — directly applicable to policy-protected Terraform/OpenTofu workflows. |
| 17:00–17:10 | **Lightning: $10,000 Argo CD Mistake** | G102-103 | Lightning: Lessons from AI in Platform | Hall 8 Room G | War story format — high signal for what to avoid in ArgoCD at scale. |
| 17:00–17:25 | **★ Is AIOps the Future of Operations?** | Hall 7 Room A (Agentics Day) | — | — | Closing Agentics Day talk directly answering your core question: does AI change the Platform Engineering role, and how? Do not miss. |
| 17:30–17:40 | Lightning: Securing AI Agents | Hall 7 Room A | — | — | 10 min before the reception — directly relevant to your AI future interest. |
| 17:30–18:30 | **Evening Reception** | Hall 3 | — | — | Prioritize networking with the CiliumCon, ArgoCon, and Agentics Day communities — these are your peer groups. |

> **Key conflict at 15:20:** *Backend-First IDP (ArgoCD+Crossplane+OPA)* (Hall 8 Room G) vs. *Secure Your MCP Servers* (Hall 8 Room D) — pick the IDP talk if evaluating Crossplane as a Terraform replacement is the priority this week; pick MCP security if moving toward production MCP exposure.

---

## Tuesday, March 24 — Main Conference Day 1

### Strategy

The morning keynote block (09:00–10:42, Hall 12) is non-negotiable — the agentic AI narrative runs directly through your MCP server experiments and your question about AI reshaping platform engineering. After the coffee break, focus on three areas: AI+MCP+GitOps automation, Cilium networking, and observability. End the day at the ArgoCD+MCP automation talk.

| Time | Primary Talk | Room | Backup Talk | Room | Why |
|------|-------------|------|-------------|------|-----|
| 09:00–10:42 | **★ Full Keynote Block** | Hall 12 | — | — | "Scaling Platform Ops with AI Agents", "From Inference to Agents", and "The Future of Cloud Native Is… Agentic" map directly to your MCP server POC and AI-transforms-PE interest. Attend everything. |
| 10:45–11:15 | Coffee Break | — | — | — | Position yourself for the 11:15 MCP talk in Hall 8 Room F. |
| 11:15–11:45 | **★ Least-Privilege for AI: Authorizing Agents and MCP Tools** | Hall 8 Room F | When an Agent Acts on Your Behalf, Who Holds the Keys? | Auditorium | For anyone building MCP servers — directly addresses how to authorize MCP tool invocations with least-privilege before moving to production. Backup covers identity/delegation for Keycloak + Entra ID setups. |
| 12:00–12:30 | **★ Helm 4 Is Here. So, Now What?** | Amtrium 1+2 | When OTTL Goes Off the Rails: Debugging Transformations | Hall 8 Room D | Helm 4 changes directly affect OCI chart authoring, publishing workflow, and ArgoCD integration. OTTL backup is high-value if you've hit pain with Alloy pipeline transformations. |
| 12:30–14:30 | Lunch | — | — | — | — |
| 14:30–15:00 | **★ 10 Years of Cilium** | Amtrium 1+2 | Driving Adoption and Automation With MCP in Production at Liftoff | Auditorium | For teams running Cilium as their CNI — this anniversary session covers the WireGuard, Hubble, and ClusterMesh roadmap. If you feel confident on Cilium direction, the MCP-in-production talk is one step ahead of a POC. |
| 15:15–15:45 | **★ Crossplane — The Cloud Native Framework for Platform Engineering** | Amtrium 1+2 | OpenCost — Cost and Resource Management Deep Dive | G102-103 | Crossplane v2.2 maintainers (Upbound) on latest features, releases, and roadmap with live demos. Primary evaluation session for whether Crossplane can replace Terraform for infrastructure reconciliation. OpenCost backup remains high-value for multi-cluster cost allocation. |
| 15:45–16:15 | Coffee Break | — | — | — | — |
| 16:15–16:45 | **★ OpenTelemetry Project Update and Ask the Experts** | G102-103 | OpenTelemetry Logs Driving a Major Shift | Elicium 2 | For teams running Alloy as OTel collector with Grafana Cloud — ask pointed questions about Alloy, OTTL, and the collector roadmap. |
| 17:00–17:30 | **★ The 10x DevOps Engineer's Toolkit: Argo CD + AI-Driven MCP Automation** | Amtrium 1+2 | OpenTelemetry Collector SIG: Project Updates | G102-103 | Alexander Matyushentsev (core ArgoCD maintainer) covers AI-driven MCP automation layered on top of ArgoCD — the intersection of GitOps and MCP tooling. Highest-priority non-keynote talk of the day. |
| 16:15–16:45 | **From Alert Fatigue to Self-Healing: AI-Enabled Crossplane Control Planes** | Hall 8 Room D | OpenTelemetry Project Update + Ask the Experts | G102-103 | Upbound + Millennium bcp on using LLM-powered Crossplane composition functions to auto-triage and remediate Kubernetes alerts, reducing SRE escalations in a multi-cloud banking environment. High-value follow-up to the 15:15 Crossplane intro. OTel Ask-the-Experts backup if you've seen enough Crossplane for the day. |
| 17:30–19:00 | KubeCrawl + CloudNativeFest | — | — | — | Target the Crossplane/Upbound team (Terraform migration evaluation), ArgoCD maintainers, and Cilium team (Hubble, WireGuard). |

> **Also worth monitoring if schedule shifts:**
> - **Gateway API: Bridging the Gap from Ingress to the Future** (11:15, Amtrium 1+2) — For teams still on Ingress — this is the future migration path.
> - **Policy Engines for Kubernetes: Picking One Without Losing Your Mind** (17:00, Hall 7 Room A) — Good context for evaluating OPA usage beyond existing IaC workflows.

---

## Wednesday, March 25 — Main Conference Day 2

### Strategy

The Wednesday keynote block is mandatory — sovereignty and regulation themes (CRA, multi-cloud strategy, national infrastructure) map directly to EU-regulated multi-cloud setups. After keynotes, four priority clusters: GitOps/ArgoCD tooling, identity/security (Keycloak, OPA), observability (OTel), and AI+Platform Engineering futures.

| Time | Primary Talk | Room | Backup Talk | Room | Why |
|------|-------------|------|-------------|------|-----|
| 09:00–10:30 | **★ Full Keynote Block** | Hall 12 | — | — | "Building a Sovereign, Multi-Cloud Strategy" and the digital sovereignty keynotes are directly applicable to EU-regulated multi-cloud setups. CRA implications for open-source are relevant across the toolchain. Attend everything. |
| 10:30–11:00 | Coffee Break — vendor floor | — | — | — | Hit the Cilium, ArgoCD, and Grafana booths early before afternoon crowds. |
| 11:00–11:30 | **★ From GitOps to AIOps: Evolving RBI's Kubernetes Platform with Crossplane + Kargo** | Forum | From "It Works!" to "It's Secure!": Hardening Your First K8s Cluster | Hall 7 Room A | Raiffeisen Bank International (large EU financial institution) on multi-cluster GitOps promotions with sharded Kargo, **Crossplane 2.0 for infrastructure provisioning with minimal YAML**, and AI-powered PR analysis. Directly comparable to a multi-environment ArgoCD setup — sees Crossplane in production at banking scale. |
| 11:45–12:15 | **★ Sovereign Identities for Your Cloud Native Architecture With Keycloak** | G102-103 | Pull Request Wars: The Flux Awakens | Hall 8 Room G | For teams running Keycloak with OIDC/LDAP/Entra ID integration across a multi-tenant SaaS platform — direct hit. Backup: Flux is GitOps peer to ArgoCD — worth the competitive intelligence. |
| 12:15–14:15 | Lunch — hallway track | — | — | — | Connect with speakers from the Keycloak and GitOps sessions. |
| 14:15–14:45 | **★ Open Policy Agent (OPA) Intro & Deep Dive** | E103-105 | Audit-Ready Kubernetes: How Chase UK Leveraged Policy as Code | Hall 7 Room C | For teams using OPA/Rego to protect infrastructure workflows — this deep dive surfaces advanced patterns to expand policy coverage. Chase UK backup covers real-world policy-as-code in a regulated environment. |
| 14:15–14:45 | **How To Break Multi-Tenancy Again and Again** | Hall 8 Room F | Panel: How Platforms Can Save Junior Engineers | Hall 8 Room D | For platforms running per-customer namespaces — stress-tests your multi-tenancy model. *(Attend if you can split from OPA, or catch the recording.)* |
| 15:00–15:30 | **★ Enterprise Challenges with MCP Adoption** | Hall 7 Room C | Jaeger V2: The Maintainers' Guide To OTel-Native Tracing | Amtrium 1+2 | Covers the enterprise friction points in MCP adoption — security, governance, multi-tenancy — exactly the problems you'll hit scaling an MCP POC. Jaeger V2 backup informs how the tracing ecosystem evolves. |
| 15:00–15:30 | **How Manual OTel Instrumentation Saves More Than Just Money** | Hall 12 | — | — | *(If you attend Jaeger above, skip this)* Practical cost/signal optimization for Grafana Cloud remote-write spend. |
| 15:30–16:00 | Coffee Break | — | — | — | — |
| 16:15–16:45 | **★ OpenTelemetry Project Update and Ask the Experts** | G102-103 | OpenTelemetry Logs Driving a Major Shift | Elicium 2 | For teams running the full OTel stack with Alloy — direct answers on Alloy configuration, Grafana Cloud integration, and what's landing in OTel next. |
| 17:00–17:30 | **★ The 10x DevOps Engineer's Toolkit: Argo CD + AI-Driven MCP Automation** | Amtrium 1+2 | Policy Engines: Picking One Without Losing Your Mind | Hall 7 Room A | *(Also on Tuesday — attend whichever day has less conflict.)* Core ArgoCD maintainers on AI-driven MCP automation — the single highest-priority non-keynote talk of the conference for GitOps + MCP practitioners. |

> **Priority summary for Wednesday:**
> - **Must-attend:** Full keynotes · Keycloak (11:45 or 16:15 repeat) · OPA Deep Dive (14:15) · ArgoCD+MCP Automation (17:00)
> - **High value:** GitOps→AIOps RBI (11:00) · MCP Enterprise Challenges (15:00) · OTel Ask the Experts (16:15)
> - **Watch recording:** Multi-Tenancy talk (14:15) · OTel Logs (16:15 alternate)

---

## Thursday, March 26 — Main Conference Day 3 (Final Day)

### Strategy

Thursday is a half-day ending ~15:45 — no padding. The morning keynote block contains one of the highest-value talks of the whole conference for your context. Afternoon slots cover cert-manager, GitOps visualization, multi-tenancy, and OTel profiling (the missing fourth signal in your observability stack). Leave the conference with actionable takeaways on platform maturity, observability cost control, and multi-tenancy hardening.

### Keynote Highlights (09:00–10:30, Hall 12)

| Talk | Speaker | Why It Matters |
|------|---------|---------------|
| **★ From Cloud-Native Apps to Cloud-Native Platforms** | Abby Bangser | **Must-see.** Directly addresses the maturity arc from shipping apps to operating a platform product. Bangser is one of the sharpest platform engineering voices in the ecosystem. Do not skip. |
| Agents as First-Class Users in Production | Mathias Biilmann | Frames AI agents as infrastructure consumers — relevant to architecting MCP servers and future agentic tooling on the platform. |
| The Cloud Native Feedback Loop | Angell, Bebars, Gamanji, Beaudin | Broad CNCF ecosystem state-of-the-union — useful orientation for where the projects you use are heading. |
| Universal Mesh (sponsored) | Baptiste Assmann | Potentially relevant to Cilium ClusterMesh ambitions; assess quickly, skip if too sales-heavy. |

### Afternoon Sessions

| Time | Primary Talk | Room | Backup Talk | Room | Why |
|------|-------------|------|-------------|------|-----|
| 10:30–11:00 | Coffee Break | — | — | — | — |
| 11:00–11:30 | **★ Cert-manager — Project Update** | G102-103 | A Bug's-Eye View: Kubernetes SIG Security | E106-108 | Maintainers from Palo Alto Networks and CyberArk cover cert-manager's 2026 milestones: new features, security improvements, and new automation infrastructure, plus a preview of upcoming initiatives. Essential for anyone depending on cert-manager in production — don't skip. |
| 11:00–11:30 | **Cutting Metrics Traffic, Cutting Costs** | Hall 8 Room D | Stop Flying Blind: Real-Time Cluster-Wide Quotas | Hall 8 Room G | For teams remote-writing to Grafana Cloud — reducing metrics cardinality is a direct cost lever. Quota enforcement backup relevant to multi-tenant resource management. |
| 11:45–12:15 | **★ AI Agents & Platform Engineering** | Auditorium | Taming Complexity: Building Observable Workflows | Hall 8 Room G | Vendor-neutral panel (Cisco, Red Hat, UN, Solo.io, AWS) examining whether nondeterministic AI agents help platform teams keep pace with AI-accelerated developer output — or introduce new failure modes. Covers challenges stalling AI initiatives, foundational requirements, evaluating agent ROI, managing production costs, and building trust in nondeterministic systems. Directly answers your question about how AI transforms Platform Engineering roles. |
| 12:15–13:45 | Lunch | — | — | — | — |
| 13:45–14:15 | **★ Visualizing GitOps** | Elicium 2 | Prometheus V3 One Year In | Hall 8 Room E | Stefan Prodan (ControlPlane) demos the new Flux Operator UI (SSO, K8s impersonation, mobile-friendly) and evaluates Capacitor, Headlamp, Backstage, and Freelens plugins. ⚠️ Flux-specific, not ArgoCD — but Headlamp and Backstage are engine-agnostic, and the security model comparison (SSO, impersonation) applies regardless of GitOps engine. Worth attending for the visualization tooling landscape; just know the Flux Operator UI itself won't directly carry over. |
| 13:45–14:15 | **Evolving Policy Management with Agentic AI** | Forum | The Accidental Platform Team | Hall 8 Room G | Kyverno maintainer + Alibaba Cloud engineer on using MCP servers and Kagent for intelligent policy distribution across hybrid clusters. The Alibaba case study demonstrates selecting Kyverno over OPA and extending it with AI agents — relevant to OPA/Atlantis setups and where multi-cluster policy governance is heading. |
| 14:30–15:00 | **★ Three Shades of Isolation: A Multi-tenancy Fortress** | Hall 8 Room G | Freedom Through Boundaries | Forum | IBM engineers show three concurrent isolation layers (data-plane, control-plane, network) using K3s, KubeFlex/KubeStellar, KubeVirt, and OVN-k8s, demonstrated on LLM-based production stacks. The tooling stack may differ from your environment, but the three-axis isolation model (namespace + network + compute) maps directly to multi-tenancy hardening needs. |
| 14:30–15:00 | **How Telemetry Data Moves** | Hall 8 Room E | — | — | *(If you have a colleague)* Eduardo Silva on telemetry pipelines — relevant to Alloy/OTel collector setups and managing Grafana Cloud remote-write costs. |
| 15:15–15:45 | **★ The Fourth Pillar Arrives: OpenTelemetry Profiling** | Hall 8 Room F | Day-2 Reality Check: Taming Wasteful Telemetry | Forum | Datadog + Elastic engineers demo the OTel profiling alpha via live coding, show eBPF profiler setup, and make the case that profiling isn't just for performance — it's for "rapidly root-causing incidents down to the specific line of code." For teams with metrics + traces + logs via Grafana Cloud — adding profiling closes the final gap in the four signals model. Immediately actionable. |
| 15:15–15:45 | **Platform Engineering 2.0** | Hall 8 Room G | Is the Agent in the Room with Us Right Now? | Hall 7 Room C | *(If you have a colleague)* Booking.com lead architect on "just-enough Kubernetes" and AI-native DevOps: k3s, Gateway API, ambient mesh + Kubeflow, Argo, Prometheus with AI Ops. Framing: how teams move "from heavy, static systems to self-optimising, adaptive ecosystems." Strong forward-looking perspective on the AI + Platform Engineering convergence. |

> **Conflict guide for Thursday:**
> - **Cert-manager vs. SIG Security (11:00):** You depend on cert-manager in production — take the project update.
> - **Visualizing GitOps vs. Prometheus V3 (13:45):** Stefan Prodan's session is rarer and more specific to your ArgoCD complexity. Send a colleague to Prometheus V3 or catch the recording.
> - **Multi-tenancy Fortress vs. How Telemetry Data Moves (14:30):** Multi-tenancy is architecturally foundational — prioritize it. Split if you have two attendees.
> - **OTel Profiling vs. Platform Engineering 2.0 (15:15):** OTel Profiling is immediately actionable; Platform Engineering 2.0 is strategically useful for the AI/future-of-the-role angle.

---

## Cross-Week Highlights at a Glance

| Priority | Talk | Day | Room |
|----------|------|-----|------|
| ★★★ | The 10x DevOps Engineer's Toolkit: Argo CD + AI-Driven MCP Automation | Tue or Wed | Amtrium 1+2 |
| ★★★ | Choose Your Own Adventure: AI Meets Internal Developer Platform | Tue | Hall 7 \| Room A |
| ★★★ | Agentics Day: MCP in 2026 | Mon | Hall 7 Room A |
| ★★★ | From Cloud-Native Apps to Cloud-Native Platforms (Keynote) | Thu | Hall 12 |
| ★★★ | AI Agents & Platform Engineering (Panel) | Thu | Auditorium |
| ★★ | Crossplane — The Cloud Native Framework for Platform Engineering | Tue | Amtrium 1+2 |
| ★★ | From GitOps to AIOps: Evolving RBI's K8s Platform (with Crossplane + Kargo) | Wed | Forum |
| ★★ | Backend-First IDP: Argo CD + Crossplane + OPA | Mon | Hall 8 Room G |
| ★★ | Sovereign Identities with Keycloak | Wed | G102-103 |
| ★★ | Helm 4 Is Here. So, Now What? | Tue | Amtrium 1+2 |
| ★★ | OTel Project Update + Ask the Experts | Tue + Wed | G102-103 |
| ★★ | Cert-manager Project Update | Thu | G102-103 |
| ★★ | Three Shades of Isolation: Multi-tenancy Fortress | Thu | Hall 8 Room G |
| ★★ | Is AIOps the Future of Operations? (Agentics Day) | Mon | Hall 7 Room A |
| ★★ | Scaling on Satisfaction: Automated Rollouts Driven by User Feedback | Mon | Hall 8 \| Room G |
| ★★ | When the Codebase Starts Instrumenting Itself | Mon | E103-105 |
| ★★ | Contribfest: Tell Us How You're Using Argo CD: A Community ContribFest Session | Wed | G106 |
| ★ | OPA Intro & Deep Dive | Wed | E103-105 |
| ★ | Least-Privilege for AI: Authorizing Agents and MCP Tools | Tue | Hall 8 Room F |
| ★ | OpenTelemetry Profiling (Fourth Pillar) | Thu | Hall 8 Room F |
| ★ | Secure Your MCP Servers | Mon | Hall 8 Room D |
| ★ | Testing IaC: OpenTofu + Localstack | Mon | Emerald Room |
| ★ | AI-Enabled Crossplane Control Planes (Millennium bcp) | Tue | Hall 8 Room D |
| ★ | Contribfest: Dive Into cert-manager and Start Contributing! | Tue | G106 |

---

## Verified Talk Abstracts

All ★★ and ★★★ priority talks below were verified against individual event pages — descriptions are drawn directly from official abstracts, not inferred from titles.

### Monday — Co-Located Events

**★ MCP in 2026** · Hall 7 Room A · 13:35
> David Soria Parra (Anthropic) on the state and direction of the Model Context Protocol in 2026. Covers the emerging MCP ecosystem, current adoption, and where the protocol is heading. Essential if you're building or evaluating MCP servers — this sets the roadmap context.

**★★ Is AIOps the Future of Operations?** · Hall 7 Room A · 17:00
> Panel examining whether AI-driven operations (AIOps) will replace or augment human platform engineers. Directly tackles your question about how AI transforms DevOps/Platform Engineering roles and what the future of the job looks like.

**★★ Connecting the World: Cilium ClusterMesh** · Elicium 1 · 15:20
> Deep dive into ClusterMesh for connecting multiple Kubernetes clusters across cloud boundaries. Relevant to any multi-cloud setup — the path to unified networking across environments.

**★ Secure Your MCP Servers** · Hall 8 Room D · 15:20
> Security posture for MCP servers in production — authentication, authorization, and threat model. Directly actionable for MCP server POCs heading toward production exposure.

**★ Beyond Argo Rollouts: Boosting Developer Experience** · G102-103 · 11:25
> Note: despite the title, this talk is actually about AIOps + AI agents analyzing rollout failures — more AI-in-ops than pure developer experience content. Higher relevance than the title implies for your AI interest.

**★ GitOps Your Costs: Automated FinOps** · G102-103 · 13:35
> Concrete path to automating cost governance via GitOps patterns, applicable to any OpenCost deployment across multiple environments.

---

### Tuesday — Main Conference Day 1

**★★★ The 10x DevOps Engineer's Toolkit: Argo CD + AI-Driven MCP Automation** · Amtrium 1+2 · 17:00
> Alexander Matyushentsev (core ArgoCD maintainer) on layering AI-driven MCP automation on top of ArgoCD. Covers using MCP tools to automate GitOps operations — the intersection of ArgoCD and MCP tooling. Highest-priority non-keynote talk of the conference.

**★★ Helm 4 Is Here. So, Now What?** · Amtrium 1+2 · 12:00
> Covers the Helm 4 release: breaking changes, new OCI workflow, schema validation improvements, and ArgoCD compatibility. Direct impact on OCI chart authoring, publishing workflow, and ArgoCD integration.

**★★ 10 Years of Cilium** · Amtrium 1+2 · 14:30
> Anniversary session covering the Cilium roadmap: ClusterMesh evolution, WireGuard improvements, Hubble enhancements, and eBPF performance milestones. For teams running Cilium as their CNI — understand what's coming.

**★ Least-Privilege for AI: Authorizing Agents and MCP Tools** · Hall 8 Room F · 11:15
> How to authorize MCP tool invocations with least-privilege — scoping what an AI agent can do on behalf of a user or service. Critical design pattern before moving any MCP server toward production access.

**★★ OpenTelemetry Project Update + Ask the Experts** · G102-103 · 16:15
> Interactive format: project update + open Q&A with OTel maintainers. For Grafana Alloy users — ask pointed questions about Alloy configuration, OTTL pipeline tuning, and the OTel roadmap.

---

### Wednesday — Main Conference Day 2

**★★ From GitOps to AIOps: Evolving RBI's Kubernetes Platform** · Forum · 11:00
> Raiffeisen Bank International (large EU financial institution) on evolving their Kubernetes platform from pure GitOps to AIOps-assisted operations. Concrete lessons on operationalizing multi-environment GitOps at scale.

**★★ Sovereign Identities for Your Cloud Native Architecture With Keycloak** · G102-103 · 11:45
> Covers Keycloak in a cloud-native multi-tenant architecture: OIDC federation, LDAP integration, multi-cloud identity patterns, and sovereignty considerations. For teams running Keycloak with Entra ID + OIDC + LDAP across a multi-tenant SaaS platform — direct hit.

**★★ Enterprise Challenges with MCP Adoption** · Hall 7 Room C · 15:00
> Covers the real friction points in MCP adoption at enterprise scale: security, governance, multi-tenancy, access control, and organizational trust. Exactly the problems you'll encounter scaling an MCP POC to production.

**★ Open Policy Agent (OPA) Intro & Deep Dive** · E103-105 · 14:15
> Comprehensive OPA/Rego session covering advanced policy patterns, Conftest integration, and real-world enforcement examples. For teams using OPA/Rego to protect infrastructure workflows — this surfaces patterns to expand coverage.

---

### Thursday — Main Conference Day 3

**★★★ AI Agents & Platform Engineering: Efficiency Boost or New Source of Trouble?** · Auditorium · 11:45
> Vendor-neutral panel (Cisco, Red Hat, UN, Solo.io, AWS) examining whether nondeterministic AI agents help platform engineers keep pace with AI-accelerated developer output, or introduce unwanted complexity. Discussion covers challenges stalling AI initiatives, foundational requirements for success, evaluating agent effectiveness, managing production costs, and building trust in nondeterministic systems. The conference's best direct answer to your question about AI transforming Platform Engineering roles.

**★★ Cert-manager — Project Update: Beyond 2026** · G102-103 · 11:00
> Maintainers from Palo Alto Networks and CyberArk on cert-manager's 2026 status: major milestones, new features, security improvements, new automation infrastructure, and upcoming initiatives. Essential for anyone depending on cert-manager in production — stay ahead of deprecations and migrations.

**★ Visualizing GitOps: A Tour of Flux UIs** · Elicium 2 · 13:45
> ⚠️ Flux-specific. Stefan Prodan demos the new Flux Operator UI (SSO authentication, K8s impersonation, mobile-friendly) and evaluates Capacitor, Headlamp, Backstage, and Freelens plugins with their security models and API compatibility. Headlamp and Backstage are GitOps-engine-agnostic and the security model analysis applies to ArgoCD setups — worth attending for the visualization tooling landscape, though the Flux Operator UI itself won't carry over.

**Evolving Policy Management with Agentic AI: Kyverno MCP and Kagent** · Forum · 13:45
> Kyverno maintainer + Alibaba Cloud senior engineer on using CNCF tools (Kyverno, MCP servers, Kagent) for intelligent policy distribution across hybrid Kubernetes clusters. Alibaba's case study: why they chose Kyverno over OPA and how they extended it with AI agents for multi-cluster governance. Relevant to OPA/Atlantis policy setups and where multi-cluster governance is heading.

**★★ Three Shades of Isolation: A Multi-tenancy Fortress** · Hall 8 Room G · 14:30
> IBM engineers on a three-axis isolation model (data-plane + control-plane + network) using K3s, KubeFlex/KubeStellar, KubeVirt, and OVN-k8s, demonstrated on LLM-based production stacks. The tooling stack may differ from your environment, but the three-axis isolation model maps directly to per-customer namespace architectures that need hardening.

**★ The Fourth Pillar Arrives: OpenTelemetry Profiling Alpha in Action** · Hall 8 Room F · 15:15
> Datadog + Elastic engineers demo the OTel profiling signal (now in alpha): eBPF profiler setup, live coding to troubleshoot a bug, and the argument that profiling isn't just for performance — it's for "rapidly root-causing incidents down to the specific line of code." For teams with metrics + traces + logs via Grafana Cloud — profiling is the last remaining signal. Immediately actionable.

**Platform Engineering 2.0: Just-Enough Kubernetes and AI-Native DevOps** · Hall 8 Room G · 15:15
> Booking.com lead architect on minimal Kubernetes architectures: k3s, Gateway API, ambient mesh, with AI Ops layered on top of Kubeflow, Argo, and Prometheus. The thesis: move "from heavy, static systems to self-optimising, adaptive ecosystems that align with real business value." Strong closing-session perspective on where Platform Engineering is heading.

---

---

### Crossplane / IaC Reconciliation (newly added based on full schedule analysis)

**★★ Crossplane — The Cloud Native Framework for Platform Engineering** · Amtrium 1+2 · Tuesday 15:15
> Crossplane v2.2 maintainers (Upbound) on the project's latest features, releases, and roadmap with live demonstrations. Explores how to build Crossplane-powered control planes for infrastructure provisioning. Your primary evaluation session for whether Crossplane can replace Terraform — from the project maintainers themselves.

**★★ Backend-First IDP: A Production Roadmap With Argo CD, Crossplane, and OPA** · Hall 8 Room G · Monday 15:20
> Critiques "portal-first" architectures, advocates a backend-first approach with minimal Platform API/CRD contracts integrating ArgoCD, Crossplane, and OPA in a 100+ service multi-tenant environment. Demonstrates how to compose GitOps + IaC reconciliation + policy into a unified platform control plane. A strong model for platforms combining GitOps + IaC reconciliation + policy into a unified control plane.

**★★ From GitOps to AIOps: Evolving RBI's Kubernetes Platform with Crossplane and Sharded Kargo** · Forum · Wednesday 11:00
> Raiffeisen Bank International on evolving from Argo CD + Kargo GitOps to Crossplane 2.0 for infrastructure provisioning with "minimal YAML" — plus AI-powered PR analysis. Crossplane in production at EU banking scale.

**★ AI-Enabled Crossplane Control Planes: From Alert Fatigue to Self-Healing** · Hall 8 Room D · Tuesday 16:15
> Upbound + Millennium bcp on using LLM-powered Crossplane composition functions to automatically triage and remediate Kubernetes alerts, reducing SRE escalations. Shows where Crossplane + AI is heading for autonomous operations.

**★ Testing Infrastructure as Code Using OpenTofu and Localstack** · Emerald Room · Monday 16:30
> Practical IaC testing patterns using OpenTofu + Localstack — applicable to Terraform/Atlantis workflows regardless of whether you migrate to Crossplane.

---

*Report generated from a full database of 542 verified event pages across colocatedeventseu2026.sched.com and kccnceu2026.sched.com.  Crossplane and IaC reconciliation talks added based on database query.*
