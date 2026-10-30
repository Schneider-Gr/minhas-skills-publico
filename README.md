# Minhas skills

Inventário das 293 skills globais que uso no Claude Code, com o repositório de origem de cada uma e o motivo de uso.

As skills ficam em `~/.claude/skills`. Este repositório guarda só a lista e os endereços, não o conteúdo delas: para reinstalar em outro computador, use o repositório de origem (ou o backup, nas que não têm origem registrada).

**Como a origem foi identificada:** registro do instalador de skills (`~/.agents/.skill-lock.json`), `git remote` da pasta, ou o conteúdo da skill (pacote gstack). As que aparecem como *origem não registrada* foram copiadas manualmente ou criadas por mim; nelas o link citado no SKILL.md, quando há, é de uma ferramenta mencionada e não necessariamente da origem.

6 skills internas, ligadas a clientes e sem repositório público, ficam fora desta lista.

Arquivos: [`skills.csv`](skills.csv) e [`skills-globais-origem.xlsx`](skills-globais-origem.xlsx).

## Por que uso cada grupo

### Anúncios pagos (34)

Montar, auditar e otimizar campanhas. Uso na captação de vendedores para o meu negócio no Meta Ads e nos anúncios de clientes: plano de mídia, criativos, orçamento, testes A/B e leitura de resultado.

| Skill | Repositório | Para que serve |
|---|---|---|
| `ads` | https://github.com/agricidaniel/claude-ads | Operate professional paid advertising across Google, Meta, YouTube, LinkedIn, TikTok, Microsoft, Apple, Amazon, Reddit, Pinterest, Snapchat, and X. Use for acco… |
| `ads-amazon` | https://github.com/agricidaniel/claude-ads | Audit Amazon Ads profiles, regions, Sponsored Products, Sponsored Brands, Sponsored Display, DSP, portfolios, targeting, search terms, retail readiness, creativ… |
| `ads-apple` | https://github.com/agricidaniel/claude-ads | Audit Apple Ads measurement, AdServices and AdAttributionKit, campaign and keyword structure, Search Match, App Store placements, custom product pages, bidding,… |
| `ads-attribution` | https://github.com/agricidaniel/claude-ads | Audit cross-platform attribution, conversion definitions, reporting windows, GA4, AdServices and AdAttributionKit, MMPs, browser and server events, offline conv… |
| `ads-audit` | https://github.com/agricidaniel/claude-ads | Run a source-grounded paid-advertising audit for one or more of Google, Meta, YouTube, LinkedIn, TikTok, Microsoft, Apple, Amazon, Reddit, Pinterest, Snapchat, … |
| `ads-budget` | https://github.com/agricidaniel/claude-ads | Plan and review paid-media budgets, bidding, pacing, marginal return, forecasts, CPA, ROAS, MER, LTV:CAC, constraints, and allocation across supported platforms… |
| `ads-competitor` | https://github.com/agricidaniel/claude-ads | Research competitor paid-ad presence, messaging, creative, formats, landing pages, keyword and auction signals, transparent ad libraries, and strategic gaps acr… |
| `ads-create` | https://github.com/agricidaniel/claude-ads | Create source-grounded paid-ad campaign concepts, messaging, copy, creative briefs, and production plans from a validated brand profile, campaign objective, pla… |
| `ads-creative` | https://github.com/agricidaniel/claude-ads | Audit paid-ad copy, images, video, hooks, concepts, format coverage, platform-native fit, message match, creative fatigue, accessibility, and policy across supp… |
| `ads-dna` | https://github.com/agricidaniel/claude-ads | Extract a public-safe brand and offer profile for paid advertising from an authorized website and operator input. Triggers on: brand DNA, brand profile, brand i… |
| `ads-generate` | https://github.com/agricidaniel/claude-ads | Generate paid-ad image assets from a validated creative brief and brand profile using an explicitly configured image provider. Triggers on: generate ads, genera… |
| `ads-google` | https://github.com/agricidaniel/claude-ads | Audit Google Ads measurement, Search, Shopping, Performance Max, Demand Gen, YouTube-linked inventory, keywords and search terms, negative-keyword generation or… |
| `ads-landing` | https://github.com/agricidaniel/claude-ads | Audit paid-ad landing pages for message match, mobile experience, performance, accessibility, trust, forms, consent, tracking, security, and conversion friction… |
| `ads-launch` | https://github.com/agricidaniel/claude-ads | Draft or explicitly apply a paid-ad campaign launch through Claude Ads capability-gated adapters. Use for campaign creation, launch plans, publishing ads, activ… |
| `ads-linkedin` | https://github.com/agricidaniel/claude-ads | Audit LinkedIn Ads measurement, Insight Tag and conversions, professional audiences, lead generation, ABM, creative, bidding, budgets, pacing, automation, and p… |
| `ads-math` | https://github.com/agricidaniel/claude-ads | Calculate and model paid-media CPA, CPL, CPC, CPM, ROAS, MER, break-even targets, contribution margin, LTV:CAC, impression-share opportunity, budgets, forecasts… |
| `ads-meta` | https://github.com/agricidaniel/claude-ads | Audit Meta Ads measurement, Pixel and Conversions API, attribution, Facebook and Instagram creative, audiences, placements, automation, budgets, account structu… |
| `ads-microsoft` | https://github.com/agricidaniel/claude-ads | Audit Microsoft Advertising measurement, UET, search and audience campaigns, Google imports, syndication, keywords, creative, bidding, budgets, Copilot inventor… |
| `ads-monitor` | https://github.com/agricidaniel/claude-ads | Monitor paid-ad account pacing, delivery, performance, creative fatigue, tracking, policy, and data quality across supported platforms. Use for daily or weekly … |
| `ads-optimize` | https://github.com/agricidaniel/claude-ads | Diagnose and draft or explicitly apply paid-ad optimizations using evidence, financial constraints, experiments, and capability-gated adapters. Use for campaign… |
| `ads-photoshoot` | https://github.com/agricidaniel/claude-ads | Generate rights-cleared paid-ad product photography variants from an authorized source image and validated brand profile. Triggers on: product photo, product ph… |
| `ads-pinterest` | https://github.com/agricidaniel/claude-ads | Audit Pinterest Ads measurement, Pinterest Tag and Conversions API, catalog and shopping readiness, visual creative, audiences, Performance+ intent, budgets, br… |
| `ads-plan` | https://github.com/agricidaniel/claude-ads | Create a professional paid-advertising strategy covering objectives, economics, platform selection, campaign architecture, audiences, budget, creative, measurem… |
| `ads-reddit` | https://github.com/agricidaniel/claude-ads | Audit Reddit Ads measurement, campaign structure, community and interest targeting, creative-native fit, catalog advertising, budgets, brand safety, and reporti… |
| `ads-report` | https://github.com/agricidaniel/claude-ads | Render Markdown, HTML, or PDF paid-advertising reports from a validated Claude Ads JSON run bundle. Use for ads report, client report, audit PDF, executive audi… |
| `ads-research` | https://github.com/agricidaniel/claude-ads | Refresh Claude Ads platform, API, policy, regulation, benchmark, issue, pull-request, fork, and repository evidence. Use for ads research refresh, expired refre… |
| `ads-server-side-tracking` | https://github.com/agricidaniel/claude-ads | Audit server-side paid-media measurement including server-side tag management, platform conversion APIs, event taxonomy, browser/server deduplication, consent, … |
| `ads-setup` | https://github.com/agricidaniel/claude-ads | Set up a paid-media client, brand, account, data-source, privacy, and mutation-guardrail profile for Claude Ads. Use for onboarding, initial configuration, bran… |
| `ads-snapchat` | https://github.com/agricidaniel/claude-ads | Audit Snapchat Ads measurement, Snap Pixel and Conversions API, mobile and app campaigns, creative, AR and catalog formats, audiences, budgets, brand safety, an… |
| `ads-test` | https://github.com/agricidaniel/claude-ads | Design and evaluate paid-ad experiments with hypotheses, randomization units, sample-size and duration assumptions, guardrails, platform experiment tools, analy… |
| `ads-tiktok` | https://github.com/agricidaniel/claude-ads | Audit TikTok Ads measurement, Pixel and Events API, mobile-first creative, audiences, Smart+, Shop and commerce campaigns, bidding, budgets, pacing, attribution… |
| `ads-validate` | https://github.com/agricidaniel/claude-ads | Validate Claude Ads contracts, scoring inputs, run bundles, capabilities, source freshness, safety, installation, uninstall, or release readiness. Use for ads v… |
| `ads-x` | https://github.com/agricidaniel/claude-ads | Audit X Ads measurement, X Pixel and Conversions API, campaign objectives, keyword and conversation targeting, creative, budgets, brand safety, app measurement,… |
| `ads-youtube` | https://github.com/agricidaniel/claude-ads | Audit YouTube Ads campaign setup, video and Demand Gen inventory, Shorts, in-stream, CTV, creative, audiences, brand safety, bidding, and measurement. Use for Y… |

### Fluxo de engenharia (gstack) (32)

O ciclo de trabalho do código dos meus produtos: planejar (office-hours, plan-*-review), investigar bug, revisar, testar no navegador (qa, browse), entregar (ship, land-and-deploy) e travas de segurança (careful, freeze, guard) para não estragar produção.

| Skill | Repositório | Para que serve |
|---|---|---|
| `autoplan` | https://github.com/garrytan/gstack | / Auto-review pipeline — reads the full CEO, design, and eng review skills from disk and runs them sequentially with auto-decisions using 6 decision principles.… |
| `benchmark` | https://github.com/garrytan/gstack | / Performance regression detection using the browse daemon. Establishes baselines for page load times, Core Web Vitals, and resource sizes. Compares before/afte… |
| `browse` | https://github.com/garrytan/gstack | / Fast headless browser for QA testing and site dogfooding. Navigate any URL, interact with elements, verify page state, diff before/after actions, take annotat… |
| `canary` | https://github.com/garrytan/gstack | / Post-deploy canary monitoring. Watches the live app for console errors, performance regressions, and page failures using the browse daemon. Takes periodic scr… |
| `careful` | https://github.com/garrytan/gstack | / Safety guardrails for destructive commands. Warns before rm -rf, DROP TABLE, force-push, git reset --hard, kubectl delete, and similar destructive operations.… |
| `codex` | https://github.com/garrytan/gstack | / OpenAI Codex CLI wrapper — three modes. Code review: independent diff review via codex review with pass/fail gate. Challenge: adversarial mode that tries to b… |
| `connect-chrome` | https://github.com/garrytan/gstack | / Launch real Chrome controlled by gstack with the Side Panel extension auto-loaded. One command: connects Claude to a visible Chrome window where you can watch… |
| `cso` | https://github.com/garrytan/gstack | / Chief Security Officer mode. Infrastructure-first security audit: secrets archaeology, dependency supply chain, CI/CD pipeline security, LLM/AI security, skil… |
| `design-consultation` | https://github.com/garrytan/gstack | / Design consultation: understands your product, researches the landscape, proposes a complete design system (aesthetic, typography, color, layout, spacing, mot… |
| `design-html` | https://github.com/garrytan/gstack | / Design finalization: takes an approved AI mockup from /design-shotgun and generates production-quality Pretext-native HTML/CSS. Text actually reflows, heights… |
| `design-review` | https://github.com/garrytan/gstack | / Designer's eye QA: finds visual inconsistency, spacing issues, hierarchy problems, AI slop patterns, and slow interactions — then fixes them. Iteratively fixe… |
| `design-shotgun` | https://github.com/garrytan/gstack | / Design shotgun: generate multiple AI design variants, open a comparison board, collect structured feedback, and iterate. Standalone design exploration you can… |
| `document-release` | https://github.com/garrytan/gstack | / Post-ship documentation update. Reads all project docs, cross-references the diff, updates README/ARCHITECTURE/CONTRIBUTING/CLAUDE.md to match what shipped, p… |
| `freeze` | https://github.com/garrytan/gstack | / Restrict file edits to a specific directory for the session. Blocks Edit and Write outside the allowed path. Use when debugging to prevent accidentally fixing… |
| `gstack` | https://github.com/garrytan/gstack |  |
| `gstack-upgrade` | https://github.com/garrytan/gstack | / Upgrade gstack to the latest version. Detects global vs vendored install, runs the upgrade, and shows what's new. Use when asked to upgrade gstack, update gst… |
| `guard` | https://github.com/garrytan/gstack | / Full safety mode: destructive command warnings + directory-scoped edits. Combines /careful (warns before rm -rf, DROP TABLE, force-push, etc.) with /freeze (b… |
| `investigate` | https://github.com/garrytan/gstack | / Systematic debugging with root cause investigation. Four phases: investigate, analyze, hypothesize, implement. Iron Law: no fixes without root cause. Use when… |
| `land-and-deploy` | https://github.com/garrytan/gstack | / Land and deploy workflow. Merges the PR, waits for CI and deploy, verifies production health via canary checks. Takes over after /ship creates the PR. Use whe… |
| `learn` | https://github.com/garrytan/gstack | / Manage project learnings. Review, search, prune, and export what gstack has learned across sessions. Use when asked to what have we learned, show learnings, p… |
| `office-hours` | https://github.com/garrytan/gstack | / YC Office Hours — two modes. Startup mode: six forcing questions that expose demand reality, status quo, desperate specificity, narrowest wedge, observation, … |
| `plan-ceo-review` | https://github.com/garrytan/gstack | / CEO/founder-mode plan review. Rethink the problem, find the 10-star product, challenge premises, expand scope when it creates a better product. Four modes: SC… |
| `plan-design-review` | https://github.com/garrytan/gstack | / Designer's eye plan review — interactive, like CEO and Eng review. Rates each design dimension 0-10, explains what would make it a 10, then fixes the plan to … |
| `plan-eng-review` | https://github.com/garrytan/gstack | / Eng manager-mode plan review. Lock in the execution plan — architecture, data flow, diagrams, edge cases, test coverage, performance. Walks through issues int… |
| `qa` | https://github.com/garrytan/gstack | / Systematically QA test a web application and fix bugs found. Runs QA testing, then iteratively fixes bugs in source code, committing each fix atomically and r… |
| `qa-only` | https://github.com/garrytan/gstack | / Report-only QA testing. Systematically tests a web application and produces a structured report with health score, screenshots, and repro steps — but never fi… |
| `retro` | https://github.com/garrytan/gstack | / Weekly engineering retrospective. Analyzes commit history, work patterns, and code quality metrics with persistent history and trend tracking. Team-aware: bre… |
| `review` | https://github.com/garrytan/gstack | / Pre-landing PR review. Analyzes diff against the base branch for SQL safety, LLM trust boundary violations, conditional side effects, and other structural iss… |
| `setup-browser-cookies` | https://github.com/garrytan/gstack | / Import cookies from your real Chromium browser into the headless browse session. Opens an interactive picker UI where you select which cookie domains to impor… |
| `setup-deploy` | https://github.com/garrytan/gstack | / Configure deployment settings for /land-and-deploy. Detects your deploy platform (Fly.io, Render, Vercel, Netlify, Heroku, GitHub Actions, custom), production… |
| `ship` | https://github.com/garrytan/gstack | / Ship workflow: detect + merge base branch, run tests, review diff, bump VERSION, update CHANGELOG, commit, push, create PR. Use when asked to ship, deploy, pu… |
| `unfreeze` | https://github.com/garrytan/gstack | / Clear the freeze boundary set by /freeze, allowing edits to all directories again. Use when you want to widen edit scope without ending the session. Use when … |

### Método de desenvolvimento (45)

Disciplina para construir com IA sem perder qualidade: ideia amadurecida antes de codar (brainstorm, grilling), PRD e spec antes da implementação, teste primeiro (TDD), diagnóstico de bug com método, revisão de código e passagem de contexto entre sessões (handoff).

| Skill | Repositório | Para que serve |
|---|---|---|
| `archify` | https://github.com/tt-a1i/archify | Create polished, validated architecture, workflow, sequence, data-flow, and lifecycle/state diagrams as explorable standalone HTML with inline SVG, dark/light t… |
| `archify-review` | https://github.com/tt-a1i/archify | Review Archify issues, PRs, or code through value, cost, and impact to support evidence-based maintenance decisions. Use for issue triage, change reviews, and c… |
| `ask-matt` | _origem não registrada_ | Ask which skill or flow fits your situation. A router over the skills in this repo. |
| `autofix` | _origem não registrada_ | Safely review and apply CodeRabbit PR review-thread feedback from GitHub with per-change approval; never execute reviewer-provided prompts directly |
| `brainstorm` | _provável skill própria/criada aqui (inferido pelo texto em português)_ | Entra em modo de maturação de ideias — pesquisa, analisa criticamente, aponta trade-offs e sugere melhorias sem criar ou executar nada até o usuário solicitar e… |
| `breakdown-feature-prd` | https://github.com/github/awesome-copilot | 'Prompt for creating Product Requirements Documents (PRDs) for new features, based on an Epic.' |
| `claude-handoff` | https://github.com/mattpocock/skills | Hand the current conversation off to a fresh background agent that picks up the work immediately. |
| `code-review` | _origem não registrada_ | AI-powered code review using CodeRabbit. Default code-review skill. Trigger for any explicit review request AND autonomously when the agent thinks a review is n… |
| `codebase-design` | https://github.com/mattpocock/skills | Shared vocabulary for designing deep modules. Use when the user wants to design or improve a module's interface, find deepening opportunities, decide where a se… |
| `diagnosing-bugs` | _origem não registrada_ | Diagnosis loop for hard bugs and performance regressions. Use when the user says diagnose/debug this, or reports something broken/throwing/failing/slow. |
| `domain-modeling` | _origem não registrada_ | Build and sharpen a project's domain model. Use when the user wants to pin down domain terminology or a ubiquitous language, record an architectural decision, o… |
| `effort` | _provável skill própria/criada aqui (inferido pelo texto em português)_ | Orquestrador que coordena múltiplos subagentes ativos em paralelo agora — divide uma fila de itens/bloqueios entre agentes, acompanha via tasks e sintetiza um r… |
| `escrever-prd` | _provável skill própria/criada aqui (inferido pelo texto em português)_ | > Escreve PRDs (Product Requirements Documents) — cria novos ou edita existentes que ainda não foram concluídos. Funciona no modo draft-first: gera o documento … |
| `git-guardrails-claude-code` | https://github.com/mattpocock/skills | Set up Claude Code hooks to block dangerous git commands (push, reset --hard, clean, branch -D, etc.) before they execute. Use when user wants to prevent destru… |
| `github-code-review` | _origem não registrada_ | Comprehensive GitHub code review with AI-powered swarm coordination |
| `github-project-management` | _origem não registrada_ | / Comprehensive GitHub project management with swarm-coordinated issue tracking, project board automation, and sprint planning |
| `grill-me` | https://github.com/mattpocock/skills | A relentless interview to sharpen a plan or design. |
| `grill-with-docs` | _origem não registrada_ | A relentless interview to sharpen a plan or design, which also creates docs (ADR's and glossary) as we go. |
| `grilling` | https://github.com/mattpocock/skills | Grill the user relentlessly about a plan, decision, or idea. Use when the user wants to stress-test their thinking, or uses any 'grill' trigger phrases. |
| `handoff` | https://github.com/mattpocock/skills | Compact the current conversation into a handoff document for another agent to pick up. |
| `hooks-automation` | _origem não registrada_ | Automated coordination, formatting, and learning from Claude Code operations using intelligent hooks with MCP integration. Includes pre/post task hooks, session… |
| `implement` | _origem não registrada_ | Implement a piece of work based on a spec or set of tickets. |
| `improve-codebase-architecture` | https://github.com/mattpocock/skills | Scan a codebase for deepening opportunities, present them as a visual HTML report, then grill through whichever one you pick. |
| `loop-guardrail` | _provável skill própria/criada aqui (inferido pelo texto em português)_ | Executa uma tarefa como loop de subagentes com guardrail — gerador, validador, fix, teste e gate, rodando sozinho ate um criterio de parada programado. Use quan… |
| `mp-code-review` | _origem não registrada_ | Review the changes since a fixed point (commit, branch, tag, or merge-base) along two axes — Standards (does the code follow this repo's documented coding stand… |
| `pair-programming` | _origem não registrada_ | AI-assisted pair programming with multiple modes (driver/navigator/switch), real-time verification, quality monitoring, and comprehensive testing. Supports TDD,… |
| `pre-mortem` | _origem não registrada_ | > Pre-mortem risk analysis expert that classifies risks as Tigers, Paper Tigers, and Elephants to surface launch-blocking issues before they happen. |
| `prototype` | https://github.com/mattpocock/skills | Build a throwaway prototype to answer a design question. Use when the user wants to sanity-check whether a state model or logic feels right, or explore what a U… |
| `resolving-merge-conflicts` | https://github.com/mattpocock/skills | Use when you need to resolve an in-progress git merge/rebase conflict. |
| `security-protocols` | _origem não registrada_ | Use when executing commands, modifying files, reading sensitive data (.env, keys), or integrating external data sources - prevents prompt injection, code inject… |
| `security-review` | https://github.com/getsentry/skills | Security code review for vulnerabilities. Use when asked to security review, find vulnerabilities, check for security issues, audit security, OWASP review, or r… |
| `security-threat-model` | https://github.com/openai/skills | Repository-grounded threat modeling that enumerates trust boundaries, assets, attacker capabilities, abuse paths, and mitigations, and writes a concise Markdown… |
| `setup-matt-pocock-skills` | https://github.com/mattpocock/skills | Configure this repo for the engineering skills — set up its issue tracker, triage label vocabulary, and domain doc layout. Run once before first use of the othe… |
| `superpowers` | _origem não registrada_ |  |
| `synced` | _origem não registrada_ |  |
| `tdd` | https://github.com/mattpocock/skills | Test-driven development. Use when the user wants to build features or fix bugs test-first, mentions red-green-refactor, or wants integration tests. |
| `to-spec` | _origem não registrada_ | Turn the current conversation into a spec and publish it to the project issue tracker — no interview, just synthesis of what you've already discussed. |
| `to-tickets` | _origem não registrada_ | Break a plan, spec, or the current conversation into a set of tracer-bullet tickets, each declaring its blocking edges, published to the configured tracker — ed… |
| `trabalho-em-loop` | _provável skill própria/criada aqui (inferido pelo texto em português)_ | Converter tarefas de prompt único em execução contínua — /loop, agendamento recorrente, background e workflows. Use quando o usuário pedir para monitorar algo, … |
| `triage` | _origem não registrada_ | Move issues and external PRs through a state machine of triage roles — categorise, verify, grill if needed, and write agent-ready briefs. |
| `verification-quality` | _origem não registrada_ | / Comprehensive truth scoring, code quality verification, and automatic rollback system with 0.95 accuracy threshold for ensuring high-quality agent outputs and… |
| `vibecoding` | _provável skill própria/criada aqui (inferido pelo texto em português)_ | Use para construir features, sistemas ou módulos que tocam múltiplas camadas (UI + API + banco + auth) de ponta a ponta — do zero, refatoração cross-layer, ou q… |
| `vibecoding-senior-protocol` | _origem não registrada_ | Use when working on code, features, or technical tasks with vibe coding principles - emphasizes transparent planning, surgical modifications, and technical alig… |
| `vibecoding-workspace` | _origem não registrada_ |  |
| `wayfinder` | _origem não registrada_ | Plan a huge chunk of work — more than one agent session can hold — as a shared map of decision tickets on your issue tracker, and resolve them one at a time unt… |

### Segurança (44)

O marketplace mexe com dinheiro (pagamentos, repasse, comissão) e dados de clientes. Uso estas skills para testar RLS e controle de acesso, JWT/OAuth, XSS, CORS, segredos vazados, pacotes maliciosos e prompt injection nos agentes, sempre em teste autorizado.

| Skill | Repositório | Para que serve |
|---|---|---|
| `analyzing-email-headers-for-phishing-investigation` | _pacote de cibersegurança_ | Parse and analyze email headers to trace the origin of phishing emails, verify sender authenticity, and identify spoofing through SPF, DKIM, and DMARC validatio… |
| `analyzing-web-server-logs-for-intrusion` | _pacote de cibersegurança_ | Parse Apache and Nginx access logs to detect SQL injection attempts, local file inclusion, directory traversal, web scanner fingerprints, and brute-force patter… |
| `auditing-mcp-servers-for-tool-poisoning` | _pacote de cibersegurança_ | Scan Model Context Protocol servers and tool metadata for poisoning, SSRF, and unauthenticated exposure. |
| `building-incident-response-playbook` | _pacote de cibersegurança_ | 'Designs and documents structured incident response playbooks that define step-by-step procedures for specific incident types aligned with NIST SP 800-61r3 and … |
| `defending-llms-with-guardrails` | _pacote de cibersegurança_ | Deploy Llama Guard, NeMo Guardrails, and LLM Guard input/output scanners as runtime defenses. |
| `detecting-ai-model-prompt-injection-attacks` | _pacote de cibersegurança_ | 'Detects prompt injection attacks targeting LLM-based applications using a multi-layered defense combining regex pattern matching for known attack signatures, h… |
| `detecting-aws-credential-exposure-with-trufflehog` | _pacote de cibersegurança_ | 'Detecting exposed AWS credentials in source code repositories, CI/CD pipelines, and configuration files using TruffleHog, git-secrets, and AWS-native detection… |
| `detecting-business-email-compromise` | _pacote de cibersegurança_ | Business Email Compromise (BEC) is a sophisticated fraud scheme where attackers impersonate executives, vendors, or trusted partners to trick employees into tra… |
| `detecting-dependency-confusion` | _pacote de cibersegurança_ | Detect and prevent public-over-private name resolution in npm, PyPI, and Maven. |
| `detecting-indirect-prompt-injection` | _pacote de cibersegurança_ | Detect and defend against prompt injection hidden in documents, web pages, and images consumed by an agent. |
| `detecting-malicious-npm-packages` | _pacote de cibersegurança_ | Triage npm packages for install-script malware, exfiltration, and worming behavior. |
| `detecting-oauth-token-theft` | _pacote de cibersegurança_ | 'Detects and responds to OAuth token theft and replay attacks in cloud environments, focusing on Microsoft Entra ID (Azure AD) token protection, conditional acc… |
| `detecting-suspicious-oauth-application-consent` | _pacote de cibersegurança_ | Detect risky OAuth application consent grants in Azure AD / Microsoft Entra ID using Microsoft Graph API, audit logs, and permission analysis to identify illici… |
| `detecting-typosquatting-packages-in-npm-pypi` | _pacote de cibersegurança_ | 'Detects typosquatting attacks in npm and PyPI package registries by analyzing package name similarity using Levenshtein distance and other string metrics, exam… |
| `generating-and-analyzing-sboms` | _pacote de cibersegurança_ | Produce and ingest CycloneDX and SPDX SBOMs and correlate them to vulnerability intelligence. |
| `implementing-api-key-security-controls` | _pacote de cibersegurança_ | 'Implements secure API key generation, storage, rotation, and revocation controls to protect API authentication credentials from leakage, brute force, and abuse… |
| `implementing-api-rate-limiting-and-throttling` | _pacote de cibersegurança_ | 'Implements API rate limiting and throttling controls using token bucket, sliding window, and fixed window algorithms to protect against brute force attacks, cr… |
| `implementing-devsecops-security-scanning` | _pacote de cibersegurança_ | 'Integrates Static Application Security Testing (SAST), Dynamic Application Security Testing (DAST), and Software Composition Analysis (SCA) into CI/CD pipeline… |
| `implementing-dmarc-dkim-spf-email-security` | _pacote de cibersegurança_ | SPF, DKIM, and DMARC form the three pillars of email authentication. Together they prevent domain spoofing, validate message integrity, and define policies for … |
| `implementing-llm-guardrails-for-security` | _pacote de cibersegurança_ | 'Implements input and output validation guardrails for LLM-powered applications to prevent prompt injection, data leakage, toxic content generation, and halluci… |
| `implementing-secret-scanning-with-gitleaks` | _pacote de cibersegurança_ | 'This skill covers implementing Gitleaks for detecting and preventing hardcoded secrets in git repositories. It addresses configuring pre-commit hooks, CI/CD pi… |
| `implementing-secrets-management-with-vault` | _pacote de cibersegurança_ | 'This skill covers deploying HashiCorp Vault for centralized secrets management across cloud environments, including dynamic secret generation for databases and… |
| `implementing-secrets-scanning-in-ci-cd` | _pacote de cibersegurança_ | Integrate gitleaks and trufflehog into CI/CD pipelines to detect leaked secrets before deployment |
| `investigating-phishing-email-incident` | _pacote de cibersegurança_ | 'Investigates phishing email incidents from initial user report through header analysis, URL/attachment detonation, impacted user identification, and containmen… |
| `performing-security-headers-audit` | _pacote de cibersegurança_ | Auditing HTTP security headers including CSP, HSTS, X-Frame-Options, and cookie attributes to identify missing or misconfigured browser-level protections. |
| `performing-web-application-penetration-test` | _pacote de cibersegurança_ | 'Performs systematic security testing of web applications following the OWASP Web Security Testing Guide (WSTG) methodology to identify vulnerabilities in authe… |
| `securing-agentic-ai-tool-invocation` | _pacote de cibersegurança_ | Apply least-privilege tool allowlisting, identity binding, and human-in-the-loop controls for agent tool calls. |
| `securing-aws-iam-permissions` | _pacote de cibersegurança_ | 'This skill guides practitioners through hardening AWS Identity and Access Management configurations to enforce least privilege access across cloud accounts. It… |
| `securing-github-actions-workflows` | _pacote de cibersegurança_ | 'This skill covers hardening GitHub Actions workflows against supply chain attacks, credential theft, and privilege escalation. It addresses pinning actions to … |
| `testing-api-authentication-weaknesses` | _pacote de cibersegurança_ | 'Tests API authentication mechanisms for weaknesses including broken token validation, missing authentication on endpoints, weak password policies, credential s… |
| `testing-api-for-broken-object-level-authorization` | _pacote de cibersegurança_ | 'Tests REST and GraphQL APIs for Broken Object Level Authorization (BOLA/IDOR) vulnerabilities where an authenticated user can access or modify resources belong… |
| `testing-api-for-mass-assignment-vulnerability` | _pacote de cibersegurança_ | 'Tests APIs for mass assignment (auto-binding) vulnerabilities where clients can modify object properties they should not have access to by including additional… |
| `testing-api-security-with-owasp-top-10` | _pacote de cibersegurança_ | Systematically assessing REST and GraphQL API endpoints against the OWASP API Security Top 10 risks using automated and manual testing techniques. |
| `testing-cors-misconfiguration` | _pacote de cibersegurança_ | Identifying and exploiting Cross-Origin Resource Sharing misconfigurations that allow unauthorized cross-domain data access and credential theft during security… |
| `testing-for-broken-access-control` | _pacote de cibersegurança_ | Systematically testing web applications for broken access control vulnerabilities including privilege escalation, missing function-level checks, and insecure di… |
| `testing-for-json-web-token-vulnerabilities` | _pacote de cibersegurança_ | Test JWT implementations for critical vulnerabilities including algorithm confusion, none algorithm bypass, kid parameter injection, and weak secret exploitatio… |
| `testing-for-open-redirect-vulnerabilities` | _pacote de cibersegurança_ | Identify and test open redirect vulnerabilities in web applications by analyzing URL redirection parameters, bypass techniques, and exploitation chains for phis… |
| `testing-for-sensitive-data-exposure` | _pacote de cibersegurança_ | Identifying sensitive data exposure vulnerabilities including API key leakage, PII in responses, insecure storage, and unprotected data transmission during secu… |
| `testing-for-system-prompt-leakage` | _pacote de cibersegurança_ | Extract and defend system prompts plus embedded secrets and routing logic. |
| `testing-for-xss-vulnerabilities` | _pacote de cibersegurança_ | 'Tests web applications for Cross-Site Scripting (XSS) vulnerabilities by injecting JavaScript payloads into reflected, stored, and DOM-based contexts to demons… |
| `testing-jwt-token-security` | _pacote de cibersegurança_ | Assessing JSON Web Token implementations for cryptographic weaknesses, algorithm confusion attacks, and authorization bypass vulnerabilities during security eng… |
| `testing-oauth2-implementation-flaws` | _pacote de cibersegurança_ | 'Tests OAuth 2.0 and OpenID Connect implementations for security flaws including authorization code interception, redirect URI manipulation, CSRF in OAuth flows… |
| `testing-prompt-injection-in-rag-pipelines` | _pacote de cibersegurança_ | Probe RAG applications for prompt injection via poisoned retrieved context and embedding manipulation. |
| `triaging-security-incident` | _pacote de cibersegurança_ | 'Performs initial triage of security incidents to determine severity, scope, and required response actions using the NIST SP 800-61r3 and SANS PICERL frameworks… |

### Vídeo, motion e reels (75)

Produção dos reels do @andreias.ai: roteiro, storyboard, motion em código (HyperFrames, GSAP, Three.js, Remotion), transições, voz clonada, avatar e geração de imagem/vídeo.

| Skill | Repositório | Para que serve |
|---|---|---|
| `after` | _provável skill própria/criada aqui (inferido pelo texto em português)_ | Biblioteca de transições e efeitos estilo After Effects em código (GSAP, seek-safe para HyperFrames) para os reels do @andreias.ai — DEGRAU (corte em escada), p… |
| `animated-chart` | https://github.com/charlie947/motion-graphics-skills | Make a looping animated chart for LinkedIn or a newsletter in code with Claude Code. Bars that become a line, a number that counts up, a before and after. Every… |
| `apple-launch-film` | https://github.com/charlie947/motion-graphics-skills | Rebuild an Apple-style Mac launch film entirely in code with Claude Code. A thin menu bar, the black notch growing into widgets one scene at a time, full-screen… |
| `autoedit` | _provável skill própria/criada aqui (inferido pelo texto em português)_ | Edita video automaticamente — detecta e corta silencio/tempo morto, frames parados (congelados) e falas repetidas (retakes), renderizando um video final mais en… |
| `brag-slim` | https://github.com/latent-spaces/brag | Turn a project directory or a website URL into a short, shareable launch video with music, motion, and share copy. One file, no bundled assets — built entirely … |
| `genjutsu` | https://github.com/AThevon/genjutsu | Creative coding for interfaces - motion, micro-interactions, full visual design systems, and whole sites built by a team of agents. Use when animating or polish… |
| `gsap-core` | _origem não registrada_ | Official GSAP skill for the core API — gsap.to(), from(), fromTo(), easing, duration, stagger, defaults, gsap.matchMedia() (responsive, prefers-reduced-motion).… |
| `gsap-frameworks` | _origem não registrada_ | Official GSAP skill for Vue, Svelte, and other non-React frameworks — lifecycle, scoping selectors, cleanup on unmount. Use when the user wants animation in Vue… |
| `gsap-performance` | _origem não registrada_ | Official GSAP skill for performance — prefer transforms, avoid layout thrashing, will-change, batching. Use when optimizing GSAP animations, reducing jank, or w… |
| `gsap-plugins` | _origem não registrada_ | Official GSAP skill for GSAP plugins — registration, ScrollToPlugin, ScrollSmoother, Flip, Draggable, Inertia, Observer, SplitText, ScrambleText, SVG and physic… |
| `gsap-react` | _origem não registrada_ | Official GSAP skill for React — useGSAP hook, refs, gsap.context(), cleanup. Use when the user wants animation in React or Next.js, or asks about GSAP with Reac… |
| `gsap-scrolltrigger` | _origem não registrada_ | Official GSAP skill for ScrollTrigger — scroll-linked animations, pinning, scrub, triggers. Use when building or recommending scroll-based animation, parallax, … |
| `gsap-timeline` | _origem não registrada_ | Official GSAP skill for timelines — gsap.timeline(), position parameter, nesting, playback. Use when sequencing animations, choreographing keyframes, or when th… |
| `gsap-utils` | _origem não registrada_ | Official GSAP skill for gsap.utils — clamp, mapRange, normalize, interpolate, random, snap, toArray, wrap, pipe. Use when the user asks about gsap.utils, clamp,… |
| `heygen-avatar` | _origem não registrada_ | / Create a persistent HeyGen avatar — a reusable face + voice identity for the agent, the user, or any named character — powered by HeyGen Avatar V technology. … |
| `heygen-translate` | _origem não registrada_ | / Translate and dub a video into another language with voice cloning and lip-sync, powered by HeyGen Video Translation. The presenter keeps their face, their vo… |
| `heygen-video` | _origem não registrada_ | / Generate HeyGen presenter videos via the v3 Video Agent pipeline — handles Frame Check (aspect ratio correction), prompt engineering, avatar resolution, and v… |
| `higgsfield-brandkit` | _origem não registrada_ | / Create and extend complete visual brand systems through the Higgsfield CLI and bundled deterministic local tooling: palettes, SVG logo marks, typography, mock… |
| `higgsfield-generate` | _origem não registrada_ | / Generate images/videos/3D assets/audio via Higgsfield AI. Defaults: GPT Image 2 for image/design/text, Seedance 2.0 for video, Nano Banana 2/Lite/Pro for char… |
| `higgsfield-marketplace-cards` | _origem não registrada_ | / Generate marketplace product image cards through Higgsfield: compliant main image, secondary product images, and A+ style content modules. Use when the user a… |
| `higgsfield-product-photoshoot` | _origem não registrada_ | / Generate brand-quality product images through Higgsfield product-photoshoot prompt enhancement on GPT Image 2 / gpt_image_2. Entry point for professional bran… |
| `higgsfield-soul-id` | _origem não registrada_ | / Train a Soul Character — a personalized model on a person's face that Higgsfield uses for identity-faithful image and video generation. Use when: create my So… |
| `higgsfield-video-explainer` | _provável skill própria/criada aqui (inferido pelo texto em português)_ | / Build a complete non-photoreal narrated explainer or story video from ordered 10-second blocks: one narrator, one universal style key, one Seed Audio take and… |
| `higgsfield-websites` | _origem não registrada_ | / Build, edit, and deploy full-stack websites, apps and games via the Higgsfield CLI (`higgsfield website …`). Each is a React 19 + TanStack Start SSR app in on… |
| `higgsfield-youtube-thumbnail` | _origem não registrada_ | / Create high-click-through YouTube thumbnails and vertical video covers through the Higgsfield CLI. Builds a truthful information-gap concept, preserves up to … |
| `hyperframes` | https://github.com/heygen-com/hyperframes | > Mandatory entry point: read this first for any request to make, create, edit, animate, or render a video, animation, or motion graphic, including a promo, exp… |
| `hyperframes-animation` | https://github.com/heygen-com/hyperframes | All animation knowledge for HyperFrames — atomic motion rules, multi-phase scene blueprints, scene transitions, broader motion-design techniques, AND the seven … |
| `hyperframes-audio` | https://github.com/heygen-com/hyperframes | > Use when audio already placed in a HyperFrames composition needs to be mixed: fade-in/fade-out, crossfade, track gain or volume, volume automation, ducking, a… |
| `hyperframes-cli` | https://github.com/heygen-com/hyperframes | > Use the HyperFrames CLI development loop: init, add, catalog, capture, lint, check, snapshot, compare, grade-compare, preview, play, present, beats, keyframes… |
| `hyperframes-core` | https://github.com/heygen-com/hyperframes | The HyperFrames composition contract — build one renderable project. Use for composition structure, the `data-*` timing attributes, `class=clip`, tracks, sub-co… |
| `hyperframes-creative` | https://github.com/heygen-com/hyperframes | Non-animation creative direction for HyperFrames videos. Use for design spec (frame.md / design.md) handling, palettes, typography, narration, beat planning, au… |
| `hyperframes-keyframes` | https://github.com/heygen-com/hyperframes | > Use when a HyperFrames composition needs a punch-in, punch-out, zoom, reframe, Ken Burns treatment, camera move, visual match/whip handoff, or other seek-safe… |
| `hyperframes-registry` | https://github.com/heygen-com/hyperframes | Search, install, and wire registry blocks and components into HyperFrames compositions. Use BEFORE hand-building any named visual — whenever a brief, a user, or… |
| `hyperframes-studio` | https://github.com/heygen-com/hyperframes | > Use when working with a person on a HyperFrames project in Studio: first, whether their message asks for a change at all (questions, loose ideas and don't cha… |
| `kie-models` | _origem não registrada_ | 在 KIE 平台(api.kie.ai)上发现、查价并调用 AI 模型。当用户提到 KIE 或 kie.ai,问X 用哪个 KIE 模型、列出 KIE 模型、在 KIE 上跑模型,或需要某个模型的 schema、价格、成功率时使用。 |
| `launch-video` | https://github.com/charlie947/motion-graphics-skills | Make a 30-45 second product launch video in code with Claude Code, the kind SaaS companies post on launch day. One sentence split across scenes, real product sc… |
| `loop-cover` | https://github.com/charlie947/motion-graphics-skills | Turn a newsletter or blog cover into a seamless looping GIF at 896 x 640, 180 frames at 20fps. Only the one element you name moves, the loop is rotated so frame… |
| `media-use` | https://github.com/heygen-com/hyperframes | Agent Media OS for a HyperFrames project. Resolve BGM, SFX, image, icon, brand logo, voice, color grade, or LUT into a frozen local file or paste-ready block + … |
| `milestone-reveal` | https://github.com/charlie947/motion-graphics-skills | Make a 12-second looping milestone clip in code with Claude Code. Thousands of tiny points drift like a night sky, pull together into your real number (follower… |
| `model-showdown` | https://github.com/charlie947/motion-graphics-skills | Give the same motion brief to three AI models, keep each first try, render all three the same way and stack them into one comparison video with model names and … |
| `motion-brief-writer` | https://github.com/charlie947/motion-graphics-skills | Turns a rough idea for an animated graphic into a precise build brief for Claude Code, in your own brand. Asks for anything essential first (exact numbers, size… |
| `motion-design` | _origem não registrada_ | > Applies motion design principles to create emotionally-driven, technically sound animations and transitions. Provides timing, easing, choreography, and Disney… |
| `motion-effects` | https://github.com/charlie947/motion-graphics-skills | Build any of 16 premium motion effects from scratch in your own brand, as one 8-second looping HTML file with window.seek(seconds) so it exports frame-exact to … |
| `motion-graphics` | https://github.com/heygen-com/hyperframes | > A short, design-led motion graphic where motion is the message — kinetic typography, stat count-up, chart/data-viz hit, logo sting / brand lockup, lower-third… |
| `motion-prompt-writer` | https://github.com/charlie947/motion-graphics-skills | Write a complete 8-part Claude Motion prompt (The bar, Format, The one rule, Look, Motion, Never, Before you finish, The scene) for one short looping motion gra… |
| `newsletter-promo` | https://github.com/charlie947/motion-graphics-skills | Turn a newsletter edition into a 12-20 second promo clip for LinkedIn, Instagram or X that drives people to read and subscribe. Hook question, three proof frame… |
| `reel` | _provável skill própria/criada aqui (inferido pelo texto em português)_ | Cria um reel vertical 1080x1920 pronto para postar, do gancho ao MP4 renderizado no computador da pessoa. Use quando a pessoa pedir faz um reel sobre X, vídeo c… |
| `reel-3d-motion` | _provável skill própria/criada aqui (inferido pelo texto em português)_ | Formato e técnica dos reels de motion design 3D do @andreias.ai (Remotion + React Three Fiber, voz clonada, mascote bloco). Use quando a dona pedir um reel em 3… |
| `reel-export` | https://github.com/charlie947/motion-graphics-skills | Turn any horizontal or square motion video into a 1080 x 1920 Instagram Reel or TikTok that uploads cleanly. Headline and logos inside the safe zone, H.264, yuv… |
| `reference-to-motion` | https://github.com/charlie947/motion-graphics-skills | Turn references you admire into a scene-by-scene Claude Motion prompt for your own topic and brand. Takes a video for the moves (screenshots, frames or a contac… |
| `remotion-best-practices` | _origem não registrada_ | Router for all Remotion skills |
| `remotion-captions` | _origem não registrada_ | Transcribing, displaying and animating captions |
| `remotion-create` | _origem não registrada_ | Create a new Remotion video |
| `remotion-docs` | _origem não registrada_ | Search Remotion documentation |
| `remotion-interactivity` | _origem não registrada_ | Structure Remotion markup for interactivity |
| `remotion-maps` | _origem não registrada_ | Remotion Map animation knowledge |
| `storyboard-reel` | _provável skill própria/criada aqui (inferido pelo texto em português)_ | Transforma um reel de referência do Instagram em prompt reverso e depois em storyboard em imagem na identidade do @andreias.ai (mascotes Claude/GitHub/Nuvem, fu… |
| `text-to-speech` | https://github.com/elevenlabs/skills | Convert text to speech using ElevenLabs voice AI. Use when generating audio from text, creating voiceovers, building voice apps, or synthesizing speech in 90+ l… |
| `threejs-animation` | _origem não registrada_ | Keyframe, skeletal and morph-target animation, procedural motion and clip blending, on WebGL or with WebGPU and TSL. Use when animating objects, playing glTF an… |
| `threejs-asset-pipeline` | _origem não registrada_ | Shrinking glTF assets for three.js with gltf-transform: inspect, validate and optimize commands, Draco, meshopt and quantization, KTX2, WebP and AVIF textures, … |
| `threejs-fundamentals` | _origem não registrada_ | Three.js scene setup: scenes and fog, cameras, the renderer and tone mapping, the animation loop, object hierarchies, transforms, core math and cleanup, on WebG… |
| `threejs-geometry` | _origem não registrada_ | Creating and shaping three.js geometry: built-in shapes, 3D text, vertex buffers and attributes, merging, instancing, batching, point clouds and lines, on WebGL… |
| `threejs-interaction` | _origem não registrada_ | Picking with raycasting, camera controls, transform gizmos, drag, hover and box selection for three.js, identical under WebGL and WebGPU. Use when handling mous… |
| `threejs-lighting` | https://github.com/cloudai-x/threejs-skills | Light types and physical units, shadow maps, HDR environment lighting, light probes, and lighting performance, on WebGL or with WebGPU and TSL. Use when adding … |
| `threejs-loaders` | _origem não registrada_ | Loading three.js assets: glTF with Draco, meshopt and KTX2 compression, other model formats, textures, HDR and EXR environments, progress, caching, cloning and … |
| `threejs-materials` | https://github.com/cloudai-x/threejs-skills | Choosing and configuring three.js materials - unlit, diffuse, specular, PBR, toon, point and line materials - shared properties like blending and stencil, envir… |
| `threejs-performance` | _origem não registrada_ | Measuring and optimizing three.js speed: render statistics, memory counters, fewer draw calls via merging, instancing, batching and LOD, fill rate, shadows, CPU… |
| `threejs-postprocessing` | _origem não registrada_ | Three.js post-processing: composer pass chains, built-in renderer effects, and the WebGPU/TSL node pipeline — bloom, depth of field, ambient occlusion, custom s… |
| `threejs-react-three-fiber` | _origem não registrada_ | Building three.js scenes from React with React Three Fiber and drei: renderer setup, the scene graph as JSX, frame-loop, state and loading hooks, pointer events… |
| `threejs-shaders` | _origem não registrada_ | Custom GLSL vertex and fragment shaders: uniforms, varyings, shader chunks, extending built-in materials, instanced attributes, plus the same effects as node ma… |
| `threejs-textures` | _origem não registrada_ | Three.js textures: image loading, color spaces, UV channels and transforms, texture types from canvas to HDR and KTX2, render targets, texture memory. Use when … |
| `title-sequence-3d` | https://github.com/charlie947/motion-graphics-skills | Make a cinematic 3D title sequence (8-15 seconds) in code with Claude Code and Three.js. A camera moves through a lit scene, such as a rainy street at night wit… |
| `video-edit` | https://github.com/genmedia-labs/skills | > Edit existing video on RunComfy — this skill is a smart router that matches the user's intent to the right edit model in the RunComfy catalog. Picks Wan 2.7 E… |
| `vox-explainer` | https://github.com/charlie947/motion-graphics-skills | Make a short Vox-style documentary explainer (30-60 seconds) entirely in code with Claude Code. Torn paper, halftone texture, bold condensed type, motion on two… |
| `voz` | _provável skill própria/criada aqui (inferido pelo texto em português)_ | >- Gera narração/voiceover na voz clonada da usuária (Andreia) usando XTTS-v2 local, sem custo e sem API. Use quando ela pedir para narrar, gerar áudio com a mi… |

### Design e front-end (9)

Interface dos produtos e das peças visuais: identidade, revisão de UI, acessibilidade, performance e qualidade das páginas.

| Skill | Repositório | Para que serve |
|---|---|---|
| `brand-intake` | https://github.com/charlie947/motion-graphics-skills | The setup step every other skill in this pack reads. A short interview plus 3 to 5 reference frames becomes two files in your project, brand.md (who you are, wh… |
| `canvas-design` | _origem não registrada_ | Create beautiful visual art in .png and .pdf documents using design philosophy. You should use this skill when the user asks to create a poster, piece of art, d… |
| `design-dna` | _origem não registrada_ | >- Extract, define, and apply design DNA across three dimensions: design system (tokens), design style (qualitative feel), and visual effects (Canvas, WebGL, 3D… |
| `frontend-design` | https://github.com/anthropics/skills | Guidance for distinctive, intentional visual design when building new UI or reshaping an existing one. Helps with aesthetic direction, typography, and making ch… |
| `impeccable` | https://github.com/pbakaus/impeccable | Use when the user wants to design, redesign, shape, critique, audit, polish, clarify, distill, harden, optimize, adapt, animate, colorize, extract, or otherwise… |
| `json-canvas` | _origem não registrada_ | Create and edit JSON Canvas files (.canvas) with nodes, edges, groups, and connections. Use when working with .canvas files, creating visual canvases, mind maps… |
| `performance` | https://github.com/addyosmani/web-quality-skills | Optimize web performance for faster loading and better user experience. Use when asked to speed up my site, optimize performance, reduce load time, fix slow loa… |
| `web-design-guidelines` | https://github.com/vercel-labs/agent-skills | Review UI code for Web Interface Guidelines compliance. Use when asked to review my UI, check accessibility, audit design, review UX, or check my site against b… |
| `web-quality-audit` | https://github.com/addyosmani/web-quality-skills | Comprehensive web quality audit covering performance, accessibility, SEO, and best practices. Use when asked to audit my site, review web quality, run lighthous… |

### Stack e operação dos produtos (13)

O dia a dia técnico dos meus produtos e dos clientes: banco Supabase/Postgres, pagamentos, e-mail, frete (Mercado Envios), WhatsApp, deploy e CRM com números conferidos na fonte.

| Skill | Repositório | Para que serve |
|---|---|---|
| `automate-whatsapp` | https://github.com/gokapso/agent-skills | Build and debug Kapso WhatsApp workflows, triggers, functions, and executions. |
| `crm-acuracidade` | _provável skill própria/criada aqui (inferido pelo texto em português)_ | Reconciliar KPIs do CRM/Dashboard do sistema contra a fonte de verdade ERP (MCP reports + API oficial). Use ao CRIAR/adicionar qualquer KPI, card, relatório ou … |
| `email-best-practices` | https://github.com/resend/email-best-practices | Use when building email features, emails going to spam, high bounce rates, setting up SPF/DKIM/DMARC authentication, implementing email capture, ensuring compli… |
| `fastapi` | https://github.com/fastapi/fastapi | FastAPI best practices and conventions. Use when working with FastAPI APIs, Pydantic models, dependencies, streaming responses including Server-Sent Events (SSE… |
| `firebase-auth-basics` | _origem não registrada_ | Guide for setting up and using Firebase Authentication. Use this skill when the user's app requires user sign-in, user management, or secure data access using a… |
| `mercado-envios-regras` | _origem não registrada_ | Regras oficiais do Mercado Envios (Mercado Livre) sobre entregadores, repasse e termos de serviço — modelo Envios Extra (Condutor Autônomo), Flex e Pontos Flex,… |
| `payment-testing` | https://github.com/petrkindlmann/qa-skills | >- Test payment and checkout flows end to end against PSP sandboxes — Stripe first, with the general pattern for Adyen/Braintree/PayPal. Covers Stripe test-mode… |
| `pgvector-semantic-search` | _origem não registrada_ | / Use this skill for setting up vector similarity search with pgvector for AI/ML embeddings, RAG applications, or semantic search. **Trigger when user asks to:*… |
| `read-only-postgres` | _origem não registrada_ | Execute read-only SQL queries against PostgreSQL databases. Use when: (1) querying PostgreSQL data, (2) exploring schemas/tables, (3) running SELECT queries for… |
| `resend` | https://github.com/resend/resend-skills | Use when working with the Resend email API — sending transactional emails (single or batch), receiving inbound emails via webhooks, managing email templates, tr… |
| `supabase` | https://github.com/supabase/agent-skills | Use when doing ANY task involving Supabase. Triggers: Supabase products (Database, Auth, Edge Functions, Realtime, Storage, Vectors, Cron, Queues); client libra… |
| `supabase-postgres-best-practices` | _origem não registrada_ | Postgres performance optimization and best practices from Supabase. Use this skill when writing, reviewing, or optimizing Postgres queries, schema designs, or d… |
| `vercel-react-native-skills` | _origem não registrada_ | React Native and Expo best practices for building performant mobile apps. Use when building React Native components, optimizing list performance, implementing a… |

### IA, agentes e RAG (12)

Construir os agentes e robôs (atendimento, esteira de conteúdo, robô do LinkedIn): RAG, fluxos com LangGraph, servidores MCP e comparação de modelos.

| Skill | Repositório | Para que serve |
|---|---|---|
| `agent-reach` | _origem não registrada_ | > MUST USE when user wants to 调研/research/搜索/search/查/找/look up anything on the internet — e.g. 全网调研 X / 帮我调研一下 X / 查一下 X / 搜搜 X / 看看大家怎么评价 X / X 上有什么讨论 / resea… |
| `aprender` | _provável skill própria/criada aqui (inferido pelo texto em português)_ | Playbook destilado dos canais Lionlab (116 vídeos) e Matheus Battisti (22 vídeos curados de 939; operação do Claude Code — hooks, subagents, /goal, CLAUDE.md, a… |
| `claude-code` | _origem não registrada_ | Delegate coding tasks to Claude Code (Anthropic's CLI agent). Use for building features, refactoring, PR reviews, and iterative coding. Requires the claude CLI … |
| `codebase-memory` | _origem não registrada_ | Use the codebase knowledge graph for structural code queries. Triggers on: explore the codebase, understand the architecture, what functions exist, show me the … |
| `context7-mcp` | _origem não registrada_ | This skill should be used when the user asks about libraries, frameworks, API references, or needs code examples. Activates for setup questions, code generation… |
| `criar-rag` | _provável skill própria/criada aqui (inferido pelo texto em português)_ | Construir um sistema RAG de verdade — escolher a arquitetura (híbrido com banco vetorial × subagente por documento sem vetor), sanitizar e chunkar documentos, i… |
| `kie-chat-agents` | _origem não registrada_ | 当用户想让本地 coding agent 跑在 KIE 的 chat 模型(api.kie.ai)上、询问某个 agent 能用哪些 KIE 模型,或询问如何为其配置 base URL、API key、provider 表或模型名时使用。目前覆盖 Codex CLI、Claude Code 和 Grok Build。模… |
| `langchain-rag` | https://github.com/langchain-ai/langchain-skills | INVOKE THIS SKILL when building ANY retrieval-augmented generation (RAG) system. Covers document loaders, RecursiveCharacterTextSplitter, embeddings (OpenAI), a… |
| `langgraph-loop` | _provável skill própria/criada aqui (inferido pelo texto em português)_ | Construir fluxos LLM com loop/estado usando LangGraph (gerar→validar→corrigir) a partir do piloto existente. Use quando o usuário pedir agente com loop, LangGra… |
| `llm-council` | _origem não registrada_ | Run any question, idea, or decision through a council of 5 AI advisors who independently analyze it, peer-review each other anonymously, and synthesize a final … |
| `mcp-builder` | https://github.com/anthropics/skills | Guide for creating high-quality MCP (Model Context Protocol) servers that enable LLMs to interact with external services through well-designed tools. Use when b… |
| `pinecone` | _provável skill própria/criada aqui (inferido pelo texto em português)_ | Usar o banco vetorial Pinecone — MCP oficial, indexar uma fonte com integrated embeddings, e busca semântica/RAG. Use quando o usuário mencionar Pinecone, quise… |

### Carreira (6)

Busca de vagas e candidaturas: perfil na Gupy, triagem de vagas aderentes e currículo.

| Skill | Repositório | Para que serve |
|---|---|---|
| `analise-de-curriculo` | https://github.com/gupy-io/gupy-skills-candidato | Descubra o que está faltando no seu perfil Gupy e receba dicas práticas para aumentar visibilidade nas vagas. Use para conduzir candidatos no portal Gupy com ch… |
| `atualizar-vagas` | _provável skill própria/criada aqui (inferido pelo texto em português)_ | Atualizar o painel de vagas de emprego do usuário (Downloads/vagas-poa-gerencia-tech.html + .csv) — coleta via LinkedIn guest API e reinserção idempotente de se… |
| `guia-de-triagem` | https://github.com/gupy-io/gupy-skills-candidato | Esclareça com empatia e transparência como a IA da Gupy funciona na seleção — o que analisa (experiências, habilidades), o que não usa para julgar (dados sensív… |
| `gupy` | _provável skill própria/criada aqui (inferido pelo texto em português)_ | Otimiza o perfil da Andreia Schneider na Gupy e prepara candidaturas por vaga, subindo na fila de aderência sem inventar experiência. Audita o perfil pela aba l… |
| `perfil` | _provável skill própria/criada aqui (inferido pelo texto em português)_ | Audita um perfil de Instagram e reescreve a bio. Use quando a pessoa pedir análise de perfil, revisão de bio, meu perfil não converte, o que melhorar no meu Ins… |
| `radar-de-vagas` | https://github.com/gupy-io/gupy-skills-candidato | > Compare vagas e empresas do portal Gupy em 6 dimensões (remuneração, modalidade, benefícios, exigências, carreira, cultura/inclusão): tabela, destaques, ponto… |

### Conteúdo e redes (7)

Posts, carrosséis e legendas para Instagram e LinkedIn, texto sem cara de IA, e coleta de dados de perfis e empresas para pauta e prospecção.

| Skill | Repositório | Para que serve |
|---|---|---|
| `apify-ultimate-scraper` | https://github.com/apify/agent-skills | Universal AI-powered web scraper for any platform. Scrape data from Instagram, Facebook, TikTok, YouTube, LinkedIn, X/Twitter, Google Maps, Google Search, Googl… |
| `carrossel` | _provável skill própria/criada aqui (inferido pelo texto em português)_ | Cria um carrossel de Instagram completo, da capa ao último slide, pronto para postar em PNG 1080x1350. Use quando a pessoa pedir carrossel, post com vários slid… |
| `comentarios` | _provável skill própria/criada aqui (inferido pelo texto em português)_ | Classifica comentários de Instagram e escreve a resposta pública e a DM de cada um. Use quando a pessoa colar ou exportar comentários de um post ou reel, pedir … |
| `content-strategy` | https://github.com/coreyhaines31/marketingskills | When the user wants to plan a content strategy, decide what content to create, or figure out what topics to cover. Also use when the user mentions content strat… |
| `firecrawl-company-directories` | https://github.com/firecrawl/firecrawl-workflows | Extract structured company lists from directories with Firecrawl. Use for scraping YC, Crunchbase, Product Hunt, G2, startup directories, category directories, … |
| `legenda` | _provável skill própria/criada aqui (inferido pelo texto em português)_ | Escreve a legenda de um post, carrossel ou reel de Instagram, com a primeira linha construída para o que aparece antes do mais, corpo fácil de escanear, um únic… |
| `stop-slop` | https://github.com/hardikpandya/stop-slop | Remove AI writing patterns from prose. Use when drafting, editing, or reviewing text to eliminate predictable AI tells. |

### Pesquisa e conhecimento (14)

Segundo cérebro no Obsidian, pesquisa na web, leitura de páginas, engenharia reversa e criação de novas skills.

| Skill | Repositório | Para que serve |
|---|---|---|
| `browser` | _origem não registrada_ | Web browser automation with AI-optimized snapshots for claude-flow agents |
| `defuddle` | _origem não registrada_ | Extract clean markdown content from web pages using Defuddle CLI, removing clutter and navigation to save tokens. Use instead of WebFetch when the user provides… |
| `find-skills` | https://github.com/vercel-labs/skills | Helps users discover and install agent skills when they ask questions like how do I do X, find a skill for X, is there a skill that can..., or express interest … |
| `last30days` | https://github.com/mvanhorn/last30days-skill | Research what people actually say about any topic in the last 30 days. Pulls posts and engagement from Reddit, X, YouTube, TikTok, Hacker News, Polymarket, GitH… |
| `notebooklm` | _origem não registrada_ | Use this skill to query your Google NotebookLM notebooks directly from Claude Code for source-grounded, citation-backed answers from Gemini. Browser automation,… |
| `obsidian-bases` | _origem não registrada_ | Create and edit Obsidian Bases (.base files) with views, filters, formulas, and summaries. Use when working with .base files, creating database-like views of no… |
| `obsidian-cli` | _origem não registrada_ | Interact with Obsidian vaults using the Obsidian CLI to read, create, search, and manage notes, tasks, properties, and more. Also supports plugin and theme deve… |
| `obsidian-markdown` | _origem não registrada_ | Create and edit Obsidian Flavored Markdown with wikilinks, embeds, callouts, properties, and other Obsidian-specific syntax. Use when working with .md files in … |
| `obsidian-segundo-cerebro` | _provável skill própria/criada aqui (inferido pelo texto em português)_ | > Transforma um vault do Obsidian em um segundo cérebro mantido pelo Claude — no estilo do vídeo do Matheus Battisti (Hora de Codar). Use SEMPRE que o usuário p… |
| `research` | _origem não registrada_ | Investigate a question against high-trust primary sources and capture the findings as a Markdown file in the repo. Use when the user wants a topic researched, d… |
| `reverse-engineer-anything` | _origem não registrada_ | Reverse engineer native, managed, Electron/JavaScript, packaged, firmware, and browser targets with REA. Use shipped-artifact or requested runtime evidence to e… |
| `skill-builder` | _origem não registrada_ | Create new Claude Code Skills with proper YAML frontmatter, progressive disclosure structure, and complete directory organization. Use when you need to build cu… |
| `skill-creator` | _origem não registrada_ | Create new skills, modify and improve existing skills, and measure skill performance. Use when users want to create a skill from scratch, edit, or optimize an e… |
| `wiki` | _origem não registrada_ | > Daniel's Zettelkasten knowledge engine — 9 verbs (ingest/query/save/lint/manage/synthesize/critique/compare/eli5) unified in one namespace. Realizes Karpathy'… |

### Outras (2)

Skills avulsas que não se encaixam nos grupos acima.

| Skill | Repositório | Para que serve |
|---|---|---|
| `generating-end-to-end-tests.md` | _origem não registrada_ | / This skill enables Claude to generate end-to-end (E2E) tests for web applications. It leverages Playwright, Cypress, or Selenium to automate browser interacti… |
| `})()` | _origem não registrada_ |  |
