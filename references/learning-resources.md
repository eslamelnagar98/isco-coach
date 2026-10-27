# Learning resource catalog

Starting points for the "Learn more" section. Titles and authors only, because links and course editions change. When recommending, verify currency with a quick search if the topic moves fast (front-end, AI, Kubernetes), and say "search: <title> <author>" instead of inventing a URL.

## Official, always safe
- **Microsoft Learn** (learn.microsoft.com): .NET, Azure, ASP.NET Core, EF Core, Azure Architecture Center, Well-Architected Framework, Cloud Adoption Framework.
- **Azure Architecture Center** design patterns: Outbox, Saga, CQRS, Circuit Breaker, Competing Consumers, Strangler Fig.
- Official docs: docs.docker.com, kubernetes.io/docs, rabbitmq.com/docs, git-scm.com/book (Pro Git, free), opentelemetry.io/docs, react.dev, angular.dev, nextjs.org/docs, learn.microsoft.com/sql.

## Backend / architecture (.NET-leaning)
- *Domain-Driven Design Distilled*: Vaughn Vernon (short entry), then *Implementing Domain-Driven Design* (deep).
- *Designing Data-Intensive Applications*: Martin Kleppmann (distributed systems, the standard reference).
- *Software Architecture: The Hard Parts*: Ford, Richards, Sadalage, Dehghani.
- *Fundamentals of Software Architecture*: Richards & Ford.
- *Enterprise Integration Patterns*: Hohpe & Woolf (messaging, RabbitMQ patterns).
- *Microservices Patterns*: Chris Richardson (Saga, Outbox, CQRS).
- *Dependency Injection Principles, Practices, and Patterns*: Steven van Deursen & Mark Seemann.
- *Pro .NET Memory Management*: Konrad Kokosa (performance internals).
- *Clean Architecture*: Robert C. Martin (use alongside pragmatic .NET examples).
- Courses/authors: **Nick Chapsas** (YouTube + Dometrain), **Milan Jovanović** (Clean Architecture, modular monolith, CQRS in .NET), **Amichai Mantinband** (REPR / Vertical Slice, YouTube), **Derek Comartin / CodeOpinion** (event-driven, messaging blog + YouTube), **Dometrain** (.NET-focused courses), **Pluralsight / Udemy** (search the topic + .NET).
- Blogs/newsletters: Andrew Lock (.NET escapades), Scott Hanselman, Steve Smith / Ardalis, Code Maze, .NET Blog (devblogs.microsoft.com/dotnet), Milan's newsletter, Thomas Levesque.

## SQL Server / data
- *T-SQL Fundamentals*: Itzik Ben-Gan; *T-SQL Querying* (advanced).
- *SQL Server Execution Plans*: Grant Fritchey (free from Redgate).
- Brent Ozar (blog, First Responder Kit, courses) for performance tuning.
- Erik Darling (blog/videos) for query tuning.
- Use The Index, Luke (use-the-index-luke.com): indexing fundamentals, free.

## Messaging / distributed systems
- RabbitMQ official tutorials (start), *RabbitMQ in Depth* by Gavin Roy.
- MassTransit docs (Outbox, Sagas), Wolverine docs, NServiceBus docs (Particular Software also has strong Saga/Outbox articles).
- CodeOpinion articles on Outbox, idempotency, eventual consistency.

## Azure / DevOps / IaC
- Microsoft Learn learning paths for AZ-204, AZ-305, AZ-400 (even without certifying).
- Bicep: Microsoft Learn "Fundamentals of Bicep"; Terraform: HashiCorp tutorials.
- *Accelerate*: Forsgren, Humble, Kim (delivery metrics, DORA).
- *The Phoenix Project* / *The DevOps Handbook* (context, lighter reading).
- GitHub Actions / Azure DevOps Pipelines docs.

## Docker / Kubernetes / Linux
- Docker: official "Get started", then *Docker Deep Dive*: Nigel Poulton.
- Kubernetes: *The Kubernetes Book*: Nigel Poulton; *Kubernetes in Action*: Marko Lukša; Kubernetes official tutorials; "Kubernetes the Hard Way": Kelsey Hightower (advanced).
- Linux CLI: *The Linux Command Line*: William Shotts (free online).
- Git: *Pro Git* (free), "Learn Git Branching" (interactive).

## Observability
- OpenTelemetry docs (.NET), Azure Monitor / Application Insights docs, *Observability Engineering*: Majors, Fong-Jones, Miranda.
- Grafana / Prometheus docs for self-hosted.

## Security
- OWASP Top 10 & ASP.NET Core security docs; *OAuth 2 in Action*: Richer & Sanso; Duende / Microsoft Entra docs; Azure Key Vault + Managed Identity docs.

## Front-end
- Fundamentals first: javascript.info, MDN, *You Don't Know JS Yet*: Kyle Simpson, TypeScript Handbook (typescriptlang.org).
- React: react.dev (official, excellent), Josh Comeau (*Joy of React*), Kent C. Dodds (Epic React), Jack Herrington (YouTube, patterns).
- Angular (common in .NET shops): angular.dev tutorials, Deborah Kurata (Pluralsight / YouTube), Netanel Basal / Angular Love blogs.
- Blazor: Microsoft Learn Blazor path, Jason Taylor / Nick Chapsas content.
- CSS: Josh Comeau's *CSS for JavaScript Developers*; web.dev Learn.
- Web performance & accessibility: web.dev, Deque University / A11y Project.

## AI / LLM integration (new area for many .NET devs)
- Microsoft Learn: Azure OpenAI / Azure AI Foundry docs, Semantic Kernel docs, Microsoft.Extensions.AI.
- Anthropic docs (docs.claude.com) for Claude API patterns, Anthropic's prompt engineering guide.
- *AI Engineering*: Chip Huyen.

## English / professional writing (for the prompt-polish module)
- *The Elements of Style*: Strunk & White (concise), *On Writing Well*: William Zinsser.
- Tools: Grammarly or LanguageTool (spot recurring errors), Hemingway Editor (clarity), Cambridge Dictionary "Grammar" section (reference).
- Practice habit: rewrite one PR description or Slack message daily using the Better-phrasing output, then note the recurring pattern.

## Leadership (senior engineer to team lead)
- *The Manager's Path*: Camille Fournier (the best single book for this step).
- *Staff Engineer*: Will Larson; *An Elegant Puzzle*: Will Larson (team and org practice).
- *The Making of a Manager*: Julie Zhuo.
- *Radical Candor*: Kim Scott (feedback that is clear and kind).
- *Crucial Conversations*: Patterson et al. (hard talks, disagreements).
- *Turn the Ship Around!*: L. David Marquet (give control, not orders).
- *Team Topologies*: Skelton & Pais (team structure and boundaries).
- *The Pragmatic Programmer*: Hunt & Thomas (craft habits).
- Practice habits: write short ADRs for decisions, run a weekly 1:1 with a clear agenda, give feedback within 48 hours, delegate with an outcome and a deadline, keep a "brag" document of results for reviews.
- Newsletters and sites: Pragmatic Engineer (Gergely Orosz), LeadDev, Will Larson's Irrational Exuberance blog.
