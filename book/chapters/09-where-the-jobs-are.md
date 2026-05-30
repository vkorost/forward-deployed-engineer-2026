# Chapter 9: Where the Jobs Are

*In this chapter, the book maps the landscape of organizations hiring Forward Deployed Engineers as of Q2 2026. The chapter organizes employers into four tiers, examines the title variants a reader will encounter on job boards, renders the compensation shape across tiers in qualitative terms, and supplies a filtering heuristic for separating genuine FDE roles from services-engineer or implementation-consultant work that has been relabeled to ride the moment.*

---

## The Tier Structure

The FDE labor market in Q2 2026 is not flat. It is a four-tier stack with meaningfully different working conditions, organizational placement, compensation levels, and role definitions at each tier. A job seeker who treats all FDE listings as equivalent will lose time to roles that are structurally incompatible with what the FDE label promises. The tier map is the first filter.

### Tier One: The Origin Tier

Palantir Technologies is where the modern FDE role was invented. The company called its customer-embedded engineers *"Deltas"* internally and, until 2016, employed more Deltas than software engineers.^\[1\]^ The company now uses two primary engineering deployment titles in parallel: Forward Deployed Software Engineer (FDSE) and Forward Deployed Engineer (FDE), where the FDSE designation marks the more product-engineering-specialized variant focused on building production-ready, eventually-productizable components on Foundry and AIP.^\[2\]^

The deployment pod at Palantir is small and intentional: typically one Deployment Strategist (a non-engineering role that bridges technology and organizational priorities) paired with two FDSEs focused on a single customer for a major use case cycle of roughly three months.^\[3\]^ FDSEs report into a deployment engineering organization, not sales. Government FDSEs frequently hold active security clearances. The work scope is real engineering: production code written inside the customer environment, architectural decisions owned end to end, outcomes measured against whether deployed systems move business metrics.

Palantir is the reference architecture for everything that follows. Its compensation sits at the upper end of the tier-one cluster. Its culture has produced the most documented alumni founding network in the role's short history. The Palantir FDSE posting is what the FDE job description is measured against.

### Tier Two: The Frontier Labs

OpenAI and Anthropic entered the FDE market with structures deliberately modeled on Palantir's deployment logic.

OpenAI formalized a Forward Deployed Engineering function in January 2025, built out across San Francisco, New York, Dublin, London, Paris, Munich, and Singapore, and then, in May 2026, launched the OpenAI Deployment Company (a majority-owned subsidiary capitalized at over four billion dollars from nineteen investors including TPG, Advent International, Bain Capital, and Brookfield) with the simultaneous acquisition of Tomoro, a London- and Edinburgh-based applied AI consulting firm whose approximately 150 experienced deployment engineers became the subsidiary's founding technical workforce.^\[4\]^ OpenAI's FDE team sits within the Model Deployment for Business function, not within sales or customer success, and FDEs are measured on whether deployments *"generate tens of millions to sometimes the low billions in value"* for customers.^\[3\]^

Anthropic hires under the title *"Forward Deployed Engineer, Applied AI,"* with federal civilian variants for government accounts.^\[5\]^ The role requires production LLM experience covering prompt engineering, agent development, and evaluation frameworks, and carries approximately 25% travel. Anthropic's founding FDEs are described in the company's own job postings as building an organizational function from scratch, not joining an established one.^\[5\]^ In parallel, Anthropic announced a joint venture with Blackstone, Hellman and Friedman, and Goldman Sachs to launch a standalone enterprise AI services firm targeting healthcare, manufacturing, financial services, and real estate; directly mirroring the OpenAI Deployment Company structure.^\[6\]^

Google Cloud formally adopted the FDE title for its Generative AI deployment function and has published a tiered structure from FDE I through Staff and Senior Staff, organized across four industry verticals: financial services, healthcare, retail, and public sector.^\[7\]^ Google Cloud FDEs reference *"direct access to DeepMind's engineering and research minds"* as a resource; they report within the Cloud organization, not DeepMind Research.

Cohere uses the Forward Deployed Engineer title and segments it by technical specialization: FDE Prompt Specialist, FDE Infrastructure Specialist, FDE Agentic Platform; reflecting the more granular technical requirements of private-cloud and on-premises model deployment for enterprise customers in finance, telecommunications, and healthcare.^\[8\]^

The frontier lab tier clusters at the upper end of FDE compensation, driven by equity exposure at companies whose valuations have moved sharply upward and by the scarcity premium for engineers capable of managing both LLM deployment complexity and enterprise stakeholder relationships. The work is among the most novel in the field: when a capability is genuinely new, the first deployment patterns have to be invented by someone, and frontier lab FDEs are the ones inventing them.

### Tier Three: The Established AI-Adjacent Tier

This tier contains companies whose FDE functions are mature enough to have distinct role levels and established organizational placement, but whose core product is a platform or infrastructure layer rather than a frontier model.

**Scale AI** operates its Forward Deployed Engineering team under the Scale Generative AI Platform umbrella, with multiple FDE levels (Forward Deployed AI Engineer, Senior Forward Deployed AI Engineer, engineering manager). Scale FDEs move customers from prototypes to production on the SGP platform, with their discoveries feeding directly into the core product roadmap.^\[9\]^ Scale's own trajectory (from data annotation services toward an applications business that more than doubled revenue in the second half of 2025) means the FDE function is operating during an explicit transition from services to software, which creates both the urgency and the career visibility that come with being load-bearing during a company's pivot.

**Databricks** is one of the larger FDE employers in the data and AI infrastructure tier. Active titles include Forward Deployed Engineer, Senior Forward Deployed Engineer, AI Engineer - FDE, AI Engineer - FDE (US Federal), and Sr. Manager AI Forward Deployed Engineering.^\[10\]^ Databricks FDEs sit within Professional Services and Operations, not product engineering or sales. The requirement stack spans Python, SQL, Java or Scala, and TypeScript alongside the ability to engage from working engineers to C-level executives.^\[10\]^ Platform-specific roles also appear through system integrator partners; Deloitte, for example, posts *"Forward Deployed Engineer - Databricks"* roles, meaning some of the FDE work at Databricks's customer base is delivered by partner firms rather than Databricks employees directly.

**Snowflake** uses FDE-adjacent titles in its deployment engineering functions. Snowflake's public filings show professional services revenue as a small single-digit percentage of total revenue, deliberately managed as deployment support rather than as a standalone business line.^\[11\]^ The FDE function sits downstream of that logic.

**C3.ai** has FDE-adjacent engineering roles in its enterprise AI deployment teams. The company's professional services revenue has represented a declining share of total revenue over FY2025 as it attempts to shift toward software-only positioning; a cautionary example of what happens when services-driven deployment generates one-time implementation revenue without durable platform lock-in.^\[12\]^

**Ramp** and similarly scaled AI-native fintech and B2B SaaS companies use deployment engineering functions under varying titles, with FDE work concentrated at the intersection of financial data integrations and AI feature deployment for enterprise accounts.

Compensation in the established AI-adjacent tier sits in the middle of the FDE stack: above the corporate-services rebrand tier below, below the frontier lab and Palantir cluster at the top. Companies at this tier typically offer equity alongside base salary, and the equity variable is where individual outcomes diverge.

### Tier Four: The Emerging and AI-First B2B Startup Tier

The third tier of meaningful FDE employers consists of AI-first B2B startups that have reached sufficient scale to maintain a dedicated forward-deployment function. The roles here are genuine engineering work; the tier is distinguished from Tier Three by company stage, not by role quality.

**Sierra** (co-founded by Bret Taylor and Clay Bavor, $100M ARR by November 2025^\[13\]^) uses the title *"Agent Engineer"* for its customer-embedded engineering function, building agents on Sierra's Agent OS platform for enterprise clients. The role requires mastery of LLM orchestration, vector databases, prompt engineering, and Sierra's Agent SDK. Sierra reached a $15.8 billion valuation in its May 2026 Series C.^\[14\]^

**Decagon** assigns dedicated Forward-Deployed Engineers to enterprise accounts, embedded within client teams to accelerate deployment of Decagon's AI concierge platform. The engineering function owns end-to-end execution of AI agent builds and creates direct feedback loops back to the platform team. Typical time-to-deployment is approximately six weeks.^\[15\]^

**Glean** organizes its FDE program around founding-level pods (Founding Forward Deployed Engineers paired with Forward Deployed Product Managers) reporting to cross-functional leadership. The role posting is explicit: *"You won't be configuring existing products or optimizing within defined constraints,"* and it requires a demonstrated track record of 0-to-1 builds with four or more years shipping production software and 25-50% travel.^\[16\]^

**Hebbia** uses the Forward Deployed Engineer title for customer-embedded engineers who own end-to-end execution with strategic customers in finance, law, and consulting, requiring comfort *"hacking directly in front of a customer."*^\[17\]^

**Distyl** uses the title *"Forward Deployed AI Engineer"* explicitly, requiring 25-50% travel and hands-on AI building experience composing LLM and AI components.^\[18\]^

**Cognition** (maker of Devin) uses the title *"Deployed Engineer"* and explicitly expects engineers to *"have a bias towards implementing requested features yourself,"* recruiting from backgrounds at Scale AI, Palantir, Waymo, and Google DeepMind.^\[19\]^

Compensation at this tier is competitive with the established AI-adjacent tier at the mid-to-senior level, though the equity component varies enormously by company stage and trajectory. Early-stage companies often offer higher equity percentages with more speculative upside; the tradeoff for the candidate is liquidity risk and the volatility that comes with pre-revenue or early-revenue companies.

### Tier Five: The Corporate-Services Rebrand Tier

The outermost tier is where the title has reached but the function has not fully followed. The major consulting firms adopted the FDE label in 2025-2026:

**EY** launched a UK and Ireland FDE practice in April 2026, making it one of the first Big Four firms to formally adopt the title, with senior engineers described as embedding directly within client delivery teams to *"design, build, integrate, and operationalize AI solutions in live environments."*^\[20\]^

**Deloitte** announced a Forward Deployed Engineering practice with cross-disciplinary pods and explicitly engagement language around speed to production and co-creation, and also hires platform-specific FDEs including *"Lead Forward Deployed Engineer - Databricks"* and *"OpenAI Forward Deployed Engineer - GPS"* within its Government and Public Services practice.^\[21\]^

**IBM Consulting** launched *"Forward Deployed Units"* (FDUs) in May 2026: pod-based teams of six that IBM frames as doing the work of a 30-person traditional consulting team, with IBM Consulting Advantage providing reusable AI agents for coding, evaluation, testing, and documentation while human FDEs handle design, stakeholder work, and production oversight.^\[22\]^

**Accenture** launched a Microsoft Forward Deployed Engineering Practice and separately partnered with Google Cloud through the Gemini Enterprise Acceleration Program.^\[23\]^

The consulting tier presents the hardest filtering problem. These firms use all the right language: embedding, pods, production-outcome framing, co-creation. The core uncertainty (whether their engineers write production code in client environments or primarily produce architectural artifacts, playbooks, and change management frameworks) is not consistently resolved in public disclosures. IBM's FDU model explicitly delegates production coding to AI agents under human supervision, which is a materially different role than the Palantir or OpenAI FDE standard. The filtering heuristic section below addresses this directly.

Compensation in the corporate-services rebrand tier sits at the lower end of the FDE stack. The variable compensation structure at consulting firms leans toward performance bonuses and billable-hours metrics rather than the equity-plus-base structure that characterizes the tiers above. The role profile also skews toward advisory and change management work, which means the Production Muscle (the engineering capability that transfers directly into product company FDE roles) is less exercised and atrophies faster.

---

## Title Variants: The Search Vocabulary

The FDE title has not standardized. A job search that uses only the string *"Forward Deployed Engineer"* misses a significant portion of active postings. The following title variants appear in active job boards as of Q2 2026 for roles that share the same core function:

**Forward Deployed Engineer (FDE)** is the broadest usage, spanning Tiers One through Five. It appears at Palantir, OpenAI, Databricks, Glean, Decagon, Hebbia, Cohere, Google Cloud, and the consulting firms.

**Forward Deployed Software Engineer (FDSE)** is Palantir-specific and marks the more product-engineering-specialized variant. Candidates searching for the Palantir role must use this variant.

**Forward Deployed AI Engineer (FDAIE or FDAE)** appears at Distyl, Scale AI, and a cohort of YC-backed AI startups. The AI suffix signals explicit LLM and agent work rather than generalist data engineering deployment.

**Applied AI Engineer** is Anthropic's preferred title for the same function. The FDE Academy's analysis concludes that *"Applied AI Engineer"* and *"Forward Deployed Engineer"* are *"largely the same role under different titles"* with narrow functional differences: Applied AI Engineer postings emphasize AI quality, evaluation rigor, safety, and model behavior; FDE postings emphasize integration, distributed systems, and deployment reliability.^\[24\]^ The practical advice from practitioners is to apply broadly regardless of which title the employer uses.

**Solutions Engineer at AI-first companies** occupies an ambiguous position. At product companies with AI-first GTM models, Solutions Engineer can be genuinely FDE-adjacent work: pre-sales technical depth combined with a post-sale handoff that requires production code. At more conventional SaaS companies, Solutions Engineer is sales support. The filtering heuristic below applies with particular force here.

**Implementation Engineer** appears at companies deploying SaaS products with complex integration requirements. At AI-native companies, it often describes work that is functionally FDE; at legacy SaaS companies, it describes onboarding and configuration work.

**Deployed Engineer** is Cognition's company-specific variant.

**Agent Engineer** is Sierra's company-specific variant, domain-scoped to its platform.

**Member of Technical Staff (MTS)** at certain labs sometimes covers FDE-adjacent work, though MTS more commonly signals a research or product engineering role. The distinction requires reading the job description, not the title.

The search strategy that works: run queries across all variants simultaneously, filter by company first (using the tier map), then apply the filtering heuristic to the listing text itself.

---

## Compensation by Tier: The Shape Without the Numbers

The compensation rule in this book is strict: no dollar figures, no salary ranges, no total-comp distributions. Published compensation data contains these figures; this chapter does not reproduce them. What follows is the tier shape, rendered in terms that are useful for negotiation framing without substituting for the candidate's own current market research.

**Tier One (Palantir) and Tier Two (frontier labs) cluster at the upper end.** Palantir's equity upside at senior levels is substantial, driven by the company's stock performance over 2024-2026. Frontier labs (OpenAI, Anthropic) offer compensation benchmarked against their product engineering peers, with equity as the primary variable lever. The AI premium on FDE roles at these employers is real, documented across multiple compensation aggregators, and grows with seniority. At the staff level, the premium over comparable non-AI engineering roles is meaningfully larger than at the mid level.^\[25\]^

**Tier Three (established AI-adjacent SaaS) sits in the middle.** Companies like Scale AI, Databricks, and Snowflake offer FDE compensation competitive with their product engineering peers. The equity component is present but less speculative than at frontier labs; these are later-stage companies with more predictable equity value. The AI premium applies here as well, though the magnitude is somewhat lower than at Tier Two.

**The next layer of AI-first B2B startups spans a wide range within the middle tier.** At companies with $100M+ ARR and recent large funding rounds (Sierra, Glean), compensation reaches the lower bound of Tier Three. At earlier-stage companies, base salary may compress in exchange for equity percentage and upside potential. The tradeoff is liquidity timeline and dilution risk.

**The corporate-services rebrand tier (Tier Five) sits at the lower end of the FDE stack.** Consulting firm compensation structures are not engineering-benchmark compensation structures. Base salaries at senior levels at Big Four firms are competitive, but the equity component is absent (consulting firms are not equity-granting companies in the same sense), and the variable compensation structure is tied to utilization and billable metrics rather than to product company equity appreciation. The practical compensation gap between a Tier Two FDE and a Big Four FDE in an equivalent role level is significant.

**Government-clearance FDE roles carry a premium not captured in posted salary bands.** Active Secret or TS/SCI clearance adds material value in the federal contractor market across all tiers. This premium is documented in the literature but the specific magnitude varies by clearance level, employer, and contract structure.^\[26\]^

The single most reliable real-time source for tier-specific compensation data is Levels.fyi, filtered by company and title. FDE Pulse maintains a dataset of active postings with salary disclosure rates. Blind has discussed data points, though with small sample sizes for frontier-lab FDE-specific roles. The candidate's responsibility is to pull current data at the time of negotiation; the tier-shape orientation above tells the reader where to look, not what numbers to expect.

---

## The Filtering Heuristic: Real FDE or Relabeled Sales Engineer

An analysis of approximately 1,000 FDE job postings found that roughly 30% were what the analysis termed *"Sales Engineer+"* (solutions engineers relabeled as FDEs) while 60% were genuine builder FDE roles and 10% were internal GTM tooling roles mislabeled.^\[27\]^ That 30% noise rate means the reader needs a working filter. Three tests.

### Test One: Does the Role Write Production Code

This is the dispositive test. Genuine FDE roles require production code written inside the customer environment: not demos, not configuration, not proofs of concept. The job description language that signals genuine FDE work: *"write production applications with [model name],"* *"deliver technical artifacts including MCP servers, sub-agents,"* *"own the behavior and performance of AI systems deployed for customers."*^\[5\]^^\[18\]^

The job description language that signals sales-engineer rebrand: *"run demos,"* *"support technical evaluation,"* *"build proof of concept."*

The compensation structure is a second signal within this test. Genuine FDE roles at product companies are compensated as engineering roles, typically with base plus equity. The analysis found zero quota-carrying positions among verified genuine FDE roles, and only 8% of genuine FDE postings mentioned OTE (on-target earnings).^\[27\]^ A listing with a quota or a commission structure is a sales engineer role, regardless of what the title says.^\[27\]^

### Test Two: Does the Role Embed at Customer Sites

Genuine FDE roles require physical or deep virtual embedding. The standard travel commitment in verified genuine FDE postings is 25-50%, with multi-week or multi-month customer engagements.^\[5\]^^\[16\]^^\[18\]^ Palantir assigns FDSEs to one customer exclusively for months at a time.^\[28\]^ OpenAI's FDE team commits long enough to *"prove the deployment actually moved a business metric."*^\[3\]^

Short-burst engagements (demo days, executive briefings, one-day workshops) are not embedding. A listing that describes *"regular customer visits"* or *"executive presentations"* as the customer-facing component is describing a pre-sales motion, not an FDE deployment.

### Test Three: Does the Role Own Customer Outcomes

Outcome ownership means the engineer is accountable for whether the deployed system performs in production. This is distinct from two adjacent functions: sales, where the engineer is accountable for whether a contract is signed; and customer success, where the engineer is accountable for whether the customer is satisfied. FDE outcome accountability is engineering accountability.

A former Palantir engineer writing about FDE culture offers a practical variant of this test: if management scrutinizes customer engagement margins closely, the function is practicing solutions engineering; genuine FDE organizations treat customer deployment work as R&D investment and accept negative-margin pilots because the learning feeds the platform.^\[29\]^ The Bloomberry analysis of 1,000 postings adds a sharper version: *"If the job has a quota or commission, it is a Sales Engineer (even if they call it FDE)."*^\[27\]^

### Where the Lines Genuinely Blur

The consulting tier is the hardest case. EY, Deloitte, IBM, and Accenture use embedding language, pod-based structures, and production-outcome framing. They have also invested in the infrastructure of the FDE function at a level that separates them from purely marketing-driven relabeling. The key uncertainty is whether their engineers write production code in client environments or primarily produce architectural artifacts, playbooks, and change management frameworks. IBM's FDU model explicitly delegates a portion of production coding to AI agents under human supervision; this is a structurally different role from the engineering-heavy FDE at Palantir or Anthropic, and one where the Production Muscle exercises less than at product companies.^\[22\]^ Whether that gap matters to a specific candidate depends on what they are trying to build: if the goal is a product-company FDE role in two years, consulting-tier FDE experience in an advisory-heavy engagement model may not generate the portfolio evidence that product-company hiring managers are looking for.

The second blur zone is *"Solutions Engineer at an AI-first company."* At a company like Glean, the Solutions Engineering function is meaningfully adjacent to FDE work; the same is true at Sierra and Decagon equivalents. At a conventional SaaS company that recently attached *"AI"* to its product name, Solutions Engineering is pre-sales support with a few AI feature demos added. The company's primary revenue model is the signal: if the company sells SaaS subscriptions and the SE org closes the deal, the SE is pre-sales. If the company's primary revenue driver is the enterprise AI deployment itself, the SE is FDE-adjacent.

### The Positive-Signal Checklist

For any listing that passes ambiguous, the following in the job description are positive signals of genuine FDE work:

- Production code requirements in the posting (Python, TypeScript, or Go specified alongside system design or data pipeline work)
- Explicit mention of writing code in the customer environment, not at the company's own offices
- Travel requirement of 25% or more stated explicitly
- Equity as part of the compensation structure
- Reporting line into engineering, not sales or customer success
- Language about owning outcomes in production, not *"supporting"* outcomes or *"enabling"* customers
- Reference to specific AI frameworks, evaluation methods, or deployment tooling (MCP, vector stores, agent orchestration, evals) rather than generic *"AI solutions"* language
- Absence of quota, OTE, or commission language anywhere in the posting

No single signal is definitive. All seven together are close.

---

## The Cycle Signature in the Job Market

The Cycle operates at the title level as well as at the function level. In Q2 2026, the FDE title is mid-expansion: the volume of postings is high, the quality variance is high, and The Snapshot Manual observation applies directly: the title is still sincere at Tiers One through Three and is increasingly cosmetic at Tier Five. The expansion phase of The Cycle is precisely when filtering discipline matters most, because the signal-to-noise ratio degrades fastest between the moment a title becomes widely recognized and the moment it becomes truly commoditized.

The tier map and the filtering heuristic in this chapter are mid-Cycle tools. By 2027-2028, if the trajectory documented in this manual holds, a portion of the Tier Five listings will have reverted to their prior titles, the genuine FDE function will have consolidated further into the most complex, highest-stakes deployments, and the title itself will have bifurcated into something more specific at the high end and something more generic at the low end. The reader who applies these tools today is acting on a window that is open but not indefinitely so.

---

## Key Points

- The FDE job market organizes into five tiers: Palantir as origin tier; frontier labs (OpenAI, Anthropic, Google Cloud, Cohere) as the premium cluster; established AI-adjacent SaaS (Scale AI, Databricks, Snowflake) as the middle band; AI-first B2B startups (Sierra, Glean, Decagon, Hebbia, Distyl, Cognition) as the emerging layer; and consulting firms (EY, Deloitte, IBM, Accenture) as the corporate-services rebrand tier.
- Title variants requiring active search include FDE, FDSE, FDAIE, Applied AI Engineer, Solutions Engineer at AI-first companies, Implementation Engineer, Deployed Engineer, Agent Engineer, and MTS in specific contexts.
- Frontier labs and Palantir cluster at the upper end of FDE compensation; established AI-adjacent SaaS sits in the middle; the corporate-services rebrand tier sits at the lower end.
- The dispositive filter for genuine FDE versus relabeled sales engineer is the production-code requirement: does the posting require writing code inside the customer environment, with outcome accountability for production system performance.
- A quota, commission, or OTE structure in any FDE listing is a conclusive signal that the role is sales engineering under a different title.
- The Cycle is visible in real time in the job market: the title is sincere at Tiers One through Three and increasingly cosmetic at Tier Five, and the filtering heuristic is the tool for acting on that distinction.

---

