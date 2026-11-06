<p align="center">
  <a href="https://www.moraph.com"><img src="moraph-mark.svg" width="72" alt="Moraph"></a>
</p>

<h1 align="center">Moraph</h1>

<p align="center"><strong>Built for high-stakes work.</strong></p>

<p align="center">
  <a href="https://www.moraph.com">Website</a> ·
  <a href="https://trust.moraph.com">Trust Center</a> ·
  <a href="https://docs.moraph.com">Docs</a> ·
  <a href="https://status.moraph.com">Status</a> ·
  <a href="https://careers.moraph.com">Careers</a>
</p>

---

Moraph is one accountable technology partner for **financial services, healthcare and government**. We build proprietary
SaaS applications for regulated work, resell, implement and manage the partner platforms around them, and run both
around the clock.

Headquartered in New York, Moraph has about 1,250 people in eleven offices across ten countries: New York, Washington,
Ottawa, Mexico City, Buenos Aires, London, Sydney, Auckland, Manila, Mumbai and Yerevan.

### How we're organized

| Industry divisions | Shared units |
| --- | --- |
| [Financial Services Solutions](https://www.moraph.com/finance) | [Moraph Fusion Center](https://www.moraph.com/fusioncenter) (engineering) |
| [Healthcare Solutions](https://www.moraph.com/healthcare) | [Global Resilience Operations](https://www.moraph.com/globalresilience) (24/7 network, security and technical assistance) |
| [Government Solutions](https://www.moraph.com/government) | [Data Trust & Governance Labs](https://www.moraph.com/datatrustgovernancelabs) (data, privacy and AI governance) |

Client workloads are hosted in sovereign regions in the United States, the United Kingdom and Australia. See the
[Trust Center](https://trust.moraph.com) for how we protect client data.

### What we build

| Product | What it is | Where |
| --- | --- | --- |
| Moraph platform | The public site and the client-facing services around it: client portal, product modules and Work API, MCP server, support, partner and supplier portals, careers, Trust Center, docs, academy and status. Runs on Cloudflare Workers. | [www.moraph.com](https://www.moraph.com) · [portal](https://portal.moraph.com) · [apps](https://apps.moraph.com) · [mcp](https://mcp.moraph.com) · [support](https://support.moraph.com) · [docs](https://docs.moraph.com) · [academy](https://academy.moraph.com) |
| Moraph Command | For IT leaders, executives and administrators: service status and notices, support tickets, services and projects, contracts and invoices. | iPhone, iPad, Mac, Apple Watch, Android |
| Moraph Boardroom | For directors, committee members and corporate secretaries: board packets, recusals, acknowledgements, minutes and action items; a room display on Apple TV. | iPhone, iPad, Mac, Apple Watch, Apple TV, Android |
| Moraph Clinician | For physicians, nurses and hospital staff: who is on call, safety event reporting, healthcare work queues and tasks. | iPhone, iPad, Mac, Apple Watch, Android |
| Moraph Clinical Trials | Find a study on ClinicalTrials.gov and keep your own study visits, reminders and check-ins on your device. | iPhone, iPad, Mac, Apple Watch, Android |
| Moraph Field | Offline-first assigned work for inspectors, enumerators, outreach and field staff. | iPhone, iPad, Mac, Apple Watch, Android |
| Moraph Onboard | Account applicants and new hires keep their links and documents; staff see onboarding queues, exceptions and pipelines. | iPhone, iPad, Mac, Apple Watch, Android |

Application repositories are private. Our [solutions catalog](https://www.moraph.com/solutions) lists the proprietary SaaS
and managed partner platforms we offer.

### Open source

Tools we built for our own work and maintain in the open (Apache-2.0):

| Project | What it does |
| --- | --- |
| [mcp-worker-kit](https://github.com/moraph-com/mcp-worker-kit) | A remote MCP server on Cloudflare Workers with OAuth 2.1, permission tiers and an audit trail, so AI assistants act only as far as the signed-in person may. Extracted from the server behind mcp.moraph.com. |
| [regulated-workflow-schemas](https://github.com/moraph-com/regulated-workflow-schemas) | Open JSON Schema record formats for vendor risk reviews, patient-safety incidents, permit applications and board actions, with a validator. |

### How we work

- **Issue forms.** Every repository uses the organization's issue forms: Bug, Feature, Task, Epic and Initiative. Each
  form sets the matching GitHub issue type and new reports start with the `needs-triage` label.
- **Hierarchy.** Work is organized as **Initiative** (a portfolio-level outcome spanning a quarter or more) &gt; **Epic**
  (a shippable body of work) &gt; **Feature / Task / Bug**, linked as sub-issues. Blocking relationships are recorded as
  issue dependencies.
- **Project boards.** Each product has a GitHub Project named "Moraph · &lt;Product&gt;" with the same fields (Status,
  Priority, Size, Iteration, Start and Target date, Platform, Area) and views (Board, Backlog, Current iteration,
  Roadmap, Bugs, My work). Portfolio view: [Portfolio · Moraph](https://github.com/orgs/moraph-com/projects/7)
- **Pull requests.** Every pull request links its issue with `Closes #<n>` and follows the
  [pull request template](https://github.com/moraph-com/.github/blob/main/.github/pull_request_template.md).
- **Labels.** Shared labels across repositories (`needs-triage`, `needs-info`, `blocked`, `security`, `accessibility`,
  `performance`, `documentation`, `design`, `dependencies`, …), plus `platform:*` and `area:*` labels per repository.

### Moraph for Good

[Moraph for Good](https://moraph.org) is our social impact program. It gives Moraph software, security help and people's
time to nonprofits, community lenders, clinics and small public bodies.

### Contact

- Work with us: [www.moraph.com/get-started](https://www.moraph.com/get-started)
- Partners: [www.moraph.com/partners](https://www.moraph.com/partners)
- Press: [www.moraph.com/newsroom](https://www.moraph.com/newsroom)
- Offices: [www.moraph.com/contact](https://www.moraph.com/contact)
- Support for clients: [support.moraph.com](https://support.moraph.com) · Service status: [status.moraph.com](https://status.moraph.com)
- Security reports: [security@moraph.com](mailto:security@moraph.com) or each repository's private vulnerability reporting; see our [security policy](https://github.com/moraph-com/.github/blob/main/SECURITY.md).
  Do not open a public issue for a vulnerability.
