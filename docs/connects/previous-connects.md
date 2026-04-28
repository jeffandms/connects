# Previous Connects baseline

This file distills the historical baseline from the Connect PDFs already in the repo so later reviews can build on it instead of recreating old context.

## 2024-05-29 Connect

### Notable impact

- Delivered initial plumbing for in-app sidecar chat and out-of-app M365 Copilot scenarios for F&O.
- Pulled the sidecar chat control into the client, wired it to MCS, created auth shims, and added MAU telemetry.
- Created the ability to expose F&O logic as Dataverse CustomAPI, enabling downstream AI and integration scenarios.
- Helped onboard the Nexus team that became the ongoing owner of the area.

### Customer and reliability examples

- Diagnosed or helped drive fixes for issues affecting customers such as USABlueBook, MattressFirm, Deere, Komatsu, and others.
- Helped uncover a global memory issue caused by forms not being closed.
- Helped identify a business events race condition and other product defects impacting multiple customers.

### Themes

- `net-new-dataverse`
- `legacy-reliability`
- `team-growth`

## 2025-05-15 Connect

### Notable impact

- Delivered the actions infrastructure that exposed X++ as CustomAPI for MCS agents, forming the basis for existing ERP agents.
- Helped define ERP strategy for enabling agents across the breadth of the product.
- Prototyped and helped code the initial Dataverse Native MCP server and aligned on tool shape and evaluation methods.
- Drove roadmap and implementation work related to moving Commerce runtime capabilities onto Dataverse plugins.

### Cross-team and customer leverage

- Unblocked multiple engineering efforts through architecture guidance, telemetry design help, and cross-team connections.
- Personally diagnosed platform issues in areas such as Virtual Entity performance and metadata loading race conditions.
- Helped de-escalate customer situations by clarifying technical and organizational misunderstandings.

### Themes

- `net-new-dataverse`
- `legacy-reliability`
- `team-growth`

## 2025-11-18 Connect

### Notable impact

- Helped bring Dataverse MCP Server from conception to preview, with GA rollout underway at the time of the Connect.
- Drove or influenced eval datasets, eval pipeline onboarding, and dogfooding through the Dataverse Python SDK.
- Helped bring F&O MCP Server from conception to preview and coordinated alignment between F&O and Dataverse patterns.
- Led discussions and POCs around DV.Next primitives such as evals, playbooks, ontologies, and glossaries.

### Signals of scale

- Dataverse MCP Server was serving more than 1,100 monthly active tenants and over 200,000 monthly tool calls.
- F&O MCP Server showed early adoption across many environments as builds became available.

### Growth and learning

- Reflected on the need for more aggressive early scoping for cutting-edge efforts like MCP and third-party auth scenarios.

### Themes

- `net-new-dataverse`
- `team-growth`

## Connect guidance baseline

- Connects are meant to clarify impact, track progress, identify learning opportunities, and align on goals through meaningful conversations.
- Two to three Connects per year is the recommended cadence.
- Good Connect material should balance impact delivered with learning, collaboration, and growth mindset.
