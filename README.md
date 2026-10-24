# Hi, I'm Aswin (Ash) Biju

**MBA · International Business Consulting** (Hochschule Offenburg, Germany). Engineering-trained analyst working at the intersection of **business processes, data, AI adoption and organisational change**. I turn messy problems into structured models, measurable KPIs, and decisions people can act on.

Currently seeking **Werkstudent / internship roles** in AI automation and growth, consulting, strategy, business operations and process management across Germany.

---

## Portfolio

Applied projects from my MBA, venture work and my own AI builds. Each is a self-contained case study with models, data, and documentation.

### AI & automation

**[Setu: EU-India Commercial Decision Engine](https://github.com/aswin-bijju/setu-decision-engine)**
A decision engine for B2B revenue teams selling between Europe and India. It matches signals from 10 sources to the right account and deal, has specialist agents propose decisions, and gives a sales leader up to ten ranked calls a week, each with its evidence, counter-signals and confidence.
Agent rules are deterministic, so every call traces back to specific signals and CRM fields, and nothing is written to the CRM or Slack without approval. A Corridor agent flags what general revenue tools miss: Diwali and fiscal-year timing, EUR/INR drift, GDPR and DPDP data transfers, CBAM and works councils.
`Python` · `SQLite` · `Agent design` · `Human-in-the-loop` · `Revenue operations` · `EU-India`

**[AIA Signal Pipeline: News-to-Team Briefing Agents](https://github.com/aswin-bijju/AIA-Signal-Pipeline-Prototype)**
A daily agent pipeline that reads trade and shipping news, routes each development to the team it affects using an organisation map, and holds back stories a team has already seen that week.
Models classify and write; routing stays in plain, testable rules, and every brief needs human approval in Slack before delivery.
Testing on live feeds surfaced three failure modes (a catch-all region tag, a false "update" from a lossy summary, one malformed model reply halting a full run), each fixed and documented.

`n8n` · `Claude` · `Agent design` · `Human-in-the-loop` · `Slack automation`

**[Human-Approved AI Agents: a 35-agent personal office](https://github.com/aswin-bijju/human-approved-ai-agents)**
Set up 35 role-based Claude Code agents on Agents Office (by Sahni.ai) for my job search, LinkedIn, thesis and admin, connected to Gmail, Calendar, Drive, Slack and Notion. Designed a three-layer approval system (an app allow-list, 45 tool-level block rules and a fail-closed launcher) so the agents can read and draft, but nothing is sent, booked or changed without my sign-off.
`AI agents` · `Claude Code` · `MCP connectors` · `Human-in-the-loop` · `Least-privilege access`

### Process & data

**[SafeProtect: Claims Process Digitalization](https://github.com/aswin-bijju/safeprotect-claims-process)**
End-to-end redesign of an insurance claims process: BPMN 2.0 modelling, process-driven IT architecture, an automation concept, a Power BI KPI dashboard, and process mining in Apromore. Discovered an undocumented escalation rule hidden in a 1,200-case event log and validated the model against the data.
`BPMN 2.0` · `Process Mining` · `Power BI / DAX` · `Apromore` · `KPI design`

**[Patient Flow & Capacity Analysis in Simio](https://github.com/aswin-bijju/simio-patient-flow-simulation)**
Discrete-event simulation of a planned medical practice, answering four client questions before opening. Static capacity arithmetic predicted the bottleneck; two Simio prototypes proved that a fourth doctor, not a sixth room or a third assistant, was the intervention that works.
`Discrete-event simulation` · `Simio` · `Bottleneck analysis` · `Scenario testing`

### Strategy & finance

**[Truvenix India: Market Entry at Vizhinjam Port, Kerala](https://github.com/aswin-bijju/truvenix-india-market-entry)**
Market-entry case and ₹1.2 crore seed pitch for taking a UK freight brokerage into India's newest gateway port. Sized the road-haulage market top-down from the port's own target (₹106 to 212 crore a year), found that brokerage alone only breaks even at 144 loads a month, and built a two-tranche plan where a volume gate caps investor downside at ₹30 lakh. Live venture work as strategy lead.
`Market entry` · `Market sizing` · `Unit economics` · `Scenario modelling` · `Milestone financing`

**[WaldWürfel: Business Plan & Cost Accounting Model](https://github.com/aswin-bijju/waldwuerfel-financial-model)**
Five-year business plan for a Black Forest manufacturing start-up. I owned the costing and financial analysis: cost structure, contribution margin by product line, break-even (~31,300 units, profitable from Year 2), and margin of safety reaching +61% by Year 5.
`Cost accounting` · `Contribution margin` · `Break-even analysis` · `Financial modelling` · `EVA`

**[Benchmarking Proposal: Company XYZ Data Centres](https://github.com/aswin-bijju/benchmarking-tqm-proposal)**
Redesigned a failing global benchmarking programme: replaced three simultaneous regional studies with a staggered three-year functional benchmarking cycle, embedded in TQM via PDCA and pre-screened with FMEA at an RPN ≥ 225 threshold.
`Benchmarking` · `TQM` · `PDCA` · `FMEA / RPN` · `Gap analysis`

### Change & people

**[SAP S/4HANA at Deutsche Bahn: People Management Analysis](https://github.com/aswin-bijju/sap-s4hana-change-management)**
People-and-change analysis of a €380M ERP transformation across 45,000 users and 12 countries: stakeholder mapping, works council (Betriebsrat) dynamics, resistance patterns, and leadership evaluation. Includes a reflection paper on expatriate cultural adjustment.
`Change management` · `IHRM` · `Stakeholder analysis` · `Intercultural competence`

**[The Psychology of Consulting: Workshop](https://github.com/aswin-bijju/consulting-psychology-workshop)**
A three-hour workshop I designed and delivered to my MBA cohort on how people learn, how experts decide under pressure, and why structured thinking wins. This course seeded my thesis direction on expertise-based identity threat and resistance to AI-augmented work.
`Cynefin` · `Recognition-Primed Decision` · `Spiral Dynamics` · `Facilitation`

---

## Also covered in the MBA

Beyond the projects above, the programme spanned: **Corporate Finance I & II** (DCF and multiples valuation, capital structure, EVA and value-based management) · **Cost & Performance Accounting** (full and partial costing, process costing) · **Financial Reporting** (IFRS, statement analysis) · **Production & Operations Management** (lean production, layout and capacity design) · **Supply Chain Management** (network structures, process optimisation, make-or-buy) · **Strategic & Marketing Management** (STP, product/pricing/distribution/communication strategy, global strategy) · **International Economic Law** (WTO law, international investment law, EU competition law) · **Turnaround Management** (distress diagnosis, restructuring, first-100-days leadership) · **Design Thinking** (charetting, personas, creative matrix; designed a 9-hour sales workshop) · **Organizational Behavior** (emotional intelligence in leadership) · **Advanced Accounting** (TOPSIM six-period general management simulation) · **Scientific Work** (research design and academic writing).

Also placed **first by equity** in a three-day board-based Board of Directors business simulation, running the finance and accounting side manually while bidding for orders in global markets.

---

## Toolbox

**Process & BPM:** BPMN 2.0 (bpmn.io) · Process Mining (Apromore) · Simio
**Data & BI:** Power BI (DAX) · KNIME · Excel modelling
**Consulting:** hypothesis-driven problem framing · change frameworks (Kotter, Lewin, ADKAR) · organisational psychology
**AI & automation:** Claude Code · MCP connectors · agent permission and approval design · Claude, Notion, Perplexity, n8n, slack
**Languages:** English (C1) · German (B1, developing) · Malayalam (native)

## About

Cross-cultural background across India, Germany, and the MENA region · FIDE-rated chess player · independent research-AI agent project [AIA Stakeholder Intelligence] · daily practitioner of agentic AI workflows.

📫 aswin.bijju@gmail.com

> Most portfolio projects are academic MBA coursework on fictional or anonymised scenarios; methods and tooling are real. Truvenix India is live venture work, and its figures are planning assumptions, not results. Setu is a working prototype that runs on fictional demo data. Human-Approved AI Agents is a personal build on third-party software (Agents Office by Sahni.ai), set up with Claude as a build partner. Team projects credit all contributors and state my individual contribution.
