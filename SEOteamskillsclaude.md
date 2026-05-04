[seo-team-skills.md](https://github.com/user-attachments/files/27376641/seo-team-skills.md)
# SEO Automation Team — Full Skills Handbook

> **Brand type:** B2C  
> **Use case:** Brand building & organic growth  
> **System:** AI-powered multi-agent SEO team  
> **Cycle frequency:** Every 1 hour (CRO audit) → continuous agent execution

---

## Table of Contents

1. [CRO Agent — Conversion Rate Optimisation](#1-cro-agent)
2. [Keyword Planner Agent](#2-keyword-planner-agent)
3. [On-Page SEO Agent](#3-on-page-seo-agent)
4. [Off-Page SEO Agent](#4-off-page-seo-agent)
5. [Backlink Agent](#5-backlink-agent)
6. [Technical SEO Agent](#6-technical-seo-agent) *(added)*
7. [Content Strategy Agent](#7-content-strategy-agent) *(added)*
8. [Local SEO Agent](#8-local-seo-agent) *(added)*
9. [Analytics & Reporting Agent](#9-analytics--reporting-agent) *(added)*
10. [Agent Workflow & Collaboration Map](#10-agent-workflow--collaboration-map)
11. [CEO Approval Protocol](#11-ceo-approval-protocol)

---

## 1. CRO Agent

**Role:** Conversion Rate Optimiser — the team lead that triggers the entire workflow.

### What it does
- Runs a full site audit every hour across all pages
- Identifies friction points, UX gaps, low-converting pages, and speed bottlenecks
- Dispatches action briefs via email to On-Page and Off-Page agents
- Scores each page against a CRO rubric (0–100)

### Core skills

**Site audit**
- Crawls all pages and flags broken elements, missing tags, slow load times
- Scores Core Web Vitals: LCP (target < 2s), CLS (target < 0.1), FID (target < 100ms)
- Checks mobile responsiveness across key device breakpoints

**Heatmap & funnel analysis**
- Analyses click maps, scroll depth, and rage clicks on top 10 pages
- Identifies funnel drop-off points (e.g. cart → checkout → payment)
- Flags CTAs that are below the fold or poorly worded

**CTA & conversion scoring**
- Scores headline clarity, CTA visibility, social proof placement, trust signals
- Benchmarks against competitor landing pages
- Recommends A/B test hypotheses

**Brief generation (agent output)**
- Writes structured email briefs to On-Page Agent (content + meta fixes)
- Writes structured email briefs to Off-Page Agent (authority + PR gaps)
- Sends summary to Keyword Planner Agent (high-intent page gaps)

### Output format
- CRO Score per page (0–100)
- Priority level per issue: 🔴 Critical / 🟡 High / 🟢 Low
- Estimated traffic impact per fix
- Email brief to relevant agents

### KPIs tracked
- Bounce rate
- Cart abandonment rate
- Average session duration
- Conversion rate (CVR) per page
- CRO score trend (week-on-week)

---

## 2. Keyword Planner Agent

**Role:** Research & keyword strategy — feeds all agents with targets.

### What it does
- Researches, clusters, and shortlists keywords based on brand category, competition gap, and search intent
- Supplies keyword targets to On-Page and Off-Page agents every cycle
- Monitors keyword ranking movements daily

### Core skills

**Keyword research**
- Seed keyword expansion using brand terms, competitor terms, and category terms
- Long-tail keyword discovery for low-competition, high-intent queries
- Semantic keyword clustering into topic groups

**Search intent classification**
- Tags each keyword: Informational / Navigational / Commercial / Transactional
- Maps intent to funnel stage (TOFU / MOFU / BOFU)
- Aligns intent with content type recommendation (blog / landing page / product page)

**Competitor keyword gap analysis**
- Scrapes top 5 competitors' ranking keywords
- Identifies keywords competitors rank for that the brand does not
- Prioritises gaps by volume × difficulty score

**SERP feature targeting**
- Identifies featured snippet, People Also Ask, and image pack opportunities
- Recommends content format to win each SERP feature
- Tracks brand's current SERP feature ownership

**Keyword shortlisting**
- Scores each keyword: Volume × (1 / Difficulty) × Intent match
- Produces a final shortlist of 8–15 priority keywords per cycle
- Assigns each keyword to a specific page or content piece

### Output format
| Keyword | Volume | KD | Intent | SERP feature | Target page | Rank goal | Timeline |
|---|---|---|---|---|---|---|---|
| example keyword | 12,400 | 28 | Transactional | None | /product | Top 3 | 4–6 wks |

### KPIs tracked
- Keywords in top 3 / top 10 / top 20
- Average ranking position
- Keyword ranking velocity (positions gained per week)
- SERP feature ownership count

---

## 3. On-Page SEO Agent

**Role:** Content & technical on-page optimisation — executes fixes on the site.

### What it does
- Receives briefs from CRO Agent and keyword targets from Keyword Planner
- Optimises all on-page elements across the site
- Writes and publishes SEO-optimised content

### Core skills

**Meta tag optimisation**
- Rewrites title tags (50–60 chars, primary keyword in first 30 chars)
- Rewrites meta descriptions (150–160 chars, includes CTA, keyword)
- Ensures no duplicate meta across pages

**Heading structure**
- Audits and fixes H1/H2/H3 hierarchy across all pages
- Ensures one H1 per page, contains primary keyword
- Adds H2s for each major content section with secondary keywords

**Content optimisation**
- Checks keyword density (target 1–2% for primary keyword)
- Adds LSI (Latent Semantic Indexing) keywords naturally within content
- Improves readability score (target Flesch-Kincaid 60+)
- Adds word count to thin pages (target 1,200+ words for pillar pages)

**Schema markup**
- Adds Product schema to all product pages
- Adds FAQ schema to blog and landing pages
- Adds BreadcrumbList schema site-wide
- Adds Review/Rating schema where applicable

**Internal linking**
- Builds a topical cluster linking structure
- Adds 3–5 internal links per new page to relevant cluster pages
- Fixes orphan pages (pages with zero internal links)
- Optimises anchor text diversity (branded / exact / partial match / generic)

**Image SEO**
- Writes descriptive alt text for every image (includes keyword where natural)
- Compresses images to WebP format
- Adds structured file names (keyword-descriptive-name.webp)

**Content brief writing**
- Writes detailed briefs for new blog posts: angle, keywords, outline, word count, SERP target
- Assigns each brief to a content topic cluster

### Output format
- Page-by-page optimisation log
- Content brief document per new piece
- Internal link map (spreadsheet)
- Before/after meta tag report

### KPIs tracked
- Pages with optimised meta: % complete
- Schema coverage: % of eligible pages
- Internal link equity score
- Organic CTR (from Google Search Console)
- Average ranking position for target keywords

---

## 4. Off-Page SEO Agent

**Role:** Brand authority building — grows the brand's presence and reputation across the web.

### What it does
- Receives CRO brief on brand authority gaps
- Manages digital PR, guest posting, influencer outreach, and brand mentions
- Works in parallel with the Backlink Agent (complementary, not duplicate)

### Core skills

**Digital PR**
- Identifies trending topics that align with the brand's category
- Pitches stories to beauty, lifestyle, and health publications (DA 40+)
- Monitors journalist requests (HARO, Qwoted, SourceBottle)
- Tracks press mentions and measures DA of coverage

**Guest posting**
- Identifies relevant guest post opportunities in niche (DA 40+ only)
- Writes or briefs guest post content aligned to target keywords
- Ensures each guest post links to a specific target page with agreed anchor text

**Unlinked brand mention conversion**
- Monitors the web for brand name mentions with no backlink
- Sends outreach to convert unlinked mentions to dofollow links
- Target: convert 30%+ of unlinked mentions per cycle

**Influencer & UGC collaboration**
- Identifies micro-influencers (10k–100k followers) in the brand niche
- Outreaches for product collaboration / review content
- Ensures content includes a linkable brand mention or bio link

**Competitor brand monitoring**
- Tracks competitor PR coverage and guest post placements
- Identifies publications covering competitors but not the brand
- Pitches those same publications with a differentiated angle

**Social signal amplification**
- Shares all new content across relevant social channels
- Submits content to relevant communities (Reddit, Quora, niche forums)
- Builds topical authority signals through consistent content distribution

### Output format
- Weekly outreach tracker (target, DA, status, link acquired)
- PR placement log (publication, date, DA, anchor text, target URL)
- Influencer collaboration pipeline
- Unlinked mention report

### KPIs tracked
- Referring domain count (monthly growth)
- Press placements secured
- Influencer mentions
- Social referral traffic
- Brand search volume trend

---

## 5. Backlink Agent

**Role:** Link acquisition specialist — builds high-quality backlinks through proven techniques.

### What it does
- Specialises in structured link-building campaigns
- Targets high-DA, niche-relevant domains
- Works alongside Off-Page Agent (Off-Page = brand/PR, Backlink = technical link building)

### Core skills

**Broken link building**
- Scans competitor and niche websites for broken outbound links
- Creates or identifies existing brand content that is a suitable replacement
- Sends personalised outreach to replace broken link with brand link

**Resource page link building**
- Identifies "best of" and resource pages in the niche
- Pitches the brand's content/product as a resource addition
- Target: 10+ resource page links per month

**Skyscraper technique**
- Identifies top-performing content in the niche (by backlink count)
- Creates a superior version of that content for the brand
- Outreaches to all sites linking to the original, pitching the better version

**HARO / journalist outreach**
- Monitors Help a Reporter Out (HARO) for relevant queries
- Submits expert quotes on behalf of the brand
- Tracks pick-up rate and resulting backlinks

**Niche edit / link insertion**
- Identifies live articles on niche sites that could naturally include a brand link
- Outreaches to site owners for a contextual link insertion
- Ensures editorial relevance and natural anchor text

**Competitor backlink replication**
- Exports full backlink profile of top 3 competitors
- Identifies the top 50 links that can be replicated
- Executes outreach campaign to win those same links

**Toxic link audit & disavow**
- Scans backlink profile for spammy, low-quality, or irrelevant links
- Prepares Google Search Console disavow file quarterly
- Monitors link velocity for unnatural spikes

### Output format
- Active link building campaign tracker (technique, target, status, DA, anchor)
- Monthly link acquisition report
- Disavow file (when applicable)
- Backlink profile health score

### KPIs tracked
- Total backlinks (monthly)
- Referring domains (monthly)
- Domain Rating / Domain Authority trend
- Average DA of acquired links
- Link velocity (links per week)
- Toxic link % (target < 5%)

---

## 6. Technical SEO Agent

*(Added — critical for B2C brands with large product catalogues)*

**Role:** Site health & crawlability — ensures Google can find, crawl, and index every page.

### What it does
- Monitors and fixes all technical SEO issues that block rankings
- Manages site architecture, crawl budget, and indexation

### Core skills

**Crawl & indexation**
- Monitors Google Search Console for crawl errors and coverage issues
- Fixes 4xx, 5xx errors, and redirect chains
- Manages robots.txt and XML sitemap (submits to Search Console weekly)

**Site speed optimisation**
- Implements lazy loading, image compression, browser caching
- Minimises render-blocking resources (CSS/JS)
- Monitors Core Web Vitals (LCP, CLS, FID) — alerts if any score drops

**Structured data & rich results**
- Validates all schema markup via Google's Rich Results Test
- Monitors rich result appearance in SERPs
- Fixes schema errors flagged in Search Console

**Canonicalisation**
- Adds canonical tags to all pages to prevent duplicate content
- Manages hreflang tags for any multi-language pages
- Resolves duplicate content issues from URL parameters

**Mobile & UX technical checks**
- Ensures all pages pass Google's Mobile-Friendly Test
- Audits tap target sizes, font sizes, and viewport configuration

### KPIs tracked
- Crawl error count (target: 0 critical errors)
- Indexed pages vs total pages ratio
- Core Web Vitals pass rate (target: 100%)
- Pages with valid schema markup (%)

---

## 7. Content Strategy Agent

*(Added — essential for B2C brand building)*

**Role:** Topical authority builder — plans and governs the brand's content ecosystem.

### What it does
- Builds a long-term content calendar aligned to keyword clusters and brand pillars
- Ensures all content serves both SEO goals and brand storytelling

### Core skills

**Content pillar planning**
- Defines 4–6 core topic pillars aligned to brand positioning
- Maps each pillar to a cluster of supporting content pieces
- Creates pillar pages (2,000+ words) and cluster pages (1,200+ words)

**Content calendar management**
- Plans 12-week rolling content calendar
- Assigns each piece: keyword target, intent, format, word count, CTA
- Ensures balanced mix: educational / product / brand / seasonal

**Content performance audit**
- Identifies underperforming content (traffic < target, low dwell time)
- Recommends refresh, consolidate, or delete for each piece
- Tracks content decay and schedules refreshes every 6 months

**Brand voice & tone guidelines**
- Maintains SEO content that is consistent with brand's tone (luxury, premium, accessible)
- Ensures content balances keyword inclusion with natural readability

### KPIs tracked
- Organic traffic per content piece
- Dwell time / time on page
- Social shares per content piece
- Content-to-ranking ratio (pieces that rank in top 10)

---

## 8. Local SEO Agent

*(Added — relevant for B2C brands with physical presence or India-specific targeting)*

**Role:** Local & regional visibility — ranks the brand in geo-specific searches.

### Core skills

**Google Business Profile management**
- Keeps GBP listing complete, accurate, and active
- Posts weekly updates, products, and offers
- Monitors and responds to all reviews within 24 hours

**Local keyword targeting**
- Identifies city/region-specific keyword variations
- Creates location-specific landing pages where relevant
- Optimises for "near me" and "in [city]" search queries

**Citation building**
- Ensures consistent NAP (Name, Address, Phone) across all directories
- Submits to India-relevant directories: Justdial, Sulekha, IndiaMART, etc.

**Review generation**
- Automates post-purchase review request emails
- Monitors review sentiment and flags negative reviews for response

### KPIs tracked
- GBP impressions and clicks
- Local pack appearances
- Average star rating
- Review count (monthly growth)

---

## 9. Analytics & Reporting Agent

*(Added — ties all agents together with data)*

**Role:** Data pipeline & insight layer — measures what all agents are doing and translates it into decisions.

### Core skills

**SEO dashboard maintenance**
- Maintains a live dashboard: rankings, traffic, backlinks, conversions
- Pulls data from: Google Search Console, GA4, Ahrefs/SEMrush, Google Business Profile

**Weekly performance report**
- Compiles agent activity log into a human-readable report
- Highlights wins, misses, and recommendations for next cycle
- Calculates ROI of SEO efforts (organic revenue / SEO investment)

**Rank tracking**
- Tracks daily rankings for all shortlisted keywords
- Alerts agents when a keyword drops more than 3 positions
- Tracks competitor ranking changes weekly

**Anomaly detection**
- Monitors for sudden traffic drops (algorithm updates, manual penalties, technical issues)
- Alerts Technical SEO Agent immediately if indexation drops
- Monitors for negative SEO attacks (sudden toxic backlink spikes)

**CEO report generation**
- Summarises the full cycle in a short executive brief
- Includes: what was done, current rankings, projected rankings, traffic forecast, revenue impact
- Sends for approval before next cycle begins

### KPIs tracked (master dashboard)
- Organic sessions (weekly/monthly)
- Keywords in top 3 / 10 / 20
- Domain Rating
- Referring domains
- Organic revenue (GA4 e-commerce)
- CVR from organic channel
- ROI of SEO investment

---

## 10. Agent Workflow & Collaboration Map

```
HOUR 0
  └── CRO Agent runs full site audit (hourly)
        ├── → Email brief → On-Page Agent  (meta, content, schema fixes)
        ├── → Email brief → Off-Page Agent  (authority gaps, PR opportunities)
        └── → Summary → Keyword Planner Agent  (page intent gaps)

HOUR 1–4 (parallel execution)
  ├── Keyword Planner Agent
  │     ├── Shortlists 8–15 priority keywords
  │     └── Feeds targets → On-Page + Off-Page + Backlink agents
  │
  ├── On-Page Agent
  │     ├── Executes meta, H1, schema, content, internal link fixes
  │     └── Writes content briefs for Content Strategy Agent
  │
  ├── Off-Page Agent
  │     ├── Runs PR pitches, influencer outreach, mention conversion
  │     └── Reports acquired links → Backlink Agent (to avoid duplication)
  │
  ├── Backlink Agent
  │     ├── Runs broken link, skyscraper, HARO, niche edit campaigns
  │     └── Reports new links → Analytics Agent
  │
  └── Technical SEO Agent
        ├── Monitors crawl health, speeds, Core Web Vitals
        └── Flags critical issues → On-Page Agent for immediate fix

END OF CYCLE
  └── Analytics & Reporting Agent
        ├── Compiles all agent outputs into cycle report
        ├── Calculates KPIs and ranking projections
        └── → CEO Report sent for approval

CEO APPROVAL
  └── On approval → All agents begin next cycle
```

---

## 11. CEO Approval Protocol

At the end of every cycle, the Analytics Agent generates a **CEO Brief** containing:

**Section 1 — What we did**
A bullet-point summary of every agent's completed tasks this cycle.

**Section 2 — Rankings update**
Table of top 10 target keywords: current rank → projected rank → estimated timeline.

**Section 3 — Traffic & revenue forecast**
- Projected organic sessions (next 30 / 60 / 90 days)
- Estimated organic revenue contribution
- ROI vs. cost of running the agent system

**Section 4 — Next cycle plan**
What the agents will do in the next cycle and why.

**Section 5 — Approval request**
One-click (or one-reply) approval to trigger the next cycle.

---

## Quick Reference — All 9 Agents at a Glance

| Agent | Trigger | Primary output | Cycle frequency |
|---|---|---|---|
| CRO Agent | Every hour | Action briefs to all agents | Hourly |
| Keyword Planner | Per CRO cycle | Keyword shortlist | Per cycle |
| On-Page SEO | Per CRO brief | Page optimisations + content briefs | Per cycle |
| Off-Page SEO | Per CRO brief | PR placements + outreach | Per cycle |
| Backlink Agent | Per cycle | New backlinks acquired | Per cycle |
| Technical SEO | Continuous | Crawl health + speed fixes | Continuous |
| Content Strategy | Weekly | Content calendar + briefs | Weekly |
| Local SEO | Weekly | GBP updates + citations | Weekly |
| Analytics & Reporting | End of cycle | CEO report + KPI dashboard | Per cycle |

---

*Document version: 1.0 | System: SEO Automation Command Center | Brand type: B2C*
