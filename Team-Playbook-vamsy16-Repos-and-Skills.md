# Team Playbook — vamsy16 GitHub Repositories & Skills

> **What this is:** a complete map of every public repository under our GitHub account ([github.com/vamsy16](https://github.com/vamsy16)) — what each one is for, **when to use it**, and a full inventory of the **1,150 AI-agent skills** packaged inside them.  
> **Generated:** 2026-08-30 · **Audience:** whole team · **Scope:** public repos only

| Overview | |
|---|---|
| Repositories mapped | **103** (5 original · 98 forks) |
| Repos containing skills | **58** |
| Skills catalogued | **1150** |
| Biggest skill libraries | `open-design` (385) · `ECC` (287) · `marketingskills` (50) · `system_prompts_leaks` (49) · `claude-ads` (34) |

**Contents:** 1️⃣ What skills are & how to install → 2️⃣ Quick router (“I want to…”) → 3️⃣ Category deep-dives with full skill tables → 4️⃣ Appendix.

---

## 1️⃣ What are “skills” and how do we use them?

Most repositories in this account ship **agent skills** — packaged instruction sets (`SKILL.md` files) that teach AI coding assistants like **Claude Code, Codex, Cursor, Copilot, and Gemini CLI** how to do a specific job well. You don't run them like an app; you **install them into your AI assistant**, and then just ask naturally — the assistant picks the right skill automatically.

**Three ways to install (pick whichever the repo documents):**

| Method | Command example | Works with |
|---|---|---|
| **`npx skills` CLI** (easiest) | `npx skills add vamsy16/marketingskills` | Claude Code, Cursor, Codex, Windsurf, Copilot + 40 more |
| **Claude Code plugin** | `/plugin marketplace add <owner>/<repo>` → `/plugin install <name>` | Claude Code |
| **Manual clone** | `git clone <repo>` into your project (or `~/.claude/skills/` for global) | any assistant that reads project files |

> 💡 **Tip:** our forks are identical copies of the upstream projects, so commands work with either owner — e.g. `npx skills add coreyhaines31/marketingskills` (upstream) or `npx skills add vamsy16/marketingskills` (our fork).

**How to invoke after install:** just describe the task in plain language — e.g. *“audit this landing page's conversion rate”* or *“write a cold email sequence for HR SaaS”*. No special commands needed.

---

## 2️⃣ Quick Router — “I want to… → use this”

| I want to… | Use |
|---|---|
| Run or fix **paid ad campaigns** | `marketingskills` → skills `ads`, `ad-creative` · deep platform ops: `claude-ads` |
| Improve **conversion rate** / landing pages | `marketingskills` → `cro`, `popups`, `paywalls`, `signup`, `pricing`, `offers` |
| Write **copy** (site, email, SMS, cold outreach) | `marketingskills` → `copywriting`, `copy-editing`, `emails`, `cold-email`, `sms` |
| **SEO audit** or technical SEO | `claude-seo` (deep) · `marketingskills` → `seo-audit`, `schema`, `site-architecture` |
| **Programmatic SEO** / keyword clustering | `claude-seo` → semantic clustering, programmatic SEO · `marketingskills` → `programmatic-seo` |
| Free **Ahrefs/Semrush alternative** | `open-ai-seo-agent` (uses your Search Console + Analytics data) |
| **Blog** content that ranks (and gets cited by AI) | `claude-blog` (30 sub-skills, Google + AI-citation optimized) |
| **Brand** strategy, naming, voice, positioning | `Brand-building-skills` · `marketingskills` → `brand`-adjacent skills |
| **Product launch** / marketing plan | `marketingskills` → `launch`, `marketing-plan`, `marketing-ideas`, `marketing-council` |
| **Competitor** research / teardown | `competitor-x-ray` (ICC/funnel PDF) · `funnel-spy` (full funnel walk) · `marketingskills` → `competitor-profiling`, `competitors` |
| **Business coaching** (numbers-first) | `alex-hormozi-coach` — type “coach me — I run …” |
| Find **B2B leads** | `lead-gen-kit` (Maps funnel + Sheets) · `lead-scraper` · `Scout` (social profiles) · `google-maps-scraper-kit` |
| **Social media** management & ideas | `open-ai-social-agent` · `content-ideas` (competitor tracking) · `content-repurposer` · `linkedin-planner` |
| **Images / thumbnails** with AI | `banana-claude` (Claude + Gemini) · `open-ai-image-agent` · `higgsfield-skill` (30+ models) |
| **Video generation** from text/image | `open-ai-video-agent` · `MoneyPrinterTurbo` · `seedance-2-generator` (SaaS) · `higgsfield-skill` |
| Long video → **shorts/clips** | `AI-Youtube-Shorts-Generator` · `autoshorts` · `Clip-Anything` · `open-ai-content-repurposing-agent` |
| **Voice**: cloning, TTS, dubbing | `VoiceStudio` (local, 646 languages) · `voicebox` |
| **Scrape a website** | `firecrawl` (LLM-ready, at scale) · `crawl4ai` · `scrapy` · `crawlee` (Node) |
| Scraping a site that **blocks bots** | `Scrapling` (Cloudflare bypass) · `curl-impersonate` (browser TLS fingerprints) |
| Read/search **social platforms** (X, Reddit, YouTube…) | `Agent-Reach` — one CLI, zero API fees |
| **Animate a website** (GSAP, Motion, scroll) | `gsap-skills` (official) · `motion-dev-animations-skill` · `claudedesignskills` |
| **3D / WebGL** experiences | `claudedesignskills` → Three.js, React Three Fiber, Babylon.js skills |
| Agent **design engine** (landing pages, dashboards, slides) | `open-design` — 385 design templates, exports HTML/PDF/PPTX/MP4 |
| On-brand UI from a **design system** | `awesome-design-md` — drop a DESIGN.md into your project |
| **Clone a website** into Next.js | `ai-site-cloner` (pixel-accurate, measured) |
| Agent **memory** across sessions | `claude-mem` |
| **Multi-agent** orchestration | `claude-swarm` · `loop-engineering` · `ECC` |
| Professional **engineering skill library** | `ECC` — 287 skills (API design, testing, security, patterns…) |
| Agent **security** audit | `agentshield` — configs, MCP servers, tool permissions |
| Cut **token costs** | `headroom` (compress outputs) · `codegraph` / `graphify` (code knowledge graphs) |
| **Structured reasoning** | `sequential-thinking-skill` |
| **Notes / second brain** | `claude-obsidian` · `second-brain` (Obsidian + Claude Code) |
| **CRM** | `twenty` (open-source Salesforce alternative) |
| **Shopify** store management via AI | `shopify-graphql-admin-mcp` |
| **Bookkeeping** with AI + human approval | `bookkeeper-starter` |
| Video editing in **Premiere Pro / DaVinci** | `premiere-pro-mcp` (285 tools) · `resolve-claude-mcp` |
| Convert **documents → Markdown** | `markitdown` |
| Make Claude **watch a video** | `claude-watch` / `claude-video` |
| **YouTube research** + scripts + thumbnails | `youtubepro` |
| Shorter, **ADHD-friendly** agent answers | `i-have-adhd` |

---

## 3️⃣ Repository Deep-Dives

### 🧩 Original Repositories (5 repos)

*Repos created from scratch under this account (everything else is a fork of an upstream project).*

| Repo | Skills | One-line purpose |
|---|---|---|
| [`ExcelToJson`](https://github.com/vamsy16/ExcelToJson) | — | Java (Maven) utility that converts Excel spreadsheet files into JSON. |
| [`git-learning`](https://github.com/vamsy16/git-learning) | — | i want to learn git |
| [`hello-world`](https://github.com/vamsy16/hello-world) | — | GitHub Pages starter site. |
| [`microservices-tutorial-config`](https://github.com/vamsy16/microservices-tutorial-config) | — | Spring Boot configuration files for a microservices tutorial. |
| [`python-training`](https://github.com/vamsy16/python-training) | — | python training |

#### `ExcelToJson`

🔗 [https://github.com/vamsy16/ExcelToJson](https://github.com/vamsy16/ExcelToJson) · Original · Language: Java · Last push: 2023-09-10

**What it is:** Java (Maven) utility that converts Excel spreadsheet files into JSON.

**When to use:** See description above.

*No packaged skills — use the project directly.*

#### `git-learning`

🔗 [https://github.com/vamsy16/git-learning](https://github.com/vamsy16/git-learning) · Original · Language: n/a · Last push: 2021-01-24

**What it is:** i want to learn git

**When to use:** See description above.

*No packaged skills — use the project directly.*

#### `hello-world`

🔗 [https://github.com/vamsy16/hello-world](https://github.com/vamsy16/hello-world) · Original · Language: HTML · Last push: 2021-10-28

**What it is:** GitHub Pages starter site.

**When to use:** See description above.

*No packaged skills — use the project directly.*

#### `microservices-tutorial-config`

🔗 [https://github.com/vamsy16/microservices-tutorial-config](https://github.com/vamsy16/microservices-tutorial-config) · Original · Language: n/a · Last push: 2024-01-02

**What it is:** Spring Boot configuration files for a microservices tutorial.

**When to use:** See description above.

*No packaged skills — use the project directly.*

#### `python-training`

🔗 [https://github.com/vamsy16/python-training](https://github.com/vamsy16/python-training) · Original · Language: n/a · Last push: 2021-09-21

**What it is:** python training

**When to use:** See description above.

*No packaged skills — use the project directly.*

---

### 📣 Marketing, SEO & Growth (19 repos)

*The largest cluster and the heart of this account: Claude Code skill suites and AI agents for marketing, ads, SEO, content, and lead generation.*

| Repo | Skills | One-line purpose |
|---|---|---|
| [`alex-hormozi-coach`](https://github.com/vamsy16/alex-hormozi-coach) | 1 | Free Claude skill that coaches your business in Alex Hormozi's hotline method — numbers first, find… |
| [`Brand-building-skills`](https://github.com/vamsy16/Brand-building-skills) | 29 | Brand building skills for Claude Code and AI agents. |
| [`claude-ads`](https://github.com/vamsy16/claude-ads) | 34 | Claude-first paid-media operations skill for Claude Code across 12 ad platforms (Google, Meta,… |
| [`claude-blog`](https://github.com/vamsy16/claude-blog) | 33 | Claude Code blog skill suite: 30 sub-skills, 5 agents, 5-gate v1.9.0 Blog Delivery Contract,… |
| [`claude-seo`](https://github.com/vamsy16/claude-seo) | 31 | Universal SEO skill for Claude Code. 25 sub-skills + 18 sub-agents covering technical SEO, E-E-A-T,… |
| [`competitor-x-ray`](https://github.com/vamsy16/competitor-x-ray) | 1 | Free Claude skill that x-rays any competitor into their ICP, funnel & monetization — sourced,… |
| [`content-ideas`](https://github.com/vamsy16/content-ideas) | 1 | Track competitors across X, Instagram, TikTok, and YouTube, see what they post, what performs, and… |
| [`content-repurposer`](https://github.com/vamsy16/content-repurposer) | 1 | Turn one Reel/TikTok into platform-correct Instagram, TikTok & YouTube posts with auto-translated… |
| [`distribb-skill`](https://github.com/vamsy16/distribb-skill) | 2 | Distribb CLI, Claude, Codex, Hermes, OpenClaw skill for AI-powered SEO. |
| [`funnel-spy`](https://github.com/vamsy16/funnel-spy) | 1 | Free Claude skill that walks any competitor's funnel end to end — every page, every price, the… |
| [`lead-gen-kit`](https://github.com/vamsy16/lead-gen-kit) | 1 | Skill-driven Google Maps lead-gen funnel for Claude Code — cheap discovery, ICP qualification,… |
| [`linkedin-planner`](https://github.com/vamsy16/linkedin-planner) | 1 | Batch-plan a month of LinkedIn posts with an AI assistant and push them to Buffer as drafts. |
| [`marketingskills`](https://github.com/vamsy16/marketingskills) | 50 | Marketing skills for Claude Code and AI agents. |
| [`open-ai-content-repurposing-agent`](https://github.com/vamsy16/open-ai-content-repurposing-agent) | 3 | An AI agent for content repurposing — turning long-form video into ranked, ready-to-post short… |
| [`open-ai-gtm-agent`](https://github.com/vamsy16/open-ai-gtm-agent) | 4 | Cross-functional GTM strategy and orchestration agents for research, launches, sales, channels, and… |
| [`open-ai-image-agent`](https://github.com/vamsy16/open-ai-image-agent) | 20 | AI agent for image and creative production — image generation, thumbnails, and on-brand visual… |
| [`open-ai-seo-agent`](https://github.com/vamsy16/open-ai-seo-agent) | 14 | Free, open-source SEO alternative to Ahrefs and Semrush for Claude, Codex, Cursor, and other AI… |
| [`open-ai-social-agent`](https://github.com/vamsy16/open-ai-social-agent) | 6 | An AI agent for social media management — listening, creator discovery, multi-platform publishing,… |
| [`open-ai-video-agent`](https://github.com/vamsy16/open-ai-video-agent) | 28 | AI agent for video production — text/image-to-video generation, avatar/UGC talking-head videos, and… |

#### `marketingskills`

🔗 [https://github.com/vamsy16/marketingskills](https://github.com/vamsy16/marketingskills) · Fork of [`coreyhaines31/marketingskills`](https://github.com/coreyhaines31/marketingskills) · Language: n/a · Last push: 2026-08-28

**What it is:** Marketing skills for Claude Code and AI agents. CRO, copywriting, SEO, analytics, and growth engineering.

**When to use:** Your default marketing toolkit. Use for ANY marketing task: landing pages, conversion optimization, copywriting, SEO basics, email/SMS, pricing, referrals, churn prevention, launches, marketing plans, competitor profiling, analytics. Start here before more specialized suites.

**Install / quick start:**

```bash
# All skills
npx skills add coreyhaines31/marketingskills
# Specific skills only
npx skills add coreyhaines31/marketingskills --skill cro copywriting
# List what's available
npx skills add coreyhaines31/marketingskills --list
```
*(Use `vamsy16/marketingskills` to install from our fork instead.)*

**Skills inside — 50** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`ab-testing`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/ab-testing) | When you want to plan, design, or implement an A/B test or experiment, or build a growth experimentation program. | For tracking implementation, see analytics. For page-level conversion optimization, see cro. |
| [`ad-creative`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/ad-creative) | When you want to generate, iterate, or scale ad creative — headlines, descriptions, primary text, or full ad variations — for any paid advertising platform. | For campaign strategy and targeting, see ads. For landing page copy, see copywriting. |
| [`ads`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/ads) | When you want help with paid advertising campaigns on Google Ads, Meta (Facebook/Instagram), LinkedIn, Twitter/X, or other ad platforms. | For bulk ad creative generation and iteration, see ad-creative. For landing page optimization, see cro. |
| [`ai-seo`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/ai-seo) | When you want to optimize content for AI search engines, get cited by LLMs, or appear in AI-generated answers. | For traditional technical and on-page SEO audits, see seo-audit. For structured data implementation, see schema. |
| [`analytics`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/analytics) | When you want to set up, improve, or audit analytics tracking and measurement. | For choosing attribution models, comparing multi-touch/MMM/incrementality, or reconciling conflicting numbers across tools, see attribution. For A/B test measurement, see ab-testing. |
| [`aso`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/aso) | When you want to audit or optimize an App Store or Google Play listing. | Audit or optimize an App Store or Google Play listing. Also use when you mention 'ASO audit,' 'app store optimization,' 'optimize my app listing,' 'improve app visibility,' 'app store ranking,' 'audit my listing,' 'why aren't… |
| [`attribution`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/attribution) | When you want to figure out which marketing actually drives conversions and revenue, choose or interpret an attribution model, or reconcile conflicting numbers across… | For ad-platform pixels/CAPI, see ads. For pipeline and CRM revenue reporting, see revops. For the AI-search attribution blind spot, see ai-seo. |
| [`churn-prevention`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/churn-prevention) | When you want to reduce churn, build cancellation flows, set up save offers, recover failed payments, or implement retention strategies. | For post-cancel win-back email sequences, see emails. For in-app upgrade paywalls, see paywalls. |
| [`co-marketing`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/co-marketing) | When you want to find co-marketing partners, plan joint campaigns, or brainstorm partnership opportunities. | For launch-specific partnerships, see launch. |
| [`cold-email`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/cold-email) | Use when you want to write cold outreach emails, prospecting emails, cold email campaigns, sales development emails, or SDR emails. | Write B2B cold emails and follow-up sequences that get replies. For warm/lifecycle email sequences, see emails. For sales collateral beyond emails, see sales-enablement. |
| [`community-marketing`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/community-marketing) | Use when you want to create a community strategy, grow a Discord or Slack community, manage a forum or subreddit, build brand advocates, increase word-of-mouth, drive… | Build and leverage online communities to drive product growth and brand loyalty. Trigger phrases: \"build a community,\" \"community strategy,\" \"Discord community,\" \"Slack community,\" \"community-led growth,\" \"brand… |
| [`competitor-profiling`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/competitor-profiling) | When you want to research, profile, or analyze competitors from their URLs. | Output is structured competitor profile markdown files. For creating comparison/alternative pages from profiles, see competitors. For sales-specific battle cards, see sales-enablement. |
| [`competitors`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/competitors) | When you want to create competitor comparison or alternative pages for SEO and sales enablement. | Covers four formats: singular alternative, plural alternatives, you vs competitor, and competitor vs competitor. For sales-specific competitor docs, see sales-enablement. |
| [`content-strategy`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/content-strategy) | When you want to plan a content strategy, decide what content to create, or figure out what topics to cover. | For writing individual pieces, see copywriting. For SEO-specific audits, see seo-audit. For social media content specifically, see social. |
| [`copy-editing`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/copy-editing) | When you want to edit, review, or improve existing marketing copy, or refresh outdated content. | For writing new copy, see copywriting. |
| [`copywriting`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/copywriting) | When you want to write, rewrite, or improve marketing copy for any page — including homepage, landing pages, pricing pages, feature pages, about pages, or product pages. | For email copy, see emails. For popup copy, see popups. For editing existing copy, see copy-editing. For the offer underneath the copy (bonuses, guarantees, value framing), see offers. |
| [`cro`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/cro) | When you want to optimize, improve, or increase conversions on any marketing page or form — including homepage, landing pages, pricing pages, feature pages, lead capture… | For signup/registration flows, see signup. For post-signup activation, see onboarding. For popups/modals, see popups. |
| [`customer-research`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/customer-research) | When you want to conduct, analyze, or synthesize customer research. Use when you mention "customer research," "ICP research," "talk to customers," "analyze transcripts,"… | For writing copy informed by research, see copywriting. For acting on research to improve pages, see cro. |
| [`directory-submissions`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/directory-submissions) | When you want to submit their product to startup, SaaS, AI, agent, MCP, no-code, or review directories for backlinks, domain rating, and discovery. | For the broader launch moment, see launch. For programmatic SEO pages that should live behind these backlinks, see programmatic-seo. For AI citation optimization, see ai-seo. |
| [`emails`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/emails) | When you want to create or optimize an email sequence, drip campaign, automated email flow, or lifecycle email program. | For cold outreach emails, see cold-email. For in-app onboarding, see onboarding. |
| [`events`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/events) | When you want to plan, run, sponsor, speak at, or get pipeline from events — webinars, conferences, trade shows, meetups, dinners, workshops, virtual summits, or user… | For product launch moments, see launch. For the partnership side of joint webinars, see co-marketing. For ongoing community programs, see community-marketing. For podcast appearances, see public-relations. |
| [`free-tools`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/free-tools) | When you want to plan, evaluate, or build a free tool for marketing purposes — lead generation, SEO value, or brand awareness. | For downloadable content lead magnets (ebooks, checklists, templates), see lead-magnets. |
| [`image`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/image) | When you want to create, generate, edit, or optimize images for marketing — blog heroes, social graphics, product mockups, profile banners, listing visuals, or brand… | For paid ad image creative and platform-specific ad specs, see ad-creative. For video production, see video. |
| [`influencer-marketing`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/influencer-marketing) | When you want to run influencer, creator, or ambassador partnerships to promote their product — finding and vetting partners, structuring deals, briefing creators,… | For community-led advocacy, see community-marketing. For turning creator content into paid ads, see ad-creative. |
| [`launch`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/launch) | When you want to plan a product launch, feature announcement, or release strategy. | For ongoing marketing after launch, see marketing-ideas. For the offer being launched (bonuses, guarantees, scarcity, naming), see offers. |
| [`lead-magnets`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/lead-magnets) | When you want to create, plan, or optimize a lead magnet for email capture or lead generation. | For interactive tools as lead magnets, see free-tools. For writing the actual content, see copywriting. For the email sequence after capture, see emails. |
| [`marketing-council`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/marketing-council) | When you want multiple expert perspectives on a marketing question — a simulated board of advisors staffed by legendary marketers (Seth Godin, David Ogilvy, Eugene… | The council gives each advisor's take through their documented frameworks, surfaces where they disagree, and synthesizes a recommendation. |
| [`marketing-ideas`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/marketing-ideas) | When you need marketing ideas, inspiration, or strategies for their SaaS or software product. | For specific channel execution, see the relevant skill (ads, social, emails, etc.). |
| [`marketing-loops`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/marketing-loops) | When you want to set up a recurring, self-running marketing workflow — a repeatable loop an AI agent runs on a cadence (weekly, daily, on a trigger) rather than a… | For one-off marketing ideas, see marketing-ideas. For the experimentation loop specifically, see ab-testing. |
| [`marketing-plan`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/marketing-plan) | When you need a comprehensive marketing plan for a client, a company they advise, or their own product. | Outputs a Notion-paste-ready markdown document. For positioning and ICP context before planning, see product-marketing. For stage-specific deep work, see onboarding, signup, emails, referrals, pricing. |
| [`marketing-psychology`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/marketing-psychology) | When you want to apply psychological principles, mental models, or behavioral science to marketing. | For applying psychology to specific pages, see cro; for pricing tactics, see pricing; for copy framing, see copywriting. |
| [`offers`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/offers) | When you want to design, construct, or improve an offer — the thing they actually sell — including value framing, bonus stacking, guarantee design, scarcity/urgency,… | If you run pure self-serve SaaS, read pricing first — tiers and packaging do more work there. For price level itself (tiers, freemium, value metric), see pricing. For the page that presents the offer, see copywriting. |
| [`onboarding`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/onboarding) | When you want to optimize post-signup onboarding, user activation, first-run experience, or time-to-value. | For signup/registration optimization, see signup. For ongoing email sequences, see emails. |
| [`paywalls`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/paywalls) | When you want to create or optimize in-app paywalls, upgrade screens, upsell modals, or feature gates. | Distinct from public pricing pages (see cro) — this focuses on in-product upgrade moments where the user has already experienced value. For pricing decisions, see pricing. |
| [`popups`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/popups) | When you want to create or optimize popups, modals, overlays, slide-ins, or banners for conversion purposes. | For forms outside of popups, see cro. For general page conversion optimization, see cro. |
| [`pricing`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/pricing) | When you want help with pricing decisions, packaging, or monetization strategy. | For in-app upgrade screens, see paywalls. For offer construction (bonuses, guarantees, value framing, naming) on services/courses/coaching/high-ticket B2B, see offers. |
| [`product-marketing`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/product-marketing) | When you want to create or update their product marketing context document. | Use this at the start of any new project before using other marketing skills — it creates `.agents/product-marketing.md` that all other skills reference for product, audience, and positioning context. |
| [`programmatic-seo`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/programmatic-seo) | When you want to create SEO-driven pages at scale using templates and data. | For auditing existing SEO issues, see seo-audit. For content strategy planning, see content-strategy. |
| [`prospecting`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/prospecting) | When you want to find, qualify, and build a list of prospects to reach out to — across B2B SaaS, general B2B, or local small businesses. | For writing the outbound copy after the list is built, see cold-email. For deep competitive research on specific accounts, see competitor-profiling. |
| [`public-relations`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/public-relations) | When you want help with public relations, earned media, press coverage, journalist outreach, or media strategy (not pull requests). | For startup/SaaS/AI directory submissions, see directory-submissions. For product launches, see launch. For social-media engagement, see social. For cold-email outreach to prospects, see cold-email. |
| [`referrals`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/referrals) | When you want to create, optimize, or analyze a referral program, affiliate program, or word-of-mouth strategy. | For launch-specific virality, see launch. |
| [`revops`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/revops) | When you want help with revenue operations, lead lifecycle management, or marketing-to-sales handoff processes. | For cold outreach emails, see cold-email. For email drip campaigns, see emails. For pricing decisions, see pricing. |
| [`sales-enablement`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/sales-enablement) | When you want to create sales collateral, pitch decks, one-pagers, objection handling docs, or demo scripts. | For competitor comparison pages and battle cards, see competitors. For marketing website copy, see copywriting. For cold outreach emails, see cold-email. |
| [`schema`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/schema) | When you want to add, fix, or optimize schema markup and structured data on their site. | For broader SEO issues, see seo-audit. For AI search optimization, see ai-seo. |
| [`seo-audit`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/seo-audit) | When you want to audit, review, or diagnose SEO issues on their site. Also use when you mention "SEO audit," "technical SEO," "why am I not ranking," "SEO issues,"… | For building pages at scale to target keywords, see programmatic-seo. For adding structured data, see schema. For AI search optimization, see ai-seo. |
| [`signup`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/signup) | When you want to optimize signup, registration, account creation, or trial activation flows. | For post-signup onboarding, see onboarding. For lead capture forms (not account creation), see cro. |
| [`site-architecture`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/site-architecture) | When you want to plan, map, or restructure their website's page hierarchy, navigation, URL structure, or internal linking. | NOT for XML sitemaps (that's technical SEO — see seo-audit). For SEO audits, see seo-audit. For structured data, see schema. |
| [`sms`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/sms) | When you want to plan, build, or optimize SMS or MMS marketing — including welcome flows, abandoned cart texts, post-purchase, win-back, promotional sends, or… | For SMS copy framing, see copywriting. For opt-in popups that capture phone numbers, see popups. |
| [`social`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/social) | When you want help creating, scheduling, or optimizing social media content for LinkedIn, Twitter/X, Instagram, TikTok, Facebook, or other platforms, or wants to do… | For broader content strategy, see content-strategy. For paid ads, see ad-creative. For earned media, see public-relations. |
| [`video`](https://github.com/vamsy16/marketingskills/tree/HEAD/skills/video) | When you want to create, generate, or produce video content using AI tools or programmatic frameworks. | For video content strategy and what to post, see social. For paid video ad creative, see ad-creative. |

#### `claude-ads`

🔗 [https://github.com/vamsy16/claude-ads](https://github.com/vamsy16/claude-ads) · Fork of [`AgriciDaniel/claude-ads`](https://github.com/AgriciDaniel/claude-ads) · Language: n/a · Last push: 2026-07-13

**What it is:** Claude-first paid-media operations skill for Claude Code across 12 ad platforms (Google, Meta, YouTube, LinkedIn, TikTok, Microsoft, Apple, Amazon, Reddit, Pinterest, Snapchat, X): source-grounded audits, deterministic scoring, versioned JSON reports, and capability-gated account changes.

**When to use:** When you're actually running paid media across platforms (Google, Meta, YouTube, LinkedIn, TikTok, Microsoft, Apple, Amazon, Reddit, Pinterest, Snapchat, X) and need audits, deterministic scoring, versioned reports, or capability-gated account changes.

**Skills inside — 34** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`ads`](https://github.com/vamsy16/claude-ads/tree/HEAD/ads) | Use for account intake, source-grounded audits, strategy, budget and measurement planning, creative production, experiments, reporting, monitoring, and explicitly… | Operate professional paid advertising across Google, Meta, YouTube, LinkedIn, TikTok, Microsoft, Apple, Amazon, Reddit, Pinterest, Snapchat, and X. |
| [`ads-amazon`](https://github.com/vamsy16/claude-ads/tree/HEAD/skills/ads-amazon) | Use for Amazon Ads, sponsored ads, Amazon PPC, ACOS, TACOS, ASIN advertising, Amazon DSP, or retail-media optimization. | Audit Amazon Ads profiles, regions, Sponsored Products, Sponsored Brands, Sponsored Display, DSP, portfolios, targeting, search terms, retail readiness, creative, budgets, ACOS, TACOS, reporting, and policy. |
| [`ads-apple`](https://github.com/vamsy16/claude-ads/tree/HEAD/skills/ads-apple) | Use for Apple Ads, Apple Search Ads, App Store ads, Search Match, custom product pages, AdServices, or Apple app-install campaigns. | Audit Apple Ads measurement, AdServices and AdAttributionKit, campaign and keyword structure, Search Match, App Store placements, custom product pages, bidding, budgets, MMP reconciliation, and policy. |
| [`ads-attribution`](https://github.com/vamsy16/claude-ads/tree/HEAD/skills/ads-attribution) | Use for attribution audit, attribution models, conversion windows, requests to add or total Meta and Google conversions, incompatible reporting-window aggregation, GA4… | Audit cross-platform attribution, conversion definitions, reporting windows, GA4, AdServices and AdAttributionKit, MMPs, browser and server events, offline conversions, and platform reconciliation. |
| [`ads-audit`](https://github.com/vamsy16/claude-ads/tree/HEAD/skills/ads-audit) | Use for full ad checks, account health reviews, paid-media diagnostics, partial audits after authentication or worker failure, missing-platform weighting, beta-feature… | Run a source-grounded paid-advertising audit for one or more of Google, Meta, YouTube, LinkedIn, TikTok, Microsoft, Apple, Amazon, Reddit, Pinterest, Snapchat, and X. |
| [`ads-budget`](https://github.com/vamsy16/claude-ads/tree/HEAD/skills/ads-budget) | Use for ad budget allocation, media budget, bidding strategy, scaling, spend pacing, budget forecast, ROAS target, or investment tradeoffs. | Plan and review paid-media budgets, bidding, pacing, marginal return, forecasts, CPA, ROAS, MER, LTV:CAC, constraints, and allocation across supported platforms. |
| [`ads-competitor`](https://github.com/vamsy16/claude-ads/tree/HEAD/skills/ads-competitor) | Use for competitor ads, ad libraries, ad spy, competitive PPC analysis, competitor creative, Google Ads Transparency, Meta Ad Library, or paid-media competitor research. | Research competitor paid-ad presence, messaging, creative, formats, landing pages, keyword and auction signals, transparent ad libraries, and strategic gaps across supported platforms. |
| [`ads-create`](https://github.com/vamsy16/claude-ads/tree/HEAD/skills/ads-create) | — | Create source-grounded paid-ad campaign concepts, messaging, copy, creative briefs, and production plans from a validated brand profile, campaign objective, platform requirements, and optional audit evidence. |
| [`ads-creative`](https://github.com/vamsy16/claude-ads/tree/HEAD/skills/ads-creative) | Use for creative audit, ad creative, creative fatigue, creative diversity, ad copy review, video review, image review, or production priorities. | Audit paid-ad copy, images, video, hooks, concepts, format coverage, platform-native fit, message match, creative fatigue, accessibility, and policy across supported platforms. |
| [`ads-dna`](https://github.com/vamsy16/claude-ads/tree/HEAD/skills/ads-dna) | — | Extract a public-safe brand and offer profile for paid advertising from an authorized website and operator input. |
| [`ads-generate`](https://github.com/vamsy16/claude-ads/tree/HEAD/skills/ads-generate) | — | Generate paid-ad image assets from a validated creative brief and brand profile using an explicitly configured image provider. |
| [`ads-google`](https://github.com/vamsy16/claude-ads/tree/HEAD/skills/ads-google) | Use for Google Ads, AdWords, Search campaigns, search terms reports, broad negatives, Shopping, Performance Max, PMax, Demand Gen, GAQL, Google conversion tracking, or… | Audit Google Ads measurement, Search, Shopping, Performance Max, Demand Gen, YouTube-linked inventory, keywords and search terms, negative-keyword generation or review, creative assets, bidding, budgets, settings, and policy. |
| [`ads-landing`](https://github.com/vamsy16/claude-ads/tree/HEAD/skills/ads-landing) | Use for landing-page audit, post-click experience, LP audit, conversion-rate optimization, form optimization, ad-to-page message match, redirects, blocked navigation, or… | Audit paid-ad landing pages for message match, mobile experience, performance, accessibility, trust, forms, consent, tracking, security, and conversion friction. |
| [`ads-launch`](https://github.com/vamsy16/claude-ads/tree/HEAD/skills/ads-launch) | Use for campaign creation, launch plans, publishing ads, activating campaigns, uploading creative, or requests to push a campaign live. | Draft or explicitly apply a paid-ad campaign launch through Claude Ads capability-gated adapters. |
| [`ads-linkedin`](https://github.com/vamsy16/claude-ads/tree/HEAD/skills/ads-linkedin) | Use for LinkedIn Ads, Campaign Manager, Insight Tag, Lead Gen Forms, Thought Leader Ads, ABM campaigns, or B2B paid media. | Audit LinkedIn Ads measurement, Insight Tag and conversions, professional audiences, lead generation, ABM, creative, bidding, budgets, pacing, automation, and policy. |
| [`ads-math`](https://github.com/vamsy16/claude-ads/tree/HEAD/skills/ads-math) | Use for PPC math, ad calculator, break-even analysis, ROAS calculator, CPA calculator, budget forecast, LTV CAC, or MER. | Calculate and model paid-media CPA, CPL, CPC, CPM, ROAS, MER, break-even targets, contribution margin, LTV:CAC, impression-share opportunity, budgets, forecasts, and experiment economics. |
| [`ads-meta`](https://github.com/vamsy16/claude-ads/tree/HEAD/skills/ads-meta) | Use for Meta Ads, Facebook Ads, Instagram Ads, Advantage+, Pixel, CAPI, Events Manager, creative fatigue, or Meta campaign optimization. | Audit Meta Ads measurement, Pixel and Conversions API, attribution, Facebook and Instagram creative, audiences, placements, automation, budgets, account structure, and policy. |
| [`ads-microsoft`](https://github.com/vamsy16/claude-ads/tree/HEAD/skills/ads-microsoft) | Use for Microsoft Ads, Bing Ads, UET, Microsoft Audience Network, Google Ads import, or Microsoft campaign optimization. | Audit Microsoft Advertising measurement, UET, search and audience campaigns, Google imports, syndication, keywords, creative, bidding, budgets, Copilot inventory, and policy. |
| [`ads-monitor`](https://github.com/vamsy16/claude-ads/tree/HEAD/skills/ads-monitor) | Use for daily or weekly checks, anomaly review, budget pacing, post-launch verification, or campaign monitoring. | Monitor paid-ad account pacing, delivery, performance, creative fatigue, tracking, policy, and data quality across supported platforms. |
| [`ads-optimize`](https://github.com/vamsy16/claude-ads/tree/HEAD/skills/ads-optimize) | Use for campaign optimization, budget reallocation, bid changes, pausing or archiving ads, requests to delete campaigns, search-term or negative-keyword actions,… | Diagnose and draft or explicitly apply paid-ad optimizations using evidence, financial constraints, experiments, and capability-gated adapters. |
| [`ads-photoshoot`](https://github.com/vamsy16/claude-ads/tree/HEAD/skills/ads-photoshoot) | — | Generate rights-cleared paid-ad product photography variants from an authorized source image and validated brand profile. |
| [`ads-pinterest`](https://github.com/vamsy16/claude-ads/tree/HEAD/skills/ads-pinterest) | Use for Pinterest Ads, promoted Pins, shopping ads, catalog sales, Pinterest Tag, Pinterest Conversions API, or Pinterest Performance+. | Audit Pinterest Ads measurement, Pinterest Tag and Conversions API, catalog and shopping readiness, visual creative, audiences, Performance+ intent, budgets, brand safety, and reporting. |
| [`ads-plan`](https://github.com/vamsy16/claude-ads/tree/HEAD/skills/ads-plan) | Use for ad plan, media plan, PPC strategy, paid-social strategy, campaign architecture, advertising roadmap, or channel planning. | Create a professional paid-advertising strategy covering objectives, economics, platform selection, campaign architecture, audiences, budget, creative, measurement, experiments, governance, rollout, and reporting. |
| [`ads-reddit`](https://github.com/vamsy16/claude-ads/tree/HEAD/skills/ads-reddit) | Use for Reddit Ads, promoted posts, conversation ads, community targeting, Reddit Pixel, Reddit Conversions API, or Reddit dynamic product ads. | Audit Reddit Ads measurement, campaign structure, community and interest targeting, creative-native fit, catalog advertising, budgets, brand safety, and reporting. |
| [`ads-report`](https://github.com/vamsy16/claude-ads/tree/HEAD/skills/ads-report) | Use for ads report, client report, audit PDF, executive audience reporting, or exporting prior audit and plan results. | Render Markdown, HTML, or PDF paid-advertising reports from a validated Claude Ads JSON run bundle. |
| [`ads-research`](https://github.com/vamsy16/claude-ads/tree/HEAD/skills/ads-research) | Use for ads research refresh, expired refresh_due dates, stale API or platform claims, reverify-or-demote decisions, release-current claim validation, ecosystem review,… | Refresh Claude Ads platform, API, policy, regulation, benchmark, issue, pull-request, fork, and repository evidence. |
| [`ads-server-side-tracking`](https://github.com/vamsy16/claude-ads/tree/HEAD/skills/ads-server-side-tracking) | Use for server-side tracking, sGTM, server-side tagging, CAPI, Events API, event_id, pixel debugging, first-party measurement, or conversion data loss. | Audit server-side paid-media measurement including server-side tag management, platform conversion APIs, event taxonomy, browser/server deduplication, consent, hashing, data quality, observability, and privacy. |
| [`ads-setup`](https://github.com/vamsy16/claude-ads/tree/HEAD/skills/ads-setup) | Use for onboarding, initial configuration, brand DNA, API tokens or credential profiles, environment-variable or keychain setup, connecting exports or read adapters,… | Set up a paid-media client, brand, account, data-source, privacy, and mutation-guardrail profile for Claude Ads. |
| [`ads-snapchat`](https://github.com/vamsy16/claude-ads/tree/HEAD/skills/ads-snapchat) | Use for Snapchat Ads, Snap Ads, Snap Pixel, Snapchat Conversions API, AR Lens ads, app-install campaigns, or Snapchat dynamic product ads. | Audit Snapchat Ads measurement, Snap Pixel and Conversions API, mobile and app campaigns, creative, AR and catalog formats, audiences, budgets, brand safety, and reporting. |
| [`ads-test`](https://github.com/vamsy16/claude-ads/tree/HEAD/skills/ads-test) | Use for A/B test, split test, experiment design, hypothesis, statistical significance, sample size, test duration, or experiment readout. | Design and evaluate paid-ad experiments with hypotheses, randomization units, sample-size and duration assumptions, guardrails, platform experiment tools, analysis, and decision rules. |
| [`ads-tiktok`](https://github.com/vamsy16/claude-ads/tree/HEAD/skills/ads-tiktok) | Use for TikTok Ads, TikTok Pixel, Events API, Smart+, TikTok Shop Ads, GMV Max, Spark Ads, or TikTok campaign optimization. | Audit TikTok Ads measurement, Pixel and Events API, mobile-first creative, audiences, Smart+, Shop and commerce campaigns, bidding, budgets, pacing, attribution, and policy. |
| [`ads-validate`](https://github.com/vamsy16/claude-ads/tree/HEAD/skills/ads-validate) | Use for ads validate, ads status, ads next, stale claims with missing tool access, maturity checks, ownership-manifest uninstall, preserving unrelated ads-* skills,… | Validate Claude Ads contracts, scoring inputs, run bundles, capabilities, source freshness, safety, installation, uninstall, or release readiness. |
| [`ads-x`](https://github.com/vamsy16/claude-ads/tree/HEAD/skills/ads-x) | Use for X Ads, Twitter Ads, promoted posts, X Pixel, X Conversions API, conversation targeting, or paid campaigns on X. | Audit X Ads measurement, X Pixel and Conversions API, campaign objectives, keyword and conversation targeting, creative, budgets, brand safety, app measurement, and reporting. |
| [`ads-youtube`](https://github.com/vamsy16/claude-ads/tree/HEAD/skills/ads-youtube) | Use for YouTube Ads, video ads, pre-roll, bumper ads, skippable in-stream, Shorts ads, Demand Gen, VAC migration, CTV, or YouTube campaign optimization. | Audit YouTube Ads campaign setup, video and Demand Gen inventory, Shorts, in-stream, CTV, creative, audiences, brand safety, bidding, and measurement. |

#### `claude-blog`

🔗 [https://github.com/vamsy16/claude-blog](https://github.com/vamsy16/claude-blog) · Fork of [`AgriciDaniel/claude-blog`](https://github.com/AgriciDaniel/claude-blog) · Language: n/a · Last push: 2026-08-28

**What it is:** Claude Code blog skill suite: 30 sub-skills, 5 agents, 5-gate v1.9.0 Blog Delivery Contract, dual-optimized for Google rankings and AI citations. Active development at AI-Marketing-Hub/claude-blog (AI Marketing Hub Pro community); public releases ship here.

**When to use:** For producing blog content end-to-end: ideation, outlines, drafts optimized for both Google rankings and AI citations, editing, and a delivery-gated publishing workflow. 30 sub-skills + 5 agents.

**Install / quick start:**

Claude Code 1.0.33+:
```bash
/plugin marketplace add AgriciDaniel/claude-blog
/plugin install claude-blog@agricidaniel-blog
```

**Skills inside — 33** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`blog`](https://github.com/vamsy16/claude-blog/tree/HEAD/skills/blog) | Use when user says "blog", "blog post", "blog audit", "topic cluster", "multilingual blog", or any /blog subcommand. | Full-lifecycle blog engine with 31 sub-skills, 12 templates, 100-point scoring, and 5 agents. Routes requests to the right sub-skill: writing, rewriting, analysis, outlines, audits, schema, charts, images, repurposing, AI… |
| [`blog-analyze`](https://github.com/vamsy16/claude-blog/tree/HEAD/skills/blog-analyze) | Use when user says "analyze blog", "audit blog", "blog score", "check blog quality", "blog review", "rate this blog", "blog health check". | Audit and score blog posts on a 5-category 100-point scoring system covering content quality, SEO optimization, E-E-A-T signals, technical elements, and AI citation readiness. |
| [`blog-audio`](https://github.com/vamsy16/claude-blog/tree/HEAD/skills/blog-audio) | Use when user says "blog audio", "narrate blog", "audio version", "text to speech", "tts", "podcast mode", "read aloud", "audio narration", "voice", "narration",… | Generate audio narration of blog posts using Google Gemini TTS. Supports summary narration, full article read-aloud, and two-speaker podcast/dialogue mode with 30 voice options. Outputs MP3 with HTML5 audio embed code. |
| [`blog-audit`](https://github.com/vamsy16/claude-blog/tree/HEAD/skills/blog-audit) | Use when user says "audit blog", "blog audit", "site audit", "blog health", "audit all posts", "check all blogs". | Full-site blog health assessment scanning all blog files for quality scores, orphan pages, topic cannibalization, stale content, and AI citation readiness. Runs canonical batch analysis before site-wide checks. |
| [`blog-brand`](https://github.com/vamsy16/claude-blog/tree/HEAD/skills/blog-brand) | Use when user says "blog brand", "create brand context", "brand voice doc", "BRAND.md", "VOICE.md", "establish editorial brand", "brand guidelines for blog". | Establish durable brand and voice context for cross-skill consumption. Generates BRAND.md (audience, positioning, do/don't editorial rules, taboo phrases, competitor differentiation) and VOICE.md (existing persona JSON… |
| [`blog-brief`](https://github.com/vamsy16/claude-blog/tree/HEAD/skills/blog-brief) | Use when user says "content brief", "blog brief", "write brief", "SEO brief", "article brief", or "content requirements". | Generate detailed content briefs for blog posts with target keywords, content outlines, competitive analysis, recommended statistics, image and chart suggestions, word count targets, internal linking architecture, template… |
| [`blog-calendar`](https://github.com/vamsy16/claude-blog/tree/HEAD/skills/blog-calendar) | Use when user says "editorial calendar", "content calendar", "blog calendar", "publishing schedule", "blog plan", "content plan", "what should I write". | Generate editorial calendars for blogs with topic clusters, publishing schedules, material-change reviews, update plans, seasonal opportunities, content mix formula, template integration, and distribution scheduling. |
| [`blog-cannibalization`](https://github.com/vamsy16/claude-blog/tree/HEAD/skills/blog-cannibalization) | Use when user says "cannibalization", "keyword overlap", "competing pages", "duplicate keywords", "cannibalize". | Detect keyword cannibalization across blog posts by extracting primary keywords from titles and headings, clustering semantically similar targets, and flagging posts competing for the same search intent. |
| [`blog-chart`](https://github.com/vamsy16/claude-blog/tree/HEAD/skills/blog-chart) | Use when user says "blog chart", "generate chart", "data visualization", "svg chart", "blog graph", or "visualize data". | Generate dark-mode-compatible inline SVG data visualization charts for blog posts. Supports horizontal bar, grouped bar, donut, line, lollipop, area, and radar charts with automatic platform detection (HTML vs JSX/MDX). |
| [`blog-cluster`](https://github.com/vamsy16/claude-blog/tree/HEAD/skills/blog-cluster) | Use when user says "blog cluster", "topic cluster", "content cluster", "cluster plan", "cluster execute", "pillar content", "hub and spoke", "content ecosystem",… | Semantic topic cluster planning and automated execution engine for claude-blog. Performs SERP-based keyword research, groups keywords by search intent and SERP overlap, builds a hub-and-spoke cluster architecture, generates an… |
| [`blog-decay`](https://github.com/vamsy16/claude-blog/tree/HEAD/skills/blog-decay) | Use when you say "/blog decay", "content decay", "traffic drop", "QoQ decline", "GSC decay", or "refresh declining posts". | Detect content decay from Google Search Console exports by comparing current and previous page performance, flagging quarter-over-quarter traffic drops, dropped pages, and refresh, consolidate, prune, or query-shift actions. |
| [`blog-discourse`](https://github.com/vamsy16/claude-blog/tree/HEAD/skills/blog-discourse) | Use when user says "blog discourse", "discourse research", "what are people saying about", "research what people are saying", "voice of customer", "social listening",… | Research what people are actually saying about a topic in the last 30 days across Reddit, X / Twitter, YouTube, Hacker News, dev.to, Medium, and other public discourse platforms. |
| [`blog-factcheck`](https://github.com/vamsy16/claude-blog/tree/HEAD/skills/blog-factcheck) | Use when user says "fact check", "verify statistics", "check sources", "validate claims", "factcheck", "source verification". | Verify statistics and claims in blog posts by fetching cited source URLs and checking if the claimed data actually appears on the page. |
| [`blog-flow`](https://github.com/vamsy16/claude-blog/tree/HEAD/skills/blog-flow) | Use when user says "FLOW", "FLOW framework", "blog flow", "evidence-led blogging", "find optimize win", or wants stage-specific blog prompts. | FLOW framework integration for bloggers. Evidence-led content workflow using the Find, Optimize, Win loop with stage-specific AI prompts from the FLOW knowledge base (30 blog-applicable prompts, CC BY 4.0). |
| [`blog-geo`](https://github.com/vamsy16/claude-blog/tree/HEAD/skills/blog-geo) | Use whenever you want their content to rank or be cited in ChatGPT, Perplexity, Claude, Gemini, Copilot, You.com, Google AI Overviews, or Google AI Mode. | AI citation readiness audit as part of SEO, covering classic Google search and AI search surfaces together. AI citation optimization audit scoring blog posts for major answer surfaces. |
| [`blog-google`](https://github.com/vamsy16/claude-blog/tree/HEAD/skills/blog-google) | Use when user says "google data", "page speed", "core web vitals", "search console", "indexation", "GA4", "keyword research", "nlp entities", "blog performance",… | Google API integration for blog performance: PageSpeed Insights, CrUX Core Web Vitals with 25-week history, Search Console performance, URL Inspection, Indexing API, GA4 organic traffic, NLP entity analysis for E-E-A-T, YouTube… |
| [`blog-image`](https://github.com/vamsy16/claude-blog/tree/HEAD/skills/blog-image) | Use when user says "blog image", "generate hero image", "blog illustration", "edit blog image", "OG image". | AI image generation and editing for blog content powered by Gemini via MCP. Generates hero images, inline illustrations, social preview cards, and OG images, and edits existing ones. |
| [`blog-locale-audit`](https://github.com/vamsy16/claude-blog/tree/HEAD/skills/blog-locale-audit) | Use when user says "locale audit", "blog locale-audit", "check translations", "multilingual audit", "translation check", "hreflang check", "Uebersetzungen pruefen". | Audit a directory of multilingual blog content for completeness, consistency, hreflang correctness, meta-tag parity, and freshness. |
| [`blog-localize`](https://github.com/vamsy16/claude-blog/tree/HEAD/skills/blog-localize) | Use when user says "localize blog", "blog localize", "cultural adaptation", "adapt for Germany", "lokalisieren", "localiser", "adaptar". | Deep cultural adaptation of translated blog posts. Run after blog-translate completes. Goes beyond translation to swap brand examples, adapt CTAs, substitute legal references, localize statistic sources where possible, and adjust… |
| [`blog-multilingual`](https://github.com/vamsy16/claude-blog/tree/HEAD/skills/blog-multilingual) | Use when user says "multilingual blog", "blog multilingual", "write in multiple languages", "international blog", "mehrsprachiger Blog", "blog multilingue", "blog… | One-command multilingual blog creation. Writes a blog post, translates it into user-specified languages, applies cultural adaptation, and emits hreflang tags, sitemap entries, and a CMS-ready language map. |
| [`blog-notebooklm`](https://github.com/vamsy16/claude-blog/tree/HEAD/skills/blog-notebooklm) | Use when user says "notebooklm", "notebook", "query notebook", "ask notebook", "notebook research", "source grounded research", "document query", "notebook library". | Query Google NotebookLM notebooks for source-grounded, citation-backed answers from user-uploaded documents. Manages notebook library, handles Google authentication, and supports smart discovery. |
| [`blog-outline`](https://github.com/vamsy16/claude-blog/tree/HEAD/skills/blog-outline) | Use when user says "outline", "blog outline", "content outline", "structure blog", "plan sections", "article skeleton", "heading structure", "SERP analysis",… | SERP-informed outline generation with H2/H3 heading hierarchy, competitive content gap analysis, section-by-section word count targets, chart and image placement markers, optional FAQ question planning, and internal linking… |
| [`blog-persona`](https://github.com/vamsy16/claude-blog/tree/HEAD/skills/blog-persona) | Use when user says "persona", "voice", "tone", "writing style", "brand voice", "create persona", "use persona". | Create and manage writing personas with NNGroup 4-dimension tone framework (Funny-Serious, Formal-Casual, Respectful-Irreverent, Enthusiastic-Matter-of-fact). |
| [`blog-repurpose`](https://github.com/vamsy16/claude-blog/tree/HEAD/skills/blog-repurpose) | Use when user says "repurpose", "blog repurpose", "share blog", "social media", "twitter thread", "linkedin post", "youtube script", "reddit post". | Repurpose blog posts for social media, email, video, podcast, and community channels. Generates Twitter/X threads, LinkedIn posts and articles, Threads, Bluesky, TikTok, Instagram, YouTube Shorts and long-form scripts, Reddit,… |
| [`blog-rewrite`](https://github.com/vamsy16/claude-blog/tree/HEAD/skills/blog-rewrite) | Use when user says "rewrite blog", "optimize blog", "update blog", "improve blog", "fix blog". | Rewrite and optimize existing blog posts for Google SEO (May 2026 Core Update, E-E-A-T) and AI citation visibility as one SEO discipline. For AI-citation-only audit (no Google work), use blog-geo instead. |
| [`blog-schema`](https://github.com/vamsy16/claude-blog/tree/HEAD/skills/blog-schema) | Use when user says "schema", "blog schema", "json-ld", "structured data", "schema markup", "generate schema". | Generate complete JSON-LD schema markup for blog posts with Article/BlogPosting, Person, Organization, BreadcrumbList, ImageObject, and optional FAQPage. Validates against Google requirements and warns about deprecated types. |
| [`blog-seo-check`](https://github.com/vamsy16/claude-blog/tree/HEAD/skills/blog-seo-check) | Use when user says "seo check", "check seo", "validate seo", "blog seo", "seo validation", "on-page seo", "title tag check", "meta description check", "heading check",… | Post-writing SEO validation with pass/fail checklist covering title tag length and keyword placement, meta description quality, heading hierarchy and keyword density, internal/external link audit with anchor text analysis,… |
| [`blog-strategy`](https://github.com/vamsy16/claude-blog/tree/HEAD/skills/blog-strategy) | Use when user says "blog strategy", "content strategy", "blog positioning", "what should I blog about", "blog topics", "content pillars", "blog ideation". | Blog strategy development including topic cluster architecture with hub-and-spoke design, audience mapping, competitive landscape analysis, AI citation surface strategy across ChatGPT/Perplexity/AI Overviews, distribution channel… |
| [`blog-style`](https://github.com/vamsy16/claude-blog/tree/HEAD/skills/blog-style) | — | Learn author writing style from 5 to 10 existing blog posts and generate a voice profile for /blog style learn, VOICE.md, blog-persona, and blog-write when users ask to infer tone, analyze author voice, learn style, or build a… |
| [`blog-taxonomy`](https://github.com/vamsy16/claude-blog/tree/HEAD/skills/blog-taxonomy) | Use when user says "tags", "categories", "taxonomy", "tag suggestions", "sync tags", "WordPress tags", "Shopify tags". | Extract, suggest, and sync tags and categories for blog posts across all major CMS platforms. Supports WordPress REST API, Shopify GraphQL, Ghost Content API, Strapi REST/GraphQL, and Sanity GROQ. |
| [`blog-translate`](https://github.com/vamsy16/claude-blog/tree/HEAD/skills/blog-translate) | Use when user says "translate blog", "blog translate", "uebersetzen", "traduire", "traducir", "translate post", "blog auf Deutsch", "blog en espanol". | Translate existing blog posts into one or more target languages with SEO-optimized localization. |
| [`blog-write`](https://github.com/vamsy16/claude-blog/tree/HEAD/skills/blog-write) | Use when user says "write blog", "new blog post", "create article", "write about", "draft blog", "generate blog post". | Write new blog articles from scratch optimized for Google rankings and AI citations. Generates full articles with template selection, answer-first formatting, Key Takeaways summary box, information gain markers, evidence-backed… |
| [`brain`](https://github.com/vamsy16/claude-blog/tree/HEAD/brain) | Use when you say "claude-blog-brain", "Claude Blog Brain", "create a blog content creation, optimization, and management dual-optimized for Google rankings (E-E-A-T, the… | Scaffold and operate Claude Blog Brain, a source-cited Obsidian brain for blog content creation, optimization, and management dual-optimized for Google rankings (E-E-A-T, the 2026 core updates) and AI citations (GEO/AEO),… |

#### `claude-seo`

🔗 [https://github.com/vamsy16/claude-seo](https://github.com/vamsy16/claude-seo) · Fork of [`AgriciDaniel/claude-seo`](https://github.com/AgriciDaniel/claude-seo) · Language: n/a · Last push: 2026-08-26

**What it is:** Universal SEO skill for Claude Code. 25 sub-skills + 18 sub-agents covering technical SEO, E-E-A-T, schema, GEO/AEO, backlinks, local SEO, maps intelligence, semantic clustering, e-commerce SEO, international SEO, Google APIs, and PDF/Excel reporting. Optional DataForSEO, Firecrawl, and Banana extensions.

**When to use:** For deep, professional SEO work: technical audits, E-E-A-T, schema, GEO/AEO (AI-search optimization), backlinks, local SEO, maps intelligence, semantic clustering, e-commerce/international SEO, Google API integrations, and PDF/Excel reporting. 25 sub-skills + 18 sub-agents.

**Install / quick start:**

Claude Code 1.0.33+:
```bash
/plugin marketplace add AgriciDaniel/claude-seo
/plugin install claude-seo@agricidaniel-claude-seo
/seo setup
```

**Skills inside — 31** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`seo`](https://github.com/vamsy16/claude-seo/tree/HEAD/skills/seo) | — | Comprehensive SEO analysis for any website or business type. Full site audits, single-page analysis, technical SEO (crawlability, indexability, Core Web Vitals with INP), schema markup, content quality (E-E-A-T), image… |
| [`seo-ahrefs`](https://github.com/vamsy16/claude-seo/tree/HEAD/extensions/ahrefs/skills/seo-ahrefs) | — | Ahrefs API analyst (extension). Reads referring domains, backlinks, organic keywords, and content explorer data via the tested @ahrefs/mcp@0.0.11 server. Pairs with seo-backlinks for multi-source confidence weighting. |
| [`seo-audit`](https://github.com/vamsy16/claude-seo/tree/HEAD/skills/seo-audit) | Use when user says audit, full SEO check, analyze my site, or website health check. | Full website SEO audit with parallel subagent delegation. Crawls up to 500 pages, detects business type, delegates to up to 15 specialists (8 always + 7 conditional), generates health score. |
| [`seo-backlinks`](https://github.com/vamsy16/claude-seo/tree/HEAD/skills/seo-backlinks) | Use when user says backlinks, link profile, referring domains, anchor text, toxic links, link gap, link building, disavow, or backlink audit. | Backlink profile analysis: referring domains, anchor text distribution, toxic link detection, competitor gap analysis. Works with free APIs (Moz, Bing Webmaster, Common Crawl) and DataForSEO extension. |
| [`seo-bing`](https://github.com/vamsy16/claude-seo/tree/HEAD/extensions/bing-webmaster/skills/seo-bing) | — | Bing Webmaster Tools + IndexNow extension. Microsoft Copilot citations are fed by the Bing index; this skill makes Bing visibility, link data, and IndexNow URL submission first-class. |
| [`seo-cluster`](https://github.com/vamsy16/claude-seo/tree/HEAD/skills/seo-cluster) | Use when user says "topic cluster", "content cluster", "semantic clustering", "pillar page", "hub and spoke", "content architecture", "keyword grouping", or "cluster… | SERP-based semantic topic clustering for content architecture planning. Groups keywords by actual Google SERP overlap (not text similarity), designs hub-and-spoke content clusters with internal link matrices, and generates… |
| [`seo-competitor-pages`](https://github.com/vamsy16/claude-seo/tree/HEAD/skills/seo-competitor-pages) | Use when user says "comparison page", "vs page", "alternatives page", "competitor comparison", "X vs Y", "versus", "compare competitors", or "alternative to". | Generate SEO-optimized competitor comparison and alternatives pages. Covers "X vs Y" layouts, "alternatives to X" pages, feature matrices, schema markup, and conversion optimization. |
| [`seo-content`](https://github.com/vamsy16/claude-seo/tree/HEAD/skills/seo-content) | Use when user says "content quality", "E-E-A-T", "content analysis", "readability check", "thin content", or "content audit". | Content quality and E-E-A-T analysis with AI citation readiness assessment. |
| [`seo-content-brief`](https://github.com/vamsy16/claude-seo/tree/HEAD/skills/seo-content-brief) | Use when user says "content brief", "write a brief", "content outline", "blog brief", "service page brief", "brief for", "writing brief", "content plan", or "outline… | Generate competitive SEO content briefs with per-section word counts, competitor scoring, keyword density guidance, and page-type templates. Supports both new page briefs and improve-existing-page briefs. |
| [`seo-dataforseo`](https://github.com/vamsy16/claude-seo/tree/HEAD/skills/seo-dataforseo) | Use when user says "dataforseo", "live SERP", "keyword volume", "backlink data", "AI visibility check", or "real search data". | Live SEO data via DataForSEO MCP server: SERP analysis, keyword research (volume, difficulty, intent, trends), backlink profiles, on-page analysis, competitor and content analysis, business listings, AI visibility (LLM mention… |
| [`seo-drift`](https://github.com/vamsy16/claude-seo/tree/HEAD/skills/seo-drift) | Use when user says "SEO drift", "baseline", "track changes", "did anything break", "SEO regression", "compare SEO", "before and after", "monitor SEO changes", or… | SEO drift monitoring: capture baselines of SEO-critical elements, detect changes, and track regressions over time. Git for SEO: baseline, diff, and track changes to your on-page SEO. |
| [`seo-ecommerce`](https://github.com/vamsy16/claude-seo/tree/HEAD/skills/seo-ecommerce) | Use when user says "ecommerce SEO", "product SEO", "Google Shopping", "marketplace SEO", "product schema", "Amazon SEO", "product listings", "shopping ads", or "merchant… | E-commerce SEO analysis: Google Shopping visibility, Amazon marketplace intelligence, product schema validation, competitor pricing analysis, and marketplace keyword gaps. |
| [`seo-firecrawl`](https://github.com/vamsy16/claude-seo/tree/HEAD/extensions/firecrawl/skills/seo-firecrawl) | Use when user says "crawl site", "map site", "full crawl", "find all pages", "broken links", "site structure", "discover pages", "JS rendering", or needs site-wide… | Full-site crawling, scraping, and site mapping via Firecrawl MCP. |
| [`seo-flow`](https://github.com/vamsy16/claude-seo/tree/HEAD/skills/seo-flow) | Use when user says "FLOW", "FLOW framework", "seo flow", "evidence-led SEO", "find leverage optimize win", or wants stage-specific SEO prompts. | FLOW framework integration: evidence-led SEO using the Find → Leverage → Optimize → Win loop. Surfaces stage-specific AI prompts from the FLOW knowledge base (41 prompts, CC BY 4.0). |
| [`seo-geo`](https://github.com/vamsy16/claude-seo/tree/HEAD/skills/seo-geo) | Use when user says "AI Overviews", "SGE", "GEO", "AI search", "LLM optimization", "Perplexity", "AI citations", "ChatGPT search", or "AI visibility". | Optimize content for AI Overviews (formerly SGE), ChatGPT web search, Perplexity, and other AI-powered search experiences. |
| [`seo-google`](https://github.com/vamsy16/claude-seo/tree/HEAD/skills/seo-google) | Use when user says "search console", "GSC", "PageSpeed", "CrUX", "field data", "indexing API", "GA4 organic", "URL inspection", or "real CWV data". | Google SEO APIs: Search Console (Search Analytics, URL Inspection, Sitemaps), PageSpeed Insights v5, CrUX field data with 25-week history, Indexing API v3, and GA4 organic traffic. |
| [`seo-hreflang`](https://github.com/vamsy16/claude-seo/tree/HEAD/skills/seo-hreflang) | Use when user says "hreflang", "i18n SEO", "international SEO", "multi-language", "multi-region", or "language tags". | Hreflang and international SEO audit, validation, and generation. Detects common mistakes, validates language/region codes, and generates correct hreflang implementations. |
| [`seo-image-gen`](https://github.com/vamsy16/claude-seo/tree/HEAD/skills/seo-image-gen) | Use when user says \"generate image\", \"OG image\", \"social preview\", \"hero image\", \"blog image\", \"product photo\", \"infographic\", \"seo image\", \"create… | AI image generation for SEO assets: OG/social preview images, blog hero images, schema images, product photography, infographics. Powered by Gemini via nanobanana-mcp. Requires banana extension installed. |
| [`seo-images`](https://github.com/vamsy16/claude-seo/tree/HEAD/skills/seo-images) | Use when user says "image optimization", "alt text", "image SEO", "image size", "image audit", "optimize images", "image metadata", "image SERP", "convert to webp", or… | Image optimization analysis for SEO and performance. Checks alt text, file sizes, formats, responsive images, lazy loading, CLS prevention, image SERP rankings (via DataForSEO), and image file optimization (WebP/AVIF conversion,… |
| [`seo-local`](https://github.com/vamsy16/claude-seo/tree/HEAD/skills/seo-local) | Use when user says "local SEO", "Google Business Profile", "GBP", "map pack", "local pack", "citations", "NAP consistency", "service area", or "multi-location". | Local SEO analysis covering Google Business Profile optimization, NAP consistency, citation health, review signals, local schema markup, location page quality, multi-location SEO, and industry-specific recommendations. |
| [`seo-maps`](https://github.com/vamsy16/claude-seo/tree/HEAD/skills/seo-maps) | Use when user says "maps", "geo-grid", "rank tracking", "GBP audit", "review velocity", "competitor radius", or "SoLV". | Maps intelligence for local SEO: geo-grid rank tracking, GBP profile auditing via API, review intelligence across Google/Tripadvisor/Trustpilot, cross-platform NAP verification, competitor radius mapping, and LocalBusiness schema… |
| [`seo-page`](https://github.com/vamsy16/claude-seo/tree/HEAD/skills/seo-page) | Use when user says "analyze this page", "check page SEO", "single URL", "check this page", "page analysis", or provides a single URL for review. | Deep single-page SEO analysis covering on-page elements, content quality, technical meta tags, schema, images, and performance. |
| [`seo-plan`](https://github.com/vamsy16/claude-seo/tree/HEAD/skills/seo-plan) | Use when user says "SEO plan", "SEO strategy", "SEO planning", "content strategy", "keyword strategy", "content calendar", "site architecture", or "SEO roadmap". | Strategic SEO planning for new or existing websites. Industry-specific templates, competitive analysis, content strategy, and implementation roadmap. |
| [`seo-profound`](https://github.com/vamsy16/claude-seo/tree/HEAD/extensions/profound/skills/seo-profound) | — | Profound LLM citation tracker (extension). Time-series brand citation rates across ChatGPT, Perplexity, and other LLMs. Pairs with seo-seranking for triangulated AI visibility coverage. |
| [`seo-programmatic`](https://github.com/vamsy16/claude-seo/tree/HEAD/skills/seo-programmatic) | Use when user says "programmatic SEO", "pages at scale", "dynamic pages", "template pages", "generated pages", or "data-driven SEO". | Programmatic SEO planning and analysis for pages generated at scale from data sources. Covers template engines, URL patterns, internal linking automation, thin content safeguards, and index bloat prevention. |
| [`seo-schema`](https://github.com/vamsy16/claude-seo/tree/HEAD/skills/seo-schema) | Use when user says "schema", "structured data", "rich results", "JSON-LD", or "markup". | Detect, validate, and generate Schema.org structured data. JSON-LD format preferred. |
| [`seo-seranking`](https://github.com/vamsy16/claude-seo/tree/HEAD/extensions/seranking/skills/seo-seranking) | — | SE Ranking AI visibility analyst (extension). Tracks AI Share-of-Voice across ChatGPT, Gemini, Perplexity, AI Overviews, and AI Mode in a single query. |
| [`seo-sitemap`](https://github.com/vamsy16/claude-seo/tree/HEAD/skills/seo-sitemap) | Use when user says "sitemap", "generate sitemap", "sitemap issues", or "XML sitemap". | Analyze existing XML sitemaps or generate new ones with industry templates. Validates format, URLs, and structure. |
| [`seo-sxo`](https://github.com/vamsy16/claude-seo/tree/HEAD/skills/seo-sxo) | Use when user says "SXO", "search experience", "page type mismatch", "SERP analysis", "user story", "persona scoring", "why isn't my page ranking", "intent mismatch", or… | Search Experience Optimization: reads Google SERPs backwards to detect page-type mismatches, derives user stories from search intent signals, and scores pages from multiple persona perspectives. |
| [`seo-technical`](https://github.com/vamsy16/claude-seo/tree/HEAD/skills/seo-technical) | Use when user says "technical SEO", "crawl issues", "robots.txt", "Core Web Vitals", "site speed", or "security headers". | Technical SEO audit across 9 categories: crawlability, indexability, security, URL structure, mobile, Core Web Vitals, structured data, JavaScript rendering, and IndexNow protocol. |
| [`seo-unlighthouse`](https://github.com/vamsy16/claude-seo/tree/HEAD/extensions/unlighthouse/skills/seo-unlighthouse) | — | Multi-page Lighthouse audit via the MIT-licensed Unlighthouse CLI. Free-tier alternative to running PageSpeed against every URL on a site, no API quota burn, runs locally. |

#### `Brand-building-skills`

🔗 [https://github.com/vamsy16/Brand-building-skills](https://github.com/vamsy16/Brand-building-skills) · Fork of [`arnabbagxd/Brand-building-skills`](https://github.com/arnabbagxd/Brand-building-skills) · Language: n/a · Last push: 2026-06-13

**What it is:** Brand building skills for Claude Code and AI agents. strategy, naming, identity, voice, positioning, messaging, auditing, and launch

**When to use:** When creating, repositioning, or auditing a brand: strategy, naming, identity, voice, positioning, messaging, and launch.

**Install / quick start:**

```bash
npx skills add arnabbagxd/brand-building-skills
```

**Skills inside — 29** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`aso`](https://github.com/vamsy16/Brand-building-skills/tree/HEAD/skills/aso) | Use when you say "ASO", "app store optimization", "optimize my app listing", "improve app store ranking", "app store keywords", "app store screenshots", "app store… | Optimize an app's store listing for maximum visibility and downloads — keyword strategy, title and subtitle optimization, screenshots, preview videos, rating and review management, and A/B testing on the App Store (iOS) and… |
| [`b2b-brand-marketing`](https://github.com/vamsy16/Brand-building-skills/tree/HEAD/skills/b2b-brand-marketing) | Use when you say "B2B marketing", "B2B brand", "business to business marketing", "selling to companies", "enterprise marketing", "we sell to businesses", "B2B brand… | Build and execute brand marketing strategy for B2B companies — thought leadership, ABM brand layer, trust signals, LinkedIn presence, long sales cycle brand touchpoints, and enterprise credibility. |
| [`brand-architecture`](https://github.com/vamsy16/Brand-building-skills/tree/HEAD/skills/brand-architecture) | Use when you say "brand architecture", "sub-brand", "brand portfolio", "master brand", "house of brands", "branded house", "product naming system", "how do our brands… | Define how multiple brands, sub-brands, and product lines relate to each other under one organization. |
| [`brand-audit`](https://github.com/vamsy16/Brand-building-skills/tree/HEAD/skills/brand-audit) | Use when you say "brand audit", "brand review", "assess our brand", "is our brand consistent", "brand health check", "brand analysis", "something's off with our brand",… | Assess the health and consistency of an existing brand — identity, messaging, voice, positioning, and market perception. |
| [`brand-context`](https://github.com/vamsy16/Brand-building-skills/tree/HEAD/skills/brand-context) | Use when you say "set brand context", "save my brand info", "store brand details", "brand profile", "create brand context file", "update brand context", or when starting… | Foundation skill that captures and stores core brand context — identity, audience, positioning, values, and voice. Every other brand skill reads this file first. |
| [`brand-guidelines`](https://github.com/vamsy16/Brand-building-skills/tree/HEAD/skills/brand-guidelines) | Use when you say "brand guidelines", "brand standards", "brand book", "style guide", "brand guide", "brand manual", "brand rules", "brand documentation", "brand… | Create a comprehensive brand standards document — covering logo usage, color, typography, voice, messaging, and application rules. |
| [`brand-identity`](https://github.com/vamsy16/Brand-building-skills/tree/HEAD/skills/brand-identity) | Use when you say "visual identity", "brand identity", "logo brief", "logo direction", "design brief", "brand design", "color palette for my brand", "typography for my… | Create a visual identity brief for a brand — logo direction, color palette, typography, imagery style, and design system foundations. |
| [`brand-launch`](https://github.com/vamsy16/Brand-building-skills/tree/HEAD/skills/brand-launch) | Use when you say "launch the brand", "brand launch plan", "how do we introduce the brand", "brand reveal", "brand debut", "going public with the brand", "announcing the… | Plan and execute a new brand launch — from internal rollout to public debut. Also use for soft launches, hard launches, and phased rollouts. |
| [`brand-manifesto`](https://github.com/vamsy16/Brand-building-skills/tree/HEAD/skills/brand-manifesto) | Use when you say "brand manifesto", "manifesto", "what we believe", "brand declaration", "brand belief statement", "rally the team around the brand", "inspire the team",… | Write a brand manifesto — a bold, belief-driven declaration of what the brand stands for, fights against, and exists to change. |
| [`brand-measurement`](https://github.com/vamsy16/Brand-building-skills/tree/HEAD/skills/brand-measurement) | Use when you say "brand measurement", "brand metrics", "how do we measure the brand", "brand KPIs", "brand health tracking", "brand awareness metrics", "brand equity… | Define KPIs, metrics, and tracking systems to measure brand health, awareness, perception, and equity over time. |
| [`brand-messaging`](https://github.com/vamsy16/Brand-building-skills/tree/HEAD/skills/brand-messaging) | Use when you say "brand messaging", "messaging framework", "value proposition", "tagline", "brand tagline", "key messages", "messaging hierarchy", "what should we say… | Build a brand's messaging hierarchy — taglines, value propositions, key messages, and proof points for each audience. |
| [`brand-naming`](https://github.com/vamsy16/Brand-building-skills/tree/HEAD/skills/brand-naming) | Use this skill whenever you say "help me name this brand", "brand naming", "I need a name for", "name ideas for", "what should I call my brand/company/product", "naming… | Full brand naming workflow for founders, agencies, and businesses. Also triggers when the user shares existing name options and asks for feedback, evaluation, ranking, or scoring of those names. |
| [`brand-packaging`](https://github.com/vamsy16/Brand-building-skills/tree/HEAD/skills/brand-packaging) | Use when you say "packaging design", "packaging brief", "product packaging", "packaging direction", "label design", "packaging identity", "unboxing experience",… | Create a packaging design brief — structure, visual direction, hierarchy, materials, and unboxing experience. |
| [`brand-partnerships`](https://github.com/vamsy16/Brand-building-skills/tree/HEAD/skills/brand-partnerships) | Use when you say "brand partnership", "brand collab", "co-branding", "brand collaboration", "partnership marketing", "brand alliance", "co-branded product", "licensing… | Build brand partnership strategy — co-branding campaigns, brand collaborations, licensing deals, partner brand alignment, and joint marketing. |
| [`brand-positioning`](https://github.com/vamsy16/Brand-building-skills/tree/HEAD/skills/brand-positioning) | Use when you say "brand positioning", "positioning statement", "where do we sit in the market", "how are we different", "differentiation strategy", "positioning map",… | Define and sharpen a brand's market positioning — where it sits relative to competitors, what it owns, and how it differentiates. |
| [`brand-story`](https://github.com/vamsy16/Brand-building-skills/tree/HEAD/skills/brand-story) | Use when you say "brand story", "origin story", "founder story", "why we exist", "about us", "our story", "company narrative", "brand narrative", "write our about page",… | Craft a brand's origin story, founder narrative, and "why we exist" statement. |
| [`brand-strategy`](https://github.com/vamsy16/Brand-building-skills/tree/HEAD/skills/brand-strategy) | Use this skill whenever a user says "brand strategy", "create a brand report", "build brand strategy for my client", "brand questionnaire", "I have a new branding… | Full brand strategy workflow for agencies and brand consultants. Acts as a senior brand strategist — collects client information through a structured questionnaire, then generates a complete, polished brand strategy report. |
| [`brand-voice`](https://github.com/vamsy16/Brand-building-skills/tree/HEAD/skills/brand-voice) | Use when you say "brand voice", "tone of voice", "how should we write", "writing guidelines", "copy style guide", "brand language", "verbal identity", "how should the… | Define a brand's verbal identity — tone, voice, writing style, vocabulary, and messaging rules. |
| [`competitor-branding`](https://github.com/vamsy16/Brand-building-skills/tree/HEAD/skills/competitor-branding) | Use when you say "competitor brand analysis", "analyze competitor brands", "how do competitors position themselves", "competitor messaging", "competitor identity", "what… | Analyze how competitors present their brand — identity, messaging, positioning, voice, and visual style — to find gaps and opportunities. |
| [`d2c-marketing`](https://github.com/vamsy16/Brand-building-skills/tree/HEAD/skills/d2c-marketing) | Use when you say "DTC marketing", "direct to consumer", "D2C strategy", "selling directly to customers", "cut out the middleman", "DTC brand", "e-commerce brand… | Build and execute marketing strategy for Direct-to-Consumer (DTC) brands — customer acquisition, retention, email flows, social proof, subscription models, and repeat purchase mechanics. |
| [`email-marketing`](https://github.com/vamsy16/Brand-building-skills/tree/HEAD/skills/email-marketing) | Use when you say "email marketing", "email strategy", "email list", "newsletter", "email campaigns", "email list building", "email deliverability", "email open rates",… | Build and run a full email marketing channel — list building, deliverability, segmentation, newsletter strategy, campaign types, A/B testing, and email design. |
| [`google-ads`](https://github.com/vamsy16/Brand-building-skills/tree/HEAD/skills/google-ads) | Use when you say "Google Ads", "Google advertising", "Google campaign", "search ads", "Google Shopping", "Performance Max", "PMax", "Google Display", "YouTube ads",… | Plan, build, and optimize Google Ads campaigns — Search, Shopping, Performance Max, Display, and YouTube — including keyword research, match types, bidding strategy, Quality Score, ad extensions, conversion tracking, and ROAS… |
| [`influencer-marketing`](https://github.com/vamsy16/Brand-building-skills/tree/HEAD/skills/influencer-marketing) | Use when you say "influencer marketing", "influencer strategy", "work with influencers", "influencer outreach", "influencer brief", "find influencers", "micro… | Build an influencer marketing strategy — finding influencers, briefing, contracts, deliverables, performance tracking, micro vs macro strategy, outreach, and FTC compliance. |
| [`meta-ads`](https://github.com/vamsy16/Brand-building-skills/tree/HEAD/skills/meta-ads) | Use when you say "Meta ads", "Facebook ads", "Instagram ads", "Facebook advertising", "Meta advertising", "Meta campaigns", "Facebook campaign", "Instagram campaign",… | Plan, build, and optimize Meta advertising campaigns on Facebook and Instagram — campaign structure, audience targeting (core, custom, lookalike), creative formats, pixel setup, retargeting strategy, budget scaling, and ROAS… |
| [`personal-brand`](https://github.com/vamsy16/Brand-building-skills/tree/HEAD/skills/personal-brand) | Use when you say "personal brand", "personal branding", "build my brand", "founder brand", "executive brand", "thought leadership", "I want to be known for", "grow my… | Build a personal brand strategy for founders, executives, creators, and consultants. |
| [`rebranding`](https://github.com/vamsy16/Brand-building-skills/tree/HEAD/skills/rebranding) | Use when you say "rebrand", "rebranding", "brand refresh", "update the brand", "modernize the brand", "our brand is outdated", "we've outgrown our brand", "the brand… | Plan and execute a brand transformation — from diagnosis to new brand definition to rollout. |
| [`target-audience`](https://github.com/vamsy16/Brand-building-skills/tree/HEAD/skills/target-audience) | Use when you say "target audience", "ideal customer", "customer persona", "audience persona", "ICP", "who is our customer", "define our audience", "audience research",… | Define a brand's target audience with deep personas, psychographics, and ICP (Ideal Customer Profile). |
| [`ugc-strategy`](https://github.com/vamsy16/Brand-building-skills/tree/HEAD/skills/ugc-strategy) | Use when you say "UGC", "user generated content", "get customers to create content", "customer content", "UGC ads", "UGC creators", "organic UGC", "UGC strategy", "how… | Build a User Generated Content (UGC) strategy — getting customers to create content, review generation, UGC briefs for creators, social campaigns, contest mechanics, legal rights management, and repurposing UGC in paid ads. |
| [`whatsapp-marketing`](https://github.com/vamsy16/Brand-building-skills/tree/HEAD/skills/whatsapp-marketing) | Use when you say "WhatsApp marketing", "WhatsApp Business", "WhatsApp campaigns", "WhatsApp broadcasts", "WhatsApp automation", "WhatsApp drip", "market on WhatsApp",… | Build a WhatsApp marketing strategy — WhatsApp Business setup, broadcast campaigns, automated flows, customer service, drip sequences, and conversational marketing. |

#### `open-ai-video-agent`

🔗 [https://github.com/vamsy16/open-ai-video-agent](https://github.com/vamsy16/open-ai-video-agent) · Fork of [`SamurAIGPT/open-ai-video-agent`](https://github.com/SamurAIGPT/open-ai-video-agent) · Language: n/a · Last push: 2026-08-27

**What it is:** AI agent for video production — text/image-to-video generation, avatar/UGC talking-head videos, and data-driven ad-creative remakes, powered by muapi.ai.

**When to use:** For video production: text/image-to-video, avatar/UGC talking-head videos, and data-driven ad-creative remakes (powered by muapi.ai).

**Install / quick start:**

Add `AGENTS.md` + the workflow skill folder from `agents/`; connect a media provider (MCP/REST); give the brief + source media.

**Skills inside — 28** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`ad-creative-remake`](https://github.com/vamsy16/open-ai-video-agent/tree/HEAD/agents/ad-creative-remake) | — | Plan draft video-ad variations from supplied performance evidence, preserving the distinction between observed data and creative hypotheses. |
| [`avatar-ugc`](https://github.com/vamsy16/open-ai-video-agent/tree/HEAD/agents/avatar-ugc) | — | Create authorized presenter, avatar, and UGC-style video drafts with explicit voice, likeness, consent, and synthetic-media handling. |
| [`b-roll-generation`](https://github.com/vamsy16/open-ai-video-agent/tree/HEAD/agents/b-roll-generation) | — | Analyze a script or existing edit, identify visual gaps, and generate supplemental B-roll coverage with clear parent and factual-status labels. |
| [`character-continuity`](https://github.com/vamsy16/open-ai-video-agent/tree/HEAD/agents/character-continuity) | — | Build a consented continuity system for an authorized person, fictional character, product, or world across video shots. |
| [`cinematic-direction`](https://github.com/vamsy16/open-ai-video-agent/tree/HEAD/agents/cinematic-direction) | — | Translate creative intent into coherent cinematography, framing, camera, lens, lighting, motion, and sound direction for a video shot. |
| [`consented-romantic-video`](https://github.com/vamsy16/open-ai-video-agent/tree/HEAD/agents/consented-romantic-video) | — | Create a non-explicit romantic scene from authorized adult references with clear consent, identity boundaries, and synthetic-media labeling. |
| [`curiosity-3d-explainer`](https://github.com/vamsy16/open-ai-video-agent/tree/HEAD/agents/curiosity-3d-explainer) | — | Turn one approved topic into a curiosity-led 3D educational short with character sheets, ordered keyframes, motion clips, narration, captions, and an auditable assembly plan. |
| [`faceless-video`](https://github.com/vamsy16/open-ai-video-agent/tree/HEAD/agents/faceless-video) | — | Turn an approved topic into a narrated, non-presenter video using a script, voice asset, visual coverage, assembly, and captions. |
| [`logo-animation`](https://github.com/vamsy16/open-ai-video-agent/tree/HEAD/agents/logo-animation) | — | Turn an authorized 2D logo into an approved visual treatment and animate a controlled brand reveal while preserving the mark. |
| [`meme-video`](https://github.com/vamsy16/open-ai-video-agent/tree/HEAD/agents/meme-video) | — | Turn an approved meme idea, image, or short source into a concise humorous video draft with a clear hook, caption plan, and platform variants. |
| [`micro-drama-video`](https://github.com/vamsy16/open-ai-video-agent/tree/HEAD/agents/micro-drama-video) | — | Develop a short scripted micro-drama from an idea or approved script through character sheets, storyboard frames, animated shots, and a reviewable assembly. |
| [`motion-control`](https://github.com/vamsy16/open-ai-video-agent/tree/HEAD/agents/motion-control) | — | Plan and execute reference-driven movement using first/last frames, driving video, and model-specific motion controls. |
| [`music-video`](https://github.com/vamsy16/open-ai-video-agent/tree/HEAD/agents/music-video) | — | Build a music-led video sequence by planning beats, creating or accepting an audio track, animating ordered visuals, and assembling a reviewable draft. |
| [`paper-collage-explainer`](https://github.com/vamsy16/open-ai-video-agent/tree/HEAD/agents/paper-collage-explainer) | — | Create a narrated editorial explainer from a topic, presenter, or photo using high-contrast paper-collage keyframes, motion, audio, and captions. |
| [`product-video-ads`](https://github.com/vamsy16/open-ai-video-agent/tree/HEAD/agents/product-video-ads) | — | Produce product-led video ad concepts and variants while preserving approved product details, claims, and platform constraints. |
| [`short-form-repurposing`](https://github.com/vamsy16/open-ai-video-agent/tree/HEAD/agents/short-form-repurposing) | — | Find useful moments in long-form video, create ranked short clips, reframe them, and generate captions without losing source provenance. |
| [`social-video`](https://github.com/vamsy16/open-ai-video-agent/tree/HEAD/agents/social-video) | — | Turn brand context and a social brief into platform-aware copy, storyboard, reference frames, and video drafts without publishing them. |
| [`storyboard-to-video`](https://github.com/vamsy16/open-ai-video-agent/tree/HEAD/agents/storyboard-to-video) | — | Turn a premise, script, or beat sheet into an ordered storyboard and animate approved keyframes into a coherent video. |
| [`video-assembly`](https://github.com/vamsy16/open-ai-video-agent/tree/HEAD/agents/video-assembly) | — | Turn approved video clips, audio, captions, and timing decisions into an ordered, reviewable draft while preserving a reproducible timeline. |
| [`video-captioning`](https://github.com/vamsy16/open-ai-video-agent/tree/HEAD/agents/video-captioning) | — | Prepare, generate, proofread, and hand off captions for an approved video without hiding transcription uncertainty or changing the source cut. |
| [`video-editing`](https://github.com/vamsy16/open-ai-video-agent/tree/HEAD/agents/video-editing) | — | Edit, extend, transition, and combine existing video while preserving an explicit parent asset and audio decision. |
| [`video-effects`](https://github.com/vamsy16/open-ai-video-agent/tree/HEAD/agents/video-effects) | — | Apply a short artistic effect or VFX transformation to an approved media parent with explicit intent, provenance, and safety labeling. |
| [`video-enhancement`](https://github.com/vamsy16/open-ai-video-agent/tree/HEAD/agents/video-enhancement) | — | Upscale and prepare a selected video parent for delivery while preserving provenance and checking that enhancement did not create new defects. |
| [`video-generation`](https://github.com/vamsy16/open-ai-video-agent/tree/HEAD/agents/video-generation) | — | Turn a brief, script, shot list, or approved reference into asynchronous text-to-video, image-to-video, or reference-driven clips. |
| [`video-model-selection`](https://github.com/vamsy16/open-ai-video-agent/tree/HEAD/agents/video-model-selection) | — | Select a current video model and endpoint against duration, references, motion, audio, ratio, quality, cost, and continuity requirements using live schemas. |
| [`video-project-setup`](https://github.com/vamsy16/open-ai-video-agent/tree/HEAD/agents/video-project-setup) | — | Establish durable project context, asset roles, delivery constraints, and approval state for repeatable video work. |
| [`video-strategist`](https://github.com/vamsy16/open-ai-video-agent/tree/HEAD/agents/video-strategist) | — | Route a broad video brief into the smallest useful production workflow, choose live model schemas, and return an evidence-backed execution plan. |
| [`youtube-shorts`](https://github.com/vamsy16/open-ai-video-agent/tree/HEAD/agents/youtube-shorts) | — | Turn an authorized long-form video into a ranked set of YouTube Shorts candidates with vertical framing, captions, timestamps, and source provenance. |

#### `open-ai-image-agent`

🔗 [https://github.com/vamsy16/open-ai-image-agent](https://github.com/vamsy16/open-ai-image-agent) · Fork of [`SamurAIGPT/open-ai-image-agent`](https://github.com/SamurAIGPT/open-ai-image-agent) · Language: n/a · Last push: 2026-08-27

**What it is:** AI agent for image and creative production — image generation, thumbnails, and on-brand visual content, powered by muapi.ai.

**When to use:** For image and creative production: image generation, thumbnails, and on-brand visual content (powered by muapi.ai).

**Install / quick start:**

Add `AGENTS.md` + the skill from `agents/`; connect an image provider (bundled MuAPI adapter supported).

**Skills inside — 20** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`ad-creative`](https://github.com/vamsy16/open-ai-image-agent/tree/HEAD/agents/ad-creative) | — | Plan and generate a conversion-oriented image-ad set in two phases: approve a hero concept and copy direction, then fan it out into platform formats. |
| [`brand-content`](https://github.com/vamsy16/open-ai-image-agent/tree/HEAD/agents/brand-content) | — | Generate on-brand social or advertising image candidates from a confirmed brand system and asset library, with explicit compliance checks. |
| [`group-photo-compositing`](https://github.com/vamsy16/open-ai-image-agent/tree/HEAD/agents/group-photo-compositing) | — | Combine multiple authorized portraits into a coherent group scene while preserving each person's likeness, placement, and consent boundaries. |
| [`image-editing`](https://github.com/vamsy16/open-ai-image-agent/tree/HEAD/agents/image-editing) | — | Edit or transform a supplied image while preserving the specific people, products, composition, or brand details the user marks as fixed. |
| [`image-enhancement`](https://github.com/vamsy16/open-ai-image-agent/tree/HEAD/agents/image-enhancement) | — | Apply a bounded image-enhancement operation such as upscaling, background removal, extension, or cleanup while preserving the intended subject. |
| [`image-generation`](https://github.com/vamsy16/open-ai-image-agent/tree/HEAD/agents/image-generation) | — | Turn a creative brief into a bounded set of text-to-image or reference-guided image candidates, selecting the MuAPI model and parameters for the actual job. |
| [`image-project-setup`](https://github.com/vamsy16/open-ai-image-agent/tree/HEAD/agents/image-project-setup) | — | Establish reusable brand, asset, platform, rights, and delivery context for repeatable image-production work. |
| [`image-storyboard`](https://github.com/vamsy16/open-ai-image-agent/tree/HEAD/agents/image-storyboard) | — | Turn a story premise into an ordered set of visual keyframes with continuity notes, without generating video or audio. |
| [`image-strategist`](https://github.com/vamsy16/open-ai-image-agent/tree/HEAD/agents/image-strategist) | — | Route a broad creative brief into the smallest useful general or specialist image workflow, coordinate MuAPI calls, and return one evidence-backed production plan. |
| [`interior-redesign`](https://github.com/vamsy16/open-ai-image-agent/tree/HEAD/agents/interior-redesign) | — | Visualize decluttered, redesigned, or staged interiors while preserving room geometry and separating concepts from property claims. |
| [`logo-and-brand-identity`](https://github.com/vamsy16/open-ai-image-agent/tree/HEAD/agents/logo-and-brand-identity) | — | Explore logos, wordmarks, symbols, and compact brand identity directions from approved brand inputs, with legibility and trademark-review gates. |
| [`multi-angle-reshoot`](https://github.com/vamsy16/open-ai-image-agent/tree/HEAD/agents/multi-angle-reshoot) | — | Re-render an authorized subject, product, or scene from selected camera angles while preserving the approved parent asset. |
| [`photo-restoration`](https://github.com/vamsy16/open-ai-image-agent/tree/HEAD/agents/photo-restoration) | — | Restore damaged, faded, noisy, or low-resolution photographs while distinguishing recovered detail from model reconstruction. |
| [`portrait-photo-pack`](https://github.com/vamsy16/open-ai-image-agent/tree/HEAD/agents/portrait-photo-pack) | — | Generate a themed pack of portraits from an authorized identity reference while locking likeness and varying only the requested scene or styling. |
| [`product-imagery`](https://github.com/vamsy16/open-ai-image-agent/tree/HEAD/agents/product-imagery) | — | Plan and produce truthful ecommerce, marketplace, reseller, or commercial product-image sets from approved SKU references, with channel-specific QA and provenance. |
| [`professional-headshots`](https://github.com/vamsy16/open-ai-image-agent/tree/HEAD/agents/professional-headshots) | — | Produce consent-based professional portrait and headshot sets from authorized identity references, with controlled styling and identity QA. |
| [`social-pack`](https://github.com/vamsy16/open-ai-image-agent/tree/HEAD/agents/social-pack) | — | Reframe one approved hero image into platform-specific social formats while preserving the subject, palette, and visual identity. |
| [`thumbnail-generation`](https://github.com/vamsy16/open-ai-image-agent/tree/HEAD/agents/thumbnail-generation) | — | Produce a small set of truthful, high-contrast video or article thumbnail directions with platform-aware composition and text-safe space. |
| [`ui-mockups`](https://github.com/vamsy16/open-ai-image-agent/tree/HEAD/agents/ui-mockups) | — | Create high-fidelity mobile or web interface mockups and lightweight design-system boards from a product brief, with accessibility and implementation handoff notes. |
| [`virtual-try-on`](https://github.com/vamsy16/open-ai-image-agent/tree/HEAD/agents/virtual-try-on) | — | Create clearly labeled garment-on-person visualization drafts while preserving authorized person and garment details. |

#### `open-ai-seo-agent`

🔗 [https://github.com/vamsy16/open-ai-seo-agent](https://github.com/vamsy16/open-ai-seo-agent) · Fork of [`SamurAIGPT/open-ai-seo-agent`](https://github.com/SamurAIGPT/open-ai-seo-agent) · Language: n/a · Last push: 2026-08-27

**What it is:** Free, open-source SEO alternative to Ahrefs and Semrush for Claude, Codex, Cursor, and other AI assistants.

**When to use:** When you need Ahrefs/Semrush-style SEO research without paying for them — free open-source SEO powered by your own Search Console/Analytics data plus Muapi for external research.

**Install / quick start:**

Pick your assistant (Claude, Codex, Cursor…), add `AGENTS.md` + the skill you need from `agents/`, connect Muapi for external research, and optionally Search Console/Analytics for first-party data.

**Skills inside — 14** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`ai-visibility`](https://github.com/vamsy16/open-ai-seo-agent/tree/HEAD/agents/ai-visibility) | — | Measure brand visibility in AI-search results and test specific AI answers using Muapi evidence. |
| [`backlink-intelligence`](https://github.com/vamsy16/open-ai-seo-agent/tree/HEAD/agents/backlink-intelligence) | — | Analyze backlink strength, linked pages, anchor patterns, and historical changes without making unsupported toxicity claims. |
| [`competitor-seo`](https://github.com/vamsy16/open-ai-seo-agent/tree/HEAD/agents/competitor-seo) | — | Compare a domain with relevant competitors across visibility, rankings, SERPs, pages, and backlinks. |
| [`content-gap`](https://github.com/vamsy16/open-ai-seo-agent/tree/HEAD/agents/content-gap) | — | Find competitor-covered topics that a domain lacks or covers weakly, then turn them into non-cannibalizing content briefs. |
| [`first-party-performance`](https://github.com/vamsy16/open-ai-seo-agent/tree/HEAD/agents/first-party-performance) | — | Analyze the user's own Search Console and Analytics data through direct, user-authorized Google connections. |
| [`keyword-clustering`](https://github.com/vamsy16/open-ai-seo-agent/tree/HEAD/agents/keyword-clustering) | — | Group keywords into intent-led page opportunities using metrics, live SERP overlap, and existing relevant pages. |
| [`keyword-research`](https://github.com/vamsy16/open-ai-seo-agent/tree/HEAD/agents/keyword-research) | — | Discover, validate, expand, and prioritize SEO keywords using Muapi search data and live SERP evidence. |
| [`local-seo`](https://github.com/vamsy16/open-ai-seo-agent/tree/HEAD/agents/local-seo) | — | Analyze local search visibility and business-profile health across rankings, listings, reviews, questions, and updates. |
| [`rank-tracking`](https://github.com/vamsy16/open-ai-seo-agent/tree/HEAD/agents/rank-tracking) | — | Capture comparable ranking snapshots and explain changes between runs using Muapi rank and SERP data. |
| [`seo-growth`](https://github.com/vamsy16/open-ai-seo-agent/tree/HEAD/agents/seo-growth) | — | Find, validate, and prioritize ranking and organic-growth opportunities from domain, keyword, SERP, and page data. |
| [`seo-project-setup`](https://github.com/vamsy16/open-ai-seo-agent/tree/HEAD/agents/seo-project-setup) | — | Establish a reusable SEO project context so later research uses consistent targets, markets, competitors, and workspace artifacts. |
| [`seo-strategist`](https://github.com/vamsy16/open-ai-seo-agent/tree/HEAD/agents/seo-strategist) | — | Route broad SEO questions into the right Muapi-backed skills, coordinate their dependencies, and return one prioritized strategy report. |
| [`technical-seo-audit`](https://github.com/vamsy16/open-ai-seo-agent/tree/HEAD/agents/technical-seo-audit) | — | Audit selected pages with Muapi Lighthouse data and turn observed issues into prioritized technical SEO actions. |
| [`youtube-seo`](https://github.com/vamsy16/open-ai-seo-agent/tree/HEAD/agents/youtube-seo) | — | Research YouTube search opportunities and analyze videos, transcripts, and audience comments with Muapi. |

#### `open-ai-social-agent`

🔗 [https://github.com/vamsy16/open-ai-social-agent](https://github.com/vamsy16/open-ai-social-agent) · Fork of [`SamurAIGPT/open-ai-social-agent`](https://github.com/SamurAIGPT/open-ai-social-agent) · Language: n/a · Last push: 2026-08-27

**What it is:** An AI agent for social media management — listening, creator discovery, multi-platform publishing, and trend research across X, Instagram, TikTok, Reddit, and YouTube

**When to use:** For social media management: listening, creator discovery, multi-platform publishing (X, Instagram, TikTok, Reddit, YouTube), and trend research.

**Skills inside — 6** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`creator-discovery`](https://github.com/vamsy16/open-ai-social-agent/tree/HEAD/agents/creator-discovery) | — | Find relevant creators and influencers for a campaign by niche, audience fit, and engagement signals. |
| [`multi-platform-publishing`](https://github.com/vamsy16/open-ai-social-agent/tree/HEAD/agents/multi-platform-publishing) | — | Adapt and schedule one media post across multiple connected social platforms with platform-appropriate formatting. |
| [`platform-research`](https://github.com/vamsy16/open-ai-social-agent/tree/HEAD/agents/platform-research) | — | Deep research on a specific platform's community, subreddit, or audience before launching content there. |
| [`social-listening`](https://github.com/vamsy16/open-ai-social-agent/tree/HEAD/agents/social-listening) | — | Monitor brand or topic mentions and sentiment across X, Instagram, TikTok, Reddit, and YouTube. |
| [`social-project-setup`](https://github.com/vamsy16/open-ai-social-agent/tree/HEAD/agents/social-project-setup) | — | Establish reusable brand, account, platform, content, approval, and measurement context for social workflows. |
| [`trend-discovery`](https://github.com/vamsy16/open-ai-social-agent/tree/HEAD/agents/trend-discovery) | — | Surface what's currently working or trending in a niche to inform content strategy. |

#### `open-ai-gtm-agent`

🔗 [https://github.com/vamsy16/open-ai-gtm-agent](https://github.com/vamsy16/open-ai-gtm-agent) · Fork of [`SamurAIGPT/open-ai-gtm-agent`](https://github.com/SamurAIGPT/open-ai-gtm-agent) · Language: n/a · Last push: 2026-08-27

**What it is:** Cross-functional GTM strategy and orchestration agents for research, launches, sales, channels, and performance review

**When to use:** For go-to-market strategy and orchestration: research, launches, sales, channels, and post-launch performance review. Use per-phase skills (setup → strategist → launch orchestrator → performance review).

**Install / quick start:**

Add `AGENTS.md`; load `gtm-project-setup` for new projects, `gtm-strategist` for broad questions, `gtm-launch-orchestrator` once strategy is approved, `gtm-performance-review` after a reporting window.

**Skills inside — 4** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`gtm-launch-orchestrator`](https://github.com/vamsy16/open-ai-gtm-agent/tree/HEAD/agents/gtm-launch-orchestrator) | — | Turn an approved GTM strategy into a coordinated cross-channel launch plan with dependencies, owners, calendar, and approval gates. |
| [`gtm-performance-review`](https://github.com/vamsy16/open-ai-gtm-agent/tree/HEAD/agents/gtm-performance-review) | — | Diagnose go-to-market funnel and channel performance from comparable first-party and sibling datasets, then propose the next experiments. |
| [`gtm-project-setup`](https://github.com/vamsy16/open-ai-gtm-agent/tree/HEAD/agents/gtm-project-setup) | — | Establish reusable product, market, ICP, funnel, channel, and goal context for later GTM workflows. |
| [`gtm-strategist`](https://github.com/vamsy16/open-ai-gtm-agent/tree/HEAD/agents/gtm-strategist) | — | Route broad go-to-market questions into the smallest useful set of sibling workflows and synthesize one evidence-backed strategy. |

#### `open-ai-content-repurposing-agent`

🔗 [https://github.com/vamsy16/open-ai-content-repurposing-agent](https://github.com/vamsy16/open-ai-content-repurposing-agent) · Fork of [`SamurAIGPT/open-ai-content-repurposing-agent`](https://github.com/SamurAIGPT/open-ai-content-repurposing-agent) · Language: n/a · Last push: 2026-08-26

**What it is:** An AI agent for content repurposing — turning long-form video into ranked, ready-to-post short clips — backed by real transcription and video APIs.

**When to use:** When you have long-form video and need it turned into ranked, ready-to-post short clips — backed by real transcription and video APIs.

**Skills inside — 3** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`content-performance-tracking`](https://github.com/vamsy16/open-ai-content-repurposing-agent/tree/HEAD/agents/content-performance-tracking) | — | Track which repurposed clips perform best across platforms to inform future clipping decisions. |
| [`cross-format-repurposing`](https://github.com/vamsy16/open-ai-content-repurposing-agent/tree/HEAD/agents/cross-format-repurposing) | — | Turn one long-form video into multiple short vertical clips ranked by virality potential. |
| [`short-video-editing`](https://github.com/vamsy16/open-ai-content-repurposing-agent/tree/HEAD/agents/short-video-editing) | — | Apply captions, hooks, and pacing edits to raw clips for platform-native short video. |

#### `distribb-skill`

🔗 [https://github.com/vamsy16/distribb-skill](https://github.com/vamsy16/distribb-skill) · Fork of [`Bomx/distribb-skill`](https://github.com/Bomx/distribb-skill) · Language: n/a · Last push: 2026-08-21

**What it is:** Distribb CLI, Claude, Codex, Hermes, OpenClaw skill for AI-powered SEO. Write content with your own AI, publish through Distribb's backlink network.

**When to use:** When writing SEO content with your own AI and publishing it through Distribb's backlink network.

**Install / quick start:**

```bash
npx skills add Bomx/distribb-skill
```

**Skills inside — 2** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`90-day-seo-sprint`](https://github.com/vamsy16/distribb-skill/tree/HEAD/90-day-seo-sprint) | Use when you ask for an "SEO sprint", "90-day SEO plan", "SEO tracker", "SEO roadmap", "where do I even start with SEO", "how do I get my first 1,000 organic visitors",… | Run the Distribb 90-Day SEO Sprint - a founder-built 13-week playbook for shipping pre-launch SEO, core pages, a content engine, and a backlink starter stack on the way to compounding organic traffic. |
| [`SKILL.md`](https://github.com/vamsy16/distribb-skill/tree/HEAD/SKILL.md) | Use this skill when you want to create SEO-optimized articles, find keywords, get real backlinks from other businesses, run link building or backlink outreach campaigns,… | Distribb is an SEO platform that handles keyword research, original data research, content publishing to WordPress/Webflow/Shopify, high-DR backlink exchange network, link building outreach playbooks, internal linking, social… |

#### `alex-hormozi-coach`

🔗 [https://github.com/vamsy16/alex-hormozi-coach](https://github.com/vamsy16/alex-hormozi-coach) · Fork of [`Mahanaicoach/alex-hormozi-coach`](https://github.com/Mahanaicoach/alex-hormozi-coach) · Language: n/a · Last push: 2026-06-04

**What it is:** Free Claude skill that coaches your business in Alex Hormozi's hotline method — numbers first, find the real constraint, prove it with math. A lead magnet by Mahan AI.

**When to use:** When you want Hormozi-style business coaching — numbers first, find the real constraint, prove it with math. Just type 'coach me — I run …'.

**Skills inside — 1** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`alex-hormozi-coach`](https://github.com/vamsy16/alex-hormozi-coach/tree/HEAD/alex-hormozi-coach) | Use this skill whenever you want business coaching, help growing or scaling a business, advice on offers, pricing, lead generation, sales, hiring, monetization, cash… | Coach a business owner in Alex Hormozi's voice, structure, and frameworks — interactive, one question at a time. |

#### `competitor-x-ray`

🔗 [https://github.com/vamsy16/competitor-x-ray](https://github.com/vamsy16/competitor-x-ray) · Fork of [`Mahanaicoach/competitor-x-ray`](https://github.com/Mahanaicoach/competitor-x-ray) · Language: n/a · Last push: 2026-06-04

**What it is:** Free Claude skill that x-rays any competitor into their ICP, funnel & monetization — sourced, evidence-tiered, with a designed PDF report. A lead magnet by Mahan AI.

**When to use:** When you need any competitor x-rayed into their ICP, funnel, and monetization — sourced, evidence-tiered, with a designed PDF report.

**Skills inside — 1** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`competitor-x-ray`](https://github.com/vamsy16/competitor-x-ray/tree/HEAD/competitor-x-ray) | Use whenever you want to research, analyze, break down, or "x-ray" competitors, creators, brands, founders, or businesses — including when they paste… | Decode any set of competitors into their ICP (ideal customer profile), their funnel (how a stranger becomes a customer), and their monetization (every revenue stream and price point). |

#### `funnel-spy`

🔗 [https://github.com/vamsy16/funnel-spy](https://github.com/vamsy16/funnel-spy) · Fork of [`Mahanaicoach/funnel-spy`](https://github.com/Mahanaicoach/funnel-spy) · Language: n/a · Last push: 2026-08-05

**What it is:** Free Claude skill that walks any competitor's funnel end to end — every page, every price, the machine behind it — and delivers a scored teardown dossier. A lead magnet by Mahan Ai.

**When to use:** When you want a competitor's entire funnel walked end-to-end — every page, every price — with a scored teardown dossier.

**Skills inside — 1** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`funnel-spy`](https://github.com/vamsy16/funnel-spy/tree/HEAD/funnel-spy) | Use whenever you want to spy on, tear down, reverse-engineer, map, or "funnel hack" a funnel, landing page, lead magnet, offer, or checkout — including when they paste… | Walk any competitor's sales funnel end to end — every page a stranger sees on the way to the checkout — and return a scored, sourced teardown: entry points (organic and ads, verified in ad libraries), the live page-by-page walk… |

#### `content-ideas`

🔗 [https://github.com/vamsy16/content-ideas](https://github.com/vamsy16/content-ideas) · Fork of [`bradautomates/content-ideas`](https://github.com/bradautomates/content-ideas) · Language: n/a · Last push: 2026-05-30

**What it is:** Track competitors across X, Instagram, TikTok, and YouTube, see what they post, what performs, and get content ideas backed by real engagement data. Cross-host plugin for Claude Code & Codex.

**When to use:** When planning social content: track competitors across X/Instagram/TikTok/YouTube, see what performs, and get engagement-backed content ideas.

**Install / quick start:**

Claude Code: `/plugin marketplace add bradautomates/content-ideas` then `/plugin install content-ideas@content-ideas`
Codex/Cursor/Copilot/Gemini CLI +50 more: `npx skills add bradautomates/content-ideas -g`

**Skills inside — 1** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`content-ideas`](https://github.com/vamsy16/content-ideas/tree/HEAD/skills/content-ideas) | Use this whenever you want competitor/creator research, a content feed or "for you" page, trending-topic ideas in their niche, to see what's working on social, to track… | Your For You page for content creators. Scrapes tracked competitors across social media platforms, scores what's performing, and turns it into actionable, differentiated content ideas backed by real engagement data. |

#### `content-repurposer`

🔗 [https://github.com/vamsy16/content-repurposer](https://github.com/vamsy16/content-repurposer) · Fork of [`Mahanaicoach/content-repurposer`](https://github.com/Mahanaicoach/content-repurposer) · Language: n/a · Last push: 2026-06-20

**What it is:** Turn one Reel/TikTok into platform-correct Instagram, TikTok & YouTube posts with auto-translated CTAs — then auto-schedule TikTok + YouTube via Zernio. A distributable Claude skill.

**When to use:** When you want one Reel/TikTok repurposed into platform-correct Instagram, TikTok, and YouTube posts with auto-translated CTAs.

**Skills inside — 1** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`SKILL.md`](https://github.com/vamsy16/content-repurposer/tree/HEAD/SKILL.md) | Use this whenever you want to repurpose, cross-post, or adapt a reel/TikTok for other platforms; fix or translate a CTA, outro, or ending across platforms; | Turn one short-form video (an Instagram Reel or a TikTok) into platform-correct versions for Instagram, TikTok, and YouTube — then auto-schedule TikTok and YouTube through the user's own Zernio account. |

#### `linkedin-planner`

🔗 [https://github.com/vamsy16/linkedin-planner](https://github.com/vamsy16/linkedin-planner) · Fork of [`audrey-560/linkedin-planner`](https://github.com/audrey-560/linkedin-planner) · Language: n/a · Last push: 2026-07-21

**What it is:** Batch-plan a month of LinkedIn posts with an AI assistant and push them to Buffer as drafts. Skill-first template: interview, draft in your voice, schedule.

**When to use:** When batch-planning a month of LinkedIn posts in your own voice and pushing them to Buffer as drafts.

**Skills inside — 1** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`SKILL.md`](https://github.com/vamsy16/linkedin-planner/tree/HEAD/SKILL.md) | Use when someone wants to batch-plan LinkedIn content, "plan my month", or fill their LinkedIn queue. | Plan and draft a month (or any window) of LinkedIn posts, then push them to Buffer as drafts. Interviews the user for their niche, content pillars, cadence, and writing voice on first run, drafts every post in their own voice,… |

#### `lead-gen-kit`

🔗 [https://github.com/vamsy16/lead-gen-kit](https://github.com/vamsy16/lead-gen-kit) · Fork of [`audrey-560/lead-gen-kit`](https://github.com/audrey-560/lead-gen-kit) · Language: n/a · Last push: 2026-07-07

**What it is:** Skill-driven Google Maps lead-gen funnel for Claude Code — cheap discovery, ICP qualification, email rescue, Google Sheets sync. Configurable for any business type.

**When to use:** When building a Google-Maps lead-gen funnel: cheap discovery, ICP qualification, email rescue, and Google Sheets sync for any business type.

**Install / quick start:**

```bash
git clone <your-fork-url> lead-gen-kit && cd lead-gen-kit
pip install -r requirements.txt
```

**Skills inside — 1** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`lead-gen`](https://github.com/vamsy16/lead-gen-kit/tree/HEAD/.claude/skills/lead-gen) | — | Run the Google Maps lead-gen funnel — plan a whole campaign (all regions + one broad category phrase), get it approved once, then discover cheap via Apify with coarse filters applied pre-bill, dedupe + qualify against the ICP for… |

---

### 🎨 Design & Front-End Engineering (7 repos)

*Skills and tools that make AI agents produce professional UI, animation, and visual design.*

| Repo | Skills | One-line purpose |
|---|---|---|
| [`ai-site-cloner`](https://github.com/vamsy16/ai-site-cloner) | 2 | Clone any website into a pixel-accurate Next.js app with AI — Playwright-measured extraction (no… |
| [`awesome-design-md`](https://github.com/vamsy16/awesome-design-md) | — | A collection of DESIGN.md files analysis by popular brand design systems. |
| [`banana-claude`](https://github.com/vamsy16/banana-claude) | 1 | AI image generation skill for Claude Code - Creative Director powered by Gemini |
| [`claudedesignskills`](https://github.com/vamsy16/claudedesignskills) | 23 | A comprehensive collection of Claude Code skills for modern web development, specializing in 3D… |
| [`gsap-skills`](https://github.com/vamsy16/gsap-skills) | 8 | Official AI skills for GSAP. These skills teach AI coding agents how to correctly use GSAP… |
| [`motion-dev-animations-skill`](https://github.com/vamsy16/motion-dev-animations-skill) | 1 | Claude Code skill for Motion.dev -- 120fps web animations, spring physics, scroll effects, gesture… |
| [`open-design`](https://github.com/vamsy16/open-design) | 385 | 🎨 Best DeepSeek Harness Design Plugin. The open-source Claude Design alternative. |

#### `open-design`

🔗 [https://github.com/vamsy16/open-design](https://github.com/vamsy16/open-design) · Fork of [`nexu-io/open-design`](https://github.com/nexu-io/open-design) · Language: n/a · Last push: 2026-08-30

**What it is:** 🎨 Best DeepSeek Harness Design Plugin. The open-source Claude Design alternative. 🖥️ Local-first desktop app. 🖼️ Your coding agent becomes the design engine: prototypes, landing pages, dashboards, slides, images & video — real files, HTML/PDF/PPTX/MP4 export.

**When to use:** When you want your coding agent to BE the design engine — prototypes, landing pages, dashboards, slides, images, and video from 385 design templates, with real file exports (HTML/PDF/PPTX/MP4).

**Skills inside — 385** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`8-bit-orbit-video-template`](https://github.com/vamsy16/open-design/tree/HEAD/skills/8-bit-orbit-video-template) | Use when users want a high-fidelity, multi-scene HTML-to-video composition with advanced transitions, interactive preview controls, and ready-to-render default style. | Hyperframes-based video template for retro pixel deck motion design. |
| [`ad-creative`](https://github.com/vamsy16/open-design/tree/HEAD/skills/ad-creative) | — | Generate and iterate ad creative including headlines, descriptions, and primary text. Useful for paid social and search ad iteration. |
| [`after-hours-editorial-template`](https://github.com/vamsy16/open-design/tree/HEAD/skills/after-hours-editorial-template) | Use when you ask for premium fashion-style motion pages, moody serif-led storytelling, or a high-end dark presentation aesthetic with rich transitions. | Luxury dark-editorial HyperFrames template for three-page cinematic storyboards, inspired by haute couture title cards and magazine chapter spreads. |
| [`agent-browser`](https://github.com/vamsy16/open-design/tree/HEAD/skills/agent-browser) | Use when you need to inspect, test, or automate browser behavior: navigating pages, filling forms, clicking buttons, taking screenshots, extracting page data, reading… | Browser automation CLI for AI agents. Prefer local OpenDesign preview URLs unless the user explicitly asks for external browsing. |
| [`agent-skill-principal-ui-ux-architect-motion-choreographer-awwwards-tier-mqu4mbbj`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/community/agent-skill-principal-ui-ux-architect-motion-choreographer-awwwards-tier-mqu4mbbj) | — | Teaches the AI to design like a high-end agency. Defines the exact fonts, spacing, shadows, card structures, and animations that make a website feel expensive. |
| [`ai-music-album`](https://github.com/vamsy16/open-design/tree/HEAD/skills/ai-music-album) | — | Full-lifecycle AI music album production — concept, lyric drafting, track sequencing, and export. Useful for indie album experiments and brand soundtracks. |
| [`algorithmic-art`](https://github.com/vamsy16/open-design/tree/HEAD/skills/algorithmic-art) | — | Create generative art using p5.js with seeded randomness so every render is reproducible. Useful for procedural posters, motion-style stills, and artistic frame studies. |
| [`apple-hig`](https://github.com/vamsy16/open-design/tree/HEAD/skills/apple-hig) | — | Apple Human Interface Guidelines as 14 agent skills covering platforms, foundations, components, patterns, inputs, and technologies for iOS, macOS, visionOS, watchOS, and tvOS. |
| [`article-magazine`](https://github.com/vamsy16/open-design/tree/HEAD/skills/article-magazine) | — | Huashu / huashu-md-html-inspired magazine article layout for turning Markdown or notes into a polished long-form HTML essay. |
| [`artifacts-builder`](https://github.com/vamsy16/open-design/tree/HEAD/skills/artifacts-builder) | — | Suite of tools for creating elaborate, multi-component claude.ai HTML artifacts using modern frontend web technologies (React, Tailwind CSS, shadcn/ui). |
| [`atelier-zero-image-generation-prompt-pack-mrrxpegw`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/community/atelier-zero-image-generation-prompt-pack-mrrxpegw) | — | Atelier Zero — Image Generation Prompt Pack — This pack is consumed by the `open-design-landing` skill. Every page-level |
| [`audio-jingle`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/audio-jingle) | — | Audio generation skill — jingles, beds, voiceover, and sound effects. Routes music requests to Suno V5 / Udio / Lyria, speech to MiniMax TTS / FishAudio / ElevenLabs V3, and SFX to ElevenLabs SFX or AudioCraft. |
| [`blog-post`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/blog-post) | Use when the brief asks for "blog", "article", "post", "essay", or "case study". | A long-form article / blog post — masthead, hero image placeholder, article body with figures and pull quotes, author byline, related posts. |
| [`brainstorming`](https://github.com/vamsy16/open-design/tree/HEAD/skills/brainstorming) | — | Transform rough ideas into fully-formed designs through structured questioning and alternative exploration. Useful early in concept work. |
| [`brand-extract`](https://github.com/vamsy16/open-design/tree/HEAD/skills/brand-extract) | Use when a brand-extraction project opens with a site in the Browser tab, or when you ask to "extract a brand", "pull the brand from <url>", "get the colors/fonts/logo… | Extract a complete Brand Kit from a live website by driving the in-app browser. Pairs with the agent-browser tool for measurement and pauses for the user when an anti-bot wall blocks the page. |
| [`brand-guidelines`](https://github.com/vamsy16/open-design/tree/HEAD/skills/brand-guidelines) | — | Apply Anthropic's official brand colors and typography to artifacts for consistent visual identity and professional design standards. A reference for shaping your own. |
| [`brandkit`](https://github.com/vamsy16/open-design/tree/HEAD/skills/brandkit) | — | Premium brand-kit image generation skill for creating high-end brand-guidelines boards, logo systems, identity decks, and visual-world presentations. |
| [`brutalist-skill`](https://github.com/vamsy16/open-design/tree/HEAD/skills/brutalist-skill) | — | Raw mechanical interfaces fusing Swiss typographic print with military terminal aesthetics. Rigid grids, extreme type scale contrast, utilitarian color, analog degradation effects. |
| [`build-test`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/atoms/build-test) | — | Run the project's build / typecheck / lint / test commands and emit the build.passing + tests.passing signals devloop convergence reads. |
| [`canvas-design`](https://github.com/vamsy16/open-design/tree/HEAD/skills/canvas-design) | — | Create beautiful visual art in PNG and PDF documents using design philosophy and aesthetic principles for posters, illustrations, and static pieces. |
| [`card-twitter`](https://github.com/vamsy16/open-design/tree/HEAD/skills/card-twitter) | — | Twitter quote or data card designed to pair with a post. |
| [`card-xiaohongshu`](https://github.com/vamsy16/open-design/tree/HEAD/skills/card-xiaohongshu) | — | Xiaohongshu-style knowledge cards, arranged as a swipeable multi-card carousel. |
| [`chat-motion-overlay`](https://github.com/vamsy16/open-design/tree/HEAD/skills/chat-motion-overlay) | Use when Codex needs to create reusable short-form chat clips for Douyin, demo videos, story reenactments, social-message proof scenes, or embeddable alpha overlays for… | Generate configurable chat motion overlays from a transcript or screenshot, including plain bubble scenes, app-style chat containers, optional device frames, preset or uploaded avatars, nickname display rules, and… |
| [`clinical-case-report`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/clinical-case-report) | Use when the brief mentions "case report", "case presentation", "SOAP note", "clinical case", "ward rounds", "case summary", or "patient presentation". | Structured medical case presentation for clinical rounds, conferences, and documentation. Generates SOAP-format or narrative case reports with physiologically accurate vitals, labs, and evidence-based plans. |
| [`clone-audit-mrlv3nl4`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/community/clone-audit-mrlv3nl4) | — | Audit cloned or reimplemented websites for fidelity gaps, tracking scripts, source-brand and language residue, placeholders, and risky external dependencies. |
| [`code-import`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/atoms/code-import) | — | Read an existing repository's structure into the project cwd as a normalised snapshot the agent can analyse without re-walking the tree on every turn. |
| [`codex-interactive-capability-map`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/examples/codex-interactive-capability-map) | — | Turn a long-form article, thread, memo, or product narrative into a compact clickable capability map with a workflow loop, use-case matrix, and responsive detail panel. |
| [`color-expert`](https://github.com/vamsy16/open-design/tree/HEAD/skills/color-expert) | — | Color science expert skill with 286K words of reference material covering OKLCH/OKLAB, palette generation, accessibility/contrast, color naming, pigment mixing, and historical color theory. |
| [`competitive-ads-extractor`](https://github.com/vamsy16/open-design/tree/HEAD/skills/competitive-ads-extractor) | — | Extract and analyze competitors' ads from ad libraries to understand messaging and creative approaches that resonate. |
| [`contact-widget`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/contact-widget) | — | Self-contained floating chat widget with welcome screen, social links, meeting button, and message input. Single HTML file, zero dependencies. |
| [`copywriting`](https://github.com/vamsy16/open-design/tree/HEAD/skills/copywriting) | — | Write and rewrite marketing copy for landing pages, homepages, and ads. Useful as a copy chief partner during launches. |
| [`create-hyperframes-launch`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/spec/examples/create-hyperframes-launch) | — | Use this plugin when the user wants a HyperFrames-ready HTML motion composition, launch animation, kinetic typography clip, product reveal, or social video made from code. |
| [`create-image-campaign`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/spec/examples/create-image-campaign) | — | Use this plugin when the user wants image assets, posters, social visuals, ad concepts, or a small campaign image system from a creative brief. |
| [`create-live-artifact-ops`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/spec/examples/create-live-artifact-ops) | — | Create a refreshable live operations artifact for customer success, support, or launch review workflows. |
| [`create-prototype-dashboard`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/spec/examples/create-prototype-dashboard) | — | Create a polished operations dashboard prototype with dense KPIs, status tables, and a focused command-center layout. |
| [`create-slides-pitch`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/spec/examples/create-slides-pitch) | — | Create a concise HTML pitch deck for an early-stage product, with a strong narrative arc and finance-ready slide structure. |
| [`create-video-storyboard`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/spec/examples/create-video-storyboard) | — | Use this plugin when the user wants a video concept, storyboard, shot list, prompt pack, or render-ready motion brief for a product, campaign, or explainer. |
| [`creative-director`](https://github.com/vamsy16/open-design/tree/HEAD/skills/creative-director) | — | AI creative director with recursive self-assessment: 20+ methodologies (SIT, TRIZ, Bisociation, SCAMPER, Synectics), 3-axis evaluation calibrated against Cannes/D&AD/HumanKind, 5-phase process from brief to presentation. |
| [`critique`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/critique) | Use when the brief asks for a "design review", "design critique", "5 维度评审", "design audit", or "what's wrong with my design". | Run a 5-dimension expert design review on any HTML artifact in the project — Philosophy / Visual hierarchy / Detail / Functionality / Innovation, each scored 0–10. |
| [`critique-theater`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/atoms/critique-theater) | — | Five-role Design Jury review that streams scored rounds, persists a replayable transcript, and ships through the daemon's Critique Theater protocol. |
| [`d3-visualization`](https://github.com/vamsy16/open-design/tree/HEAD/skills/d3-visualization) | — | Teaches the agent to produce D3 charts and interactive data visualizations. A comprehensive D3.js skill with examples across chart types and techniques giving the agent expert-level knowledge to generate complex, interactive… |
| [`dashboard`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/dashboard) | Use when the brief asks for a "dashboard", "admin", "analytics", or "control panel" screen. | Admin / analytics dashboard in a single HTML file. Fixed left sidebar, top bar with user/search, main grid of KPI cards and one or two charts. |
| [`data-report`](https://github.com/vamsy16/open-design/tree/HEAD/skills/data-report) | — | Turns CSV, Excel, or JSON data into a polished visual report page. |
| [`dating-web`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/dating-web) | Use when the brief asks for a "dating site", "matchmaking", "community dashboard", "social network dashboard", or any consumer product where the data is the story. | A consumer-feeling dating / matchmaking dashboard — left rail navigation, ticker bar of community signals, headline KPIs, a 30-day mutual-matches bar chart, and a match-rate trend block. Editorial typography, restrained accent. |
| [`dcf-valuation`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/dcf-valuation) | Use when the brief asks for DCF, fair value, intrinsic value, price target, undervalued or overvalued analysis, or "what is this company worth? | Discounted cash flow valuation and intrinsic value analysis for public companies. |
| [`deck-guizang-editorial`](https://github.com/vamsy16/open-design/tree/HEAD/skills/deck-guizang-editorial) | — | Editorial magazine meets e-ink: 10 layouts and 5 palettes (Ink, Indigo Porcelain, Forest Ink, Kraft Paper, Dune). |
| [`deck-open-slide-canvas`](https://github.com/vamsy16/open-design/tree/HEAD/skills/deck-open-slide-canvas) | — | Locked 1920x1080 canvas deck with React component-level free composition, not bound to a fixed template. |
| [`deck-swiss-international`](https://github.com/vamsy16/open-design/tree/HEAD/skills/deck-swiss-international) | — | 16-column grid, one saturated accent, and 22 locked layouts (Klein Blue, Lemon, Mint, Safety Orange). |
| [`deep-think-maximum-cognitive-effort-protocol-mq8kvw92`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/community/deep-think-maximum-cognitive-effort-protocol-mq8kvw92) | — | Use this plugin when the user wants a maximum-effort reasoning workflow for a complex, high-stakes, or ambiguous task. |
| [`deploy-vercel-static`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/spec/examples/deploy-vercel-static) | — | Use this plugin when the user wants to deploy an accepted static web artifact to Vercel or prepare an equivalent deployment handoff with preview and production URLs. |
| [`design-brief`](https://github.com/vamsy16/open-design/tree/HEAD/skills/design-brief) | — | Parse a structured design brief written in I-Lang protocol format into a concrete design spec. |
| [`design-consultation`](https://github.com/vamsy16/open-design/tree/HEAD/skills/design-consultation) | — | Build a complete design system from scratch with creative risks and realistic product mockups. Useful for kickoff workshops and brand-from-zero work. |
| [`design-extract`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/atoms/design-extract) | — | Extract design tokens (color / typography / spacing) from imported source code, screenshots, or Figma exports into the canonical token bag token-map consumes. |
| [`design-md`](https://github.com/vamsy16/open-design/tree/HEAD/skills/design-md) | — | Create and manage DESIGN.md files. Useful for capturing design direction, tokens, and visual rules in a single source of truth. |
| [`design-review`](https://github.com/vamsy16/open-design/tree/HEAD/skills/design-review) | — | Designer Who Codes: visual audit then fixes with atomic commits and before/after screenshots. Useful for tightening shipped UI before launch. |
| [`design-system-source-context-mr0bb87z`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/community/design-system-source-context-mr0bb87z) | — | Design System Source Context — This file is generated during setup and should be treated as source evidence for the design-system project. Use it before writing or revising DESIGN.md, previews, tokens, UI kit examples, or assets. |
| [`diff-review`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/atoms/diff-review) | — | Render the patch-edit run's accumulated changes as a reviewable diff, surface it through a GenUI choice surface, and persist the user's accept / reject decision into the artifact manifest. |
| [`digital-eguide`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/digital-eguide) | Use when the brief asks for an "e-guide", "digital guide", "lookbook", "lead magnet", "creator guide", "playbook", "PDF guide", or "电子指南". | A two-spread digital e-guide preview — page 1 is a cover (display title, author, "What's inside" stats, table of contents teaser); page 2 is a spread (lesson body with pull-quote and a step list). Lifestyle / creator brand tone. |
| [`digits-fintech-swiss-template`](https://github.com/vamsy16/open-design/tree/HEAD/skills/digits-fintech-swiss-template) | Use when users ask for premium data-story slides with strict modular layout, bold numeric cards, restrained motion, and keyboard/click navigation in one HTML file. | Swiss-grid fintech deck template in black / warm paper / neon-lime contrast. |
| [`direction-picker`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/atoms/direction-picker) | — | Optional 3-5 direction picker for users who explicitly ask to compare visual directions. |
| [`discovery-question-form`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/atoms/discovery-question-form) | — | Structured clarification form for unresolved material requirements. |
| [`doc`](https://github.com/vamsy16/open-design/tree/HEAD/skills/doc) | — | Read, create, and edit .docx documents with formatting and layout fidelity via OpenAI's document skill. |
| [`doc-kami-parchment`](https://github.com/vamsy16/open-design/tree/HEAD/skills/doc-kami-parchment) | — | Warm parchment canvas (#f5f4ed), monochrome ink-blue accent (#1B365D), one serif family, and editorial-grade typography. |
| [`docs-page`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/docs-page) | Use when the brief mentions "docs", "documentation", "guide", "API reference", or "tutorial". | A documentation page — inline-start nav, scrollable article body, inline-end table of contents. |
| [`docx`](https://github.com/vamsy16/open-design/tree/HEAD/skills/docx) | — | Create, edit, and analyze Word documents with tracked changes, comments, and formatting. Useful for design briefs, copy docs, and review-ready deliverables. |
| [`domain-name-brainstormer`](https://github.com/vamsy16/open-design/tree/HEAD/skills/domain-name-brainstormer) | — | Generate creative domain name ideas and check availability across multiple TLDs including .com, .io, .dev, and .ai. |
| [`ecommerce-image-workflow`](https://github.com/vamsy16/open-design/tree/HEAD/skills/ecommerce-image-workflow) | — | Reference-product ecommerce image workflow for generating a compact set of product-faithful main, feature, and lifestyle images from real product reference photos. |
| [`editorial-burgundy-principles-template`](https://github.com/vamsy16/open-design/tree/HEAD/skills/editorial-burgundy-principles-template) | Use when users ask for premium manifesto or culture slides with pill tags, large typographic statements, principle cards, and guided keyboard/click navigation. | Editorial studio deck template in burgundy / blush / muted-gold palette. |
| [`email-marketing`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/email-marketing) | Use when the brief asks for an "email", "newsletter blast", "MJML", "product launch email", or "email template". | A brand product-launch email — masthead with wordmark, hero image block, headline lockup with skewed-italic accent, body copy, primary CTA, and a specifications grid. |
| [`emil-design-eng`](https://github.com/vamsy16/open-design/tree/HEAD/skills/emil-design-eng) | — | This skill encodes Emil Kowalski's philosophy on UI polish, component design, animation decisions, and the invisible details that make software feel great. |
| [`emilkowalski-motion`](https://github.com/vamsy16/open-design/tree/HEAD/skills/emilkowalski-motion) | Use after an interface exists to add tasteful micro-interactions, state transitions, and page motion with product-grade restraint. | Motion-design follow-up skill inspired by Emil Kowalski's animation guidance. |
| [`eng-runbook`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/eng-runbook) | Use when the brief mentions "runbook", "ops doc", "on-call guide", "SRE doc", or "运维手册". | An engineering runbook — service overview, alerts table, dashboards links, common procedures with copy-pasteable commands, on-call rotation, and an incident-response checklist. |
| [`enhance-prompt`](https://github.com/vamsy16/open-design/tree/HEAD/skills/enhance-prompt) | — | Improve prompts with design specs and UI/UX vocabulary. Useful for design-to-code workflows and clarifying requests for visual output. |
| [`export-download-debugging`](https://github.com/vamsy16/open-design/tree/HEAD/skills/export-download-debugging) | — | Diagnose and fix browser, preview, or Electron export/download failures, especially image export issues involving Save As, Blob/Data URLs, the File System Access API, createWritable failures, and 0 KB files. |
| [`export-nextjs-handoff`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/spec/examples/export-nextjs-handoff) | — | Use this plugin when the user wants an accepted OpenDesign artifact converted into a Next.js App Router handoff with clean components, styles, assets, and implementation notes. |
| [`extend-plugin-author`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/spec/examples/extend-plugin-author) | — | Use this plugin when the user wants to create, improve, validate, publish, or submit an OpenDesign plugin using the plugin spec, examples, and PR workflow. |
| [`fal-3d`](https://github.com/vamsy16/open-design/tree/HEAD/skills/fal-3d) | — | Generate 3D models from text or images via fal.ai. Useful for game assets, AR previews, product mockups, and concept sculpting. |
| [`fal-generate`](https://github.com/vamsy16/open-design/tree/HEAD/skills/fal-generate) | — | Generate images and videos using fal.ai AI models. Production-grade catalogue covering Flux, SDXL, ideogram, and other community-hosted endpoints. |
| [`fal-image-edit`](https://github.com/vamsy16/open-design/tree/HEAD/skills/fal-image-edit) | — | AI-powered image editing with style transfer, background removal, object removal, and inpainting via fal.ai hosted models. |
| [`fal-kling-o3`](https://github.com/vamsy16/open-design/tree/HEAD/skills/fal-kling-o3) | — | Generate images and videos with Kling O3 — Kling's most powerful model family — via fal.ai. |
| [`fal-lip-sync`](https://github.com/vamsy16/open-design/tree/HEAD/skills/fal-lip-sync) | — | Create talking head videos and lip sync audio to video via fal.ai. Useful for explainer avatars, multilingual dubbing previews, and social cuts. |
| [`fal-realtime`](https://github.com/vamsy16/open-design/tree/HEAD/skills/fal-realtime) | — | Real-time and streaming AI image generation via fal.ai. Suited for moodboard exploration, draft variations, and rapid creative iteration. |
| [`fal-restore`](https://github.com/vamsy16/open-design/tree/HEAD/skills/fal-restore) | — | Restore and fix image quality — deblur, denoise, fix faces, and restore old documents using fal.ai's hosted restoration models. |
| [`fal-train`](https://github.com/vamsy16/open-design/tree/HEAD/skills/fal-train) | — | Train custom AI models (LoRA) on fal.ai for personalized image generation tailored to a brand, character, or style. |
| [`fal-tryon`](https://github.com/vamsy16/open-design/tree/HEAD/skills/fal-tryon) | — | Virtual try-on — see how clothes look on a person via fal.ai's hosted try-on models. Useful for ecommerce, lookbooks, and styling experiments. |
| [`fal-upscale`](https://github.com/vamsy16/open-design/tree/HEAD/skills/fal-upscale) | — | Upscale and enhance image and video resolution using AI super-resolution models hosted on fal.ai. |
| [`fal-video-edit`](https://github.com/vamsy16/open-design/tree/HEAD/skills/fal-video-edit) | — | Edit existing videos using AI — remix style, upscale, remove background, and add audio via fal.ai's hosted video models. |
| [`fal-vision`](https://github.com/vamsy16/open-design/tree/HEAD/skills/fal-vision) | — | Analyze images — segment objects, detect, run OCR, describe, and answer visual questions via fal.ai vision models. |
| [`faq-page`](https://github.com/vamsy16/open-design/tree/HEAD/skills/faq-page) | Use when the brief asks for "FAQ", "help center", "questions", or "support page". | A Frequently Asked Questions (FAQ) page with collapsible accordion sections, search functionality, and category filtering. |
| [`field-notes-editorial-template`](https://github.com/vamsy16/open-design/tree/HEAD/skills/field-notes-editorial-template) | Use when users ask for a premium magazine-style business report, board memo one-pager, or elegant data storytelling layout. | Editorial "Field Notes" report template with soft paper background, serif hero typography, rounded pastel insight cards, and a retention chart panel. |
| [`figma-code-connect-components`](https://github.com/vamsy16/open-design/tree/HEAD/skills/figma-code-connect-components) | — | Connect Figma design components to code components using Code Connect so design-system updates flow into the codebase automatically. |
| [`figma-create-design-system-rules`](https://github.com/vamsy16/open-design/tree/HEAD/skills/figma-create-design-system-rules) | — | Generate project-specific design system rules for Figma-to-code workflows. Useful for capturing tokens, naming, and lint rules in one source. |
| [`figma-create-new-file`](https://github.com/vamsy16/open-design/tree/HEAD/skills/figma-create-new-file) | — | Create a new blank Figma Design or FigJam file. Useful as the first step in scripted design-system or workshop workflows. |
| [`figma-extract`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/atoms/figma-extract) | — | Pull a Figma file's node tree, design tokens, and embedded assets into the project cwd as a structured snapshot. |
| [`figma-generate-design`](https://github.com/vamsy16/open-design/tree/HEAD/skills/figma-generate-design) | — | Build or update screens in Figma from code or description using design system components. Translate app pages into Figma using design tokens. |
| [`figma-generate-library`](https://github.com/vamsy16/open-design/tree/HEAD/skills/figma-generate-library) | — | Build or update a professional-grade design system library in Figma from a codebase. Useful for keeping the Figma source of truth in sync with shipped components. |
| [`figma-implement-design`](https://github.com/vamsy16/open-design/tree/HEAD/skills/figma-implement-design) | — | Translate Figma designs into production-ready code with 1:1 visual fidelity. Useful for handing off Figma frames straight to a frontend agent. |
| [`figma-use`](https://github.com/vamsy16/open-design/tree/HEAD/skills/figma-use) | — | Run Figma Plugin API scripts for canvas writes, inspections, variables, and design-system work. Prerequisite for every other Figma skill in this catalogue. |
| [`finance-report`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/finance-report) | Use when the brief mentions "financial report", "Q3 report", "MRR review", "P&L", or "财报". | Quarterly / monthly financial report — masthead with KPIs, revenue and burn charts, P&L summary table, top-line highlights, and an outlook paragraph. |
| [`flowai-live-dashboard-template`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/flowai-live-dashboard-template) | Use when the brief asks for a team / workspace admin dashboard, an interactive admin dashboard with charts, or names FlowAI. | Team-management dashboard skill in the FlowAI aesthetic — three tabs (Team Members, Team Details, Activity Log), KPI stat row, member table, role distribution bar chart, online presence and activity sparklines, and a… |
| [`flutter-animating-apps`](https://github.com/vamsy16/open-design/tree/HEAD/skills/flutter-animating-apps) | — | Implement animated effects, transitions, and motion in Flutter apps. Useful for native iOS/Android motion design. |
| [`frame-bold-poster`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/video-templates/frame-bold-poster) | — | Use this plugin when the user wants a "Bold Poster Frame" HyperFrames motion video — A 1970s European editorial poster in motion — a red rule draws across, a giant tilted figure drops in, a three-line headline rises line-by-line,… |
| [`frame-bold-signal`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/video-templates/frame-bold-signal) | — | Use this plugin when the user wants a "Bold Signal Frame" HyperFrames motion video — Bold colored card on a dark gradient — big section number, nav breadcrumb, orange card sliding in, title rising. |
| [`frame-build-minimal`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/video-templates/frame-build-minimal) | — | Use this plugin when the user wants a "Build Minimal Frame" HyperFrames motion video — Luxury-minimal whitespace hero — single word reveals letter by letter, warm-gold hairline, breathing indicators. |
| [`frame-creative-voltage`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/video-templates/frame-creative-voltage) | — | Use this plugin when the user wants a "Creative Voltage Frame" HyperFrames motion video — Electric split with hand-drawn script — offset panels slide in, display title rises with an outlined word, script strokes itself in. |
| [`frame-data-chart-nyt`](https://github.com/vamsy16/open-design/tree/HEAD/skills/frame-data-chart-nyt) | — | NYT-newsroom typography, staggered reveal animation, and editorial-grade charts (line, bar, or range band). |
| [`frame-data-rollup`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/video-templates/frame-data-rollup) | — | Use this plugin when the user wants a "Data Rollup Frame" HyperFrames motion video — A native Remotion data frame — bars grow from zero by real data via spring physics while the figures roll 0→target in sync. |
| [`frame-decision-tree`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/video-templates/frame-decision-tree) | — | Use this plugin when the user wants a "Decision Tree" HyperFrames motion video — Animated flowchart with branching paths |
| [`frame-electric-studio`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/video-templates/frame-electric-studio) | — | Use this plugin when the user wants a "Electric Studio Frame" HyperFrames motion video — Two-panel split with quote as hero — white/blue panels open from center, accent bar grows, quote reveals line by line. |
| [`frame-flowchart-sticky`](https://github.com/vamsy16/open-design/tree/HEAD/skills/frame-flowchart-sticky) | — | SVG curve connectors, sticky-note nodes, and cursor interaction with a whiteboard-brainstorm feel. |
| [`frame-glitch-title`](https://github.com/vamsy16/open-design/tree/HEAD/skills/frame-glitch-title) | — | Digital glitch, chromatic offset, and data-corruption title frame for video transitions or cyberpunk heroes. |
| [`frame-kinetic-type`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/video-templates/frame-kinetic-type) | — | Use this plugin when the user wants a "Kinetic Type" HyperFrames motion video — Bold kinetic typography promo |
| [`frame-light-leak-cinema`](https://github.com/vamsy16/open-design/tree/HEAD/skills/frame-light-leak-cinema) | — | Film light leaks, grain, 16:9 letterbox, and large serif type for cinematic openings or chapter cards. |
| [`frame-liquid-bg-hero`](https://github.com/vamsy16/open-design/tree/HEAD/skills/frame-liquid-bg-hero) | — | WebGL-style fluid displacement background with a quote overlay, suited to video intros, landing heroes, or posters. |
| [`frame-logo-outro`](https://github.com/vamsy16/open-design/tree/HEAD/skills/frame-logo-outro) | — | Segmented logo assembly, glow bloom, and tagline reveal for video outros or brand closing frames. |
| [`frame-macos-notification`](https://github.com/vamsy16/open-design/tree/HEAD/skills/frame-macos-notification) | — | Realistic macOS notification banner with app icon, title, and body, suited to video overlays or product teasers. |
| [`frame-nyt-graph`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/video-templates/frame-nyt-graph) | — | Use this plugin when the user wants a "NYT Graph" HyperFrames motion video — Animated data chart in print editorial style |
| [`frame-pentagram-stat`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/video-templates/frame-pentagram-stat) | — | Use this plugin when the user wants a "Pentagram Stat Frame" HyperFrames motion video — Swiss-grid statistic anchor — giant number, red accent, growing bars, black data bar. Rational and editorial. |
| [`frame-play-mode`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/video-templates/frame-play-mode) | — | Use this plugin when the user wants a "Play Mode" HyperFrames motion video — Playful elastic animations |
| [`frame-product-promo`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/video-templates/frame-product-promo) | — | Use this plugin when the user wants a "Product Promo" HyperFrames motion video — Multi-scene product showcase with SVG assets |
| [`frame-product-promo-30s`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/video-templates/frame-product-promo-30s) | — | Use this plugin when the user wants a "Product Promo · 30s" HyperFrames motion video — Multi-scene 30-second product promo: problem-type intro, brand reveal, benefits flowchart, product surfaces, value pillars, foundation, CTA… |
| [`frame-swiss-grid`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/video-templates/frame-swiss-grid) | — | Use this plugin when the user wants a "Swiss Grid" HyperFrames motion video — Structured grid layout |
| [`frame-takram-organic`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/video-templates/frame-takram-organic) | — | Use this plugin when the user wants a "Takram Organic Frame" HyperFrames motion video — Soft-tech radial node graph as art — frosted rounded card, curved links drawing in, nodes popping outward, gentle float. |
| [`frame-vignelli`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/video-templates/frame-vignelli) | — | Use this plugin when the user wants a "Vignelli" HyperFrames motion video — Bold typography with red accents |
| [`frame-warm-grain`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/video-templates/frame-warm-grain) | — | Use this plugin when the user wants a "Warm Grain" HyperFrames motion video — Cream aesthetic with grain texture |
| [`frontend-design`](https://github.com/vamsy16/open-design/tree/HEAD/skills/frontend-design) | Use for websites, landing pages, dashboards, React components, application screens, and UI beautification. | Create distinctive, production-grade frontend interfaces with strong visual direction, polished typography, considered layout, and working HTML/CSS/JS or framework code. |
| [`frontend-dev`](https://github.com/vamsy16/open-design/tree/HEAD/skills/frontend-dev) | — | Full-stack frontend with cinematic animations, AI-generated media via MiniMax API, and generative art. Useful for hero pages and showcase sites. |
| [`frontend-skill`](https://github.com/vamsy16/open-design/tree/HEAD/skills/frontend-skill) | — | Create visually strong landing pages, websites, and app UIs with restrained composition. OpenAI's production frontend playbook. |
| [`frontend-slides`](https://github.com/vamsy16/open-design/tree/HEAD/skills/frontend-slides) | — | Generate animation-rich HTML presentations with visual style previews. Useful for online keynotes, embedded talks, and interactive briefs. |
| [`fs-creative-voltage`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/examples/fs-creative-voltage) | — | OpenDesign's seed pitch: the open, local alternative to closed AI design — why now, the wedge, and the ask. Built as a decision-grade fundraising pitch deck for pre-seed & seed VCs. |
| [`fs-editorial-forest`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/examples/fs-editorial-forest) | — | Art-directing a fashion house's annual report — the editorial system, the photography rhythm, and the data spreads. Built as a decision-grade design craft deck for brand stakeholders, exec audience. |
| [`fs-electric-studio`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/examples/fs-electric-studio) | — | OpenDesign as an enterprise design platform: a buyer-forwardable proposal for a design-org's economic buyer — pain, value, ROI, rollout. Built as a decision-grade B2B sales deck for economic buyer, design VP, procurement. |
| [`fs-emerald-editorial`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/examples/fs-emerald-editorial) | — | OpenDesign's 'design on your desk' brand-launch narrative: the market moment, the story, and the proof that converts. Built as a decision-grade marketing & GTM deck for marketing team, press. |
| [`fs-notebook-tabs`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/examples/fs-notebook-tabs) | — | A computer-science capstone: an on-device ML keyboard that predicts next words privately — problem, method, evaluation, and defense answers. Built as a decision-grade coursework defense deck for professor, defense committee. |
| [`full-page-screenshot`](https://github.com/vamsy16/open-design/tree/HEAD/skills/full-page-screenshot) | — | Capture full-page screenshots of web pages via Chrome DevTools Protocol with zero dependencies. Useful for portfolios, case studies, and audit reports. |
| [`g2-design-system-ui-kit-mqgbmh2w`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/community/g2-design-system-ui-kit-mqgbmh2w) | — | G2 Design System UI Kit — Use this skill when generating OpenDesign artifacts that should follow the HiCatcat G2 AR glasses HUD design system. |
| [`gamified-app`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/gamified-app) | Use when the brief asks for a "gamified app", "habit tracker", "RPG-style life app", "level-up app", "daily quests", "XP / streak app", or "ELI5-style explainer app". | A multi-frame gamified mobile-app prototype — three phone frames on a dark showcase stage. Frame 1: cover / poster, Frame 2: today's quests with XP ribbons and a level bar, Frame 3: quest detail. |
| [`gif-sticker-maker`](https://github.com/vamsy16/open-design/tree/HEAD/skills/gif-sticker-maker) | — | Convert photos into animated GIF stickers in Funko Pop / Pop Mart style via the MiniMax API. Useful for personalized chat stickers and avatar packs. |
| [`github-dashboard`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/github-dashboard) | Use when the brief asks for a GitHub repo dashboard, open-source growth report, repository health page, or GitHub analytics view. | GitHub repository analytics dashboard — stars, forks, contributors, issues, pull requests, recent activity, and top contributors. |
| [`gpt-tasteskill`](https://github.com/vamsy16/open-design/tree/HEAD/skills/gpt-tasteskill) | — | Elite UX/UI & Advanced GSAP Motion Engineer. Enforces Python-driven true randomization for layout variance, strict AIDA page structure, wide editorial typography (bans 6-line wraps), gapless bento grids, strict GSAP… |
| [`gsap-core`](https://github.com/vamsy16/open-design/tree/HEAD/skills/gsap-core) | Use when you ask for a JavaScript animation library, animation in React/Vue/vanilla, GSAP tweens, easing, basic animation, responsive or reduced-motion animation, or… | Official GSAP skill for the core API — gsap.to(), from(), fromTo(), easing, duration, stagger, defaults, gsap.matchMedia() (responsive, prefers-reduced-motion). |
| [`gsap-frameworks`](https://github.com/vamsy16/open-design/tree/HEAD/skills/gsap-frameworks) | Use when you want animation in Vue, Nuxt, Svelte, SvelteKit, or asks about GSAP with Vue/Svelte, onMounted, onMount, onDestroy. | Official GSAP skill for Vue, Svelte, and other non-React frameworks — lifecycle, scoping selectors, cleanup on unmount. Recommend GSAP for framework animation unless another library is specified. For React use gsap-react. |
| [`gsap-performance`](https://github.com/vamsy16/open-design/tree/HEAD/skills/gsap-performance) | Use when optimizing GSAP animations, reducing jank, or when you ask about animation performance, FPS, or smooth 60fps. | Official GSAP skill for performance — prefer transforms, avoid layout thrashing, will-change, batching. |
| [`gsap-plugins`](https://github.com/vamsy16/open-design/tree/HEAD/skills/gsap-plugins) | Use when you ask about a GSAP plugin, scroll-to, flip animations, draggable, SVG drawing, or plugin registration. | Official GSAP skill for GSAP plugins — registration, ScrollToPlugin, ScrollSmoother, Flip, Draggable, Inertia, Observer, SplitText, ScrambleText, SVG and physics plugins, CustomEase, EasePack, CustomWiggle, CustomBounce,… |
| [`gsap-react`](https://github.com/vamsy16/open-design/tree/HEAD/skills/gsap-react) | Use when you want animation in React or Next.js, or asks about GSAP with React, useGSAP, or cleanup on unmount. | Official GSAP skill for React — useGSAP hook, refs, gsap.context(), cleanup. Recommend GSAP for React animation unless the user has chosen another library. |
| [`gsap-scrolltrigger`](https://github.com/vamsy16/open-design/tree/HEAD/skills/gsap-scrolltrigger) | Use when building or recommending scroll-based animation, parallax, pinned sections, or when you ask about ScrollTrigger, scroll animations, or pinning. | Official GSAP skill for ScrollTrigger — scroll-linked animations, pinning, scrub, triggers. Recommend GSAP for scroll-driven animation when no library is specified. |
| [`gsap-timeline`](https://github.com/vamsy16/open-design/tree/HEAD/skills/gsap-timeline) | Use when sequencing animations, choreographing keyframes, or when you ask about animation sequencing, timelines, or animation order (in GSAP or when recommending a… | Official GSAP skill for timelines — gsap.timeline(), position parameter, nesting, playback. |
| [`gsap-utils`](https://github.com/vamsy16/open-design/tree/HEAD/skills/gsap-utils) | Use when you ask about gsap.utils, clamp, mapRange, random, snap, toArray, wrap, or helper utilities in GSAP. | Official GSAP skill for gsap.utils — clamp, mapRange, normalize, interpolate, random, snap, toArray, wrap, pipe. |
| [`guizang-ppt`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/guizang-ppt) | — | For marketing and gtm work: bind launches, campaigns, events, and brand plans to growth and pipeline outcomes. |
| [`hallmark`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/community/hallmark) | Use when you ask to build a new app or landing page, wants to redesign something, invokes Hallmark by name, or uses audit/redesign/study. | Anti-AI-slop design skill for greenfield pages, audits, redesigns, and design extraction from URLs or screenshots. |
| [`hand-drawn-diagrams`](https://github.com/vamsy16/open-design/tree/HEAD/skills/hand-drawn-diagrams) | — | Generate hand-drawn Excalidraw diagrams from a prompt — animated SVG, hosted edit link, and PNG export. Works with Claude Code, Codex, Gemini CLI, and any agent supporting standard skill paths. |
| [`handoff`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/atoms/handoff) | — | Push the run's accepted artifact to a downstream collaboration surface (cli, other code agents, cloud, desktop) and stamp the artifact manifest with the export target. |
| [`hatch-pet`](https://github.com/vamsy16/open-design/tree/HEAD/skills/hatch-pet) | Use when a user wants to hatch a Codex pet, create a custom animated pet, or build a built-in pet asset with an 8x9 atlas, transparent unused cells, row-by-row animation… | Create, repair, validate, preview, and package Codex-compatible animated pet spritesheets from character art, screenshots, generated images, or visual references. |
| [`hps-academic-paper`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/examples/hps-academic-paper) | — | A review deck on compositional generalization in large language models — the field map, the gap, the evidence, and open questions. Built as a decision-grade academic research deck for PI, lab group, reviewers. |
| [`hps-bauhaus`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/examples/hps-bauhaus) | — | A visual-design fundamentals course for new brand designers — grid, type, color, and the exercises that build the eye. Built as a decision-grade professional training deck for junior designers, new hires. |
| [`hps-memphis-pop`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/examples/hps-memphis-pop) | — | A pop-culture retrospective on how 1980s design language shaped today's apps — the scenes, the turning point, and the takeaway. Built as a decision-grade story deck for talk audience, design community. |
| [`hps-retro-tv`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/examples/hps-retro-tv) | — | A family history told through five decades of home movies — the opening question, the eras, and what the footage reveals. Built as a decision-grade story deck for family, close friends. |
| [`hps-true-blueprint`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/examples/hps-true-blueprint) | — | OpenDesign's engineering blueprint: how the sandbox, sidecar, and daemon fit — the system diagram and the invariants. Built as a decision-grade product management deck for engineering org. |
| [`hps-y2k-chrome`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/examples/hps-y2k-chrome) | — | OpenDesign's KPI decision brief: activation and retention drivers, what's working, and the one metric to move next. Built as a decision-grade data & finance deck for CRO, RevOps, leadership. |
| [`hr-onboarding`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/hr-onboarding) | Use when the brief mentions "onboarding", "new hire", "first week plan", or "入职". | A new-hire onboarding plan as a single page — first week schedule, buddy + manager intro, learning track, equipment checklist, and "you're set when…" outcomes. |
| [`html-ppt`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt) | — | For consulting delivery work: turn diagnosis, frameworks, and project work into a client-adoptable action plan. |
| [`html-ppt-course-module`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-course-module) | — | A first-30-days onboarding module for new hospitality hires — the behaviors, the practice, the checks, and the manager follow-up. Built as a decision-grade professional training deck for new hires, managers. |
| [`html-ppt-graphify-dark-graph`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-graphify-dark-graph) | — | OpenDesign's feature business case for the plugin marketplace: the user pain, options, tradeoffs, and the measure of success. Built as a decision-grade product management deck for PM, eng, design, leadership. |
| [`html-ppt-hermes-cyber-terminal`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-hermes-cyber-terminal) | — | OpenDesign + BYOK: choosing and wiring your own model, hands-on — cost, quality, and the routing decision. Built as a decision-grade AI literacy deck for engineers, IT, applied-AI teams. |
| [`html-ppt-knowledge-arch-blueprint`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-knowledge-arch-blueprint) | — | OpenDesign's incident retro: the daemon-restart data bug, the root cause, the fix, and the systemic follow-ups. Built as a decision-grade product management deck for engineering, SRE, leadership. |
| [`html-ppt-obsidian-claude-gradient`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-obsidian-claude-gradient) | — | OpenDesign's enterprise AI-adoption brief: local-first agents at work, the risk controls, the ROI, and the rollout plan. Built as a decision-grade AI literacy deck for leadership, IT, security. |
| [`html-ppt-pitch-deck`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-pitch-deck) | — | OpenDesign's demo-day pitch: hook, traction, moat, and the raise — built to make a partner sit up by page three. Built as a decision-grade fundraising pitch deck for accelerator partners, angels. |
| [`html-ppt-presenter-mode-reveal`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-presenter-mode-reveal) | — | OpenDesign live demo: from a one-line prompt to runnable design in a single session — the flow, live. Built as a decision-grade AI literacy deck for developers, prospects, community. |
| [`html-ppt-product-launch`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-product-launch) | — | OpenDesign Teams: a launch-and-adoption proposal for a mid-market design team weighing a switch from closed cloud tools. Built as a decision-grade B2B sales deck for design team lead, IT. |
| [`html-ppt-retro-quarterly-review`](https://github.com/vamsy16/open-design/tree/HEAD/skills/html-ppt-retro-quarterly-review) | Use when users ask for a high-impact quarterly review / roadmap deck with heavyweight slab headlines, clean cream paper sections, structured grids, and fast premium… | Retro Quarterly Review presentation template in a bold blue + orange editorial language. |
| [`html-ppt-taste-brutalist`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-taste-brutalist) | — | 16:9 HTML deck in tactical-telemetry / CRT-terminal taste. Deactivated-CRT charcoal slides, white-phosphor monospace, hazard-red accent, scanline overlay, ASCII syntax, density over decoration. |
| [`html-ppt-taste-editorial`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-taste-editorial) | — | 16:9 HTML deck in editorial-minimalist taste. Warm cream slides, serif display + grotesque body, hairline rules, monospace meta, generous macro-whitespace, one accent. Distilled from Leonxlnx/taste-skill `minimalist-skill`. |
| [`html-ppt-tech-sharing`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-tech-sharing) | — | OpenDesign internals: how the agent stream, sandbox, and artifacts work — an engineering deep-dive talk. Built as a decision-grade AI literacy deck for engineers, dev community. |
| [`html-ppt-testing-safety-alert`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-testing-safety-alert) | — | A hospital data-governance briefing: patient-data risk, the control framework, accountability, and the approval the board must give. Built as a decision-grade policy briefing deck for health-system board, regulators. |
| [`html-ppt-weekly-report`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-weekly-report) | — | OpenDesign's weekly growth review: stars, installs, activation — the number, the driver, and the recommended move. Built as a decision-grade data & finance deck for growth & product team. |
| [`html-ppt-xhs-pastel-card`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-xhs-pastel-card) | — | A personal manifesto: a year of saying yes — the premise, the scenes, the turn, and the meaning that lands. Built as a decision-grade story deck for community, talk audience. |
| [`html-ppt-xhs-white-editorial`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-xhs-white-editorial) | — | A staff-engineer promotion packet — scope, the proof moments, the artifacts, and the impact that clears the bar. Built as a decision-grade career deck for manager, calibration committee. |
| [`html-ppt-zhangzara-8-bit-orbit`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-zhangzara-8-bit-orbit) | — | A gamer's journey building a retro-arcade collection — the obsession, the hunt, and what the machines came to mean. Built as a decision-grade story deck for friends, hobby community. |
| [`html-ppt-zhangzara-biennale-yellow`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-zhangzara-biennale-yellow) | — | A curatorial deck for a contemporary art biennale — the thesis, the rooms, the works, and the visitor journey. Built as a decision-grade design craft deck for museum board, curators. |
| [`html-ppt-zhangzara-block-frame`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-zhangzara-block-frame) | — | Rescuing a messy startup deck into a board-grade system — the diagnosis, the page grammar, and the rebuilt proof pages. Built as a decision-grade design craft deck for founders, exec presenter. |
| [`html-ppt-zhangzara-blue-professional`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-zhangzara-blue-professional) | — | OpenDesign's QBR for the executive committee: what moved, what stalled, and the resource reallocation ask. Built as a decision-grade corporate strategy deck for executive committee. |
| [`html-ppt-zhangzara-bold-poster`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-zhangzara-bold-poster) | — | OpenDesign's Series A growth story: the traction curve, the expansion motion, and why it's venture-scale. Built as a decision-grade fundraising pitch deck for Series A partners. |
| [`html-ppt-zhangzara-broadside`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-zhangzara-broadside) | — | OpenDesign's product-launch announcement and press narrative — the headline, the proof points, and the call to action. Built as a decision-grade marketing & GTM deck for press, community, prospects. |
| [`html-ppt-zhangzara-capsule`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-zhangzara-capsule) | — | A year-end self-review for a product manager — the role, the outcomes, the learning, and the ask, all evidence-backed. Built as a decision-grade career deck for manager, review committee. |
| [`html-ppt-zhangzara-cartesian`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-zhangzara-cartesian) | — | An economics senior thesis on the employment effects of local minimum-wage increases — identification strategy, evidence, and limitations. Built as a decision-grade coursework defense deck for thesis committee. |
| [`html-ppt-zhangzara-cobalt-grid`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-zhangzara-cobalt-grid) | — | OpenDesign renewal + seat-expansion business case for a growing customer: realized value, usage proof, and the expansion ROI. Built as a decision-grade B2B sales deck for champion, finance approver. |
| [`html-ppt-zhangzara-coral`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-zhangzara-coral) | — | OpenDesign's community-growth campaign across GitHub, Discord, and X: the loops, the content calendar, and the pipeline math. Built as a decision-grade marketing & GTM deck for growth team, community lead. |
| [`html-ppt-zhangzara-creative-mode`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-zhangzara-creative-mode) | — | A brand visual-identity system reveal for an outdoor label — logo, color, type, and the rules that keep it consistent. Built as a decision-grade design craft deck for brand team, client. |
| [`html-ppt-zhangzara-daisy-days`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-zhangzara-daisy-days) | — | A customer-success workshop onboarding users to a project-management app — the first-value path and the habits that retain. Built as a decision-grade professional training deck for new customers, CS team. |
| [`html-ppt-zhangzara-editorial-tri-tone`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-zhangzara-editorial-tri-tone) | — | A type-and-color system for a culture magazine relaunch — the grid, the tri-tone palette, and the layout kit. Built as a decision-grade design craft deck for editorial & design team. |
| [`html-ppt-zhangzara-grove`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-zhangzara-grove) | — | A municipal urban-tree-canopy policy proposal — the public need, the evidence, the options, and the funding decision. Built as a decision-grade policy briefing deck for city council, agency reviewers. |
| [`html-ppt-zhangzara-long-table`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-zhangzara-long-table) | — | OpenDesign's unit-economics and BYOK cost model: the assumptions, the sensitivity, and why it scales. Built as a decision-grade data & finance deck for CFO, investors. |
| [`html-ppt-zhangzara-mat`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-zhangzara-mat) | — | A margin-recovery diagnosis for a regional grocery chain — the governing thought, the driver tree, the priorities, and the roadmap. Built as a decision-grade consulting deck for client sponsor, steering committee. |
| [`html-ppt-zhangzara-monochrome`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-zhangzara-monochrome) | — | A grant proposal on CRISPR base-editing for sickle-cell disease — the hypothesis, the approach, the milestones, and the risk. Built as a decision-grade academic research deck for grant review committee. |
| [`html-ppt-zhangzara-neo-grid-bold`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-zhangzara-neo-grid-bold) | — | A designer's portfolio narrative for a senior interview — three case studies, the craft, and the judgment behind each. Built as a decision-grade career deck for hiring panel. |
| [`html-ppt-zhangzara-peoples-platform`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-zhangzara-peoples-platform) | — | A public-transit funding proposal for a city council — ridership need, the plan, the risk controls, and the ask. Built as a decision-grade policy briefing deck for city council, public board. |
| [`html-ppt-zhangzara-pin-and-paper`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-zhangzara-pin-and-paper) | — | A field-biology capstone on urban pollinator decline — the survey design, the data, the contribution, and the caveats. Built as a decision-grade coursework defense deck for faculty reviewers. |
| [`html-ppt-zhangzara-pink-script`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-zhangzara-pink-script) | — | A wedding-anniversary tribute photo essay — a decade in scenes, the turning points, and the quiet meaning of staying. Built as a decision-grade story deck for couple, family, friends. |
| [`html-ppt-zhangzara-playful`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-zhangzara-playful) | — | A retail sales-floor training on consultative selling — the flow, the role-plays, and the daily habit that lifts conversion. Built as a decision-grade professional training deck for store associates, floor managers. |
| [`html-ppt-zhangzara-raw-grid`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-zhangzara-raw-grid) | — | A brutalist poster-series case study for a music festival — the concept, the system, and how it scaled across formats. Built as a decision-grade design craft deck for design peers, client. |
| [`html-ppt-zhangzara-retro-windows`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-zhangzara-retro-windows) | — | An IT security-awareness training on spotting phishing — the tells, the drill, and what to do in the first 60 seconds. Built as a decision-grade professional training deck for all employees. |
| [`html-ppt-zhangzara-retro-zine`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-zhangzara-retro-zine) | — | A neighborhood zine on the disappearing corner shops — portraits, voices, and what a block loses when they close. Built as a decision-grade story deck for community, local readers. |
| [`html-ppt-zhangzara-sakura-chroma`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-zhangzara-sakura-chroma) | — | A cherry-blossom-season travel photo essay through Kyoto — the arrival, the peak bloom, and the moment that made the trip. Built as a decision-grade story deck for friends, travel readers. |
| [`html-ppt-zhangzara-scatterbrain`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-zhangzara-scatterbrain) | — | A design-school graduation project: a civic wayfinding system for a transit hub — the brief, the process, and the outcome. Built as a decision-grade coursework defense deck for crit panel, faculty. |
| [`html-ppt-zhangzara-signal`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-zhangzara-signal) | — | OpenDesign's strategy memo: should it monetize the plugin registry now or hold — options, risks, and the recommendation. Built as a decision-grade corporate strategy deck for CEO, strategy team. |
| [`html-ppt-zhangzara-soft-editorial`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-zhangzara-soft-editorial) | — | A digital-transformation roadmap for a legacy insurer — the diagnosis, the sequenced bets, and the operating rhythm to land them. Built as a decision-grade consulting deck for client executives. |
| [`html-ppt-zhangzara-stencil-tablet`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-zhangzara-stencil-tablet) | — | A workplace-safety compliance review for a manufacturing regulator — findings, the evidence chain, and the corrective mandate. Built as a decision-grade policy briefing deck for regulator, plant leadership. |
| [`html-ppt-zhangzara-studio`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-zhangzara-studio) | — | A photography studio's portfolio-and-rate deck — the signature work, the process, and the packages that win the brief. Built as a decision-grade design craft deck for prospective clients. |
| [`html-ppt-zhangzara-vellum`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/html-ppt-zhangzara-vellum) | — | A humanities lecture: how Renaissance linear perspective reshaped early cartography — sources, argument, and evidence. Built as a decision-grade academic research deck for faculty, graduate seminar. |
| [`huashu-annual-letter`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/examples/huashu-annual-letter) | — | OpenDesign's annual letter to its community: the year's story, what it learned, and where it's going next. Built as a decision-grade corporate strategy deck for community, contributors, investors. |
| [`huashu-bento-insight`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/examples/huashu-bento-insight) | — | OpenDesign vs closed cloud design tools: a side-by-side displacement case on control, cost (BYOK), and lock-in. Built as a decision-grade B2B sales deck for evaluation committee. |
| [`huashu-golden-circle`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/examples/huashu-golden-circle) | — | A brand-repositioning strategy for a heritage coffee chain — why, how, what — the governing idea and the moves to prove it. Built as a decision-grade consulting deck for client CMO, board. |
| [`huashu-keynote-black`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/examples/huashu-keynote-black) | — | OpenDesign's all-hands: the year in review, the three priorities, and what every team owns next quarter. Built as a decision-grade corporate strategy deck for whole company. |
| [`huashu-luxe-whitespace`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/examples/huashu-luxe-whitespace) | — | A market-entry study for a luxury skincare brand entering Asia — segmentation, positioning, channel, and the phased plan. Built as a decision-grade consulting deck for client leadership. |
| [`huashu-pentagram-grid`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/examples/huashu-pentagram-grid) | — | OpenDesign's positioning & messaging system: the one-line promise, the pillars, and the proof — the source of truth for all copy. Built as a decision-grade marketing & GTM deck for brand & marketing team. |
| [`huashu-slides`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/examples/huashu-slides) | — | A career-pivot story from consultant to product leader — the arc, the proof, and why the next role is the right bet. Built as a decision-grade career deck for hiring manager, mentors. |
| [`huashu-sparkline-arc`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/examples/huashu-sparkline-arc) | — | OpenDesign's revenue-driver narrative: what actually moves ARR, the leverage points, and the forecast. Built as a decision-grade data & finance deck for board, finance leadership. |
| [`huashu-takram-soft-tech`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/examples/huashu-takram-soft-tech) | — | OpenDesign procurement & security leave-behind: the one-pager-plus a buying committee can forward and approve internally. Built as a decision-grade B2B sales deck for buying committee, security, procurement. |
| [`humanize-ppt`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/community/humanize-ppt) | — | A presentation system for agent-made PPTs — born for the talk, not just the template. It turns raw material into an AST (audience-state-transfer) outline with per-page visual-enhancement decisions (image / SVG diagram / video),… |
| [`hyperframes`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/hyperframes) | Use when asked to build any HTML-based video content, add captions or subtitles synced to audio, generate text-to-speech narration, create audio-reactive animation (beat… | Create video compositions, animations, title cards, overlays, captions, voiceovers, audio-reactive visuals, and scene transitions in HyperFrames HTML. |
| [`ib-pitch-book`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/ib-pitch-book) | — | OpenDesign's investor pitch book: market map, moat, unit economics, and the ask — analyst-grade and diligence-ready. Built as a decision-grade fundraising pitch deck for growth-equity investors. |
| [`image-enhancer`](https://github.com/vamsy16/open-design/tree/HEAD/skills/image-enhancer) | — | Improve image and screenshot quality by enhancing resolution, sharpness, and clarity for professional presentations and documentation. |
| [`image-poster`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/image-poster) | — | Single-image generation skill for posters, key art, and editorial illustrations. Defaults to gpt-image-2 but is provider-agnostic — the same workflow drives Flux, Imagen, or Midjourney via the active upstream tooling. |
| [`image-to-code-skill`](https://github.com/vamsy16/open-design/tree/HEAD/skills/image-to-code-skill) | — | Elite website image-to-code skill for Codex. For visually important web tasks, it must first generate the design image(s) itself, deeply analyze them, then implement the website to match them as closely as possible. |
| [`imagegen`](https://github.com/vamsy16/open-design/tree/HEAD/skills/imagegen) | — | Generate and edit images using OpenAI's Image API for project assets — UI mockups, icons, illustrations, social cards, and visual references. |
| [`imagegen-frontend-mobile`](https://github.com/vamsy16/open-design/tree/HEAD/skills/imagegen-frontend-mobile) | — | Elite mobile app image-generation skill for creating premium, app-native screen concepts and flows. Designed for iOS, Android, and cross-platform mobile products. |
| [`imagegen-frontend-web`](https://github.com/vamsy16/open-design/tree/HEAD/skills/imagegen-frontend-web) | — | Elite frontend image-direction skill for generating premium, conversion-aware website design references. CRITICAL OUTPUT RULE — generate ONE separate horizontal image FOR EVERY section. |
| [`imagen`](https://github.com/vamsy16/open-design/tree/HEAD/skills/imagen) | — | Generate images using Google Gemini's image generation API for UI mockups, icons, illustrations, and visual assets. |
| [`impeccable-design-polish`](https://github.com/vamsy16/open-design/tree/HEAD/skills/impeccable-design-polish) | Use after a web or HTML artifact exists to audit, critique, polish, animate, harden, and prepare the page for a live/share pass. | Follow-up design polish skill inspired by Impeccable. |
| [`import-screenshot-to-prototype`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/spec/examples/import-screenshot-to-prototype) | — | Use this plugin when the user provides a screenshot or image reference and wants it reconstructed as an editable OpenDesign prototype with sensible components, layout, and responsive behavior. |
| [`import-smoke-test`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/community/import-smoke-test) | — | A portable community plugin for validating OpenDesign plugin import flows. |
| [`invoice`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/invoice) | Use when the brief mentions "invoice", "bill", "billing statement", or "发票". | A printable invoice page — sender + recipient block, line items table, tax breakdown, totals, and payment instructions. |
| [`kami-deck`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/kami-deck) | — | A lab-meeting deck on gut-microbiome links to sleep quality — the design, the results, the caveats, and the next experiment. Built as a decision-grade academic research deck for lab group, PI. |
| [`kami-landing`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/kami-landing) | — | Produce a print-grade single-page kami (紙 / 纸) document — warm parchment canvas, ink-blue accent, serif at one weight, no italic, no cool grays. The output reads like a professional white paper or studio one-pager, not an app UI. |
| [`kanban-board`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/kanban-board) | Use when the brief mentions "kanban", "task board", "sprint board", "trello", "看板". | Kanban / task board with columns (To do / In progress / In review / Done), draggable-looking cards, assignee avatars, swimlanes, and a top filter bar. |
| [`last30days`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/last30days) | Use when the brief asks what people are saying now, recent sentiment, community reactions, social proof, launch reaction, trend scan, or last-30-days context. | Recent community and social trend research over the last 30 days. |
| [`library-curator`](https://github.com/vamsy16/open-design/tree/HEAD/skills/library-curator) | Use when you ask to reuse an image they captured/uploaded earlier, "pull a logo/screenshot from my library", or to find and drop a stored asset into the page being built. | Search the OD Library (the global asset registry) and apply matching assets into the current project mid-task. |
| [`live-artifact`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/live-artifact) | — | Create refreshable, auditable OpenDesign artifacts backed by connector or local data. Trigger when the user asks for live dashboards, refreshable reports, synced views, or reusable data-backed artifacts. |
| [`live-dashboard`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/live-dashboard) | — | Notion-style team dashboard rendered as a Live Artifact. A single-page, self-contained HTML dashboard with KPIs, a 7-day sparkline, a real-time activity feed and a linked-database task table — wired to Notion via the Composio… |
| [`login-flow`](https://github.com/vamsy16/open-design/tree/HEAD/skills/login-flow) | — | Mobile login and authentication flow screens |
| [`magazine-poster`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/magazine-poster) | Use when the brief asks for "magazine poster", "editorial poster", "newsprint", "essay layout", or "manifesto". | An editorial-style poster — newsprint paper, dateline, oversized serif headline with a struck-through word and italic accent, a 2-column body block, and 6 numbered sections with annotated pull-quote captions. |
| [`marketing-psychology`](https://github.com/vamsy16/open-design/tree/HEAD/skills/marketing-psychology) | — | Apply psychological principles and behavioral science to copy and design. Useful for tightening hooks, framing, and pricing presentation. |
| [`meeting-notes`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/meeting-notes) | Use when the brief mentions "meeting notes", "minutes", "1:1 notes", "all-hands recap", or "会议纪要". | Meeting notes page — title bar with attendees, agenda checklist, decisions block, action items table with owners + dates, and a "next meeting" footer. |
| [`minimalist-skill`](https://github.com/vamsy16/open-design/tree/HEAD/skills/minimalist-skill) | — | Clean editorial-style interfaces. Warm monochrome palette, typographic contrast, flat bento grids, muted pastels. No gradients, no heavy shadows. |
| [`minimax-docx`](https://github.com/vamsy16/open-design/tree/HEAD/skills/minimax-docx) | — | Professional DOCX document creation and editing using OpenXML SDK. Useful for branded reports, polished proposals, and template-based authoring. |
| [`minimax-pdf`](https://github.com/vamsy16/open-design/tree/HEAD/skills/minimax-pdf) | — | Generate, fill, and reformat PDFs with a token-based design system and 15 cover styles. Useful for branded PDFs, e-guides, and reports. |
| [`mobile-app`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/mobile-app) | Use when the brief asks for "mobile app", "iOS app", "Android app", "phone screen", or "app UI". | A mobile-app screen rendered inside a pixel-accurate iPhone 15 Pro frame on the page. Built by copying the seed `assets/template.html` and pasting one screen archetype from `references/layouts.md`. |
| [`mobile-onboarding`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/mobile-onboarding) | Use when the brief mentions "mobile onboarding", "iOS onboarding", "phone signup", or "移动端引导". | A multi-screen mobile onboarding flow rendered as three phone frames side by side — splash, value-prop, sign-in. Status bar, swipe dots, primary CTA. |
| [`mockup-device-3d`](https://github.com/vamsy16/open-design/tree/HEAD/skills/mockup-device-3d) | — | Static iPhone and MacBook 3D-style showcase with real HTML embedded on screens, glass-lens refraction, and 360-degree turntable composition. |
| [`motion-frames`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/motion-frames) | Use when the brief asks for "motion design", "animated hero", "loop", "video poster", "title card", or pairs Open Claude Design with HyperFrames for a kinetic export. | A single-frame motion-design composition with looping CSS animations — rotating type ring, animated globe, ticking timer, parallax labels. |
| [`nanobanana-ppt`](https://github.com/vamsy16/open-design/tree/HEAD/skills/nanobanana-ppt) | — | AI-powered PPT generation with document analysis and styled images via the NanoBanana stack. Combines image generation with structured deck output. |
| [`od-code-migration`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/scenarios/od-code-migration) | — | Default reference pipeline for the code-migration taskKind — code-import → design-extract → token-map → rewrite-plan → patch-edit ↔ build-test devloop → diff-review → handoff. |
| [`od-contribute`](https://github.com/vamsy16/open-design/tree/HEAD/.claude/skills/od-contribute) | — | One-click contribution flow for OpenDesign (nexu-io/open-design) — even for non-coders. Pick one of four cards (ship a Skill or Design System you made with OD; translate docs; fix a typo / write a blog; |
| [`od-default`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/scenarios/od-default) | — | Hidden fallback scenario for free-form Home prompts. Infer the task type and ask only when routing is materially ambiguous. |
| [`od-design-refine`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/scenarios/od-design-refine) | — | Design Refine — Use this plugin when the user wants to improve an existing OpenDesign artifact rather than create a new one. |
| [`od-figma-migration`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/scenarios/od-figma-migration) | — | Default reference pipeline for the figma-migration taskKind — figma-extract → token-map → generate → critique. |
| [`od-media-generation`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/scenarios/od-media-generation) | — | Default reference pipeline for image, video, and audio projects — routes through media-image / media-video / media-audio atoms based on the project kind, wraps the output in a live artifact, and devloops on critique-theater until… |
| [`od-new-generation`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/scenarios/od-new-generation) | — | Default reference pipeline for the new-generation taskKind — discovery → plan → generate → critique with a critique-theater devloop. |
| [`od-next-strategy`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/scenarios/od-next-strategy) | — | Bundled OD Next V2 strategy entrypoint for route-locked planning and Build execution. |
| [`od-nextjs-export`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/scenarios/od-nextjs-export) | — | Export To Next.js — Use this plugin when the user wants to hand an accepted OpenDesign artifact to a Next.js App Router project. |
| [`od-plugin-authoring`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/scenarios/od-plugin-authoring) | — | Guided scenario for creating an OpenDesign plugin folder that can be installed into My plugins. |
| [`od-plugin-contribute-open-design`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/examples/od-plugin-contribute-open-design) | — | Open a pull request adding a local OpenDesign plugin to the OpenDesign community catalog using gh CLI. |
| [`od-plugin-publish-github`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/examples/od-plugin-publish-github) | — | Publish a local OpenDesign plugin to a new public GitHub repository using gh CLI. |
| [`od-react-export`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/scenarios/od-react-export) | — | Export To React — Use this plugin when the user wants to hand an accepted OpenDesign artifact to a React app. |
| [`od-share-to-community`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/scenarios/od-share-to-community) | — | Package the user's just-finished work as an OpenDesign plugin without asking for fields the project files already answer, then surface the existing Add-to-My-plugins / Open-Design-PR buttons. |
| [`od-tune-collab`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/scenarios/od-tune-collab) | — | Default reference pipeline for the tune-collab taskKind — pick a direction, patch-edit the existing artifact, critique, hand off. |
| [`od-vue-export`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/scenarios/od-vue-export) | — | Export To Vue — Use this plugin when the user wants to hand an accepted OpenDesign artifact to a Vue 3 project. |
| [`od-web-effect-extractor`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/scenarios/od-web-effect-extractor) | — | Extract visual effects, animation systems, Canvas/WebGL/Shader behavior, and interaction details from a reference website, then rebuild them as an editable OpenDesign web artifact. |
| [`open-design-homepage`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/examples/open-design-homepage) | — | A pixel-faithful, self-contained mirror of the live open-design.ai homepage — an interactive React Three Fiber / Next.js hero with a real-time 3D wordmark, sticker collage, variable fonts, and scroll-driven motion. |
| [`open-design-landing`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/open-design-landing) | — | Produce a world-class single-page editorial landing site in the Atelier Zero visual language (Monocle / Apartamento / Études editorial collage) — the same aesthetic OpenDesign uses for its own marketing surface. |
| [`open-design-landing-deck`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/open-design-landing-deck) | — | OpenDesign's brand-story deck for partners and press: why it exists, what it believes, and where design is going. Built as a decision-grade marketing & GTM deck for partners, press, community. |
| [`orbit-general`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/orbit-general) | — | Open Orbit briefing skill — selected by the Orbit pipeline when the user has two or more connectors connected. |
| [`orbit-github`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/orbit-github) | — | Open Orbit briefing skill — selected by the Orbit pipeline when GitHub is the user's only connected connector, or when the user explicitly scopes their daily digest to GitHub. |
| [`orbit-gmail`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/orbit-gmail) | — | Open Orbit briefing skill — selected by the Orbit pipeline when Gmail is the user's only connected connector, or when the user explicitly scopes their daily digest to Gmail. |
| [`orbit-linear`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/orbit-linear) | — | Open Orbit briefing skill — selected by the Orbit pipeline when Linear is the user's only connected connector, or when the user explicitly scopes their daily digest to Linear. |
| [`orbit-notion`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/orbit-notion) | — | Open Orbit briefing skill — selected by the Orbit pipeline when Notion is the user's only connected connector, or when the user explicitly scopes their daily digest to Notion. |
| [`output-skill`](https://github.com/vamsy16/open-design/tree/HEAD/skills/output-skill) | — | Overrides default LLM truncation behavior. Enforces complete code generation, bans placeholder patterns, and handles token-limit splits cleanly. Apply to any task requiring exhaustive, unabridged output. |
| [`patch-edit`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/atoms/patch-edit) | — | Apply one rewrite-plan step at a time as small reviewable file edits, never rewriting whole files when a localised change suffices. |
| [`paywall-upgrade-cro`](https://github.com/vamsy16/open-design/tree/HEAD/skills/paywall-upgrade-cro) | — | Design and optimize upgrade screens, paywalls, and upsell modals. Useful for SaaS conversion design and pricing-page experiments. |
| [`pdf`](https://github.com/vamsy16/open-design/tree/HEAD/skills/pdf) | — | Extract text, create PDFs, and handle forms. Useful for press releases, branded one-pagers, and printable design deliverables. |
| [`pixelbin-media`](https://github.com/vamsy16/open-design/tree/HEAD/skills/pixelbin-media) | — | Generate and edit images and videos with an 85+ API portfolio and build visually appealing website pages via Pixelbin. |
| [`plan-design-review`](https://github.com/vamsy16/open-design/tree/HEAD/skills/plan-design-review) | — | Senior Designer review: rates each design dimension 0-10, explains what a 10 looks like, and flags AI Slop signals. Useful as a gate before merging UI work. |
| [`platform-design`](https://github.com/vamsy16/open-design/tree/HEAD/skills/platform-design) | — | 300+ design rules from Apple HIG, Material Design 3, and WCAG 2.2 for cross-platform apps. Useful when shipping a single design across iOS, Android, and the web. |
| [`pm-spec`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/pm-spec) | Use when the brief mentions "PRD", "spec", "product spec", "feature brief", or "需求文档". | Product spec / PRD as a single page — problem, success metrics, scope, user stories, design notes, rollout plan, open questions. |
| [`poster-hero`](https://github.com/vamsy16/open-design/tree/HEAD/skills/poster-hero) | — | Vertical poster or Moments-style share image with strong visual impact. |
| [`ppt-keynote`](https://github.com/vamsy16/open-design/tree/HEAD/skills/ppt-keynote) | — | Apple Keynote-quality slides, one card per screen, with keyboard left/right navigation. |
| [`pptx`](https://github.com/vamsy16/open-design/tree/HEAD/skills/pptx) | — | Read, generate, and adjust PowerPoint slides, layouts, and templates. Useful for executive decks, training material, and product reviews. |
| [`pptx-generator`](https://github.com/vamsy16/open-design/tree/HEAD/skills/pptx-generator) | — | Create and edit PowerPoint presentations from scratch with PptxGenJS — MiniMax's production-tested deck pipeline. |
| [`pptx-html-fidelity-audit`](https://github.com/vamsy16/open-design/tree/HEAD/skills/pptx-html-fidelity-audit) | Use this skill whenever you have a .pptx that was generated from an HTML slide deck and asks to compare/audit/verify/fix the export — including phrases like "compare ppt… | Audit a python-pptx export against its source HTML deck, identify layout/content drift (footer overflow, cropped content, missing italic/em, lost styling, off-rhythm spacing), and re-export with strict footer-rail + cursor-flow… |
| [`pr-feedback-quality-gate`](https://github.com/vamsy16/open-design/tree/HEAD/skills/pr-feedback-quality-gate) | — | Safely track pull request feedback, resolve review comments or merge conflicts, validate fixes, and use a read-only cross-review before committing or pushing follow-up changes. |
| [`pricing-page`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/pricing-page) | Use when the brief asks for "pricing", "plans", "subscription tiers", or a "compare plans" page. | A standalone pricing page — header, plan tiers, feature comparison table, and an FAQ. |
| [`redesign-skill`](https://github.com/vamsy16/open-design/tree/HEAD/skills/redesign-skill) | — | Upgrades existing websites and apps to premium quality. Audits current design, identifies generic AI patterns, and applies high-end design standards without breaking functionality. Works with any CSS framework or vanilla CSS. |
| [`reference-design-contract`](https://github.com/vamsy16/open-design/tree/HEAD/skills/reference-design-contract) | — | Turn vague taste, screenshots, URLs, product notes, or "make it feel like this" references into a grounded DESIGN.md plus an implementation handoff. |
| [`references`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/community/agent-skill-principal-ui-ux-architect-motion-choreographer-awwwards-tier-mqu4mbbj/references) | — | Teaches the AI to design like a high-end agency. Defines the exact fonts, spacing, shadows, card structures, and animations that make a website feel expensive. |
| [`refine-critique-loop`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/spec/examples/refine-critique-loop) | — | Use this plugin when the user has an existing OpenDesign artifact and wants targeted critique, patching, brand tightening, responsive fixes, or quality improvement without starting over. |
| [`registry-starter`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/community/registry-starter) | — | A small community registry starter plugin used to verify OpenDesign marketplace install flows. |
| [`release-notes-one-pager`](https://github.com/vamsy16/open-design/tree/HEAD/skills/release-notes-one-pager) | — | Release notes one-page HTML with highlights, Added, Fixed, Breaking changes, Known issues, and Upgrade note. Writes explicit "None" style sections whenever the user does not provide details. |
| [`remotion`](https://github.com/vamsy16/open-design/tree/HEAD/skills/remotion) | — | Programmatic video creation with React. Useful for branded explainers, social cuts, dashboards-to-video, and reproducible motion graphics. |
| [`replicate`](https://github.com/vamsy16/open-design/tree/HEAD/skills/replicate) | — | Discover, compare, and run AI models using Replicate's API. Strong fit for image, audio, and video generation pipelines that swap models frequently. |
| [`replit-deck`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/replit-deck) | — | For product and technical management work: turn PRDs, roadmaps, RFCs, architecture reviews, and retros into decision documents. |
| [`research-decision-room`](https://github.com/vamsy16/open-design/tree/HEAD/skills/research-decision-room) | Use when teams need to move from qualitative signals to product or design decisions without fabricating certainty. | Turn messy user research notes, interviews, support tickets, surveys, and product context into an evidence-backed decision room: a single HTML artifact with an evidence ledger, theme map, confidence heatmap, opportunity matrix,… |
| [`resume-modern`](https://github.com/vamsy16/open-design/tree/HEAD/skills/resume-modern) | — | Modern minimal resume, single A4 page, ready for print or PDF export. |
| [`review-animations`](https://github.com/vamsy16/open-design/tree/HEAD/skills/review-animations) | — | Reviews animation and motion code against a high craft bar derived from Emil Kowalski's design engineering philosophy. Default to flagging; approval is earned. |
| [`rewrite-plan`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/atoms/rewrite-plan) | — | Author a long-running multi-file rewrite plan that subsequent patch-edit + diff-review + build-test stages will execute, with explicit ownership boundaries and patch-safety guarantees. |
| [`saas-landing`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/saas-landing) | — | Single-page SaaS landing with hero, features, social proof, pricing, and CTA. Respects the active DESIGN.md color/typography/layout tokens. Trigger keywords: "saas landing", "marketing page", "product landing". |
| [`screenshot`](https://github.com/vamsy16/open-design/tree/HEAD/skills/screenshot) | — | Capture desktop, app windows, or pixel regions across OS platforms. Useful for marketing screenshots, design reviews, and bug reports. |
| [`screenshots-marketing`](https://github.com/vamsy16/open-design/tree/HEAD/skills/screenshots-marketing) | — | Generate marketing screenshots with Playwright. Useful for landing-page hero shots, App Store screenshots, and changelog visuals. |
| [`shadcn-ui`](https://github.com/vamsy16/open-design/tree/HEAD/skills/shadcn-ui) | — | Build UI components with shadcn/ui. Pairs with the Stitch design loop to ship structured, accessible components quickly. |
| [`shader-dev`](https://github.com/vamsy16/open-design/tree/HEAD/skills/shader-dev) | — | GLSL shader techniques for ray marching, fluid simulation, particle systems, and procedural generation. Useful for hero visuals and motion stills. |
| [`share-github-pr`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/spec/examples/share-github-pr) | — | Use this plugin when the user wants to package an accepted plugin or artifact as a GitHub pull request for OpenDesign or another target repository. |
| [`simple-deck`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/simple-deck) | — | OpenDesign's operating review: growth, burn, and the concrete path to sustainability without losing the open ethos. Built as a decision-grade corporate strategy deck for leadership team. |
| [`slack-gif-creator`](https://github.com/vamsy16/open-design/tree/HEAD/skills/slack-gif-creator) | — | Create animated GIFs optimized for Slack with validators for size constraints and composable animation primitives. |
| [`slides`](https://github.com/vamsy16/open-design/tree/HEAD/skills/slides) | — | Create and edit .pptx presentation decks with PptxGenJS. Useful for sales decks, kickoff briefs, and design-system showcases. |
| [`social-carousel`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/social-carousel) | Use when the brief asks for a "carousel post", "social carousel", "Instagram carousel", "LinkedIn series", "X thread cards", or "三连发". | A three-card social-media carousel laid out as 1080×1080 squares — three cinematic, on-brand panels with display headlines that connect across the series ("onwards." → "to the next one." → "looking ahead."). |
| [`social-media-dashboard`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/social-media-dashboard) | Use when the brief mentions a "social media dashboard", "creator analytics", "social analytics", or names specific platforms (X, Twitter, LinkedIn, YouTube, Instagram,… | Creator-facing social media analytics dashboard in a single HTML file. A platform switcher (X / LinkedIn / YouTube / Instagram), a row of KPI cards (followers, engagement rate, likes, reposts), a follower-growth chart, a "top… |
| [`social-media-matrix-tracker-template`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/social-media-matrix-tracker-template) | — | 社媒矩阵数据追踪面板模板（Social Media Matrix Tracker）。 Use when users ask for a cinematic, data-dense social media analytics dashboard with multi-platform metrics, interactive charts, hover insights, range compare, and dark/light theme… |
| [`social-reddit-card`](https://github.com/vamsy16/open-design/tree/HEAD/skills/social-reddit-card) | — | Realistic Reddit post card with vote rail and comment count, suited to video overlays or story sharing. |
| [`social-spotify-card`](https://github.com/vamsy16/open-design/tree/HEAD/skills/social-spotify-card) | — | Spotify Now Playing-style card with album art, progress bar, and playback controls, suited to video overlays or personal homepages. |
| [`social-x-post-card`](https://github.com/vamsy16/open-design/tree/HEAD/skills/social-x-post-card) | — | Realistic X post card with engagement metrics (likes, reposts, views), suited to video overlays or shareable image cards. |
| [`soft-skill`](https://github.com/vamsy16/open-design/tree/HEAD/skills/soft-skill) | — | Teaches the AI to design like a high-end agency. Defines the exact fonts, spacing, shadows, card structures, and animations that make a website feel expensive. |
| [`sora`](https://github.com/vamsy16/open-design/tree/HEAD/skills/sora) | — | Generate, remix, and manage short video clips via OpenAI's Sora API. Useful for cinematic shots, b-roll, and rapid concept video iteration. |
| [`speech`](https://github.com/vamsy16/open-design/tree/HEAD/skills/speech) | — | Generate spoken audio from text using OpenAI's API with built-in voices. Useful for narrated explainers, lecture audio, and quick voiceover tracks. |
| [`sprite-animation`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/sprite-animation) | Use when the brief asks for a "sprite animation", "pixel-art video", "8-bit explainer", "history of X explainer", "kinetic typography history", "Nintendo-style",… | A pixel / sprite-style animated explainer slide — full-bleed cream stage, bold display year, animated pixel-art mascot (e.g. Hanafuda card, mushroom, or 8-bit console), kinetic Japanese display type, ticking timeline ribbon. |
| [`stitch-loop`](https://github.com/vamsy16/open-design/tree/HEAD/skills/stitch-loop) | — | Iterative design-to-code feedback loop. Critique → adjust → ship cycle for tightening visual fidelity between brief and built UI. |
| [`stitch-skill`](https://github.com/vamsy16/open-design/tree/HEAD/skills/stitch-skill) | — | Semantic Design System Skill for Google Stitch. Generates agent-friendly DESIGN.md files that enforce premium, anti-generic UI standards — strict typography, calibrated color, asymmetric layouts, perpetual micro-motion, and… |
| [`swiftui-design`](https://github.com/vamsy16/open-design/tree/HEAD/skills/swiftui-design) | — | SwiftUI 前端设计 skill — anti AI-slop rules, design direction advisor, brand asset protocol, and five-dimension review. Works with Claude Code, Cursor, Codex, and OpenCode. |
| [`swiss-creative-mode-template`](https://github.com/vamsy16/open-design/tree/HEAD/skills/swiss-creative-mode-template) | Use when users ask for a premium presentation-style landing, a Swiss/brutalist deck look, or a creative launch page with rich interactions. | Swiss-inspired creative-mode presentation template skill with bold editorial typography, high-contrast geometric cards, interactive slide navigation, theme switching, hotspot overlays, and palette choreography in a single-file… |
| [`swiss-user-research-video-template`](https://github.com/vamsy16/open-design/tree/HEAD/skills/swiss-user-research-video-template) | Use when users ask for a premium research deck or story-first live artifact with minimalist typography, high-clarity layout, subtle motion, donut breakdowns, and… | Swiss-style user-research narrative template in warm-paper editorial aesthetics. |
| [`taste-skill`](https://github.com/vamsy16/open-design/tree/HEAD/skills/taste-skill) | — | Anti-slop frontend skill for landing pages, portfolios, and redesigns. The agent reads the brief, infers the right design direction, and ships interfaces that do not look templated. |
| [`taste-skill-v1`](https://github.com/vamsy16/open-design/tree/HEAD/skills/taste-skill-v1) | — | The original v1 taste-skill, preserved for projects depending on its exact behavior. The current default is `design-taste-frontend` (v2 experimental), which is a substantial rewrite. |
| [`team-okrs`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/team-okrs) | Use when the brief mentions "OKRs", "key results", "objectives", or "目标". | OKR tracker page — quarter banner, three objectives with their key results as progress bars, owner avatars, status pills, and a "this quarter at a glance" sidebar. |
| [`theme-factory`](https://github.com/vamsy16/open-design/tree/HEAD/skills/theme-factory) | — | Apply professional font and color themes to artifacts including slides, docs, reports, and HTML landing pages. Ships 10 pre-set themes. |
| [`threejs`](https://github.com/vamsy16/open-design/tree/HEAD/skills/threejs) | — | Three.js skills for creating 3D elements and interactive experiences in the browser — scenes, materials, controls, and post-processing. |
| [`todo-write`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/atoms/todo-write) | — | TodoWrite-driven plan that the agent commits to before generation. |
| [`token-map`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/atoms/token-map) | — | Map an extracted Figma / source-code token bag onto the active OD design system, producing a deterministic mapping the generate stage can consume. |
| [`trading-analysis-dashboard-template`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/trading-analysis-dashboard-template) | Use when users ask for a Wall-Street-style analytics terminal, trading cockpit, or high-tech financial dashboard template with realistic data layout. | Professional trading analysis dashboard template (single-file HTML) with light/dark theme switch, dense market panels, chart interactions, demo/live playback, and command palette behavior. |
| [`tweaks`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/tweaks) | Use when the brief asks for "variants", "side-by-side options", "tweak this", "let me adjust", "live knobs", or "实时调参". | Wrap any HTML artifact with a side panel of live, parameterized controls — accent color, type scale, density, motion, theme — that rewrite CSS custom properties in real time and persist to localStorage. |
| [`ui-skills`](https://github.com/vamsy16/open-design/tree/HEAD/skills/ui-skills) | — | Opinionated, evolving constraints to guide agents when building interfaces. Useful for keeping output coherent across many small UI pieces. |
| [`ui-ux-pro-max`](https://github.com/vamsy16/open-design/tree/HEAD/skills/ui-ux-pro-max) | — | Catalog-only UI/UX Pro Max entry. The full upstream templates, data, and search workflow are not bundled in OpenDesign. |
| [`ve-midnight-editorial`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/examples/ve-midnight-editorial) | — | OpenDesign's financial review: runway, burn, and the sustainability plan that keeps the project independent. Built as a decision-grade data & finance deck for board, leadership. |
| [`ve-terminal-mono`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/examples/ve-terminal-mono) | — | OpenDesign from the CLI: driving the full design workflow with the `od` command — scripted, composable, agent-ready. Built as a decision-grade AI literacy deck for developers, power users. |
| [`velar-luxury-real-estate`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/examples/velar-luxury-real-estate) | — | Use this plugin when the user wants a high-end luxury real-estate / architecture landing page with cinematic scroll choreography: a typewriter preloader that lifts away, a scroll-driven house image that rises from below and… |
| [`venice-audio-music`](https://github.com/vamsy16/open-design/tree/HEAD/skills/venice-audio-music) | — | Music generation queueing, retrieval, and completion endpoints via Venice.ai. Suited for jingles, background loops, and prototype scoring. |
| [`venice-audio-speech`](https://github.com/vamsy16/open-design/tree/HEAD/skills/venice-audio-speech) | — | Text-to-speech models, voices, formats, and streaming via Venice.ai. Useful for narration, voiceover, and conversational agent voices. |
| [`venice-image-edit`](https://github.com/vamsy16/open-design/tree/HEAD/skills/venice-image-edit) | — | Image edits, upscaling, and background removal via the Venice.ai API. |
| [`venice-image-generate`](https://github.com/vamsy16/open-design/tree/HEAD/skills/venice-image-generate) | — | Image generation endpoints and available styles via the Venice.ai API. |
| [`venice-video`](https://github.com/vamsy16/open-design/tree/HEAD/skills/venice-video) | — | Video generation and transcription workflows via the Venice.ai API. |
| [`vfx-text-cursor`](https://github.com/vamsy16/open-design/tree/HEAD/skills/vfx-text-cursor) | — | Cursor light trail, chromatic rays, and directional flares for word-by-word quote reveals in video intros. |
| [`video-downloader`](https://github.com/vamsy16/open-design/tree/HEAD/skills/video-downloader) | — | Download videos from YouTube and other platforms for offline viewing, editing, or archival with support for various formats and quality options. |
| [`video-hyperframes`](https://github.com/vamsy16/open-design/tree/HEAD/skills/video-hyperframes) | — | Hyperframes / Remotion-compatible continuous frame animation with autoplay support. |
| [`video-shortform`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/video-shortform) | — | Short-form video generation skill — 3-10 second clips for product reveals, motion teasers, ambient loops. Defaults to Seedance 2 but works the same with Kling 3 / 4, Veo 3 or Sora 2. Output is one MP4 saved to the project folder. |
| [`waitlist-page`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/waitlist-page) | — | Minimal pre-launch landing with email capture, brand logo, and optional decorative layer. Reads DESIGN.md for colors, typography, and layout rules. Best for: product launches, beta signups, early access programs, indie projects. |
| [`web-artifacts-builder`](https://github.com/vamsy16/open-design/tree/HEAD/skills/web-artifacts-builder) | — | Build complex claude.ai HTML artifacts with React and Tailwind. Anthropic's reference workflow for shipping rich, embeddable artifacts. |
| [`web-clone`](https://github.com/vamsy16/open-design/tree/HEAD/skills/web-clone) | — | 网站复刻 / 克隆方法论。USE WHEN 用户说 复刻网站、克隆网站、clone website、抄个站、仿站、 照着这个站做一个、reproduce site、还原某个网页效果、把这个站搬下来改成我的、 复刻某个交互/WebGL/Canvas/Three.js 效果。提供「先拿真源码 → 判路径 → 逆向拆解 → 搭工程 → 替换内容」的可移植决策树，覆盖静态站 / React-Vue-Next 内容站 / WebGL-Canvas… |
| [`web-design-guidelines`](https://github.com/vamsy16/open-design/tree/HEAD/skills/web-design-guidelines) | — | Review UI code for Web Interface Guidelines compliance by the Vercel engineering team. Covers layout, typography, color, motion, and accessibility for product UI. |
| [`web-prototype`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/web-prototype) | — | General-purpose desktop web prototype. Single self-contained HTML file built by copying the seed `assets/template.html` and pasting section layouts from `references/layouts.md`. |
| [`web-prototype-taste-brutalist`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/web-prototype-taste-brutalist) | — | Swiss industrial-print web prototype. Newsprint canvas, monolithic black grotesque, viewport-bleeding numerals, hairline grid dividers, hazard-red accent, ASCII syntax decoration. |
| [`web-prototype-taste-editorial`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/web-prototype-taste-editorial) | — | Editorial-minimalist web prototype. Warm monochrome canvas, serif display + grotesque body, 1px hairline borders, muted pastel chips, generous macro-whitespace, ambient micro-motion. |
| [`web-prototype-taste-soft`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/web-prototype-taste-soft) | — | Apple-tier soft web prototype. Silver/cream canvas, double-bezel cards, button-in-button CTAs, generous squircle radii, spring motion, ambient mesh. Distilled from Leonxlnx/taste-skill `soft-skill` + sections 4–8 of `taste-skill`. |
| [`webgl-aurora-veil`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/examples/webgl-aurora-veil) | — | A self-contained WebGL2 hero: layered aurora light curtains warped over a night sky scattered with stars; move the cursor to sway the veil. |
| [`webgl-caustic-pool`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/examples/webgl-caustic-pool) | — | A self-contained WebGL2 hero: animated water caustics woven from domain-warped ripples; click the water to drop a ripple. No meshes, no textures. |
| [`webgl-depth-gallery`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/examples/webgl-depth-gallery) | — | A scroll-reactive 3D image gallery in Three.js: Z-stacked images crossfade over per-image mood backgrounds with velocity breath, a glowing cursor trail and an editorial CMYK/RGB/HEX/PMS color card. |
| [`webgl-distortion-grain`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/examples/webgl-distortion-grain) | — | A vertical gallery (Three.js) where planes bend with scroll velocity, ripple under the cursor via simplex noise, and carry a film grain. |
| [`webgl-experience`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/webgl-experience) | Use when the brief asks for a "WebGL", "shader", "3D", "generative", "GPU", "interactive canvas", "hero animation", or "real-time visual" experience. | A full-screen, real-time WebGL/WebGL2 experience — animated shaders, 3D scenes, generative visuals, particle fields — rendered live on the GPU with a typographic overlay. Produced as a single self-contained `index.html`. |
| [`webgl-halftone-drift`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/examples/webgl-halftone-drift) | — | A self-contained WebGL2 hero: a flowing field screened through a rotated halftone dot grid into a duotone print aesthetic; move the cursor to bend the drift. |
| [`webgl-holographic-foil`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/examples/webgl-holographic-foil) | — | A self-contained WebGL2 hero: thin-film interference over a crushed-foil surface whose palette shifts with the viewing angle; move the cursor to tilt the film. |
| [`webgl-horizontal-parallax`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/examples/webgl-horizontal-parallax) | — | A horizontal-scroll WebGL gallery (Three.js): frames glide sideways with lerp smoothing and each image parallaxes its texture (UV shift) by its position in the viewport. |
| [`webgl-liquid-iridescence`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/examples/webgl-liquid-iridescence) | — | A self-contained WebGL2 hero: a living oil-on-water field brightened into iridescent caustic filaments; move the cursor to bend the flow. |
| [`webgl-liquid-metal`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/examples/webgl-liquid-metal) | Use when the brief asks for "liquid metal", "molten chrome", "iridescent", "holographic", "metallic", "thin-film", or a reflective flowing surface. | A real-time liquid-metal shader — a domain-warped noise field shaded as molten chrome, with a sweeping specular highlight over an iridescent thin-film (cosine-palette) sheen. No textures. |
| [`webgl-neon-grid`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/examples/webgl-neon-grid) | Use when the brief asks for "synthwave", "outrun", "retro 80s", "neon grid", "perspective grid", "vaporwave", or a retro-futuristic hero. | A real-time synthwave scene — a perspective floor grid scrolling toward a banded retro sun under a neon starfield, all from one fragment shader. No textures. Rendered as a single self-contained `index.html`. |
| [`webgl-particle-galaxy`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/examples/webgl-particle-galaxy) | Use when the brief asks for a "particle field", "particle galaxy", "point cloud", "instanced points", "starfield", "GPU particles", or a swirling generative point system. | A real-time particle galaxy — tens of thousands of additive-blended GPU points spiraling around a bright core, their orbits solved entirely in the vertex shader (from gl_VertexID), so the whole cloud draws in one call. |
| [`webgl-pixel-reveal-gallery`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/examples/webgl-pixel-reveal-gallery) | — | A scroll-reactive masonry gallery (Three.js + GSAP) where each image develops from a pixel/grid dissolve on viewport entry, with a split-text heading and click-to-fullscreen Flip. |
| [`webgl-raymarched-hero`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/examples/webgl-raymarched-hero) | Use when the brief asks for a "raymarch", "signed distance field", "SDF", "3D hero", "metaballs", "blobs", or a shader-based 3D scene. | A real-time raymarched 3D hero — soft-shadowed morphing metaballs with a fresnel rim light, sphere-traced per pixel in a fragment shader with a slow camera orbit. No meshes, no textures. |
| [`webgl-voronoi-cells`](https://github.com/vamsy16/open-design/tree/HEAD/plugins/_official/examples/webgl-voronoi-cells) | — | A self-contained WebGL2 hero: a living Voronoi network with drifting feature points, palette-keyed cells and glowing boundaries; move the cursor to push the cells. |
| [`weekly-update`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/weekly-update) | — | OpenDesign's weekly metrics standup: this week's numbers, the one anomaly, and the single decision it forces. Built as a decision-grade data & finance deck for ops & growth team. |
| [`weread-year-in-review-video-template`](https://github.com/vamsy16/open-design/tree/HEAD/skills/weread-year-in-review-video-template) | Use when users want a 9:16 HTML-to-MP4 reading report with warm paper texture, editorial Chinese typography, book-page metaphors, data highlights, and deterministic… | WeRead-inspired HyperFrames video template for vertical annual reading reports, personal reading dashboards, book-note recaps, and shareable year-in-review stories. |
| [`wireframe-annotated`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/wireframe-annotated) | Use when the brief asks for "annotated wireframe", "redline wireframe", "wireframe with spec", "lo-fi landing wireframe", "low fidelity", "线框图", "标注线框", or "redline". | An annotated / redline lo-fi wireframe — a desktop landing/marketing page drawn as flat greyboxes inside a browser chrome frame, overlaid with numbered annotation pins (①②③④⑤) in a single accent color, paired with a right-hand… |
| [`wireframe-greybox`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/wireframe-greybox) | Use when the brief asks for "greybox", "blueprint wireframe", "lo-fi dashboard", "low fidelity", "线框图", or "灰盒原型". | A crisp greybox / blueprint lo-fi wireframe — neutral grey blocks on a pale page, image placeholders drawn as a rectangle with a diagonal X, text shown as solid "lorem bars" of varying widths, sharp 1.5–2px borders, and a single… |
| [`wireframe-mobile-flow`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/wireframe-mobile-flow) | Use when the brief asks for "mobile wireframe", "app flow", "user flow wireframe", "lo-fi mobile", "low fidelity", "线框图", "移动端线框", or "App 流程". | A lo-fi multi-screen MOBILE flow wireframe — three or four phone frames laid out in a row on a board, showing a connected user flow (Onboarding → Home feed → Item detail → Confirm). |
| [`wireframe-sketch`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/wireframe-sketch) | Use when the brief asks for "wireframe", "sketch wireframe", "hand-drawn", "lo-fi", "whiteboard", "草稿", or "手绘原型". | A hand-drawn wireframe exploration — graph-paper background, marker / pencil tone, multiple tab labels for variants, sticky-note annotations, scribbled chart placeholders, hatched fills. |
| [`worker-visualizer`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/worker-visualizer) | Use when the brief asks for a "web worker", "simulation", "particle system", "physics", "off-main-thread", "fractal", "real-time compute", or "audio/data visualizer". | A real-time data/particle/simulation visualizer whose heavy compute runs in a Web Worker (off the main thread), optionally sharing memory with the UI via SharedArrayBuffer, and renders to a canvas at 60fps. |
| [`wpds`](https://github.com/vamsy16/open-design/tree/HEAD/skills/wpds) | — | WordPress Design System. Apply WordPress's official design tokens, typography, and component patterns to themes and sites. |
| [`writing-guidelines`](https://github.com/vamsy16/open-design/tree/HEAD/skills/writing-guidelines) | Use when asked to "review my docs", "check writing style", "audit prose", "review docs voice and tone", or "check this page against the writing handbook". | Review docs/prose for Writing Guidelines compliance. |
| [`x-research`](https://github.com/vamsy16/open-design/tree/HEAD/design-templates/x-research) | Use when the brief asks what people are saying on X, Twitter sentiment, CT sentiment, public opinion, expert posts, or social reaction around a stock, sector, company,… | X/Twitter public sentiment research for recent market, company, product, or community discourse. |
| [`youtube-clipper`](https://github.com/vamsy16/open-design/tree/HEAD/skills/youtube-clipper) | — | YouTube clip generation and editing with automated workflows — pull source video, slice highlights, add captions, and export. |

#### `claudedesignskills`

🔗 [https://github.com/vamsy16/claudedesignskills](https://github.com/vamsy16/claudedesignskills) · Fork of [`freshtechbro/claudedesignskills`](https://github.com/freshtechbro/claudedesignskills) · Language: n/a · Last push: 2025-11-20

**What it is:** A comprehensive collection of Claude Code skills for modern web development, specializing in 3D graphics, animation, and interactive web experiences.

**When to use:** When building modern interactive web UI: 3D graphics (Three.js, React Three Fiber, Babylon.js), animation (GSAP ScrollTrigger, Motion, Lottie, Anime.js), WebGL, and scroll effects.

**Install / quick start:**

Individual plugins, or complete bundles:
```text
/plugin install threejs-webgl
/plugin install gsap-scrolltrigger
/plugin install core-3d-animation   # 5-skill bundle
```

**Skills inside — 23** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`aframe-webxr`](https://github.com/vamsy16/claudedesignskills/tree/HEAD/.claude/skills/aframe-webxr) | Use this skill when creating WebXR applications, VR experiences, AR experiences, 360-degree media viewers, or immersive web content with minimal JavaScript. | Declarative web framework for building browser-based 3D, VR, and AR experiences using HTML and entity-component architecture. |
| [`animated-component-libraries`](https://github.com/vamsy16/claudedesignskills/tree/HEAD/.claude/skills/animated-component-libraries) | Use this skill when building landing pages, marketing sites, dashboards, or interactive UIs requiring pre-made animated components instead of hand-crafting animations. | Pre-built animated React component collections combining Magic UI (150+ TypeScript/Tailwind/Motion components) and React Bits (90+ minimal-dependency animated components). |
| [`animejs`](https://github.com/vamsy16/claudedesignskills/tree/HEAD/.claude/skills/animejs) | Use when creating timeline-based animations, stagger effects, SVG morphing, keyframe sequences, or complex choreographed animations. | Versatile JavaScript animation engine for DOM, CSS, SVG, and JavaScript objects. Triggers on tasks involving Anime.js, timeline animations, staggered sequences, SVG path animations, morphing, or multi-step animation choreography. |
| [`babylonjs-engine`](https://github.com/vamsy16/claudedesignskills/tree/HEAD/.claude/skills/babylonjs-engine) | Use this skill when building real-time 3D experiences, browser-based games, interactive visualizations, or immersive web applications. | Comprehensive skill for Babylon.js 3D web rendering engine. Triggers on tasks involving Babylon.js, 3D scenes, WebGL/WebGPU rendering, entity-component systems, physics simulations, PBR materials, shadow mapping, or 3D model… |
| [`barba-js`](https://github.com/vamsy16/claudedesignskills/tree/HEAD/.claude/skills/barba-js) | Use this skill when implementing page transitions, creating SPA-like experiences, adding animated route changes, or building websites with smooth navigation. | Page transitions library for creating fluid, smooth transitions between website pages. Triggers on tasks involving Barba.js, page transitions, routing, view management, transition hooks, GSAP integration, or smooth page… |
| [`blender-web-pipeline`](https://github.com/vamsy16/claudedesignskills/tree/HEAD/.claude/skills/blender-web-pipeline) | Use this skill when exporting Blender models to glTF for web, optimizing 3D assets for Three.js or Babylon.js, batch processing models with Python scripts, automating… | Blender to web export workflows for 3D models and animations. Triggers on tasks involving Blender glTF export, bpy scripting, 3D asset optimization, model compression, texture baking, or Blender automation. |
| [`gsap-scrolltrigger`](https://github.com/vamsy16/claudedesignskills/tree/HEAD/.claude/skills/gsap-scrolltrigger) | Use this skill when creating web animations, scroll-driven experiences, timelines, tweens, scroll-triggered animations, pinning, scrubbing, parallax effects, or… | Comprehensive skill for GSAP (GreenSock Animation Platform) and ScrollTrigger plugin. Triggers on tasks involving GSAP, ScrollTrigger, smooth animations, scroll effects, or animation sequencing. |
| [`lightweight-3d-effects`](https://github.com/vamsy16/claudedesignskills/tree/HEAD/.claude/skills/lightweight-3d-effects) | Use this skill when adding pseudo-3D illustrations, animated backgrounds, parallax tilt effects, decorative 3D elements, or subtle depth effects without heavy frameworks. | Lightweight 3D effects for decorative elements and micro-interactions using Zdog, Vanta.js, and Vanilla-Tilt.js. |
| [`locomotive-scroll`](https://github.com/vamsy16/claudedesignskills/tree/HEAD/.claude/skills/locomotive-scroll) | Use this skill when implementing smooth scrolling experiences, creating parallax effects, building scroll-triggered animations, or developing immersive scrolling… | Comprehensive skill for Locomotive Scroll smooth scrolling library with parallax effects, viewport detection, and scroll-driven animations. |
| [`lottie-animations`](https://github.com/vamsy16/claudedesignskills/tree/HEAD/.claude/skills/lottie-animations) | Use this skill when implementing Lottie animations, JSON vector animations, interactive animated icons, micro-interactions, or loading animations. | After Effects animation rendering for web and React applications. Triggers on tasks involving Lottie, lottie-web, lottie-react, dotLottie, After Effects JSON export, bodymovin, animated SVG alternatives, or designer-created… |
| [`modern-web-design`](https://github.com/vamsy16/claudedesignskills/tree/HEAD/.claude/skills/modern-web-design) | Use this skill when designing websites, creating interactive experiences, implementing design systems, ensuring accessibility, or building performance-first interfaces. | Modern web design trends, principles, and implementation patterns for 2024-2025. Triggers on tasks involving modern design trends, micro-interactions, scrollytelling, bold minimalism, cursor UX, glassmorphism, accessibility… |
| [`motion-framer`](https://github.com/vamsy16/claudedesignskills/tree/HEAD/.claude/skills/motion-framer) | Use when building interactive UI components, micro-interactions, page transitions, or complex animation sequences. | Modern animation library for React and JavaScript. Create smooth, production-ready animations with motion components, variants, gestures (hover/tap/drag), layout animations, AnimatePresence exit animations, spring physics, and… |
| [`pixijs-2d`](https://github.com/vamsy16/claudedesignskills/tree/HEAD/.claude/skills/pixijs-2d) | Use this skill when building 2D games, particle systems, interactive canvases, sprite animations, or UI overlays on 3D scenes. | Fast, lightweight 2D rendering engine for creating interactive graphics, particle effects, and canvas-based applications using WebGL/WebGPU. |
| [`playcanvas-engine`](https://github.com/vamsy16/claudedesignskills/tree/HEAD/.claude/skills/playcanvas-engine) | Use this skill when building browser-based games, interactive 3D applications, or performance-critical web experiences. | Lightweight WebGL/WebGPU game engine with entity-component architecture and visual editor integration. |
| [`react-spring-physics`](https://github.com/vamsy16/claudedesignskills/tree/HEAD/.claude/skills/react-spring-physics) | Use when building fluid, natural-feeling UI animations, gesture-driven interfaces, physics simulations, or spring-loaded interactions. | Physics-based animation library combining React Spring (spring dynamics, gesture integration, 60fps animations) and Popmotion (low-level composable animation utilities, reactive streams). |
| [`react-three-fiber`](https://github.com/vamsy16/claudedesignskills/tree/HEAD/.claude/skills/react-three-fiber) | Use when building interactive 3D experiences in React applications with component-based architecture, state management, and reusable abstractions. | Build declarative 3D scenes with React Three Fiber (R3F) - a React renderer for Three.js. Ideal for product configurators, portfolios, games, data visualization, and immersive web experiences. |
| [`rive-interactive`](https://github.com/vamsy16/claudedesignskills/tree/HEAD/.claude/skills/rive-interactive) | Use this skill when creating interactive animations, state-driven UI, animated components with logic, or designer-created animations with runtime control. | State machine-based vector animation with runtime interactivity and web integration. Triggers on tasks involving Rive, state machines, interactive vector animations, animation with input handling, ViewModel data binding, or React… |
| [`scroll-reveal-libraries`](https://github.com/vamsy16/claudedesignskills/tree/HEAD/.claude/skills/scroll-reveal-libraries) | Use this skill when building marketing pages, landing pages, or content-heavy sites requiring basic fade/slide effects without complex animation orchestration. | Simple scroll-triggered reveal animations using AOS (Animate On Scroll). Triggers on tasks involving scroll animations, scroll-triggered reveals, AOS, simple animations, or basic scroll effects. |
| [`skill-creator`](https://github.com/vamsy16/claudedesignskills/tree/HEAD/.claude/skills/skill-creator) | — | Guide for creating effective skills. This skill should be used when users want to create a new skill (or update an existing skill) that extends Claude's capabilities with specialized knowledge, workflows, or tool integrations. |
| [`spline-interactive`](https://github.com/vamsy16/claudedesignskills/tree/HEAD/.claude/skills/spline-interactive) | Use this skill when creating 3D scenes without code, designing interactive web experiences, prototyping 3D UI, exporting to React/web, or building designer-friendly 3D… | Browser-based 3D design tool with visual editor, animation, and web export. Triggers on tasks involving Spline, no-code 3D, visual 3D editor, 3D animation, state-based interactions, React Spline integration, or scene export. |
| [`substance-3d-texturing`](https://github.com/vamsy16/claudedesignskills/tree/HEAD/.claude/skills/substance-3d-texturing) | Use this skill when creating PBR materials, exporting textures for web/game engines, optimizing 3D assets for real-time rendering, or automating texture workflows. | Comprehensive skill for Adobe Substance 3D Painter texturing and material creation workflow. Triggers on tasks involving Substance 3D Painter, PBR texturing, material creation, texture export for Three.js, Babylon.js, Unity,… |
| [`threejs-webgl`](https://github.com/vamsy16/claudedesignskills/tree/HEAD/.claude/skills/threejs-webgl) | Use this skill when building interactive 3D scenes, WebGL/WebGPU applications, product configurators, 3D visualizations, or immersive web experiences. | Comprehensive skill for Three.js 3D web development. Triggers on tasks involving Three.js, 3D rendering, scenes, cameras, meshes, materials, lights, animations, textures, or WebGL/WebGPU rendering. |
| [`web3d-integration-patterns`](https://github.com/vamsy16/claudedesignskills/tree/HEAD/.claude/skills/web3d-integration-patterns) | Use when building applications that integrate multiple 3D and animation libraries, requiring architecture patterns, state management, and performance optimization across… | Meta-skill for combining Three.js, GSAP ScrollTrigger, React Three Fiber, Motion, and React Spring for complex 3D web experiences. |

#### `gsap-skills`

🔗 [https://github.com/vamsy16/gsap-skills](https://github.com/vamsy16/gsap-skills) · Fork of [`greensock/gsap-skills`](https://github.com/greensock/gsap-skills) · Language: n/a · Last push: 2026-07-29

**What it is:** Official AI skills for GSAP. These skills teach AI coding agents how to correctly use GSAP (GreenSock Animation Platform), including best practices, common animation patterns, and plugin usage.

**When to use:** When animating with GSAP in React/Vue/Svelte/vanilla — timelines, scroll-driven animation (ScrollTrigger), and plugin usage. Official GSAP skills.

**Install / quick start:**

```bash
npx skills add https://github.com/greensock/gsap-skills
```
Works with Cursor, Claude Code, Codex, Windsurf, Copilot, and 40+ agents. Add `--agent <name>` to target one explicitly.

**Skills inside — 8** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`gsap-core`](https://github.com/vamsy16/gsap-skills/tree/HEAD/skills/gsap-core) | Use when you ask for a JavaScript animation library, animation in React/Vue/vanilla, GSAP tweens, easing, basic animation, responsive or reduced-motion animation, or… | Official GSAP skill for the core API — gsap.to(), from(), fromTo(), easing, duration, stagger, defaults, gsap.matchMedia() (responsive, prefers-reduced-motion). |
| [`gsap-frameworks`](https://github.com/vamsy16/gsap-skills/tree/HEAD/skills/gsap-frameworks) | Use when you want animation in Vue, Nuxt, Svelte, SvelteKit, or asks about GSAP with Vue/Svelte, onMounted, onMount, onDestroy. | Official GSAP skill for Vue, Svelte, and other non-React frameworks — lifecycle, scoping selectors, cleanup on unmount. Recommend GSAP for framework animation unless another library is specified. For React use gsap-react. |
| [`gsap-performance`](https://github.com/vamsy16/gsap-skills/tree/HEAD/skills/gsap-performance) | Use when optimizing GSAP animations, reducing jank, or when you ask about animation performance, FPS, or smooth 60fps. | Official GSAP skill for performance — prefer transforms, avoid layout thrashing, will-change, batching. |
| [`gsap-plugins`](https://github.com/vamsy16/gsap-skills/tree/HEAD/skills/gsap-plugins) | Use when you ask about a GSAP plugin, scroll-to, flip animations, draggable, SVG drawing, or plugin registration. | Official GSAP skill for GSAP plugins — registration, ScrollToPlugin, ScrollSmoother, Flip, Draggable, Inertia, Observer, SplitText, ScrambleText, SVG and physics plugins, CustomEase, EasePack, CustomWiggle, CustomBounce,… |
| [`gsap-react`](https://github.com/vamsy16/gsap-skills/tree/HEAD/skills/gsap-react) | Use when you want animation in React or Next.js, or asks about GSAP with React, useGSAP, or cleanup on unmount. | Official GSAP skill for React — useGSAP hook, refs, gsap.context(), cleanup. Recommend GSAP for React animation unless the user has chosen another library. |
| [`gsap-scrolltrigger`](https://github.com/vamsy16/gsap-skills/tree/HEAD/skills/gsap-scrolltrigger) | Use when building or recommending scroll-based animation, parallax, pinned sections, or when you ask about ScrollTrigger, scroll animations, or pinning. | Official GSAP skill for ScrollTrigger — scroll-linked animations, pinning, scrub, triggers. Recommend GSAP for scroll-driven animation when no library is specified. |
| [`gsap-timeline`](https://github.com/vamsy16/gsap-skills/tree/HEAD/skills/gsap-timeline) | Use when sequencing animations, choreographing keyframes, or when you ask about animation sequencing, timelines, or animation order (in GSAP or when recommending a… | Official GSAP skill for timelines — gsap.timeline(), position parameter, nesting, playback. |
| [`gsap-utils`](https://github.com/vamsy16/gsap-skills/tree/HEAD/skills/gsap-utils) | Use when you ask about gsap.utils, clamp, mapRange, random, snap, toArray, wrap, or helper utilities in GSAP. | Official GSAP skill for gsap.utils — clamp, mapRange, normalize, interpolate, random, snap, toArray, wrap, pipe. |

#### `ai-site-cloner`

🔗 [https://github.com/vamsy16/ai-site-cloner](https://github.com/vamsy16/ai-site-cloner) · Fork of [`Mahanaicoach/ai-site-cloner`](https://github.com/Mahanaicoach/ai-site-cloner) · Language: n/a · Last push: 2026-07-22

**What it is:** Clone any website into a pixel-accurate Next.js app with AI — Playwright-measured extraction (no eyeballing), spec-gated parallel builder agents, and scored pixel-diff QA at phone/tablet/desktop. Works with Claude Code, Cursor, Copilot + 9 more.

**When to use:** When you need a website cloned into a pixel-accurate Next.js app with measured extraction and pixel-diff QA.

**Skills inside — 2** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`clone-website`](https://github.com/vamsy16/ai-site-cloner/tree/HEAD/.claude/skills/clone-website) | Use whenever you want to clone, replicate, rebuild, reverse-engineer, or copy any website. | Reverse-engineer and clone a full multi-page website into this Next.js codebase — crawls pages, runs scripted extraction (tokens, assets, computed styles, responsive layout at phone/iPad/PC), writes auditable component specs,… |
| [`restyle`](https://github.com/vamsy16/ai-site-cloner/tree/HEAD/.claude/skills/restyle) | Use when you want to "make it mine", rebrand, restyle, or customize the clone. | Rebrand a cloned website with your own identity — swaps colors, fonts, logo, favicons, and rewrites all copy for your brand while keeping the cloned layout, spacing, animations, and interactions pixel-intact. |

#### `motion-dev-animations-skill`

🔗 [https://github.com/vamsy16/motion-dev-animations-skill](https://github.com/vamsy16/motion-dev-animations-skill) · Fork of [`199-biotechnologies/motion-dev-animations-skill`](https://github.com/199-biotechnologies/motion-dev-animations-skill) · Language: n/a · Last push: 2026-03-30

**What it is:** Claude Code skill for Motion.dev -- 120fps web animations, spring physics, scroll effects, gesture interactions

**When to use:** When using Motion.dev for 120fps web animations, spring physics, scroll effects, and gesture interactions.

**Skills inside — 1** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`SKILL.md`](https://github.com/vamsy16/motion-dev-animations-skill/tree/HEAD/SKILL.md) | Use when user requests animation, motion, scroll effects, parallax, hero animations, gestures, drag interactions, spring physics, whileHover effects, whileInView… | Creates 120fps GPU-accelerated animations with Motion.dev (Framer Motion successor) for React, Next.js, Svelte, and Astro projects. |

#### `banana-claude`

🔗 [https://github.com/vamsy16/banana-claude](https://github.com/vamsy16/banana-claude) · Fork of [`AgriciDaniel/banana-claude`](https://github.com/AgriciDaniel/banana-claude) · Language: n/a · Last push: 2026-08-30

**What it is:** AI image generation skill for Claude Code - Creative Director powered by Gemini

**When to use:** When you need AI image generation inside Claude Code — a Creative Director persona powered by Gemini.

**Install / quick start:**

```text
/plugin marketplace add AgriciDaniel/banana-claude
/plugin install banana-claude@banana-claude-marketplace
/plugin enable banana-claude@banana-claude-marketplace
/reload-plugins
```

**Skills inside — 1** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`banana`](https://github.com/vamsy16/banana-claude/tree/HEAD/skills/banana) | Use for image creation, image editing, reference-based consistency, product and character visuals, text-bearing graphics, grounded diagrams, video-derived images, and… | Direct, generate, edit, compare, and review visual assets with current Google Gemini image models. |

#### `awesome-design-md`

🔗 [https://github.com/vamsy16/awesome-design-md](https://github.com/vamsy16/awesome-design-md) · Fork of [`VoltAgent/awesome-design-md`](https://github.com/VoltAgent/awesome-design-md) · Language: n/a · Last push: 2026-07-31

**What it is:** A collection of DESIGN.md files analysis by popular brand design systems. Drop one into your project and let coding agents generate a matching UI.

**When to use:** When you want coding agents to generate UI matching a known brand's design system — drop the DESIGN.md into your project.

*No packaged skills — use the project directly.*

---

### 🎬 Video, Audio & Creative AI (21 repos)

*AI video generation, editing, shorts, voice, and creative production.*

| Repo | Skills | One-line purpose |
|---|---|---|
| [`AI-Faceless-Video-Generator`](https://github.com/vamsy16/AI-Faceless-Video-Generator) | — | Generate a video script, voice and a talking face completely with AI |
| [`AI-Influencer-Generator`](https://github.com/vamsy16/AI-Influencer-Generator) | — | Create and customize your AI influencer open-source |
| [`AI-VFX`](https://github.com/vamsy16/AI-VFX) | — | AI-powered tool for creating advanced visual effects (VFX) in videos |
| [`AI-Youtube-Shorts-Generator`](https://github.com/vamsy16/AI-Youtube-Shorts-Generator) | 1 | Open-source alternative to Opus Clip, Vidyo.ai, Klap & SubMagic. |
| [`autoshorts`](https://github.com/vamsy16/autoshorts) | — | AutoShorts is a local-first desktop application for turning long-form video or audio recordings… |
| [`claude-video`](https://github.com/vamsy16/claude-video) | 1 | Give Claude the ability to watch any video. |
| [`claude-watch`](https://github.com/vamsy16/claude-watch) | 1 | Give Claude the ability to watch any video — scene-change frames + transcript + a structured… |
| [`Clip-Anything`](https://github.com/vamsy16/Clip-Anything) | — | Clip any moment from any video with prompts |
| [`higgsfield-skill`](https://github.com/vamsy16/higgsfield-skill) | 1 | One MCP, 30+ image and video models. Higgsfield skill for Claude Code. |
| [`hyperframes-cinematic-caption`](https://github.com/vamsy16/hyperframes-cinematic-caption) | 1 | Portable HyperFrames skill for premium spatial editorial captions, animated translucent hero text,… |
| [`MoneyPrinterTurbo`](https://github.com/vamsy16/MoneyPrinterTurbo) | — | 利用 AI 大模型和自动化工作流，根据主题或关键词一键生成高清短视频。Generate HD short videos from a topic or keyword with an… |
| [`premiere-pro-mcp`](https://github.com/vamsy16/premiere-pro-mcp) | 2 | Local-first Adobe Premiere Pro MCP: 285 AI video editing tools, opt-in project context, CEP bridge,… |
| [`resolve-claude-mcp`](https://github.com/vamsy16/resolve-claude-mcp) | — | Connect DaVinci Resolve Studio to Claude AI through the Model Context Protocol (MCP) |
| [`seedance-2-generator`](https://github.com/vamsy16/seedance-2-generator) | — | Open-source Next.js SaaS for Seedance 2.0 , Seedance 2.5 and Seedance 2 Mini video generation —… |
| [`super-video-maker-skill`](https://github.com/vamsy16/super-video-maker-skill) | 1 | AI video production skill for agents: HeyGen avatars, Seedance b-roll, OpenAI images, Remotion,… |
| [`Text-To-Video-AI`](https://github.com/vamsy16/Text-To-Video-AI) | — | Generate video from text using AI |
| [`video-use`](https://github.com/vamsy16/video-use) | 2 | Edit videos with coding agents |
| [`voicebox`](https://github.com/vamsy16/voicebox) | 4 | The open-source AI voice studio. Clone, dictate, create. |
| [`VoiceStudio`](https://github.com/vamsy16/VoiceStudio) | 4 | VoiceStudio is the open-source, fully-local ElevenLabs alternative — voice cloning, voice design,… |
| [`Wan2GP`](https://github.com/vamsy16/Wan2GP) | 1 | A fast AI Video Generator for the GPU Poor. |
| [`youtubepro`](https://github.com/vamsy16/youtubepro) | — | Local-first YouTube research, grounded AI insights, script writing, and thumbnail creation. |

#### `voicebox`

🔗 [https://github.com/vamsy16/voicebox](https://github.com/vamsy16/voicebox) · Fork of [`jamiepine/voicebox`](https://github.com/jamiepine/voicebox) · Language: n/a · Last push: 2026-08-09

**What it is:** The open-source AI voice studio. Clone, dictate, create.

**When to use:** When you need an open-source AI voice studio: cloning, dictation, creation. Runs locally.

**Skills inside — 4** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`add-tts-engine`](https://github.com/vamsy16/voicebox/tree/HEAD/.agents/skills/add-tts-engine) | — | Use this skill to add a new TTS engine to Voicebox. It walks through dependency research, backend implementation, frontend wiring, PyInstaller bundling, and frozen-build testing. |
| [`draft-release-notes`](https://github.com/vamsy16/voicebox/tree/HEAD/.agents/skills/draft-release-notes) | — | Use this skill to draft or update the [Unreleased] section of CHANGELOG.md from the actual changes since the last tag. Run this at any point during development to keep a working copy of the release narrative. |
| [`release-bump`](https://github.com/vamsy16/voicebox/tree/HEAD/.agents/skills/release-bump) | — | Use this skill to finalize a release. It stamps the [Unreleased] changelog section with a version and date, runs bumpversion to update all version files, and creates the release commit and tag. |
| [`triage-prs`](https://github.com/vamsy16/voicebox/tree/HEAD/.agents/skills/triage-prs) | — | Use this skill to triage the open PR queue before a release. Classifies every open PR into must-merge, candidate, superseded, or deferred; writes a working triage doc; and runs the merge loop end-to-end. |

#### `VoiceStudio`

🔗 [https://github.com/vamsy16/VoiceStudio](https://github.com/vamsy16/VoiceStudio) · Fork of [`debpalash/VoiceStudio`](https://github.com/debpalash/VoiceStudio) · Language: n/a · Last push: 2026-08-28

**What it is:** VoiceStudio is the open-source, fully-local ElevenLabs alternative — voice cloning, voice design, video dubbing, dictation, transcription & audiobook creation in 646 languages.

**When to use:** When you need a fully-local ElevenLabs alternative: voice cloning, voice design, video dubbing, dictation, transcription, and audiobooks in 646 languages.

**Skills inside — 4** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`fastapi-python`](https://github.com/vamsy16/VoiceStudio/tree/HEAD/.agents/skills/fastapi-python) | — | Expert in FastAPI Python development with best practices for APIs and async operations |
| [`omnivoice`](https://github.com/vamsy16/VoiceStudio/tree/HEAD/skills/omnivoice) | — | Speak and transcribe through the user's local VoiceStudio — free, offline, no API key. Text-to-speech (including the user's cloned voices) and speech-to-text via the OpenAI-compatible API at localhost:3900. |
| [`oss-maintainer`](https://github.com/vamsy16/VoiceStudio/tree/HEAD/skills/oss-maintainer) | — | Run an open-source project's issue/PR/release loop like a careful human maintainer — triage to root cause, absorb community PRs before duplicating them, gate every merge, ship honest releases, and thank the people doing your QA… |
| [`vite`](https://github.com/vamsy16/VoiceStudio/tree/HEAD/.agents/skills/vite) | — | Expert guidance for Vite development with modern build tooling, HMR, framework integrations, and performance optimization |

#### `video-use`

🔗 [https://github.com/vamsy16/video-use](https://github.com/vamsy16/video-use) · Fork of [`browser-use/video-use`](https://github.com/browser-use/video-use) · Language: n/a · Last push: 2026-08-30

**What it is:** Edit videos with coding agents

**When to use:** When editing videos with coding agents.

**Skills inside — 2** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`manim-video`](https://github.com/vamsy16/video-use/tree/HEAD/skills/manim-video) | Use when users request: animated explanations, math animations, concept visualizations, algorithm walkthroughs, technical explainers, 3Blue1Brown style videos, or any… | Production pipeline for mathematical and technical animations using Manim Community Edition. Creates 3Blue1Brown-style explainer videos, algorithm visualizations, equation derivations, architecture diagrams, and data stories. |
| [`SKILL.md`](https://github.com/vamsy16/video-use/tree/HEAD/SKILL.md) | — | Edit any video by conversation. Transcribe, cut, color grade, generate overlay animations, burn subtitles — for talking heads, montages, tutorials, travel, interviews. No presets, no menus. |

#### `premiere-pro-mcp`

🔗 [https://github.com/vamsy16/premiere-pro-mcp](https://github.com/vamsy16/premiere-pro-mcp) · Fork of [`leancoderkavy/premiere-pro-mcp`](https://github.com/leancoderkavy/premiere-pro-mcp) · Language: n/a · Last push: 2026-08-29

**What it is:** Local-first Adobe Premiere Pro MCP: 285 AI video editing tools, opt-in project context, CEP bridge, and capability-aware UXP.

**When to use:** When editing in Adobe Premiere Pro with an AI agent — 285 local-first video-editing tools via MCP.

**Skills inside — 2** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`develop-premiere-pro-mcp`](https://github.com/vamsy16/premiere-pro-mcp/tree/HEAD/claude-plugins/premiere-pro/skills/develop-premiere-pro-mcp) | Use when changing MCP tools, schemas, server registration, CEP or UXP bridges, generated ExtendScript, authority profiles, packaging, release metadata, or compatibility… | Develop, debug, test, review, document, and release the premiere-pro-mcp repository. |
| [`edit-premiere-project`](https://github.com/vamsy16/premiere-pro-mcp/tree/HEAD/claude-plugins/premiere-pro/skills/edit-premiere-project) | Use for rough cuts, timeline assembly or cleanup, clip and track changes, transitions and effects, dialogue or audio adjustments, captions, project organization, frame… | Inspect, edit, verify, save, and export an open Adobe Premiere Pro project through the premiere-pro MCP server. |

#### `AI-Youtube-Shorts-Generator`

🔗 [https://github.com/vamsy16/AI-Youtube-Shorts-Generator](https://github.com/vamsy16/AI-Youtube-Shorts-Generator) · Fork of [`Anil-matcha/AI-Youtube-Shorts-Generator`](https://github.com/Anil-matcha/AI-Youtube-Shorts-Generator) · Language: n/a · Last push: 2026-07-29

**What it is:** Open-source alternative to Opus Clip, Vidyo.ai, Klap & SubMagic. Turn long-form YouTube videos into viral 9:16 shorts using LLM highlight detection, Whisper transcription, and auto vertical cropping — free, no watermarks, no per-clip credits.

**When to use:** When turning long YouTube videos into viral 9:16 shorts — LLM highlight detection, Whisper transcription, auto vertical cropping. Free, no watermarks.

**Skills inside — 1** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`youtube-shorts-generator`](https://github.com/vamsy16/AI-Youtube-Shorts-Generator/tree/HEAD/.claude/skills/youtube-shorts-generator) | — | Generate viral 9:16 YouTube Shorts (or TikTok/Reels clips) from a long-form YouTube URL or local video. |

#### `Wan2GP`

🔗 [https://github.com/vamsy16/Wan2GP](https://github.com/vamsy16/Wan2GP) · Fork of [`deepbeepmeep/Wan2GP`](https://github.com/deepbeepmeep/Wan2GP) · Language: n/a · Last push: 2026-08-30

**What it is:** A fast AI Video Generator for the GPU Poor. Supports Wan 2.1/2.2, LTX-2, Qwen Image, Hunyuan Video, LTX Video and Flux.

**When to use:** When running Wan video-generation models on consumer GPUs locally.

**Skills inside — 1** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`wangp-agent`](https://github.com/vamsy16/Wan2GP/tree/HEAD/wangp-agent) | Use when an agent needs to operate WanGP: discover available model capabilities, choose a model, inspect accepted inputs and setting values, build settings, run… | Use when an agent needs to operate WanGP: discover available model capabilities, choose a model, inspect accepted inputs and setting values, build settings, run generation through the MCP server or Python API, poll jobs, cancel… |

#### `claude-video`

🔗 [https://github.com/vamsy16/claude-video](https://github.com/vamsy16/claude-video) · Fork of [`bradautomates/claude-video`](https://github.com/bradautomates/claude-video) · Language: n/a · Last push: 2026-07-01

**What it is:** Give Claude the ability to watch any video. /watch downloads, extracts frames, transcribes, hands it all to Claude.

**When to use:** When you want Claude to watch any video: /watch downloads, extracts frames, transcribes, and hands it all over.

**Skills inside — 1** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`watch`](https://github.com/vamsy16/claude-video/tree/HEAD/skills/watch) | — | Watch a video (URL or local path). Downloads with yt-dlp, extracts auto-scaled frames with ffmpeg, pulls the transcript from captions (or Whisper API fallback), and hands the result to Claude so it can answer questions about… |

#### `claude-watch`

🔗 [https://github.com/vamsy16/claude-watch](https://github.com/vamsy16/claude-watch) · Fork of [`taoufik123-collab/claude-watch`](https://github.com/taoufik123-collab/claude-watch) · Language: n/a · Last push: 2026-07-24

**What it is:** Give Claude the ability to watch any video — scene-change frames + transcript + a structured report, with a 0-10s hook microscope and optional Obsidian auto-save.

**When to use:** When you want Claude to watch any video with scene-change frames, transcript, structured report, and a 0–10s hook microscope.

**Skills inside — 1** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`SKILL.md`](https://github.com/vamsy16/claude-watch/tree/HEAD/SKILL.md) | — | Watch a video (URL or local path) like an editor. Extracts scene-change frames, pacing metrics (cuts/min, shot length), and a dense 0-10s hook microscope; pulls transcript from captions or Whisper. |

#### `super-video-maker-skill`

🔗 [https://github.com/vamsy16/super-video-maker-skill](https://github.com/vamsy16/super-video-maker-skill) · Fork of [`Bomx/super-video-maker-skill`](https://github.com/Bomx/super-video-maker-skill) · Language: n/a · Last push: 2026-08-09

**What it is:** AI video production skill for agents: HeyGen avatars, Seedance b-roll, OpenAI images, Remotion, HyperFrames, screen recording, FFmpeg captions and QC.

**When to use:** For full AI video production: HeyGen avatars, Seedance b-roll, OpenAI images, Remotion, HyperFrames, screen recording, FFmpeg captions, and QC.

**Install / quick start:**

```bash
git clone https://github.com/Bomx/super-video-maker-skill.git
```

**Skills inside — 1** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`SKILL.md`](https://github.com/vamsy16/super-video-maker-skill/tree/HEAD/SKILL.md) | Use when you ask to make, edit, repurpose, caption, soundtrack, or export videos using HeyGen avatars, Seedance or ByteDance b-roll, OpenAI image generation and editing,… | End-to-end AI video production skill for agentic frameworks. |

#### `higgsfield-skill`

🔗 [https://github.com/vamsy16/higgsfield-skill](https://github.com/vamsy16/higgsfield-skill) · Fork of [`robonuggets/higgsfield-skill`](https://github.com/robonuggets/higgsfield-skill) · Language: n/a · Last push: 2026-05-01

**What it is:** One MCP, 30+ image and video models. Higgsfield skill for Claude Code.

**When to use:** When you need 30+ image and video models (Seedance 2, Sora 2, Veo, Kling, Nano Banana Pro, GPT Image 2, Flux…) through one Higgsfield MCP.

**Install / quick start:**

```bash
git clone https://github.com/robonuggets/higgsfield-skill
```
Then install the Higgsfield MCP at user scope in Claude Code (one auth for all sessions).

**Skills inside — 1** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`higgsfield`](https://github.com/vamsy16/higgsfield-skill/tree/HEAD/.claude/skills/higgsfield) | Use this skill when you want to generate images or videos via Higgsfield (Seedance 2.0, Sora 2, Veo, Kling, Nano Banana Pro, GPT Image 2, Flux, Hailuo, Soul, Cinema… | One MCP, 30+ image and video models. Triggers on "higgsfield", "higgsfield mcp", "use higgsfield", or any image/video generation request when the user already has a Higgsfield subscription. |

#### `hyperframes-cinematic-caption`

🔗 [https://github.com/vamsy16/hyperframes-cinematic-caption](https://github.com/vamsy16/hyperframes-cinematic-caption) · Fork of [`audrey-560/hyperframes-cinematic-caption`](https://github.com/audrey-560/hyperframes-cinematic-caption) · Language: n/a · Last push: 2026-08-25

**What it is:** Portable HyperFrames skill for premium spatial editorial captions, animated translucent hero text, and subject-aware video editing.

**When to use:** When you need premium spatial editorial captions, animated translucent hero text, or subject-aware video editing.

**Skills inside — 1** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`SKILL.md`](https://github.com/vamsy16/hyperframes-cinematic-caption/tree/HEAD/SKILL.md) | Use for cinematic captions, editorial subtitles, dynamic real-estate or creator-reel captions, or requests to make important words, numbers, or locations large,… | Apply designed cinematic captions to an existing HyperFrames video by selecting hero words from speech, building ordered mixed-case stacks, placing type around a speaker, and using subject-aware depth, translucent fills, or… |

#### `AI-Faceless-Video-Generator`

🔗 [https://github.com/vamsy16/AI-Faceless-Video-Generator](https://github.com/vamsy16/AI-Faceless-Video-Generator) · Fork of [`SamurAIGPT/AI-Faceless-Video-Generator`](https://github.com/SamurAIGPT/AI-Faceless-Video-Generator) · Language: n/a · Last push: 2026-08-02

**What it is:** Generate a video script, voice and a talking face completely with AI

**When to use:** When you want a faceless video — script, voice, and talking face all AI-generated.

*No packaged skills — use the project directly.*

#### `AI-Influencer-Generator`

🔗 [https://github.com/vamsy16/AI-Influencer-Generator](https://github.com/vamsy16/AI-Influencer-Generator) · Fork of [`SamurAIGPT/AI-Influencer-Generator`](https://github.com/SamurAIGPT/AI-Influencer-Generator) · Language: n/a · Last push: 2026-08-02

**What it is:** Create and customize your AI influencer open-source

**When to use:** When creating/customizing an AI influencer persona.

*No packaged skills — use the project directly.*

#### `AI-VFX`

🔗 [https://github.com/vamsy16/AI-VFX](https://github.com/vamsy16/AI-VFX) · Fork of [`SamurAIGPT/AI-VFX`](https://github.com/SamurAIGPT/AI-VFX) · Language: n/a · Last push: 2026-02-05

**What it is:** AI-powered tool for creating advanced visual effects (VFX) in videos

**When to use:** When creating advanced visual effects in videos with AI.

*No packaged skills — use the project directly.*

#### `autoshorts`

🔗 [https://github.com/vamsy16/autoshorts](https://github.com/vamsy16/autoshorts) · Fork of [`JayWebtech/autoshorts`](https://github.com/JayWebtech/autoshorts) · Language: n/a · Last push: 2026-08-02

**What it is:** AutoShorts is a local-first desktop application for turning long-form video or audio recordings into high-impact, vertical short-form clip candidates (9:16 portrait) with AI-powered viral moment ranking.

**When to use:** When you have long recordings and want AI-ranked vertical clip candidates locally.

*No packaged skills — use the project directly.*

#### `Clip-Anything`

🔗 [https://github.com/vamsy16/Clip-Anything](https://github.com/vamsy16/Clip-Anything) · Fork of [`SamurAIGPT/Clip-Anything`](https://github.com/SamurAIGPT/Clip-Anything) · Language: n/a · Last push: 2026-07-21

**What it is:** Clip any moment from any video with prompts

**When to use:** When you need a specific moment clipped from any video using prompts.

*No packaged skills — use the project directly.*

#### `MoneyPrinterTurbo`

🔗 [https://github.com/vamsy16/MoneyPrinterTurbo](https://github.com/vamsy16/MoneyPrinterTurbo) · Fork of [`harry0703/MoneyPrinterTurbo`](https://github.com/harry0703/MoneyPrinterTurbo) · Language: n/a · Last push: 2026-08-30

**What it is:** 利用 AI 大模型和自动化工作流，根据主题或关键词一键生成高清短视频。Generate HD short videos from a topic or keyword with an automated AI workflow.

**When to use:** When you want HD short videos auto-generated from just a topic or keyword.

*No packaged skills — use the project directly.*

#### `seedance-2-generator`

🔗 [https://github.com/vamsy16/seedance-2-generator](https://github.com/vamsy16/seedance-2-generator) · Fork of [`SamurAIGPT/seedance-2-generator`](https://github.com/SamurAIGPT/seedance-2-generator) · Language: n/a · Last push: 2026-08-03

**What it is:** Open-source Next.js SaaS for Seedance 2.0 , Seedance 2.5 and Seedance 2 Mini video generation — Stripe billing, credits, NextAuth, and Prisma out of the box.

**When to use:** When you need a ready-made SaaS for Seedance video generation with Stripe billing, credits, NextAuth, and Prisma.

*No packaged skills — use the project directly.*

#### `Text-To-Video-AI`

🔗 [https://github.com/vamsy16/Text-To-Video-AI](https://github.com/vamsy16/Text-To-Video-AI) · Fork of [`SamurAIGPT/Text-To-Video-AI`](https://github.com/SamurAIGPT/Text-To-Video-AI) · Language: n/a · Last push: 2026-08-24

**What it is:** Generate video from text using AI

**When to use:** When generating video from text using AI.

*No packaged skills — use the project directly.*

#### `resolve-claude-mcp`

🔗 [https://github.com/vamsy16/resolve-claude-mcp](https://github.com/vamsy16/resolve-claude-mcp) · Fork of [`barckley75/resolve-claude-mcp`](https://github.com/barckley75/resolve-claude-mcp) · Language: n/a · Last push: 2026-05-14

**What it is:** Connect DaVinci Resolve Studio to Claude AI through the Model Context Protocol (MCP)

**When to use:** When connecting DaVinci Resolve Studio to Claude via MCP for color/edit workflows.

*No packaged skills — use the project directly.*

#### `youtubepro`

🔗 [https://github.com/vamsy16/youtubepro](https://github.com/vamsy16/youtubepro) · Fork of [`AgriciDaniel/youtubepro`](https://github.com/AgriciDaniel/youtubepro) · Language: n/a · Last push: 2026-08-27

**What it is:** Local-first YouTube research, grounded AI insights, script writing, and thumbnail creation.

**When to use:** For local-first YouTube research: grounded AI insights, script writing, and thumbnail creation.

*No packaged skills — use the project directly.*

---

### 🕷️ Web Scraping & Lead Generation (11 repos)

*Scrapers, crawlers, and B2B lead-generation tooling.*

| Repo | Skills | One-line purpose |
|---|---|---|
| [`Agent-Reach`](https://github.com/vamsy16/Agent-Reach) | 1 | Give your AI agent eyes to see the entire internet. |
| [`autoscraper`](https://github.com/vamsy16/autoscraper) | — | A Smart, Automatic, Fast and Lightweight Web Scraper for Python |
| [`crawl4ai`](https://github.com/vamsy16/crawl4ai) | — | 🚀🤖 Crawl4AI: Open-source LLM Friendly Web Crawler & Scraper. |
| [`crawlee`](https://github.com/vamsy16/crawlee) | — | Crawlee—A web scraping and browser automation library for Node.js to build reliable crawlers. |
| [`curl-impersonate`](https://github.com/vamsy16/curl-impersonate) | — | curl-impersonate: A special build of curl that can impersonate Chrome & Firefox |
| [`firecrawl`](https://github.com/vamsy16/firecrawl) | 5 | The context API to search, scrape, and interact with the web at scale. 🔥 |
| [`google-maps-scraper-kit`](https://github.com/vamsy16/google-maps-scraper-kit) | 1 | Run a free open-source Google Maps scraper locally and let Claude drive it on autopilot. |
| [`lead-scraper`](https://github.com/vamsy16/lead-scraper) | — | Two-stage B2B lead scraper (Google Maps discovery + website email/phone/social enrichment) built on… |
| [`Scout`](https://github.com/vamsy16/Scout) | — | Free lead generation tool. Scrape Instagram, Twitch, TikTok, and LinkedIn profiles. |
| [`Scrapling`](https://github.com/vamsy16/Scrapling) | 1 | 🕷️ An adaptive Web Scraping framework that handles everything from a single request to a full-scale… |
| [`scrapy`](https://github.com/vamsy16/scrapy) | — | Scrapy, a fast high-level web crawling & scraping framework for Python. |

#### `firecrawl`

🔗 [https://github.com/vamsy16/firecrawl](https://github.com/vamsy16/firecrawl) · Fork of [`firecrawl/firecrawl`](https://github.com/firecrawl/firecrawl) · Language: n/a · Last push: 2026-08-30

**What it is:** The context API to search, scrape, and interact with the web at scale. 🔥

**When to use:** When you need to scrape/crawl/search any website and get LLM-ready data at scale — the context API for the web.

**Skills inside — 5** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`firecrawl-build`](https://github.com/vamsy16/firecrawl/tree/HEAD/skills/firecrawl-build) | Use when building any feature that needs data from the web in code, even if you do not mention Firecrawl explicitly and only describes wanting web data, website content,… | Integrate Firecrawl into application code whenever a product, agent, or workflow needs web data inside the app — web search, live search results, page scraping, structured extraction, or browser interaction. |
| [`firecrawl-build-interact`](https://github.com/vamsy16/firecrawl/tree/HEAD/skills/firecrawl-build-interact) | Use when a feature needs clicks, form fills, pagination, authentication-aware flows, or other multi-step interactions that plain `/scrape` cannot complete. | Integrate Firecrawl `/interact` into product code for dynamic pages and browser actions after scraping. |
| [`firecrawl-build-onboarding`](https://github.com/vamsy16/firecrawl/tree/HEAD/skills/firecrawl-build-onboarding) | Use when an application needs `FIRECRAWL_API_KEY`, when an agent should add Firecrawl to `.env`, when you want to authenticate Firecrawl for app code, or when choosing… | Get Firecrawl credentials and SDK setup into a project. This skill includes its own browser auth flow, so it does not depend on the website onboarding skill. |
| [`firecrawl-build-scrape`](https://github.com/vamsy16/firecrawl/tree/HEAD/skills/firecrawl-build-scrape) | Use when an app already has a URL and needs markdown, HTML, links, screenshots, metadata, or structured page output. | Integrate Firecrawl `/scrape` into product code for single-page extraction. Prefer this skill over broader crawl patterns when the feature is page-level. |
| [`firecrawl-build-search`](https://github.com/vamsy16/firecrawl/tree/HEAD/skills/firecrawl-build-search) | Use when an app needs discovery before extraction, when the feature starts with a query instead of a URL, or when the system should search the web and optionally hydrate… | Integrate Firecrawl `/search` into product code and agent workflows. |

#### `Scrapling`

🔗 [https://github.com/vamsy16/Scrapling](https://github.com/vamsy16/Scrapling) · Fork of [`D4Vinci/Scrapling`](https://github.com/D4Vinci/Scrapling) · Language: n/a · Last push: 2026-08-25

**What it is:** 🕷️ An adaptive Web Scraping framework that handles everything from a single request to a full-scale crawl!

**When to use:** When a site blocks you — adaptive scraping with anti-bot bypass (Cloudflare Turnstile) and stealth headless browsing.

**Skills inside — 1** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`Scrapling-Skill`](https://github.com/vamsy16/Scrapling/tree/HEAD/agent-skill/Scrapling-Skill) | Use when asked to scrape, crawl, or extract data from websites; web_fetch fails; the site has anti-bot protections; write Python code to scrape/crawl; or write spiders. | Scrape web pages using Scrapling with anti-bot bypass (like Cloudflare Turnstile), stealth headless browsing, spiders framework, adaptive scraping, and JavaScript rendering. |

#### `Agent-Reach`

🔗 [https://github.com/vamsy16/Agent-Reach](https://github.com/vamsy16/Agent-Reach) · Fork of [`Panniantong/Agent-Reach`](https://github.com/Panniantong/Agent-Reach) · Language: n/a · Last push: 2026-08-25

**What it is:** Give your AI agent eyes to see the entire internet. Read & search Twitter, Reddit, YouTube, GitHub, Bilibili, XiaoHongShu — one CLI, zero API fees.

**When to use:** When your agent needs to read/search Twitter, Reddit, YouTube, GitHub, Bilibili, or XiaoHongShu — one CLI, zero API fees.

**Skills inside — 1** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`skill`](https://github.com/vamsy16/Agent-Reach/tree/HEAD/agent_reach/skill) | — | MUST USE when user wants to 调研/research/搜索/search/查/找/look up anything on the internet — e.g. 全网调研 X / 帮我调研一下 X / 查一下 X / 搜搜 X / 看看大家怎么评价 X / X 上有什么讨论 / research this topic。 Also MUST USE when user mentions any platform or shares… |

#### `google-maps-scraper-kit`

🔗 [https://github.com/vamsy16/google-maps-scraper-kit](https://github.com/vamsy16/google-maps-scraper-kit) · Fork of [`Mahanaicoach/google-maps-scraper-kit`](https://github.com/Mahanaicoach/google-maps-scraper-kit) · Language: n/a · Last push: 2026-06-29

**What it is:** Run a free open-source Google Maps scraper locally and let Claude drive it on autopilot.

**When to use:** When you want a free Google Maps scraper running locally with Claude driving it on autopilot.

**Skills inside — 1** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`google-maps-scraper`](https://github.com/vamsy16/google-maps-scraper-kit/tree/HEAD/.claude/skills/google-maps-scraper) | Use when you want local-business / lead-gen data, "a list of [businesses] in [place]", or to enrich places with contact info. | Scrape Google Maps business listings (name, address, phone, website, rating, reviews, lat/lng, hours, emails) via the local gosom google-maps-scraper REST API. NOT for Instagram/TikTok/YouTube or any social-media scraping. |

#### `autoscraper`

🔗 [https://github.com/vamsy16/autoscraper](https://github.com/vamsy16/autoscraper) · Fork of [`alirezamika/autoscraper`](https://github.com/alirezamika/autoscraper) · Language: n/a · Last push: 2026-07-29

**What it is:** A Smart, Automatic, Fast and Lightweight Web Scraper for Python

**When to use:** When you want a Python scraper that learns the rules automatically from sample data.

*No packaged skills — use the project directly.*

#### `crawl4ai`

🔗 [https://github.com/vamsy16/crawl4ai](https://github.com/vamsy16/crawl4ai) · Fork of [`unclecode/crawl4ai`](https://github.com/unclecode/crawl4ai) · Language: n/a · Last push: 2026-08-29

**What it is:** 🚀🤖 Crawl4AI: Open-source LLM Friendly Web Crawler & Scraper. Don't be shy, join here: https://discord.gg/jP8KfhDhyN

**When to use:** When you need an open-source LLM-friendly crawler/scraper in Python.

*No packaged skills — use the project directly.*

#### `crawlee`

🔗 [https://github.com/vamsy16/crawlee](https://github.com/vamsy16/crawlee) · Fork of [`apify/crawlee`](https://github.com/apify/crawlee) · Language: n/a · Last push: 2026-08-29

**What it is:** Crawlee—A web scraping and browser automation library for Node.js to build reliable crawlers. In JavaScript and TypeScript. Extract data for AI, LLMs, RAG, or GPTs. Download HTML, PDF, JPG, PNG, and other files from websites. Works with Puppeteer, Playwright, Cheerio, JSDOM, and raw HTTP. Both headful and headless mode.

**When to use:** When building reliable crawlers/browser automation in Node.js/TypeScript (Puppeteer, Playwright, Cheerio) with proxy rotation.

*No packaged skills — use the project directly.*

#### `curl-impersonate`

🔗 [https://github.com/vamsy16/curl-impersonate](https://github.com/vamsy16/curl-impersonate) · Fork of [`lwthiker/curl-impersonate`](https://github.com/lwthiker/curl-impersonate) · Language: n/a · Last push: 2024-07-18

**What it is:** curl-impersonate: A special build of curl that can impersonate Chrome & Firefox

**When to use:** When your HTTP requests get blocked — a special curl build that impersonates Chrome/Firefox TLS fingerprints.

*No packaged skills — use the project directly.*

#### `scrapy`

🔗 [https://github.com/vamsy16/scrapy](https://github.com/vamsy16/scrapy) · Fork of [`scrapy/scrapy`](https://github.com/scrapy/scrapy) · Language: n/a · Last push: 2026-08-28

**What it is:** Scrapy, a fast high-level web crawling & scraping framework for Python.

**When to use:** When building full-scale crawlers in Python with the classic Scrapy framework.

*No packaged skills — use the project directly.*

#### `lead-scraper`

🔗 [https://github.com/vamsy16/lead-scraper](https://github.com/vamsy16/lead-scraper) · Fork of [`sanketagarwal/lead-scraper`](https://github.com/sanketagarwal/lead-scraper) · Language: n/a · Last push: 2026-06-20

**What it is:** Two-stage B2B lead scraper (Google Maps discovery + website email/phone/social enrichment) built on Botasaurus

**When to use:** For two-stage B2B lead scraping: Google Maps discovery + website email/phone/social enrichment.

*No packaged skills — use the project directly.*

#### `Scout`

🔗 [https://github.com/vamsy16/Scout](https://github.com/vamsy16/Scout) · Fork of [`kiryano/Scout`](https://github.com/kiryano/Scout) · Language: n/a · Last push: 2026-02-22

**What it is:** Free lead generation tool. Scrape Instagram, Twitch, TikTok, and LinkedIn profiles. Extract emails from bios, verify via SMTP, export to CSV.

**When to use:** For free lead generation from Instagram, Twitch, TikTok, and LinkedIn profiles — bio emails, SMTP verification, CSV export.

*No packaged skills — use the project directly.*

---

### 🤖 AI Agents, Harnesses & Developer Tooling (20 repos)

*Agent harnesses, orchestration, memory, security, and engineering skills for AI coding agents.*

| Repo | Skills | One-line purpose |
|---|---|---|
| [`agentshield`](https://github.com/vamsy16/agentshield) | 1 | AI agent security scanner. Detect vulnerabilities in agent configurations, MCP servers, and tool… |
| [`ai-operating-system-template`](https://github.com/vamsy16/ai-operating-system-template) | 5 | A clean starter template for building a personal AI Operating System in Claude Code — core skills… |
| [`browser-harness`](https://github.com/vamsy16/browser-harness) | 3 | Browser Harness \| Self-healing harness that enables LLMs to complete any task. |
| [`browser-use`](https://github.com/vamsy16/browser-use) | 6 | 🌐 Make websites accessible for AI agents. Automate tasks online with ease. |
| [`browsercode`](https://github.com/vamsy16/browsercode) | 2 | The browser-native agent framework |
| [`build-your-own-claude-code`](https://github.com/vamsy16/build-your-own-claude-code) | — | Definition for the claude-code challenge. |
| [`claude-counter`](https://github.com/vamsy16/claude-counter) | — | A minimal browser extension that shows token count, cache timer, and usage bars on claude.ai. |
| [`claude-mem`](https://github.com/vamsy16/claude-mem) | 21 | Persistent Context Across Sessions for Every Agent – Captures everything your agent does during… |
| [`claude-swarm`](https://github.com/vamsy16/claude-swarm) | — | Multi-agent orchestration for Claude Code — decompose tasks, coordinate agents, visualize… |
| [`codegraph`](https://github.com/vamsy16/codegraph) | 2 | Pre-indexed code knowledge graph, auto syncs on code changes, for Claude Code, Codex, Gemini,… |
| [`company-skills-marketplace-template`](https://github.com/vamsy16/company-skills-marketplace-template) | 2 | Fork-and-go template for a private team skills marketplace usable from Claude Code and Codex CLI |
| [`ECC`](https://github.com/vamsy16/ECC) | 287 | The agent harness performance optimization system. |
| [`graphify`](https://github.com/vamsy16/graphify) | — | Turn any codebase, with its docs, SQL schemas, configs, and PDFs, into a queryable knowledge graph. |
| [`headroom`](https://github.com/vamsy16/headroom) | — | Compress tool outputs, logs, files, and RAG chunks before they reach the LLM. |
| [`JARVIS`](https://github.com/vamsy16/JARVIS) | 2 | JARVIS: a real-time agentic intelligence-gathering platform powered by autonomous web scraping &… |
| [`loop-engineering`](https://github.com/vamsy16/loop-engineering) | 14 | Practical patterns, starters & CLI tools for loop engineering with AI coding agents. |
| [`markitdown`](https://github.com/vamsy16/markitdown) | — | Python tool for converting files and office documents to Markdown. |
| [`n8n-nodes-browser-use`](https://github.com/vamsy16/n8n-nodes-browser-use) | — | n8n community node for Browser Use Cloud — browser-automation agent workflows inside n8n. |
| [`scrcpy`](https://github.com/vamsy16/scrcpy) | — | Display and control your Android device |
| [`sequential-thinking-skill`](https://github.com/vamsy16/sequential-thinking-skill) | 1 | Claude Code skill replicating the Sequential Thinking MCP server — structured reasoning with… |

#### `ECC`

🔗 [https://github.com/vamsy16/ECC](https://github.com/vamsy16/ECC) · Fork of [`affaan-m/ECC`](https://github.com/affaan-m/ECC) · Language: n/a · Last push: 2026-08-29

**What it is:** The agent harness performance optimization system. Skills, instincts, memory, security, and research-first development for Claude Code, Codex, Opencode, Cursor and beyond.

**When to use:** The engineering skills library — 287 skills for coding agents covering API design, testing, security, frontend, backend patterns, agent architecture, and much more. Install as a Claude Code plugin when you want a professional-grade default skillset.

**Install / quick start:**

Inside Claude Code:
```text
/plugin marketplace add https://github.com/affaan-m/ECC
/plugin install ecc@ecc
```

**Skills inside — 287** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`accessibility`](https://github.com/vamsy16/ECC/tree/HEAD/skills/accessibility) | Use when building or auditing UI that must meet WCAG 2.2 Level AA, or when reviewing a change for keyboard, contrast, or screen-reader support. | Design, implement, and audit inclusive digital products using WCAG 2.2 Level AA. |
| [`agent-architecture-audit`](https://github.com/vamsy16/ECC/tree/HEAD/skills/agent-architecture-audit) | Use when an agent or LLM feature misbehaves and the failing layer is unknown, or before shipping an agent stack. | Full-stack diagnostic for agent and LLM applications. Audits the 12-layer agent stack for wrapper regression, memory pollution, tool discipline failures, hidden repair loops, and rendering corruption. |
| [`agent-eval`](https://github.com/vamsy16/ECC/tree/HEAD/skills/agent-eval) | Use when choosing between coding agents, or when a change to an agent setup needs measured pass rate, cost, and time rather than an impression. | Head-to-head comparison of coding agents (Claude Code, Aider, Codex, etc.) on custom tasks with pass rate, cost, time, and consistency metrics. |
| [`agent-harness-construction`](https://github.com/vamsy16/ECC/tree/HEAD/skills/agent-harness-construction) | Use when defining or revising an agent's tool set, action space, or observation format. | Design and optimize AI agent action spaces, tool definitions, and observation formatting for higher completion rates. |
| [`agent-introspection-debugging`](https://github.com/vamsy16/ECC/tree/HEAD/skills/agent-introspection-debugging) | Use when an agent run fails and you need a reproducible diagnosis instead of a retry. | Structured self-debugging workflow for AI agent failures using capture, diagnosis, contained recovery, and introspection reports. |
| [`agent-payment-x402`](https://github.com/vamsy16/ECC/tree/HEAD/skills/agent-payment-x402) | Use when an agent must pay for something itself and needs per-task budgets, spending controls, and a non-custodial wallet. | Add x402 payment execution to AI agents with per-task budgets, spending controls, and non-custodial wallets. Supports Base through agentwallet-sdk and X Layer through OKX Payments / OKX Agent Payments Protocol. |
| [`agent-self-evaluation`](https://github.com/vamsy16/ECC/tree/HEAD/skills/agent-self-evaluation) | Use after completing any non-trivial task. | The agent self-rates its output on 5 axes — accuracy, completeness, clarity, actionability, conciseness — with concrete evidence per criterion. Produces a structured 1-5 scorecard with specific improvement suggestions. |
| [`agent-sort`](https://github.com/vamsy16/ECC/tree/HEAD/skills/agent-sort) | Use when ECC should be trimmed to what a project actually needs instead of loading the full bundle. | Build an evidence-backed ECC install plan for a specific repo by sorting skills, commands, rules, hooks, and extras into DAILY vs LIBRARY buckets using parallel repo-aware review passes. |
| [`agentic-engineering`](https://github.com/vamsy16/ECC/tree/HEAD/skills/agentic-engineering) | Use when planning or executing engineering work that agents will carry out end to end. | Operate as an agentic engineer using eval-first execution, decomposition, and cost-aware model routing. |
| [`agentic-os`](https://github.com/vamsy16/ECC/tree/HEAD/skills/agentic-os) | Use when building a persistent multi-agent system on Claude Code with its own memory, commands, and scheduling. | Build persistent multi-agent operating systems on Claude Code. Covers kernel architecture, specialist agents, slash commands, file-based memory, scheduled automation, and state management without external databases. |
| [`ai-first-engineering`](https://github.com/vamsy16/ECC/tree/HEAD/skills/ai-first-engineering) | Use when setting team process, review gates, or ownership rules for a codebase largely written by agents. | Engineering operating model for teams where AI agents generate a large share of implementation output. |
| [`ai-regression-testing`](https://github.com/vamsy16/ECC/tree/HEAD/skills/ai-regression-testing) | Use when adding regression coverage to AI-assisted code, or when the same model both wrote and reviewed a change. | Regression testing strategies for AI-assisted development. Sandbox-mode API testing without database dependencies, automated bug-check workflows, and patterns to catch AI blind spots where the same model writes and reviews code. |
| [`android-clean-architecture`](https://github.com/vamsy16/ECC/tree/HEAD/skills/android-clean-architecture) | Use when structuring modules, layers, or data flow in an Android or KMP project. | Clean Architecture patterns for Android and Kotlin Multiplatform projects — module structure, dependency rules, UseCases, Repositories, and data layer patterns. |
| [`angular-developer`](https://github.com/vamsy16/ECC/tree/HEAD/skills/angular-developer) | — | Generates Angular code and provides architectural guidance. Trigger when creating projects, components, or services, or for best practices on reactivity (signals, linkedSignal, resource), forms, dependency injection, routing,… |
| [`api-connector-builder`](https://github.com/vamsy16/ECC/tree/HEAD/skills/api-connector-builder) | Use when adding one more integration without inventing a second architecture. | Build a new API connector or provider by matching the target repo's existing integration pattern exactly. |
| [`api-design`](https://github.com/vamsy16/ECC/tree/HEAD/skills/api-design) | Use when designing or reviewing REST endpoints, resource names, status codes, pagination, or versioning. | REST API design patterns including resource naming, status codes, pagination, filtering, error responses, versioning, and rate limiting for production APIs. |
| [`architecture-decision-records`](https://github.com/vamsy16/ECC/tree/HEAD/skills/architecture-decision-records) | — | Capture architectural decisions made during Claude Code sessions as structured ADRs. Auto-detects decision moments, records context, alternatives considered, and rationale. |
| [`article-writing`](https://github.com/vamsy16/ECC/tree/HEAD/skills/article-writing) | Use when you want polished written content longer than a paragraph, especially when voice consistency, structure, and credibility matter. | Write articles, guides, blog posts, tutorials, newsletter issues, and other long-form content in a distinctive voice derived from supplied examples or brand guidance. |
| [`automation-audit-ops`](https://github.com/vamsy16/ECC/tree/HEAD/skills/automation-audit-ops) | Use when you want to know which jobs, hooks, connectors, MCP servers, or wrappers are live, broken, redundant, or missing before fixing anything. | Evidence-first automation inventory and overlap audit workflow for ECC. |
| [`autonomous-agent-harness`](https://github.com/vamsy16/ECC/tree/HEAD/skills/autonomous-agent-harness) | Use when you want continuous autonomous operation, scheduled tasks, or a self-directing agent loop. | Transform Claude Code into a fully autonomous agent system with persistent memory, scheduled operations, computer use, and task queuing. |
| [`autonomous-loops`](https://github.com/vamsy16/ECC/tree/HEAD/skills/autonomous-loops) | — | Patterns and architectures for autonomous Claude Code loops — from simple sequential pipelines to RFC-driven multi-agent DAG systems. |
| [`backend-patterns`](https://github.com/vamsy16/ECC/tree/HEAD/skills/backend-patterns) | Use when building or reviewing Node.js, Express, or Next.js API routes and their data access. | Backend architecture patterns, API design, database optimization, and server-side best practices for Node.js, Express, and Next.js API routes. |
| [`benchmark`](https://github.com/vamsy16/ECC/tree/HEAD/skills/benchmark) | — | Use this skill to measure performance baselines, detect regressions before/after PRs, and compare stack alternatives. |
| [`benchmark-methodology`](https://github.com/vamsy16/ECC/tree/HEAD/skills/benchmark-methodology) | Use after competitive-platform-analysis has produced a tiered competitor set. | Scores each competitor across nine weighted dimensions (positioning, voice, visual craft, offer packaging, evidence, enterprise-readiness, thought leadership, pricing, client's strategic tension) with explicit 1–5 rubrics and a… |
| [`benchmark-optimization-loop`](https://github.com/vamsy16/ECC/tree/HEAD/skills/benchmark-optimization-loop) | Use when you ask to make something faster, try many variants, run recursive optimization, benchmark latency/throughput/cost, or choose the best implementation by… | Use when you ask to make something faster, try many variants, run recursive optimization, benchmark latency/throughput/cost, or choose the best implementation by repeated measured tests. |
| [`blender-motion-state-inspection`](https://github.com/vamsy16/ECC/tree/HEAD/skills/blender-motion-state-inspection) | Use this skill when inspecting Blender characters, rigs, poses, animation retargeting, ground contact, facing direction, or model-vs-motion alignment where screenshots… | Use this skill when inspecting Blender characters, rigs, poses, animation retargeting, ground contact, facing direction, or model-vs-motion alignment where screenshots alone are not enough. |
| [`blueprint`](https://github.com/vamsy16/ECC/tree/HEAD/skills/blueprint) | — | Turn a one-line objective into a step-by-step construction plan for multi-session, multi-agent engineering projects. Each step has a self-contained context brief so a fresh agent can execute it cold. |
| [`brand-discovery`](https://github.com/vamsy16/ECC/tree/HEAD/skills/brand-discovery) | Use when a brand needs to discover or articulate its identity through structured multi-session interviews. | Covers purpose, positioning, audience, personality, voice, narrative, and founder-brand tension across 8 modules using laddering, 5 Whys, and projective techniques. |
| [`brand-voice`](https://github.com/vamsy16/ECC/tree/HEAD/skills/brand-voice) | Use when you want voice consistency without generic AI writing tropes. | Build a source-derived writing style profile from real posts, essays, launch notes, docs, or site copy, then reuse that profile across content, outreach, and social workflows. |
| [`browser-qa`](https://github.com/vamsy16/ECC/tree/HEAD/skills/browser-qa) | — | Use this skill to automate visual testing and UI interaction verification using browser automation after deploying features. |
| [`bun-runtime`](https://github.com/vamsy16/ECC/tree/HEAD/skills/bun-runtime) | — | Bun as runtime, package manager, bundler, and test runner. When to choose Bun vs Node, migration notes, and Vercel support. |
| [`canary-watch`](https://github.com/vamsy16/ECC/tree/HEAD/skills/canary-watch) | — | Use this skill to monitor and verify a deployed URL after releases — checks HTTP endpoints, SSE streams, static assets, console errors, and performance regressions after deploys, merges, or dependency upgrades. |
| [`carrier-relationship-management`](https://github.com/vamsy16/ECC/tree/HEAD/skills/carrier-relationship-management) | Use when managing carriers, negotiating rates, evaluating carrier performance, or building freight strategies. | Codified expertise for managing carrier portfolios, negotiating freight rates, tracking carrier performance, allocating freight, and maintaining strategic carrier relationships. |
| [`cisco-ios-patterns`](https://github.com/vamsy16/ECC/tree/HEAD/skills/cisco-ios-patterns) | Use when reading, writing, or reviewing Cisco IOS / IOS-XE configuration or planning a change window. | Cisco IOS and IOS-XE review patterns for show commands, config hierarchy, wildcard masks, ACL placement, interface hygiene, and safe change-window verification. |
| [`ck`](https://github.com/vamsy16/ECC/tree/HEAD/skills/ck) | Use when a project needs context to survive across Claude Code sessions instead of being re-explained each time. | Persistent per-project memory for Claude Code. Auto-loads project context on session start, tracks sessions with git activity, and writes to native memory. |
| [`claude-devfleet`](https://github.com/vamsy16/ECC/tree/HEAD/skills/claude-devfleet) | Use when dispatching parallel coding agents across isolated worktrees and tracking their reports. | Orchestrate multi-agent coding tasks via Claude DevFleet — plan projects, dispatch parallel agents in isolated worktrees, monitor progress, and read structured reports. |
| [`click-path-audit`](https://github.com/vamsy16/ECC/tree/HEAD/skills/click-path-audit) | Use when: systematic debugging found no bugs but users report broken buttons, or after any major refactor touching shared state stores. | Trace every user-facing button/touchpoint through its full state change sequence to find bugs where functions individually work but cancel each other out, produce wrong final state, or leave the UI in an inconsistent state. |
| [`clickhouse-io`](https://github.com/vamsy16/ECC/tree/HEAD/skills/clickhouse-io) | Use when writing ClickHouse schemas or queries, or when an analytical query is too slow. | ClickHouse database patterns, query optimization, analytics, and data engineering best practices for high-performance analytical workloads. |
| [`code-tour`](https://github.com/vamsy16/ECC/tree/HEAD/skills/code-tour) | Use for onboarding tours, architecture walkthroughs, PR tours, RCA tours, and structured "explain how this works" requests. | Create CodeTour `.tour` files — persona-targeted, step-by-step walkthroughs with real file and line anchors. |
| [`codebase-onboarding`](https://github.com/vamsy16/ECC/tree/HEAD/skills/codebase-onboarding) | Use when joining a new project or setting up Claude Code for the first time in a repo. | Analyze an unfamiliar codebase and generate a structured onboarding guide with architecture map, key entry points, conventions, and a starter CLAUDE.md. |
| [`codehealth-mcp`](https://github.com/vamsy16/ECC/tree/HEAD/skills/codehealth-mcp) | Use when reviewing code quality, refactoring, checking if AI changes degraded a file, or before commit/PR. | Real-time structural Code Health via CodeScene MCP — review before edits, verify score deltas after changes, gate commits and PRs. |
| [`coding-standards`](https://github.com/vamsy16/ECC/tree/HEAD/skills/coding-standards) | Use when reviewing code quality or naming with no framework-specific skill that applies. | Baseline cross-project coding conventions for naming, readability, immutability, and code-quality review. Use detailed frontend or backend skills for framework-specific patterns. |
| [`competitive-platform-analysis`](https://github.com/vamsy16/ECC/tree/HEAD/skills/competitive-platform-analysis) | Use when scoping a competitive landscape — identifying, categorising, and score-filtering a competitor set before any benchmarking begins. | Decides who counts as a competitor, which tier they belong to, and which sources to mine. First step in the three-skill competitive pipeline; precedes benchmark-methodology. |
| [`competitive-report-structure`](https://github.com/vamsy16/ECC/tree/HEAD/skills/competitive-report-structure) | Use after benchmark-methodology has produced scored competitor profile cards. | Assembles findings into a decision-grade report: landscape map, competitor profiles, benchmarking matrix, white-space analysis, strategic recommendations, and team alignment trigger questions. |
| [`compose-multiplatform-patterns`](https://github.com/vamsy16/ECC/tree/HEAD/skills/compose-multiplatform-patterns) | Use when building Compose or Jetpack Compose UI, state, navigation, or theming in a KMP project. | Compose Multiplatform and Jetpack Compose patterns for KMP projects — state management, navigation, theming, performance, and platform-specific UI. |
| [`config-gc`](https://github.com/vamsy16/ECC/tree/HEAD/skills/config-gc) | Use when you say "clean up my config", "config GC", "too many skills", "audit my setup", "my .claude is bloated", or asks for a periodic config review. | Garbage collection for your Claude Code configuration. Periodically scans ~/.claude (skills, memory, hooks, permissions, MCP servers, caches) for redundant, stale, orphaned, or low-value items, then walks the user through a… |
| [`configure-ecc`](https://github.com/vamsy16/ECC/tree/HEAD/skills/configure-ecc) | — | Guide ECC installation, update, or reconfiguration from inside Claude Code, Codex, or Kimi while respecting each harness's real plugin, scope, and hook capabilities. |
| [`connections-optimizer`](https://github.com/vamsy16/ECC/tree/HEAD/skills/connections-optimizer) | Use when you want to clean up following lists, grow toward current priorities, or rebalance a social graph around higher-signal relationships. | Reorganize the user's X and LinkedIn network with review-first pruning, add/follow recommendations, and channel-specific warm outreach drafted in the user's real voice. |
| [`content-engine`](https://github.com/vamsy16/ECC/tree/HEAD/skills/content-engine) | Use when you want social posts, threads, scripts, content calendars, or one source asset adapted cleanly across platforms. | Create platform-native content systems for X, LinkedIn, TikTok, YouTube, newsletters, and repurposed multi-platform campaigns. |
| [`content-hash-cache-pattern`](https://github.com/vamsy16/ECC/tree/HEAD/skills/content-hash-cache-pattern) | Use when repeated file processing is slow and results should be cached and invalidated by content rather than path. | Cache expensive file processing results using SHA-256 content hashes — path-independent, auto-invalidating, with service layer separation. |
| [`context-budget`](https://github.com/vamsy16/ECC/tree/HEAD/skills/context-budget) | Use when the context window is filling up too fast and the agents, skills, MCP servers, or rules consuming it need to be identified. | Audits Claude Code context window consumption across agents, skills, MCP servers, and rules. Identifies bloat, redundant components, and produces prioritized token-savings recommendations. |
| [`continuous-agent-loop`](https://github.com/vamsy16/ECC/tree/HEAD/skills/continuous-agent-loop) | Use when running an agent loop that must self-check, gate on evals, and recover from failures. | Patterns for continuous autonomous agent loops with quality gates, evals, and recovery controls. |
| [`continuous-learning`](https://github.com/vamsy16/ECC/tree/HEAD/skills/continuous-learning) | — | [DEPRECATED - use continuous-learning-v2] Legacy v1 stop-hook skill extractor. v2 is a strict superset with instinct-based, project-scoped, hook-reliable learning. |
| [`continuous-learning-v2`](https://github.com/vamsy16/ECC/tree/HEAD/skills/continuous-learning-v2) | Use when capturing lessons from a session, managing instincts, or promoting them into skills, commands, or agents. | Instinct-based learning system that observes sessions via hooks, creates atomic instincts with confidence scoring, and evolves them into skills/commands/agents. |
| [`contract-first`](https://github.com/vamsy16/ECC/tree/HEAD/skills/contract-first) | Use when multiple consumers and providers must evolve an API or event schema without field drift, integration surprises, or one side silently redefining the interface. | Use when multiple consumers and providers must evolve an API or event schema without field drift, integration surprises, or one side silently redefining the interface. |
| [`cost-aware-llm-pipeline`](https://github.com/vamsy16/ECC/tree/HEAD/skills/cost-aware-llm-pipeline) | Use when LLM spend needs to come down, or when routing tasks across model tiers and budgets. | Cost optimization patterns for LLM API usage — model routing by task complexity, budget tracking, retry logic, and prompt caching. |
| [`cost-tracking`](https://github.com/vamsy16/ECC/tree/HEAD/skills/cost-tracking) | Use when you ask about costs, spending, usage, tokens, budgets, or cost breakdowns by model, session, or date. | Track and report Claude Code token usage, spending, and budgets from the local ECC cost-tracker metrics log. |
| [`council`](https://github.com/vamsy16/ECC/tree/HEAD/skills/council) | Use when multiple valid paths exist and you need structured disagreement before choosing. | Convene a four-voice council for ambiguous decisions, tradeoffs, and go/no-go calls. |
| [`council-multi-model`](https://github.com/vamsy16/ECC/tree/HEAD/skills/council-multi-model) | Use when an ambiguous, high-consequence decision would benefit from a separate model invocation's attempt to break the synthesis. | Add one optional external Codex critique after the existing council has produced a decision draft. |
| [`cpp-coding-standards`](https://github.com/vamsy16/ECC/tree/HEAD/skills/cpp-coding-standards) | Use when writing, reviewing, or refactoring C++ code to enforce modern, safe, and idiomatic practices. | C++ coding standards based on the C++ Core Guidelines (isocpp.github.io). |
| [`cpp-testing`](https://github.com/vamsy16/ECC/tree/HEAD/skills/cpp-testing) | — | Use only when writing/updating/fixing C++ tests, configuring GoogleTest/CTest, diagnosing failing or flaky tests, or adding coverage/sanitizers. |
| [`crosspost`](https://github.com/vamsy16/ECC/tree/HEAD/skills/crosspost) | Use when you want to distribute content across social platforms. | Multi-platform content distribution across X, LinkedIn, Threads, and Bluesky. Adapts content per platform using content-engine patterns. Never posts identical content cross-platform. |
| [`csharp-testing`](https://github.com/vamsy16/ECC/tree/HEAD/skills/csharp-testing) | Use when writing or reviewing xUnit tests, mocks, or integration tests in a C# / .NET project. | C# and .NET testing patterns with xUnit, FluentAssertions, mocking, integration tests, and test organization best practices. |
| [`customer-billing-ops`](https://github.com/vamsy16/ECC/tree/HEAD/skills/customer-billing-ops) | Use when you need to help a customer, inspect subscription state, or manage revenue-impacting billing operations. | Operate customer billing workflows such as subscriptions, refunds, churn triage, billing-portal recovery, and plan analysis using connected billing tools like Stripe. |
| [`customs-trade-compliance`](https://github.com/vamsy16/ECC/tree/HEAD/skills/customs-trade-compliance) | Use when handling customs clearance, tariff classification, trade compliance, import/export documentation, or duty optimization. | Codified expertise for customs documentation, tariff classification, duty optimization, restricted party screening, and regulatory compliance across multiple jurisdictions. |
| [`dart-flutter-patterns`](https://github.com/vamsy16/ECC/tree/HEAD/skills/dart-flutter-patterns) | Use when writing or reviewing Dart and Flutter code — state, widgets, navigation, networking, or architecture. | Production-ready Dart and Flutter patterns covering null safety, immutable state, async composition, widget architecture, popular state management frameworks (BLoC, Riverpod, Provider), GoRouter navigation, Dio networking,… |
| [`dashboard-builder`](https://github.com/vamsy16/ECC/tree/HEAD/skills/dashboard-builder) | Use when turning metrics into a working dashboard instead of a vanity board. | Build monitoring dashboards that answer real operator questions for Grafana, SigNoz, and similar platforms. |
| [`data-scraper-agent`](https://github.com/vamsy16/ECC/tree/HEAD/skills/data-scraper-agent) | Use when you want to monitor, collect, or track any public data automatically. | Build a fully automated AI-powered data collection agent for any public source — job boards, prices, news, GitHub, sports, anything. |
| [`data-throughput-accelerator`](https://github.com/vamsy16/ECC/tree/HEAD/skills/data-throughput-accelerator) | Use when large data ingestion, backfill, export, ETL, warehouse loading, manifest catch-up, or table synchronization needs to become much faster while preserving data… | Use when large data ingestion, backfill, export, ETL, warehouse loading, manifest catch-up, or table synchronization needs to become much faster while preserving data correctness. |
| [`database-migrations`](https://github.com/vamsy16/ECC/tree/HEAD/skills/database-migrations) | Use when writing a schema or data migration, planning a rollback, or aiming for zero-downtime deployment. | Database migration best practices for schema changes, data migrations, rollbacks, and zero-downtime deployments across PostgreSQL, MySQL, and common ORMs (Prisma, Drizzle, Kysely, Django, TypeORM, golang-migrate). |
| [`deep-research`](https://github.com/vamsy16/ECC/tree/HEAD/skills/deep-research) | Use when you want thorough research on any topic with evidence and citations. | Multi-source deep research using firecrawl and exa MCPs. Searches the web, synthesizes findings, and delivers cited reports with source attribution. |
| [`defi-amm-security`](https://github.com/vamsy16/ECC/tree/HEAD/skills/defi-amm-security) | Use when auditing or writing Solidity AMM, liquidity pool, or swap code. | Security checklist for Solidity AMM contracts, liquidity pools, and swap flows. Covers reentrancy, CEI ordering, donation or inflation attacks, oracle manipulation, slippage, admin controls, and integer math. |
| [`delivery-gate`](https://github.com/vamsy16/ECC/tree/HEAD/skills/delivery-gate) | Use when Claude should be mechanically blocked from declaring work finished before quality checks and learning capture actually pass. | Stop hook that blocks Claude from finishing until quality checks pass. Detects rationalization patterns (surface text heuristics), stale learning logs (filesystem mtime), and low disk space. |
| [`deployment-patterns`](https://github.com/vamsy16/ECC/tree/HEAD/skills/deployment-patterns) | Use when setting up CI/CD, containerizing an app, or checking production readiness before a release. | Deployment workflows, CI/CD pipeline patterns, Docker containerization, health checks, rollback strategies, and production readiness checklists for web applications. |
| [`design-system`](https://github.com/vamsy16/ECC/tree/HEAD/skills/design-system) | Use when generating or auditing a design system, checking visual consistency, or reviewing a PR that touches styling. | Use this skill to generate or audit design systems, check visual consistency, and review PRs that touch styling. |
| [`dev-team`](https://github.com/vamsy16/ECC/tree/HEAD/skills/dev-team) | Use when designing a feature, reviewing a proposal, or onboarding a new initiative and you want multi-role perspective without switching agents manually. | Simulate a collaborative dev team session where multiple role-based personas (PM, Architect, Developer, QA) respond to the same problem together in one session. |
| [`django-celery`](https://github.com/vamsy16/ECC/tree/HEAD/skills/django-celery) | Use when adding background jobs, scheduled tasks, or async processing to a Django app. | Django + Celery async task patterns — configuration, task design, beat scheduling, retries, canvas workflows, monitoring, and testing. |
| [`django-patterns`](https://github.com/vamsy16/ECC/tree/HEAD/skills/django-patterns) | Use when building or reviewing Django apps, DRF APIs, ORM queries, or caching. | Django architecture patterns, REST API design with DRF, ORM best practices, caching, signals, middleware, and production-grade Django apps. |
| [`django-security`](https://github.com/vamsy16/ECC/tree/HEAD/skills/django-security) | Use when reviewing Django authentication, authorization, input handling, or deployment settings. | Django security best practices, authentication, authorization, CSRF protection, SQL injection prevention, XSS prevention, and secure deployment configurations. |
| [`django-tdd`](https://github.com/vamsy16/ECC/tree/HEAD/skills/django-tdd) | Use when writing Django or DRF tests with pytest-django, or driving a Django feature test-first. | Django testing strategies with pytest-django, TDD methodology, factory_boy, mocking, coverage, and testing Django REST Framework APIs. |
| [`django-verification`](https://github.com/vamsy16/ECC/tree/HEAD/skills/django-verification) | — | Verification loop for Django projects: migrations, linting, tests with coverage, security scans, and deployment readiness checks before release or PR. |
| [`dmux-workflows`](https://github.com/vamsy16/ECC/tree/HEAD/skills/dmux-workflows) | Use when running multiple agent sessions in parallel or coordinating multi-agent development workflows. | Multi-agent orchestration using dmux (tmux pane manager for AI agents). Patterns for parallel agent workflows across Claude Code, Codex, OpenCode, and other harnesses. |
| [`docker-patterns`](https://github.com/vamsy16/ECC/tree/HEAD/skills/docker-patterns) | Use when creating or reviewing Dockerfiles and Compose services, testing installers across Linux distributions, or planning accurate native macOS and Windows validation. | Docker and Docker Compose patterns for local development, hardened CLI installer harnesses, container security, networking, volumes, and multi-service orchestration. |
| [`documentation-lookup`](https://github.com/vamsy16/ECC/tree/HEAD/skills/documentation-lookup) | — | Use up-to-date library and framework docs via Context7 MCP instead of training data. Activates for setup questions, API references, code examples, or when the user names a framework (e.g. React, Next.js, Prisma). |
| [`dotnet-patterns`](https://github.com/vamsy16/ECC/tree/HEAD/skills/dotnet-patterns) | Use when writing or reviewing C# / .NET code — DI, async, or general conventions. | Idiomatic C# and .NET patterns, conventions, dependency injection, async/await, and best practices for building robust, maintainable .NET applications. |
| [`dynamic-workflow-mode`](https://github.com/vamsy16/ECC/tree/HEAD/skills/dynamic-workflow-mode) | Use when building a task-local harness, adding eval gates, or extracting a reusable skill from ad-hoc work. | Design task-local harnesses, eval gates, and reusable skill extraction for Claude dynamic workflow mode and other adaptive agent harnesses. |
| [`e2e-testing`](https://github.com/vamsy16/ECC/tree/HEAD/skills/e2e-testing) | Use when writing Playwright tests, structuring page objects, or fixing flaky E2E runs in CI. | Playwright E2E testing patterns, Page Object Model, configuration, CI/CD integration, artifact management, and flaky test strategies. |
| [`ecc-guide`](https://github.com/vamsy16/ECC/tree/HEAD/skills/ecc-guide) | — | Guide users through ECC's current agents, skills, commands, hooks, rules, install profiles, and project onboarding by reading the live repository surface before answering. |
| [`ecc-recipes`](https://github.com/vamsy16/ECC/tree/HEAD/skills/ecc-recipes) | — | Map a described workflow to the right ECC command-GROUP with run-order and stop condition, and browse all command-group recipe families. Adds a family-grouping + run-order + when-to-stop layer on top of the flat command catalog. |
| [`ecc-tools-cost-audit`](https://github.com/vamsy16/ECC/tree/HEAD/skills/ecc-tools-cost-audit) | Use when investigating runaway PR creation, quota bypass, premium-model leakage, duplicate jobs, or GitHub App cost spikes in the ECC Tools repo. | Evidence-first ECC Tools burn and billing audit workflow. |
| [`email-ops`](https://github.com/vamsy16/ECC/tree/HEAD/skills/email-ops) | Use when you want to organize email, draft or send through the real mail surface, or prove what landed in Sent. | Evidence-first mailbox triage, drafting, send verification, and sent-mail-safe follow-up workflow for ECC. |
| [`energy-procurement`](https://github.com/vamsy16/ECC/tree/HEAD/skills/energy-procurement) | Use when procuring energy, optimizing tariffs, managing demand charges, evaluating PPAs, or developing energy strategies. | Codified expertise for electricity and gas procurement, tariff optimization, demand charge management, renewable PPA evaluation, and multi-facility energy cost management. |
| [`enterprise-agent-ops`](https://github.com/vamsy16/ECC/tree/HEAD/skills/enterprise-agent-ops) | Use when running long-lived agent workloads that need observability, security boundaries, or lifecycle control. | Operate long-lived agent workloads with observability, security boundaries, and lifecycle management. |
| [`error-handling`](https://github.com/vamsy16/ECC/tree/HEAD/skills/error-handling) | Use when designing error types, retries, circuit breakers, or user-facing failure messages in TypeScript, Python, or Go. | Patterns for robust error handling across TypeScript, Python, and Go. Covers typed errors, error boundaries, retries, circuit breakers, and user-facing error messages. |
| [`eval-harness`](https://github.com/vamsy16/ECC/tree/HEAD/skills/eval-harness) | Use when a Claude Code workflow needs a formal eval before it is trusted or changed. | Formal evaluation framework for Claude Code sessions implementing eval-driven development (EDD) principles. |
| [`everything-claude-code`](https://github.com/vamsy16/ECC/tree/HEAD/.agents/skills/everything-claude-code) | — | Development conventions and patterns for everything-claude-code. JavaScript project with conventional commits. |
| [`evm-token-decimals`](https://github.com/vamsy16/ECC/tree/HEAD/skills/evm-token-decimals) | Use when handling token amounts across EVM chains, or when a balance, price, or transfer amount is off by orders of magnitude. | Prevent silent decimal mismatch bugs across EVM chains. Covers runtime decimal lookup, chain-aware caching, bridged-token precision drift, and safe normalization for bots, dashboards, and DeFi tools. |
| [`exa-search`](https://github.com/vamsy16/ECC/tree/HEAD/skills/exa-search) | Use when you need web search, code examples, company intel, people lookup, or AI-powered deep research with Exa's neural search engine. | Neural search via Exa MCP for web, code, and company research. |
| [`fal-ai-media`](https://github.com/vamsy16/ECC/tree/HEAD/skills/fal-ai-media) | Use when you want to generate images, videos, or audio with AI. | Unified media generation via fal.ai MCP — image, video, and audio. Covers text-to-image (Nano Banana), text/image-to-video (Seedance, Kling, Veo 3), text-to-speech (CSM-1B), and video-to-audio (ThinkSound). |
| [`fastapi-patterns`](https://github.com/vamsy16/ECC/tree/HEAD/skills/fastapi-patterns) | Use when building or reviewing FastAPI apps — Pydantic schemas, dependencies, async handlers, auth, or tests. | FastAPI best practices covering project structure, Pydantic v2 schemas, dependency injection, async handlers, authentication, authorization, transactional service layers, and testing with httpx and pytest. |
| [`finance-billing-ops`](https://github.com/vamsy16/ECC/tree/HEAD/skills/finance-billing-ops) | Use when you want a sales snapshot, pricing comparison, duplicate-charge diagnosis, or code-backed billing reality instead of generic payments advice. | Evidence-first revenue, pricing, refunds, team-billing, and billing-model truth workflow for ECC. |
| [`flox-environments`](https://github.com/vamsy16/ECC/tree/HEAD/skills/flox-environments) | Use when setting up project toolchains for any language, installing system-level dependencies (compilers, databases, native libs like openssl/BLAS), pinning exact… | Create reproducible, cross-platform (macOS/Linux) development environments with Flox, a declarative Nix-based environment manager. |
| [`flutter-dart-code-review`](https://github.com/vamsy16/ECC/tree/HEAD/skills/flutter-dart-code-review) | Use when reviewing Flutter or Dart code, whatever state management library the project uses. | Library-agnostic Flutter/Dart code review checklist covering widget best practices, state management patterns (BLoC, Riverpod, Provider, GetX, MobX, Signals), Dart idioms, performance, accessibility, security, and clean… |
| [`foundation-models-on-device`](https://github.com/vamsy16/ECC/tree/HEAD/skills/foundation-models-on-device) | Use when adding on-device LLM features with Apple FoundationModels on iOS 26+. | Apple FoundationModels framework for on-device LLM — text generation, guided generation with @Generable, tool calling, and snapshot streaming in iOS 26+. |
| [`frontend-a11y`](https://github.com/vamsy16/ECC/tree/HEAD/skills/frontend-a11y) | Use when building any interactive UI component or form. | Accessibility patterns for React and Next.js — semantic HTML, ARIA attributes, form labeling, keyboard navigation, focus management, and screen reader support. |
| [`frontend-design-direction`](https://github.com/vamsy16/ECC/tree/HEAD/skills/frontend-design-direction) | Use when building or improving websites, dashboards, applications, components, landing pages, visual tools, or any web UI that needs stronger product-specific design… | Set an ECC-specific frontend design direction for production UI work. |
| [`frontend-patterns`](https://github.com/vamsy16/ECC/tree/HEAD/skills/frontend-patterns) | Use when building or reviewing React or Next.js components, state, or render performance. | Frontend development patterns for React, Next.js, state management, performance optimization, and UI best practices. |
| [`frontend-slides`](https://github.com/vamsy16/ECC/tree/HEAD/skills/frontend-slides) | Use when you want to build a presentation, convert a PPT/PPTX to web, or create slides for a talk/pitch. | Create stunning, animation-rich HTML presentations from scratch or by converting PowerPoint files. Helps non-designers discover their aesthetic through visual exploration rather than abstract choices. |
| [`fsharp-testing`](https://github.com/vamsy16/ECC/tree/HEAD/skills/fsharp-testing) | Use when writing F# tests with xUnit, FsUnit, Unquote, or FsCheck. | F# testing patterns with xUnit, FsUnit, Unquote, FsCheck property-based testing, integration tests, and test organization best practices. |
| [`gan-style-harness`](https://github.com/vamsy16/ECC/tree/HEAD/skills/gan-style-harness) | Use when a feature should be built autonomously through generator and evaluator iteration until it clears a quality bar. | GAN-inspired Generator-Evaluator agent harness for building high-quality applications autonomously. Based on Anthropic's March 2026 harness design paper. |
| [`gateguard`](https://github.com/vamsy16/ECC/tree/HEAD/skills/gateguard) | — | Fact-forcing gate that blocks Edit/Write/Bash (including MultiEdit) and demands concrete investigation (importers, data schemas, user instruction) before allowing the action. |
| [`generating-python-installer`](https://github.com/vamsy16/ECC/tree/HEAD/skills/generating-python-installer) | Use when a Python app must ship as a minimal, fast-starting Windows installer; not for basic script-to-exe conversion. | Commercial-grade Python installer expert for Windows: Nuitka extreme compilation, dist slimming, DLL footprint analysis, and Inno Setup packaging to ship the smallest, fastest installers. |
| [`git-workflow`](https://github.com/vamsy16/ECC/tree/HEAD/skills/git-workflow) | Use when choosing a branching strategy, writing commit conventions, deciding merge versus rebase, or resolving conflicts. | Git workflow patterns including branching strategies, commit conventions, merge vs rebase, conflict resolution, and collaborative development best practices for teams of all sizes. |
| [`github-ops`](https://github.com/vamsy16/ECC/tree/HEAD/skills/github-ops) | Use when you want to manage GitHub issues, PRs, CI status, releases, contributors, stale items, or any GitHub operational task beyond simple git commands. | GitHub repository operations, automation, and management. Issue triage, PR management, CI/CD operations, release management, and security monitoring using the gh CLI. |
| [`golang-patterns`](https://github.com/vamsy16/ECC/tree/HEAD/skills/golang-patterns) | Use when writing or reviewing Go code and idiomatic structure or conventions are in question. | Idiomatic Go patterns, best practices, and conventions for building robust, efficient, and maintainable Go applications. |
| [`golang-testing`](https://github.com/vamsy16/ECC/tree/HEAD/skills/golang-testing) | Use when writing Go tests — table-driven cases, subtests, benchmarks, fuzzing, or coverage. | Go testing patterns including table-driven tests, subtests, benchmarks, fuzzing, and test coverage. Follows TDD methodology with idiomatic Go practices. |
| [`google-workspace-ops`](https://github.com/vamsy16/ECC/tree/HEAD/skills/google-workspace-ops) | Use when you need to find, summarize, edit, migrate, or clean up Google Workspace assets without dropping to raw tool calls. | Operate across Google Drive, Docs, Sheets, and Slides as one workflow surface for plans, trackers, decks, and shared documents. |
| [`growth-log`](https://github.com/vamsy16/ECC/tree/HEAD/skills/growth-log) | Use after a complex task, failure, or when reviewing what was learned. | Teaches how to write growth logs that extract reusable patterns — not diary entries. |
| [`healthcare-cdss-patterns`](https://github.com/vamsy16/ECC/tree/HEAD/skills/healthcare-cdss-patterns) | Use when building clinical decision support — drug interaction checks, dose validation, clinical scoring, or alert severity. | Clinical Decision Support System (CDSS) development patterns. Drug interaction checking, dose validation, clinical scoring (NEWS2, qSOFA), alert severity classification, and integration into EMR workflows. |
| [`healthcare-emr-patterns`](https://github.com/vamsy16/ECC/tree/HEAD/skills/healthcare-emr-patterns) | Use when building EMR or EHR features such as encounter workflows, prescription generation, or clinical data entry UI. | EMR/EHR development patterns for healthcare applications. Clinical safety, encounter workflows, prescription generation, clinical decision support integration, and accessibility-first UI for medical data entry. |
| [`healthcare-eval-harness`](https://github.com/vamsy16/ECC/tree/HEAD/skills/healthcare-eval-harness) | Use when a healthcare deployment must be gated on patient-safety tests for CDSS accuracy, PHI exposure, and workflow integrity. | Patient safety evaluation harness for healthcare application deployments. Automated test suites for CDSS accuracy, PHI exposure, clinical workflow integrity, and integration compliance. Blocks deployments on safety failures. |
| [`healthcare-phi-compliance`](https://github.com/vamsy16/ECC/tree/HEAD/skills/healthcare-phi-compliance) | Use when code touches PHI or PII in a healthcare system, or when auditing access control, audit trails, or leak vectors. | Protected Health Information (PHI) and Personally Identifiable Information (PII) compliance patterns for healthcare applications. Covers data classification, access control, audit trails, encryption, and common leak vectors. |
| [`hermes-imports`](https://github.com/vamsy16/ECC/tree/HEAD/skills/hermes-imports) | Use when preparing a Hermes workflow for public ECC reuse without leaking private workspace state, credentials, or local-only paths. | Convert local Hermes operator workflows into sanitized ECC skills and release-pack artifacts. |
| [`hexagonal-architecture`](https://github.com/vamsy16/ECC/tree/HEAD/skills/hexagonal-architecture) | Use when introducing or refactoring toward Ports and Adapters, or when domain logic has become entangled with I/O. | Design, implement, and refactor Ports & Adapters systems with clear domain boundaries, dependency inversion, and testable use-case orchestration across TypeScript, Java, Kotlin, and Go services. |
| [`hipaa-compliance`](https://github.com/vamsy16/ECC/tree/HEAD/skills/hipaa-compliance) | Use when a task is explicitly framed around HIPAA, PHI handling, covered entities, BAAs, breach posture, or US healthcare compliance requirements. | HIPAA-specific entrypoint for healthcare privacy and security work. |
| [`homelab-network-readiness`](https://github.com/vamsy16/ECC/tree/HEAD/skills/homelab-network-readiness) | — | Readiness checklist for homelab VLAN segmentation, local DNS filtering, and WireGuard-style remote access before changing router, firewall, DHCP, or VPN configuration. |
| [`homelab-network-setup`](https://github.com/vamsy16/ECC/tree/HEAD/skills/homelab-network-setup) | Use when planning or fixing a home or homelab network — gateway, switch, AP, IP ranges, DHCP, DNS, or cabling. | Practical home and homelab network planning for gateways, switches, access points, IP ranges, DHCP reservations, DNS, cabling, and common beginner mistakes. |
| [`homelab-pihole-dns`](https://github.com/vamsy16/ECC/tree/HEAD/skills/homelab-pihole-dns) | Use when the task explicitly involves Pi-hole — installing it, managing blocklists, configuring DoH or DHCP, adding local DNS records, or diagnosing DNS resolution with… | Pi-hole installation, blocklist management, DNS-over-HTTPS setup, DHCP integration, local DNS records, and troubleshooting broken DNS resolution on a home network. |
| [`homelab-vlan-segmentation`](https://github.com/vamsy16/ECC/tree/HEAD/skills/homelab-vlan-segmentation) | Use when splitting a home network into IoT, guest, trusted, and server VLANs on UniFi, pfSense/OPNsense, or MikroTik. | Segmenting home networks into VLANs for IoT, guest, trusted, and server traffic using UniFi, pfSense/OPNsense, and MikroTik — including switch trunk config, firewall rules, and wireless SSID mapping. |
| [`homelab-wireguard-vpn`](https://github.com/vamsy16/ECC/tree/HEAD/skills/homelab-wireguard-vpn) | Use when setting up WireGuard for remote access to a home network, or deciding between split and full tunnel routing. | WireGuard VPN server setup, peer configuration, key generation, split tunneling vs full tunnel routing, and remote access to a home network from mobile and laptop clients. |
| [`hookify-rules`](https://github.com/vamsy16/ECC/tree/HEAD/skills/hookify-rules) | — | This skill should be used when the user asks to create a hookify rule, write a hook rule, configure hookify, add a hookify rule, or needs guidance on hookify rule syntax and patterns. |
| [`inherit-legacy-style`](https://github.com/vamsy16/ECC/tree/HEAD/skills/inherit-legacy-style) | Use when you type /inherit-legacy-style, or when onboarding an AI coding agent onto a hand-written legacy project and you need to prevent "style drift" (the model… | Legacy-project style inheritance skill. Language- and framework-agnostic — it aligns meta-architecture only, not syntax. Once run, it becomes a behavioral constraint on all subsequent coding tasks. |
| [`intent-driven-development`](https://github.com/vamsy16/ECC/tree/HEAD/skills/intent-driven-development) | Use when a user asks to clarify a feature, define acceptance criteria, de-risk a security/data/migration/integration change, prepare implementation requirements for… | Turn ambiguous or high-impact product and engineering changes into scoped, verifiable acceptance criteria before or alongside implementation. |
| [`inventory-demand-planning`](https://github.com/vamsy16/ECC/tree/HEAD/skills/inventory-demand-planning) | Use when forecasting demand, setting safety stock, planning replenishment, managing promotions, or optimizing inventory levels. | Codified expertise for demand forecasting, safety stock optimization, replenishment planning, and promotional lift estimation at multi-location retailers. |
| [`investor-materials`](https://github.com/vamsy16/ECC/tree/HEAD/skills/investor-materials) | Use when you need investor-facing documents, projections, use-of-funds tables, milestone plans, or materials that must stay internally consistent across multiple… | Create and update pitch decks, one-pagers, investor memos, accelerator applications, financial models, and fundraising materials. |
| [`investor-outreach`](https://github.com/vamsy16/ECC/tree/HEAD/skills/investor-outreach) | Use when you want outreach to angels, VCs, strategic investors, or accelerators and needs concise, personalized, investor-facing messaging. | Draft cold emails, warm intro blurbs, follow-ups, update emails, and investor communications for fundraising. |
| [`ios-icon-gen`](https://github.com/vamsy16/ECC/tree/HEAD/skills/ios-icon-gen) | Use when generating icons, creating icon assets, adding icons to asset catalog, or searching for icons for iOS projects. | Generate iOS app icons as PNG imagesets for Xcode asset catalogs from SF Symbols (5000+ Apple-native) or Iconify API (275k+ open source icons from 200+ collections). |
| [`iterative-retrieval`](https://github.com/vamsy16/ECC/tree/HEAD/skills/iterative-retrieval) | Use when a subagent lacks the context it needs and retrieval must be refined across passes. | Pattern for progressively refining context retrieval to solve the subagent context problem. |
| [`ito-baskets`](https://github.com/vamsy16/ECC/tree/HEAD/skills/ito-baskets) | Use when a user asks to browse or index Itô baskets, compare a basket against notes or a thesis, research prediction-market events/venues/liquidity, or plan a basket or… | Read-only Itô basket and prediction-market data skill. Index the live basket catalog, compare a basket against user-supplied research or a watchlist, build a source-grounded market brief, or draft a non-executable planning… |
| [`ito-compute`](https://github.com/vamsy16/ECC/tree/HEAD/skills/ito-compute) | Use when a user asks to find H100/H200 capacity, request a fixed compute rate, check Itô compute status, validate GPU nodes, revoke Itô access, or rent or purchase GPU… | Query live GPU inventory, submit an authenticated Itô fixed-rate RFQ, inspect RFQ or procurement status, revoke device credentials, and run explicitly gated node qualification through the separately installed canonical CLI. |
| [`ito-inference`](https://github.com/vamsy16/ECC/tree/HEAD/skills/ito-inference) | Use after ito-compute has booked GPU nodes and you ask for an OpenAI-compatible endpoint, ito-serve, hosted Kimi, or self-hosted open-weights inference. | Inspect the availability of model serving on a completed Itô compute booking and, when the canonical backend becomes available, hand off an explicitly confirmed serving manifest. ECC implements no serving stack of its own. |
| [`ito-training`](https://github.com/vamsy16/ECC/tree/HEAD/skills/ito-training) | Use after ito-compute has booked GPU nodes and you want pre-training, fine-tuning, or RL on that metal. | Inspect the availability of ML training on a completed Itô compute booking and, when the canonical backend becomes available, hand off an explicitly confirmed training manifest. ECC implements no training stack of its own. |
| [`java-coding-standards`](https://github.com/vamsy16/ECC/tree/HEAD/skills/java-coding-standards) | Use when writing or reviewing Java in a Spring Boot or Quarkus service. | Java coding standards for Spring Boot and Quarkus services: naming, immutability, Optional usage, streams, exceptions, generics, CDI, reactive patterns, and project layout. Automatically applies framework-specific conventions. |
| [`jira-integration`](https://github.com/vamsy16/ECC/tree/HEAD/skills/jira-integration) | Use this skill when retrieving Jira tickets, analyzing requirements, updating ticket status, adding comments, or transitioning issues. | Provides Jira API patterns via MCP or direct REST calls. |
| [`jpa-patterns`](https://github.com/vamsy16/ECC/tree/HEAD/skills/jpa-patterns) | Use when designing JPA entities or relationships, or when a Hibernate query, transaction, or N+1 problem needs fixing. | JPA/Hibernate patterns for entity design, relationships, query optimization, transactions, auditing, indexing, pagination, and pooling in Spring Boot. |
| [`knowledge-ops`](https://github.com/vamsy16/ECC/tree/HEAD/skills/knowledge-ops) | Use when you want to save, organize, sync, deduplicate, or search across their knowledge systems. | Knowledge base management, ingestion, sync, and retrieval across multiple storage layers (local files, MCP memory, vector stores, Git repos). |
| [`kotlin-coroutines-flows`](https://github.com/vamsy16/ECC/tree/HEAD/skills/kotlin-coroutines-flows) | Use when writing coroutines or Flow code on Android or KMP, or debugging cancellation and concurrency. | Kotlin Coroutines and Flow patterns for Android and KMP — structured concurrency, Flow operators, StateFlow, error handling, and testing. |
| [`kotlin-exposed-patterns`](https://github.com/vamsy16/ECC/tree/HEAD/skills/kotlin-exposed-patterns) | Use when working with the Exposed ORM — DSL or DAO queries, transactions, pooling, or migrations. | JetBrains Exposed ORM patterns including DSL queries, DAO pattern, transactions, HikariCP connection pooling, Flyway migrations, and repository pattern. |
| [`kotlin-ktor-patterns`](https://github.com/vamsy16/ECC/tree/HEAD/skills/kotlin-ktor-patterns) | Use when building a Ktor server — routing, plugins, auth, DI, serialization, or tests. | Ktor server patterns including routing DSL, plugins, authentication, Koin DI, kotlinx.serialization, WebSockets, and testApplication testing. |
| [`kotlin-patterns`](https://github.com/vamsy16/ECC/tree/HEAD/skills/kotlin-patterns) | Use when writing or reviewing Kotlin code and idiomatic structure or null safety is in question. | Idiomatic Kotlin patterns, best practices, and conventions for building robust, efficient, and maintainable Kotlin applications with coroutines, null safety, and DSL builders. |
| [`kotlin-testing`](https://github.com/vamsy16/ECC/tree/HEAD/skills/kotlin-testing) | Use when writing Kotlin tests with Kotest or MockK, or testing coroutines and checking coverage. | Kotlin testing patterns with Kotest, MockK, coroutine testing, property-based testing, and Kover coverage. Follows TDD methodology with idiomatic Kotlin practices. |
| [`kubernetes-patterns`](https://github.com/vamsy16/ECC/tree/HEAD/skills/kubernetes-patterns) | Use when writing or reviewing Kubernetes manifests, or debugging probes, RBAC, autoscaling, or resource limits. | Kubernetes workload patterns, resource management, RBAC, probes, autoscaling, ConfigMap/Secret handling, and kubectl debugging for production-grade deployments. |
| [`laravel-patterns`](https://github.com/vamsy16/ECC/tree/HEAD/skills/laravel-patterns) | Use when building or reviewing Laravel apps — controllers, Eloquent, service layers, queues, or API resources. | Laravel architecture patterns, routing/controllers, Eloquent ORM, service layers, queues, events, caching, and API resources for production apps. |
| [`laravel-plugin-discovery`](https://github.com/vamsy16/ECC/tree/HEAD/skills/laravel-plugin-discovery) | Use when you want to find plugins, check package health, or assess Laravel/PHP compatibility. | Discover and evaluate Laravel packages via LaraPlugins.io MCP. |
| [`laravel-security`](https://github.com/vamsy16/ECC/tree/HEAD/skills/laravel-security) | Use when reviewing Laravel auth, Eloquent safety, CSRF, XSS, API security, or deployment configuration. | Laravel security best practices — authentication, authorization, Eloquent safety, CSRF, XSS prevention, API security, and secure deployment configurations. |
| [`laravel-tdd`](https://github.com/vamsy16/ECC/tree/HEAD/skills/laravel-tdd) | Use when writing Laravel tests with PHPUnit or Pest, or driving a Laravel feature test-first. | Laravel testing strategies with PHPUnit, Pest, model factories, HTTP tests, Sanctum authentication testing, mocking, and coverage. |
| [`laravel-verification`](https://github.com/vamsy16/ECC/tree/HEAD/skills/laravel-verification) | Use when verifying a Laravel project before merge or deploy — lint, static analysis, tests, coverage, security. | Verification loop for Laravel projects: env checks, linting, static analysis, tests with coverage, security scans, and deployment readiness. |
| [`latency-critical-systems`](https://github.com/vamsy16/ECC/tree/HEAD/skills/latency-critical-systems) | Use for latency-sensitive systems such as realtime dashboards, market data, streaming agents, execution gateways, queues, caches, or HFT-like infrastructure where… | Use for latency-sensitive systems such as realtime dashboards, market data, streaming agents, execution gateways, queues, caches, or HFT-like infrastructure where freshness and p95 latency matter. |
| [`lead-intelligence`](https://github.com/vamsy16/ECC/tree/HEAD/skills/lead-intelligence) | Use when you want to find, qualify, and reach high-value contacts. | AI-native lead intelligence and outreach pipeline. Replaces Apollo, Clay, and ZoomInfo with agent-powered signal scoring, mutual ranking, warm path discovery, source-derived voice modeling, and channel-specific outreach across… |
| [`liquid-glass-design`](https://github.com/vamsy16/ECC/tree/HEAD/skills/liquid-glass-design) | Use when building iOS 26 Liquid Glass UI in SwiftUI, UIKit, or WidgetKit. | iOS 26 Liquid Glass design system — dynamic glass material with blur, reflection, and interactive morphing for SwiftUI, UIKit, and WidgetKit. |
| [`living-docs-governance`](https://github.com/vamsy16/ECC/tree/HEAD/skills/living-docs-governance) | — | Keep a long-lived project's documentation from rotting by assigning existing project docs clear constitution, map, status, and history roles, then wiring the active agent harness to those canonical sources. |
| [`llm-trading-agent-security`](https://github.com/vamsy16/ECC/tree/HEAD/skills/llm-trading-agent-security) | Use when an autonomous agent holds wallet or transaction authority and its limits, simulation, or key handling need review. | Security patterns for autonomous trading agents with wallet or transaction authority. Covers prompt injection, spend limits, pre-send simulation, circuit breakers, MEV protection, and key handling. |
| [`logistics-exception-management`](https://github.com/vamsy16/ECC/tree/HEAD/skills/logistics-exception-management) | Use when handling shipping exceptions, freight claims, delivery issues, or carrier disputes. | Codified expertise for handling freight exceptions, shipment delays, damages, losses, and carrier disputes. Informed by logistics professionals with 15+ years operational experience. |
| [`loop-design-check`](https://github.com/vamsy16/ECC/tree/HEAD/skills/loop-design-check) | Use when designing an autonomous agent loop, or when you already have one and worry it will spin, cheat, or run a wrong answer to the end. | Design a goal-oriented agent loop, and review it for the ways loops go wrong — spinning and burning tokens, Goodhart-gaming the verifier, or running a wrong answer to completion. |
| [`mailtrap-email-integration`](https://github.com/vamsy16/ECC/tree/HEAD/skills/mailtrap-email-integration) | Use when implementing email-sending features, debugging delivery issues, or setting up safe dev/staging email testing. | Guides agents through integrating transactional email sending via Mailtrap's Email API, including sandbox testing, domain verification, and API authentication. |
| [`make-interfaces-feel-better`](https://github.com/vamsy16/ECC/tree/HEAD/skills/make-interfaces-feel-better) | Use when reviewing or improving UI spacing, typography, borders, shadows, motion, hit areas, icons, text wrapping, and interaction states. | Apply concrete design-engineering details that make interfaces feel polished. |
| [`manim-video`](https://github.com/vamsy16/ECC/tree/HEAD/skills/manim-video) | Use when you want a clean animated explainer rather than a generic talking-head script. | Build reusable Manim explainers for technical concepts, graphs, system diagrams, and product walkthroughs, then hand off to the wider ECC video stack if needed. |
| [`market-research`](https://github.com/vamsy16/ECC/tree/HEAD/skills/market-research) | Use when you want market sizing, competitor comparisons, fund research, technology scans, or research that informs business decisions. | Conduct market research, competitive analysis, investor due diligence, and industry intelligence with source attribution and decision-oriented summaries. |
| [`marketing-campaign`](https://github.com/vamsy16/ECC/tree/HEAD/skills/marketing-campaign) | Use when planning or executing a multi-channel product launch, or producing landing page, email, social, or ad copy. | End-to-end marketing campaign planning and execution. Covers audience research, positioning, campaign angle definition, landing page copy, email sequences, social posts, ad copy, short-form video scripts, and content calendars. |
| [`mcp-server-patterns`](https://github.com/vamsy16/ECC/tree/HEAD/skills/mcp-server-patterns) | Use when building or debugging an MCP server — tools, resources, prompts, validation, or transport choice. | Build MCP servers with Node/TypeScript SDK — tools, resources, prompts, Zod validation, stdio vs Streamable HTTP. Use Context7 or official MCP docs for latest API. |
| [`messages-ops`](https://github.com/vamsy16/ECC/tree/HEAD/skills/messages-ops) | Use when you want to read texts or DMs, recover a recent one-time code, inspect a thread before replying, or prove which message source was actually checked. | Evidence-first live messaging workflow for ECC. |
| [`ml-adoption-playbook`](https://github.com/vamsy16/ECC/tree/HEAD/skills/ml-adoption-playbook) | Use when adding a machine learning capability to a codebase that has none, from problem framing through a baseline model. | End-to-end methodology for AI agents and software engineers to add machine learning algorithms to existing non-ML codebases. Covers problem framing, data readiness, architectural decoupling, and baseline model integration. |
| [`mle-workflow`](https://github.com/vamsy16/ECC/tree/HEAD/skills/mle-workflow) | Use when building, reviewing, or hardening ML systems beyond one-off notebooks. | Production machine-learning engineering workflow for data contracts, reproducible training, model evaluation, deployment, monitoring, and rollback. |
| [`motion-advanced`](https://github.com/vamsy16/ECC/tree/HEAD/skills/motion-advanced) | Use when building drag and drop, gestures, text or SVG animation, or imperative animation sequences in React or Next.js. | Advanced motion patterns for React / Next.js — drag & drop, gestures, text animations, SVG path drawing, custom hooks, imperative sequences (useAnimate), loaders, and the full API decision tree. Requires motion-foundations. |
| [`motion-foundations`](https://github.com/vamsy16/ECC/tree/HEAD/skills/motion-foundations) | Use when setting up motion tokens, spring presets, reduced-motion handling, or SSR-safe animation in React or Next.js. | Motion tokens, spring presets, performance rules, device adaptation, accessibility enforcement, and SSR safety for React / Next.js using motion/react. Foundation layer — all other motion skills depend on this. |
| [`motion-patterns`](https://github.com/vamsy16/ECC/tree/HEAD/skills/motion-patterns) | Use when animating a specific UI element in React or Next.js — button, modal, toast, stagger, page transition, or scroll. | Production-ready animation patterns for React / Next.js — button, modal, toast, stagger, page transitions, exit animations, scroll, and layout — built on motion-foundations tokens and springs. |
| [`motion-ui`](https://github.com/vamsy16/ECC/tree/HEAD/skills/motion-ui) | Use when implementing animations, transitions, or motion patterns. | Production-ready UI motion system for React/Next.js. |
| [`mysql-patterns`](https://github.com/vamsy16/ECC/tree/HEAD/skills/mysql-patterns) | Use when designing MySQL or MariaDB schemas and indexes, or when a query, transaction, or replica lags. | MySQL and MariaDB schema, query, indexing, transaction, replication, and connection-pool patterns for production backends. |
| [`nanoclaw-repl`](https://github.com/vamsy16/ECC/tree/HEAD/skills/nanoclaw-repl) | Use when operating or extending the NanoClaw REPL. | Operate and extend NanoClaw v2, ECC's zero-dependency session-aware REPL built on claude -p. |
| [`nasiko-control-plane`](https://github.com/vamsy16/ECC/tree/HEAD/skills/nasiko-control-plane) | — | Use the experimental Nasiko CLI lifecycle bridge for pinned installation, read-only status, and qualified uninstall with explicit consent and telemetry and secrets boundaries. |
| [`nestjs-patterns`](https://github.com/vamsy16/ECC/tree/HEAD/skills/nestjs-patterns) | Use when building or reviewing a NestJS backend — modules, providers, DTO validation, guards, or interceptors. | NestJS architecture patterns for modules, controllers, providers, DTO validation, guards, interceptors, config, and production-grade TypeScript backends. |
| [`netmiko-ssh-automation`](https://github.com/vamsy16/ECC/tree/HEAD/skills/netmiko-ssh-automation) | Use when automating network device access with Python Netmiko, whether collecting state or pushing guarded config changes. | Safe Python Netmiko patterns for read-only collection, bounded batch SSH, TextFSM parsing, guarded config changes, timeouts, and network automation error handling. |
| [`network-bgp-diagnostics`](https://github.com/vamsy16/ECC/tree/HEAD/skills/network-bgp-diagnostics) | Use when a BGP neighbor is down, routes are missing, or prefix policy and AS path need inspection. | Diagnostics-only BGP troubleshooting patterns for neighbor state, route exchange, prefix policy, AS path inspection, and safe evidence collection. |
| [`network-config-validation`](https://github.com/vamsy16/ECC/tree/HEAD/skills/network-config-validation) | Use when reviewing a router or switch configuration before deployment. | Pre-deployment checks for router and switch configuration, including dangerous commands, duplicate addresses, subnet overlaps, stale references, management-plane risk, and IOS-style security hygiene. |
| [`network-interface-health`](https://github.com/vamsy16/ECC/tree/HEAD/skills/network-interface-health) | Use when an interface shows errors, drops, CRCs, flapping, or a duplex or speed mismatch. | Diagnose interface errors, drops, CRCs, duplex mismatches, flapping, speed negotiation issues, and counter trends on routers, switches, and Linux hosts. |
| [`nextjs-turbopack`](https://github.com/vamsy16/ECC/tree/HEAD/skills/nextjs-turbopack) | — | Next.js 16+ and Turbopack — incremental bundling, FS caching, dev speed, and when to use Turbopack vs webpack. |
| [`nodejs-keccak256`](https://github.com/vamsy16/ECC/tree/HEAD/skills/nodejs-keccak256) | Use when hashing for Ethereum in JavaScript or TypeScript, or when a selector, signature, storage slot, or derived address is wrong. | Prevent Ethereum hashing bugs in JavaScript and TypeScript. Node's sha3-256 is NIST SHA3, not Ethereum Keccak-256, and silently breaks selectors, signatures, storage slots, and address derivation. |
| [`nutrient-document-processing`](https://github.com/vamsy16/ECC/tree/HEAD/skills/nutrient-document-processing) | Use when converting, OCRing, extracting from, redacting, signing, or filling documents via the Nutrient DWS API. | Process, convert, OCR, extract, redact, sign, and fill documents using the Nutrient DWS API. Works with PDFs, DOCX, XLSX, PPTX, HTML, and images. |
| [`nuxt4-patterns`](https://github.com/vamsy16/ECC/tree/HEAD/skills/nuxt4-patterns) | Use when building or reviewing a Nuxt 4 app, or debugging hydration mismatches and SSR-safe data fetching. | Nuxt 4 app patterns for hydration safety, performance, route rules, lazy loading, and SSR-safe data fetching with useFetch and useAsyncData. |
| [`openclaw-persona-forge`](https://github.com/vamsy16/ECC/tree/HEAD/skills/openclaw-persona-forge) | — | 为 OpenClaw AI Agent 锻造完整的龙虾灵魂方案。根据用户偏好或随机抽卡， 输出身份定位、灵魂描述(SOUL.md)、角色化底线规则、名字和头像生图提示词。 如当前环境提供已审核的生图 skill，可自动生成统一风格头像图片。 当用户需要创建、设计或定制 OpenClaw 龙虾灵魂时使用。 不适用于：微调已有 SOUL.md、非 OpenClaw 平台的角色设计、纯工具型无性格 Agent。 触发词：龙虾灵魂、虾魂、OpenClaw… |
| [`opensource-pipeline`](https://github.com/vamsy16/ECC/tree/HEAD/skills/opensource-pipeline) | Use when a private project must be forked, stripped of secrets, and packaged for public release. | Open-source pipeline: fork, sanitize, and package private projects for safe public release. Chains 3 agents (forker, sanitizer, packager). Triggers: '/opensource', 'open source this', 'make this public', 'prepare for open source'. |
| [`orch-add-feature`](https://github.com/vamsy16/ECC/tree/HEAD/skills/orch-add-feature) | Use when adding a capability that does not exist yet. | Orchestrate building a brand-new feature end to end — research, plan, TDD implementation, review, and gated commit — by delegating each phase to the matching ECC agent. |
| [`orch-build-mvp`](https://github.com/vamsy16/ECC/tree/HEAD/skills/orch-build-mvp) | Use when a design or spec document must become a running MVP through planned vertical slices. | Orchestrate bootstrapping a working MVP from a design or spec document — ingest the doc, plan thin vertical slices, scaffold the first end-to-end slice, then TDD-implement, review, and gated commit. |
| [`orch-change-feature`](https://github.com/vamsy16/ECC/tree/HEAD/skills/orch-change-feature) | Use when behavior is not broken but should be different. | Orchestrate altering an existing, working feature to new desired behavior — update its tests to the new spec, change the implementation to match, review, and gated commit. |
| [`orch-fix-defect`](https://github.com/vamsy16/ECC/tree/HEAD/skills/orch-fix-defect) | Use when existing behavior is broken or wrong. | Orchestrate fixing a bug — reproduce it as a failing regression test, fix to green, review, and gated commit — by delegating each phase to the matching ECC agent. |
| [`orch-pipeline`](https://github.com/vamsy16/ECC/tree/HEAD/skills/orch-pipeline) | — | Shared orchestration engine for the orch-* skill family. Defines the gated Research-Plan-TDD-Review-Commit pipeline, the size classifier, the agent map, and the two human gates that the orch-* operation skills delegate to. |
| [`orch-refine-code`](https://github.com/vamsy16/ECC/tree/HEAD/skills/orch-refine-code) | Use when the structure should improve but behavior must not change. | Orchestrate a behavior-preserving refactor — confirm tests are green, restructure without changing behavior, keep tests green, review, and gated commit. |
| [`parallel-execution-optimizer`](https://github.com/vamsy16/ECC/tree/HEAD/skills/parallel-execution-optimizer) | Use when you want a task done much faster through parallel work, concurrent agents, batched tool calls, isolated worktrees, or many independent verification lanes… | Use when you want a task done much faster through parallel work, concurrent agents, batched tool calls, isolated worktrees, or many independent verification lanes without losing correctness. |
| [`perl-patterns`](https://github.com/vamsy16/ECC/tree/HEAD/skills/perl-patterns) | Use when writing or reviewing modern Perl 5.36+ code. | Modern Perl 5.36+ idioms, best practices, and conventions for building robust, maintainable Perl applications. |
| [`perl-security`](https://github.com/vamsy16/ECC/tree/HEAD/skills/perl-security) | Use when reviewing Perl input handling, process execution, DBI queries, or web-facing code. | Comprehensive Perl security covering taint mode, input validation, safe process execution, DBI parameterized queries, web security (XSS/SQLi/CSRF), and perlcritic security policies. |
| [`perl-testing`](https://github.com/vamsy16/ECC/tree/HEAD/skills/perl-testing) | Use when writing Perl tests with Test2::V0 or Test::More, or measuring coverage. | Perl testing patterns using Test2::V0, Test::More, prove runner, mocking, coverage with Devel::Cover, and TDD methodology. |
| [`plan-canvas`](https://github.com/vamsy16/ECC/tree/HEAD/skills/plan-canvas) | Use when presenting a plan for review, or when feedback like "move this, change that" is easier pointed at than typed. | Open plans and HTML artifacts in a local browser canvas where the human annotates elements, chats, and approves or requests changes without leaving the page. |
| [`plan-orchestrate`](https://github.com/vamsy16/ECC/tree/HEAD/skills/plan-orchestrate) | Use when you have a multi-step plan and wants to drive it through orchestrate without composing chains by hand. | Read a plan document, decompose it into steps, design a per-step agent chain from the ECC catalogue, and emit ready-to-paste /orchestrate custom prompts. Generative only — never invokes /orchestrate itself. |
| [`plankton-code-quality`](https://github.com/vamsy16/ECC/tree/HEAD/skills/plankton-code-quality) | Use when setting up write-time formatting, linting, or auto-fix hooks on file edits. | Write-time code quality enforcement using Plankton — auto-formatting, linting, and Claude-powered fixes on every file edit via hooks. |
| [`postgres-patterns`](https://github.com/vamsy16/ECC/tree/HEAD/skills/postgres-patterns) | Use when designing PostgreSQL schemas, indexes, or RLS policies, or when a query is too slow. | PostgreSQL database patterns for query optimization, schema design, indexing, and security. Based on Supabase best practices. |
| [`prediction-market-oracle-research`](https://github.com/vamsy16/ECC/tree/HEAD/skills/prediction-market-oracle-research) | Use for source-grounded analysis of market-implied probabilities, caveats, and integration patterns without investment advice. | Research prediction markets as data sources or oracle signals for products, agents, dashboards, and corporate decision intelligence. |
| [`prediction-market-risk-review`](https://github.com/vamsy16/ECC/tree/HEAD/skills/prediction-market-risk-review) | — | Review prediction-market, basket, oracle, and trading-agent workflows for compliance, safety, data-quality, privacy, and execution risk. Use before any workflow handles venue auth, user portfolio data, API keys, or trade planning. |
| [`prisma-patterns`](https://github.com/vamsy16/ECC/tree/HEAD/skills/prisma-patterns) | Use when writing a Prisma schema or query, or debugging transactions, migrations, or serverless connection limits. | Prisma ORM patterns for TypeScript backends — schema design, query optimization, transactions, pagination, and critical traps like updateMany returning count not records, $transaction timeouts, migrate dev resetting the DB,… |
| [`product-capability`](https://github.com/vamsy16/ECC/tree/HEAD/skills/product-capability) | Use when you need an ECC-native PRD-to-SRS lane instead of vague planning prose. | Translate PRD intent, roadmap asks, or product discussions into an implementation-ready capability plan that exposes constraints, invariants, interfaces, and unresolved decisions before multi-service work starts. |
| [`product-lens`](https://github.com/vamsy16/ECC/tree/HEAD/skills/product-lens) | — | Use this skill to validate the "why" before building, run product diagnostics, and pressure-test product direction before the request becomes an implementation contract. |
| [`production-audit`](https://github.com/vamsy16/ECC/tree/HEAD/skills/production-audit) | Use when auditing production readiness before launch, after a merge, or when asked what breaks in prod. | Local-evidence production readiness audit for shipped apps, pre-launch reviews, post-merge checks, and "what breaks in prod?" questions without sending repo data to an external audit service. |
| [`production-scheduling`](https://github.com/vamsy16/ECC/tree/HEAD/skills/production-scheduling) | Use when scheduling production, resolving bottlenecks, optimizing changeovers, responding to disruptions, or balancing manufacturing lines. | Codified expertise for production scheduling, job sequencing, line balancing, changeover optimization, and bottleneck resolution in discrete and batch manufacturing. Informed by production schedulers with 15+ years experience. |
| [`project-flow-ops`](https://github.com/vamsy16/ECC/tree/HEAD/skills/project-flow-ops) | Use when you want backlog control, PR triage, or GitHub-to-Linear coordination. | Operate execution flow across GitHub and Linear by triaging issues and pull requests, linking active work, and keeping GitHub public-facing while Linear remains the internal execution layer. |
| [`prompt-optimizer`](https://github.com/vamsy16/ECC/tree/HEAD/skills/prompt-optimizer) | — | Analyze raw prompts, identify intent and gaps, match ECC components (skills/commands/agents/hooks), and output a ready-to-paste optimized prompt. Advisory role only — never executes the task itself. |
| [`python-patterns`](https://github.com/vamsy16/ECC/tree/HEAD/skills/python-patterns) | Use when writing or reviewing Python code and idiomatic structure, typing, or PEP 8 is in question. | Pythonic idioms, PEP 8 standards, type hints, and best practices for building robust, efficient, and maintainable Python applications. |
| [`python-testing`](https://github.com/vamsy16/ECC/tree/HEAD/skills/python-testing) | Use when writing pytest tests — fixtures, mocks, parametrization, or coverage. | Python testing strategies using pytest, TDD methodology, fixtures, mocking, parametrization, and coverage requirements. |
| [`pytorch-patterns`](https://github.com/vamsy16/ECC/tree/HEAD/skills/pytorch-patterns) | Use when writing or reviewing PyTorch training loops, model architectures, or data loading, or when a run will not reproduce. | PyTorch deep learning patterns and best practices for building robust, efficient, and reproducible training pipelines, model architectures, and data loading. |
| [`quality-nonconformance`](https://github.com/vamsy16/ECC/tree/HEAD/skills/quality-nonconformance) | Use when investigating non-conformances, performing root cause analysis, managing CAPAs, interpreting SPC data, or handling supplier quality issues. | Codified expertise for quality control, non-conformance investigation, root cause analysis, corrective action, and supplier quality management in regulated manufacturing. |
| [`quarkus-patterns`](https://github.com/vamsy16/ECC/tree/HEAD/skills/quarkus-patterns) | Use for Java Quarkus backend work with event-driven architectures. Use when building or reviewing a Quarkus service, especially with Camel messaging or Panache data… | Quarkus 3.x LTS architecture patterns with Camel for messaging, RESTful API design, CDI services, data access with Panache, and async processing. |
| [`quarkus-security`](https://github.com/vamsy16/ECC/tree/HEAD/skills/quarkus-security) | Use when reviewing Quarkus authn/authz, JWT or OIDC, RBAC, validation, or secrets. | Quarkus Security best practices for authentication, authorization, JWT/OIDC, RBAC, input validation, CSRF, secrets management, and dependency security. |
| [`quarkus-tdd`](https://github.com/vamsy16/ECC/tree/HEAD/skills/quarkus-tdd) | Use when adding features, fixing bugs, or refactoring event-driven services. | Test-driven development for Quarkus 3.x LTS using JUnit 5, Mockito, REST Assured, Camel testing, and JaCoCo. |
| [`quarkus-verification`](https://github.com/vamsy16/ECC/tree/HEAD/skills/quarkus-verification) | — | Verification loop for Quarkus projects: build, static analysis, tests with coverage, security scans, native compilation, and diff review before release or PR. |
| [`ralphinho-rfc-pipeline`](https://github.com/vamsy16/ECC/tree/HEAD/skills/ralphinho-rfc-pipeline) | Use when running RFC-driven multi-agent execution with quality gates and a merge queue. | RFC-driven multi-agent DAG execution pattern with quality gates, merge queues, and work unit orchestration. |
| [`react-native-patterns`](https://github.com/vamsy16/ECC/tree/HEAD/skills/react-native-patterns) | Use when building or editing React Native / Expo screens, components, navigation, or data layers. | React Native and Expo app patterns — Expo Router navigation, state separation (server/client/route/form), TanStack Query data fetching with Zod, performant lists, NativeWind/StyleSheet styling, native APIs, and secure storage. |
| [`react-patterns`](https://github.com/vamsy16/ECC/tree/HEAD/skills/react-patterns) | Use when writing or reviewing React components. | React 18/19 patterns including hooks discipline, server/client component boundaries, Suspense + error boundaries, form actions, data fetching, state management decision trees, and accessibility-first composition. |
| [`react-performance`](https://github.com/vamsy16/ECC/tree/HEAD/skills/react-performance) | Use when writing, reviewing, or refactoring React/Next.js code for performance. | React and Next.js performance optimization patterns adapted from Vercel Engineering's React Best Practices (https://github.com/vercel-labs/agent-skills). |
| [`react-testing`](https://github.com/vamsy16/ECC/tree/HEAD/skills/react-testing) | Use when writing or fixing tests for React components, hooks, or pages. | React component testing with React Testing Library, Vitest/Jest, MSW for network mocking, accessibility assertions with axe, and the decision boundary between component tests and Playwright/Cypress end-to-end runs. |
| [`recsys-pipeline-architect`](https://github.com/vamsy16/ECC/tree/HEAD/skills/recsys-pipeline-architect) | Use this skill whenever you are building any system that picks "the top K items for a (user, context)" — social feeds, content CMSs, RAG rerankers, task prioritizers,… | Design composable recommendation, ranking, and feed pipelines using the six-stage Source→Hydrator→Filter→Scorer→Selector→SideEffect framework popularized by xAI's open-sourced For You algorithm. |
| [`recursive-decision-ledger`](https://github.com/vamsy16/ECC/tree/HEAD/skills/recursive-decision-ledger) | Use when you ask for repeated rollouts, marked decision processes, high-dimensional search, stochastic optimization, local-optima exploration, ensemble comparison, or… | Use when you ask for repeated rollouts, marked decision processes, high-dimensional search, stochastic optimization, local-optima exploration, ensemble comparison, or recursive reasoning with a visible evidence trail. |
| [`redis-patterns`](https://github.com/vamsy16/ECC/tree/HEAD/skills/redis-patterns) | Use when adding caching, a distributed lock, rate limiting, or pub/sub with Redis, or when key design needs review. | Redis data structure patterns, caching strategies, distributed locks, rate limiting, pub/sub, and connection management for production applications. |
| [`regex-vs-llm-structured-text`](https://github.com/vamsy16/ECC/tree/HEAD/skills/regex-vs-llm-structured-text) | — | Decision framework for choosing between regex and LLM when parsing structured text — start with regex, add LLM only for low-confidence edge cases. |
| [`remotion-video-creation`](https://github.com/vamsy16/ECC/tree/HEAD/skills/remotion-video-creation) | Use when building video in React with Remotion — animations, audio, captions, charts, or transitions. | Best practices for Remotion - Video creation in React. 29 domain-specific rules covering 3D, animations, audio, captions, charts, transitions, and more. |
| [`repo-scan`](https://github.com/vamsy16/ECC/tree/HEAD/skills/repo-scan) | Use when repo-scan must be installed before running its cross-stack source-code asset audit; this ECC pointer does not perform the audit itself. | Bootstrap pointer that installs the external repo-scan skill from a pinned, reviewable commit. |
| [`research-ops`](https://github.com/vamsy16/ECC/tree/HEAD/skills/research-ops) | Use when you want fresh facts, comparisons, enrichment, or a recommendation built from current public evidence and any supplied local context. | Evidence-first current-state research workflow for ECC. |
| [`returns-reverse-logistics`](https://github.com/vamsy16/ECC/tree/HEAD/skills/returns-reverse-logistics) | Use when handling product returns, reverse logistics, refund decisions, return fraud detection, or warranty claims. | Codified expertise for returns authorization, receipt and inspection, disposition decisions, refund processing, fraud detection, and warranty claims management. Informed by returns operations managers with 15+ years experience. |
| [`rules-distill`](https://github.com/vamsy16/ECC/tree/HEAD/skills/rules-distill) | Use when the same principle keeps recurring across skills and belongs in a rule file instead. | Scan skills to extract cross-cutting principles and distill them into rules — append, revise, or create new rule files. |
| [`rust-patterns`](https://github.com/vamsy16/ECC/tree/HEAD/skills/rust-patterns) | Use when writing or reviewing Rust code and ownership, error handling, traits, or concurrency is in question. | Idiomatic Rust patterns, ownership, error handling, traits, concurrency, and best practices for building safe, performant applications. |
| [`rust-testing`](https://github.com/vamsy16/ECC/tree/HEAD/skills/rust-testing) | Use when writing Rust tests — unit, integration, async, property-based, or coverage. | Rust testing patterns including unit tests, integration tests, async testing, property-based testing, mocking, and coverage. Follows TDD methodology. |
| [`safety-guard`](https://github.com/vamsy16/ECC/tree/HEAD/skills/safety-guard) | — | Use this skill to prevent destructive operations when working on production systems or running agents autonomously. |
| [`santa-method`](https://github.com/vamsy16/ECC/tree/HEAD/skills/santa-method) | Use when output must clear two independent adversarial reviewers before it ships. | Multi-agent adversarial verification with convergence loop. Two independent review agents must both pass before output ships. |
| [`scientific-db-pubmed-database`](https://github.com/vamsy16/ECC/tree/HEAD/skills/scientific-db-pubmed-database) | Use when a task needs biomedical literature from PubMed rather than general web search. | Direct PubMed and NCBI E-utilities search workflows for biomedical literature, MeSH queries, PMID lookup, citation retrieval, and API-backed literature monitoring. |
| [`scientific-db-uspto-database`](https://github.com/vamsy16/ECC/tree/HEAD/skills/scientific-db-uspto-database) | Use when a task needs official United States patent or trademark records from USPTO systems. | USPTO patent and trademark data workflow for official record lookup, PatentSearch queries, TSDR checks, assignment data, and reproducible IP research logs. |
| [`scientific-pkg-gget`](https://github.com/vamsy16/ECC/tree/HEAD/skills/scientific-pkg-gget) | Use when a task needs quick bioinformatics lookup across genomic reference databases with the gget CLI or Python package. | gget CLI and Python workflow for quick genomic database queries, sequence lookup, BLAST-style searches, enrichment checks, and reproducible bioinformatics evidence logs. |
| [`scientific-thinking-literature-review`](https://github.com/vamsy16/ECC/tree/HEAD/skills/scientific-thinking-literature-review) | Use when the task is to find, screen, synthesize, and cite a body of academic or technical literature. | Systematic literature-review workflow for academic, biomedical, technical, and scientific topics, including search planning, source screening, synthesis, citation checks, and evidence logging. |
| [`scientific-thinking-scholar-evaluation`](https://github.com/vamsy16/ECC/tree/HEAD/skills/scientific-thinking-scholar-evaluation) | Use when evaluating academic or scientific work — papers, proposals, methods sections, or evidence quality — against a repeatable rubric. | Structured scholarly-work evaluation for papers, proposals, literature reviews, methods sections, evidence quality, citation support, and research-writing feedback. |
| [`search-first`](https://github.com/vamsy16/ECC/tree/HEAD/skills/search-first) | — | Research-before-coding workflow. Search for existing tools, libraries, and patterns before writing custom code. Invokes the researcher agent. |
| [`security-bounty-hunter`](https://github.com/vamsy16/ECC/tree/HEAD/skills/security-bounty-hunter) | Use when hunting reportable, remotely reachable vulnerabilities in a repository. | Hunt for exploitable, bounty-worthy security issues in repositories. Focuses on remotely reachable vulnerabilities that qualify for real reports instead of noisy local-only findings. |
| [`security-review`](https://github.com/vamsy16/ECC/tree/HEAD/skills/security-review) | Use this skill when adding authentication, handling user input, working with secrets, creating API endpoints, or implementing payment/sensitive features. | Provides comprehensive security checklist and patterns. |
| [`security-scan`](https://github.com/vamsy16/ECC/tree/HEAD/skills/security-scan) | Use when auditing a .claude/ directory — CLAUDE.md, settings.json, MCP servers, hooks, or agent definitions. | Scan your Claude Code configuration (.claude/ directory) for security vulnerabilities, misconfigurations, and injection risks using AgentShield. Checks CLAUDE.md, settings.json, MCP servers, hooks, and agent definitions. |
| [`seo`](https://github.com/vamsy16/ECC/tree/HEAD/skills/seo) | Use when you want better search visibility, SEO remediation, schema markup, sitemap/robots work, or keyword mapping. | Audit, plan, and implement SEO improvements across technical SEO, on-page optimization, structured data, Core Web Vitals, and content strategy. |
| [`skill-comply`](https://github.com/vamsy16/ECC/tree/HEAD/skills/skill-comply) | Use when checking whether agents actually follow the skills, rules, and definitions they were given, rather than assuming they do. | Visualize whether skills, rules, and agent definitions are actually followed — auto-generates scenarios at 3 prompt strictness levels, runs agents, classifies behavioral sequences, and reports compliance rates with full tool call… |
| [`skill-scout`](https://github.com/vamsy16/ECC/tree/HEAD/skills/skill-scout) | Use when you want to create, build, fork, or find a skill for a workflow. | Search existing local, marketplace, GitHub, and web skill sources before creating a new skill. |
| [`skill-stocktake`](https://github.com/vamsy16/ECC/tree/HEAD/skills/skill-stocktake) | Use when auditing Claude skills and commands for quality. | Supports Quick Scan (changed skills only) and Full Stocktake modes with sequential subagent batch evaluation. |
| [`social-graph-ranker`](https://github.com/vamsy16/ECC/tree/HEAD/skills/social-graph-ranker) | Use when you want the reusable graph-ranking engine itself, not the broader outreach or network-maintenance workflow layered on top of it. | Weighted social-graph ranking for warm intro discovery, bridge scoring, and network gap analysis across X and LinkedIn. |
| [`social-publisher`](https://github.com/vamsy16/ECC/tree/HEAD/skills/social-publisher) | Use when you want to publish to X, LinkedIn, Instagram, Facebook Pages, TikTok, Discord, Telegram, YouTube, Reddit, WordPress, or Pinterest — or when managing campaigns,… | Agent-driven scheduling and publishing of social media posts across 13 platforms via SocialClaw. |
| [`springboot-patterns`](https://github.com/vamsy16/ECC/tree/HEAD/skills/springboot-patterns) | Use for Java Spring Boot backend work. Use when building or reviewing a Spring Boot backend — REST layer, services, data access, caching, or async work. | Spring Boot architecture patterns, REST API design, layered services, data access, caching, async processing, and logging. |
| [`springboot-security`](https://github.com/vamsy16/ECC/tree/HEAD/skills/springboot-security) | Use when reviewing Spring Security authn/authz, validation, CSRF, secrets, headers, or rate limiting. | Spring Security best practices for authn/authz, validation, CSRF, secrets, headers, rate limiting, and dependency security in Java Spring Boot services. |
| [`springboot-tdd`](https://github.com/vamsy16/ECC/tree/HEAD/skills/springboot-tdd) | Use when adding features, fixing bugs, or refactoring. | Test-driven development for Spring Boot using JUnit 5, Mockito, MockMvc, Testcontainers, and JaCoCo. |
| [`springboot-verification`](https://github.com/vamsy16/ECC/tree/HEAD/skills/springboot-verification) | — | Verification loop for Spring Boot projects: build, static analysis, tests with coverage, security scans, and diff review before release or PR. |
| [`strategic-compact`](https://github.com/vamsy16/ECC/tree/HEAD/skills/strategic-compact) | Use when a session is approaching a context limit and a task phase is a natural place to compact. | Suggests manual context compaction at logical intervals to preserve context through task phases rather than arbitrary auto-compaction. |
| [`swift-actor-persistence`](https://github.com/vamsy16/ECC/tree/HEAD/skills/swift-actor-persistence) | Use when persisting data in Swift and a data race or thread-safety problem needs designing out. | Thread-safe data persistence in Swift using actors — in-memory cache with file-backed storage, eliminating data races by design. |
| [`swift-concurrency-6-2`](https://github.com/vamsy16/ECC/tree/HEAD/skills/swift-concurrency-6-2) | Use when adopting Swift 6.2 concurrency — offloading with @concurrent or resolving main-actor isolation. | Swift 6.2 Approachable Concurrency — single-threaded by default, @concurrent for explicit background offloading, isolated conformances for main actor types. |
| [`swift-protocol-di-testing`](https://github.com/vamsy16/ECC/tree/HEAD/skills/swift-protocol-di-testing) | Use when Swift code needs testing and file system, network, or external APIs must be mocked. | Protocol-based dependency injection for testable Swift code — mock file system, network, and external APIs using focused protocols and Swift Testing. |
| [`swiftui-patterns`](https://github.com/vamsy16/ECC/tree/HEAD/skills/swiftui-patterns) | Use when building or reviewing SwiftUI views, @Observable state, navigation, or render performance. | SwiftUI architecture patterns, state management with @Observable, view composition, navigation, performance optimization, and modern iOS/macOS UI best practices. |
| [`taste`](https://github.com/vamsy16/ECC/tree/HEAD/skills/taste) | Use when the work is not just making a video function but making it feel intentional, when building a music video, a fancam/edit, a moodboard-driven reel, or when… | A creative-direction (taste) layer for music videos and short-form edits in the angelcore / cloud-trance / hyperpop visual family. |
| [`tasteforge-video`](https://github.com/vamsy16/ECC/tree/HEAD/skills/tasteforge-video) | Use for file-driven multimodal image, video, and 3D-asset discovery; taste interviews; distill or apply workflows; style-pack validation; editable EDL/FCPXML export; | Use for file-driven multimodal image, video, and 3D-asset discovery; taste interviews; distill or apply workflows; style-pack validation; editable EDL/FCPXML export; provenance audits; |
| [`tdd-workflow`](https://github.com/vamsy16/ECC/tree/HEAD/skills/tdd-workflow) | Use this skill when writing new features, fixing bugs, or refactoring code. | Enforces test-driven development with 80%+ coverage including unit, integration, and E2E tests. |
| [`team-agent-orchestration`](https://github.com/vamsy16/ECC/tree/HEAD/skills/team-agent-orchestration) | Use when coordinating an agent squad with work items, ownership, Kanban, and merge gates. | Run team-based orchestration for agent squads using work items, ownership, agent Kanban, merge gates, and control pane handoffs. |
| [`team-builder`](https://github.com/vamsy16/ECC/tree/HEAD/skills/team-builder) | Use when composing and dispatching a parallel team of agents for a task. | Interactive agent picker for composing and dispatching parallel teams. |
| [`terminal-opener`](https://github.com/vamsy16/ECC/tree/HEAD/skills/terminal-opener) | Use when Codex needs to open an interactive CLI, SSH session, local development process, sandbox, or other argv-based command in a new host terminal; | Open an executable and its argument array in a visible terminal window through a reusable, shell-free launch plan with dry-run, JSON, capability detection, detached fallback, and standalone recovery modes. |
| [`terminal-ops`](https://github.com/vamsy16/ECC/tree/HEAD/skills/terminal-ops) | Use when you want a command run, a repo checked, a CI failure debugged, or a narrow fix pushed with exact proof of what was executed and verified. | Evidence-first repo execution workflow for ECC. |
| [`tinystruct-patterns`](https://github.com/vamsy16/ECC/tree/HEAD/skills/tinystruct-patterns) | Use when working on the tinystruct codebase or any project built on tinystruct — including creating Application classes, @Action-mapped routes, unit tests,… | Expert guidance for developing with the tinystruct Java framework. |
| [`token-budget-advisor`](https://github.com/vamsy16/ECC/tree/HEAD/skills/token-budget-advisor) | Use this skill when you explicitly wants to control response length, depth, or token budget. | Offers the user an informed choice about how much response depth to consume before answering. TRIGGER when: "token budget", "token count", "token usage", "token limit", "response length", "answer depth", "short version", "brief… |
| [`ui-demo`](https://github.com/vamsy16/ECC/tree/HEAD/skills/ui-demo) | Use when you ask to create a demo, walkthrough, screen recording, or tutorial video of a web application. | Record polished UI demo videos using Playwright. Produces WebM videos with visible cursor, natural pacing, and professional feel. |
| [`ui-to-vue`](https://github.com/vamsy16/ECC/tree/HEAD/skills/ui-to-vue) | Use when you have UI screenshots or design exports that need batch conversion into Vue 3 components, especially with Vant, Element Plus, or Ant Design Vue. | Use when you have UI screenshots or design exports that need batch conversion into Vue 3 components, especially with Vant, Element Plus, or Ant Design Vue. |
| [`uncloud`](https://github.com/vamsy16/ECC/tree/HEAD/skills/uncloud) | Use when managing an Uncloud cluster — deploying services, configuring Caddy ingress, adding static proxy routes for non-cluster devices, publishing ports, scaling,… | Use when managing an Uncloud cluster — deploying services, configuring Caddy ingress, adding static proxy routes for non-cluster devices, publishing ports, scaling, inspecting logs, or managing machines and volumes with the `uc`… |
| [`unified-memory`](https://github.com/vamsy16/ECC/tree/HEAD/skills/unified-memory) | Use when an agent must save work state, transfer context, resume another agent's task, or search shared project knowledge. | Share durable, inspectable context and handoffs between Claude, Codex, Hermes, Cursor, OpenCode, and other agents through the local ECC Memory Vault. |
| [`unified-notifications-ops`](https://github.com/vamsy16/ECC/tree/HEAD/skills/unified-notifications-ops) | Use when the real problem is alert routing, deduplication, escalation, or inbox collapse. | Operate notifications as one ECC-native workflow across GitHub, Linear, desktop alerts, hooks, and connected communication surfaces. |
| [`verification-loop`](https://github.com/vamsy16/ECC/tree/HEAD/skills/verification-loop) | Use when verifying a Claude Code session's work before claiming it is complete. | A comprehensive verification system for Claude Code sessions. |
| [`video-editing`](https://github.com/vamsy16/ECC/tree/HEAD/skills/video-editing) | Use when you want to edit video, cut footage, create vlogs, or build video content. | AI-assisted video editing workflows for cutting, structuring, and augmenting real footage. Covers the full pipeline from raw capture through FFmpeg, Remotion, ElevenLabs, fal.ai, and final polish in Descript or CapCut. |
| [`videodb`](https://github.com/vamsy16/ECC/tree/HEAD/skills/videodb) | Use when ingesting, indexing, searching, editing, transcoding, or alerting on video or audio content. | See, Understand, Act on video and audio. See- ingest from local files, URLs, RTSP/live feeds, or live record desktop; return realtime context and playable stream links. |
| [`visa-doc-translate`](https://github.com/vamsy16/ECC/tree/HEAD/skills/visa-doc-translate) | Use when visa application document images must be translated to English as a bilingual PDF. | Translate visa application documents (images) to English and create a bilingual PDF with original and translation. |
| [`vite-patterns`](https://github.com/vamsy16/ECC/tree/HEAD/skills/vite-patterns) | Activate when working with vite.config.ts, Vite plugins, or Vite-based projects. | Vite build tool patterns including config, plugins, HMR, env variables, proxy setup, SSR, library mode, dependency pre-bundling, and build optimization. |
| [`vue-patterns`](https://github.com/vamsy16/ECC/tree/HEAD/skills/vue-patterns) | Use when building or reviewing Vue 3, Nuxt, or Pinia code — Composition API, reactivity, or router navigation. | Vue.js 3 Composition API patterns, component architecture, reactivity best practices, Pinia state management, Vue Router navigation, and Nuxt SSR patterns. Activates for Vue, Nuxt, Vite, or Pinia projects. |
| [`windows-desktop-e2e`](https://github.com/vamsy16/ECC/tree/HEAD/skills/windows-desktop-e2e) | Use when writing E2E tests for a Windows native desktop app with pywinauto or UI Automation. | E2E testing for Windows native desktop apps (WPF, WinForms, Win32/MFC, Qt) using pywinauto and Windows UI Automation. |
| [`workspace-surface-audit`](https://github.com/vamsy16/ECC/tree/HEAD/skills/workspace-surface-audit) | Use when you want help setting up Claude Code or understanding what capabilities are actually available in their environment. | Audit the active repo, MCP servers, plugins, connectors, env surfaces, and harness setup, then recommend the highest-value ECC-native skills, hooks, agents, and operator workflows. |
| [`x-api`](https://github.com/vamsy16/ECC/tree/HEAD/skills/x-api) | Use when you want to interact with X programmatically. | X/Twitter API integration for posting tweets, threads, reading timelines, search, and analytics. Covers OAuth auth patterns, rate limits, and platform-native content posting. |

#### `claude-mem`

🔗 [https://github.com/vamsy16/claude-mem](https://github.com/vamsy16/claude-mem) · Fork of [`thedotmack/claude-mem`](https://github.com/thedotmack/claude-mem) · Language: n/a · Last push: 2026-08-29

**What it is:** Persistent Context Across Sessions for Every Agent – Captures everything your agent does during sessions, compresses it with AI, and injects relevant context back into future sessions. Works with Claude Code, OpenClaw, Codex, Gemini, Hermes, Copilot, OpenCode + More

**When to use:** When your agent forgets everything between sessions — persistent context that captures, compresses, and re-injects memory. Works with Claude Code, Codex, Gemini, Copilot, and more.

**Skills inside — 21** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`babysit`](https://github.com/vamsy16/claude-mem/tree/HEAD/plugin/skills/babysit) | Use when asked to babysit, monitor, or keep checking PR comments, reviews, and CI until all actionable issues are resolved. | Watch a pull request or review cycle until it is ready to merge. |
| [`cloud-sync`](https://github.com/vamsy16/claude-mem/tree/HEAD/plugin/skills/cloud-sync) | Use when you say "set up cloud sync", "sync my memories", "cmem pro", "cloud backup", "sync status", or wants their memory database backed up or synced to their cmem.ai… | Set up or check claude-mem cloud sync with cmem.ai Pro. |
| [`design-is`](https://github.com/vamsy16/claude-mem/tree/HEAD/plugin/skills/design-is) | Use when you say "audit this design", "design review", "check this UI against Rams", "is this UI good", "critique this design", "design audit", or asks for a critique… | Audit a design against Dieter Rams' ten "Good design is..." principles, then hand off a /make-plan prompt for one of three outcomes — new design, refine design, or redesign. |
| [`do`](https://github.com/vamsy16/claude-mem/tree/HEAD/openclaw/skills/do) | Use when asked to execute, run, or carry out a plan — especially one created by make-plan. | Execute a phased implementation plan using subagents. |
| [`how-it-works`](https://github.com/vamsy16/claude-mem/tree/HEAD/plugin/skills/how-it-works) | Use when you ask "how does claude-mem work?" or "what is this thing doing?". | Explain how claude-mem captures observations, when memory injection kicks in, and where data lives. |
| [`knowledge-agent`](https://github.com/vamsy16/claude-mem/tree/HEAD/plugin/skills/knowledge-agent) | Use when users want to create focused "brains" from their observation history, ask questions about past work patterns, or compile expertise on specific topics. | Build and query AI-powered knowledge bases from claude-mem observations. |
| [`learn-codebase`](https://github.com/vamsy16/claude-mem/tree/HEAD/plugin/skills/learn-codebase) | Use when starting work on a new or unfamiliar project, or when you ask to "learn the codebase", "read the codebase", "prime", or "get up to speed". | Prime a codebase by reading every source file in full. |
| [`make-plan`](https://github.com/vamsy16/claude-mem/tree/HEAD/openclaw/skills/make-plan) | Use when asked to plan a feature, task, or multi-step implementation — especially before executing with do. | Create a detailed, phased implementation plan with documentation discovery. |
| [`mem-search`](https://github.com/vamsy16/claude-mem/tree/HEAD/cowork/skills/mem-search) | — | This skill should be used when the user asks to "search memory", "what do you remember about X", "check claude-mem", "mem search", "find past observations", "what did we do last session", or wants prior-session context about a… |
| [`mem-setup`](https://github.com/vamsy16/claude-mem/tree/HEAD/cowork/skills/mem-setup) | — | This skill should be used when the user asks to "set up claude-mem", "pair claude-mem", "connect cmem", "add my cmem key", "set up cloud sync in Cowork", or provides cmem.ai Connect values (sync token, user id, SyncHub URL) for… |
| [`mode-creator`](https://github.com/vamsy16/claude-mem/tree/HEAD/plugin/skills/mode-creator) | Use this whenever someone asks to customize what claude-mem remembers, create or change a mode, track domain-specific notes, add observation types or tags, or send… | Interactively create, install, activate, and verify custom claude-mem modes, including domain-specific observation types, concept tags, optional Telegram alerts, bot setup, worker restart, and startup-context verification. |
| [`oh-my-issues`](https://github.com/vamsy16/claude-mem/tree/HEAD/plugin/skills/oh-my-issues) | Use when an issue tracker has accumulated dozens of reports that share underlying defects, when asked to triage / consolidate / cluster / dedupe issues, when asked to… | Cluster a GitHub issue backlog by root cause into a small set of plan-master issues, redirect children with a standardized comment, and bundle architectural-fix PRs that close clusters atomically. |
| [`openclaw`](https://github.com/vamsy16/claude-mem/tree/HEAD/openclaw) | — | Claude-Mem OpenClaw Plugin — Setup Guide — This guide walks through setting up the claude-mem plugin on an OpenClaw gateway. |
| [`pathfinder`](https://github.com/vamsy16/claude-mem/tree/HEAD/plugin/skills/pathfinder) | Use when asked to "find the ideal path," unify duplicated systems, or audit architecture before a refactor. | Map a codebase into feature-grouped flowcharts, identify duplicated concerns across features, and propose a unified architecture. Emits a proposed unified flowchart plus per-system /make-plan prompts. |
| [`smart-explore`](https://github.com/vamsy16/claude-mem/tree/HEAD/plugin/skills/smart-explore) | — | Token-optimized structural code search using tree-sitter AST parsing. Use instead of reading full files when you need to understand code structure, find functions, or explore a codebase efficiently. |
| [`standup`](https://github.com/vamsy16/claude-mem/tree/HEAD/plugin/skills/standup) | — | Facilitate a read-only standup across git worktrees, branches, or PRs to compare changes and produce one consolidation plan. |
| [`timeline-report`](https://github.com/vamsy16/claude-mem/tree/HEAD/plugin/skills/timeline-report) | Use when asked for a timeline report, project history analysis, development journey, or full project report. | Generate a "Journey Into [Project]" narrative report analyzing a project's entire development history from claude-mem's timeline. |
| [`version-bump`](https://github.com/vamsy16/claude-mem/tree/HEAD/plugin/skills/version-bump) | — | Automated semantic versioning and release workflow for Claude Code plugins. Handles version increments across package.json, marketplace.json, plugin.json manifests, build verification, git tagging, GitHub releases, and changelog… |
| [`weekly-digests`](https://github.com/vamsy16/claude-mem/tree/HEAD/plugin/skills/weekly-digests) | Use when asked for "weekly digests", "week-by-week story", "serial timeline", or "narrative chapters" of a project's history. | Generate a serial week-by-week narrative digest of a project's full claude-mem timeline. Splits the timeline into per-ISO-week files, then runs one consecutive subagent per week — each receiving the prior week's carry-forward… |
| [`what-the`](https://github.com/vamsy16/claude-mem/tree/HEAD/plugin/skills/what-the) | Use when you want a plain-English breakdown of something technical — the who, what, where, why, and when. | What the? |
| [`wowerpoint`](https://github.com/vamsy16/claude-mem/tree/HEAD/plugin/skills/wowerpoint) | Use for "wowerpoint this", "make a deck about <file>", "turn this report into slides", or any request to render a single document as shareable narrative slides. | Turn one document into a kawaii NotebookLM slide-deck PDF. |

#### `loop-engineering`

🔗 [https://github.com/vamsy16/loop-engineering](https://github.com/vamsy16/loop-engineering) · Fork of [`cobusgreyling/loop-engineering`](https://github.com/cobusgreyling/loop-engineering) · Language: n/a · Last push: 2026-08-30

**What it is:** Practical patterns, starters & CLI tools for loop engineering with AI coding agents. Design systems that prompt and orchestrate agents (inspired by Addy Osmani and Boris Cherny). Includes loop-audit, loop-init, loop-cost.

**When to use:** When designing systems that prompt and orchestrate agents — practical patterns, starters, and CLI tools (loop-audit, loop-init, loop-cost).

**Skills inside — 14** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`budget-negotiator`](https://github.com/vamsy16/loop-engineering/tree/HEAD/skills/budget-negotiator) | — | An advanced skill for L3 autonomous loops. When the token budget nears exhaustion, the agent analyzes its ROI and autonomously drafts a negotiation request for a budget increase rather than silently failing. |
| [`changelog-scan`](https://github.com/vamsy16/loop-engineering/tree/HEAD/starters/changelog-drafter-opencode/skills/changelog-scan) | — | Scan merged PRs and commits since a given reference, extract titles, labels, types, and signals. Produces structured input for release notes drafting. |
| [`ci-triage`](https://github.com/vamsy16/loop-engineering/tree/HEAD/starters/ci-sweeper-opencode/skills/ci-triage) | — | Classify CI failures — distinguish clear regressions from infra flakes and security-test failures. Produces structured failure reports. |
| [`dependency-triage`](https://github.com/vamsy16/loop-engineering/tree/HEAD/starters/dependency-sweeper-opencode/skills/dependency-triage) | — | Scan package manifests and lockfiles for outdated and vulnerable dependencies. Classify by severity and update type. |
| [`draft-release-notes`](https://github.com/vamsy16/loop-engineering/tree/HEAD/starters/changelog-drafter/.claude/skills/draft-release-notes) | — | Turn changelog-scan output into polished, categorized release notes draft. Propose only. |
| [`install-loop`](https://github.com/vamsy16/loop-engineering/tree/HEAD/skills/install-loop) | — | Install Loop Engineering into a project via the unified CLI front door (@cobusgreyling/loop). Prefer this over invoking loop-init / loop-audit separately. |
| [`issue-triage`](https://github.com/vamsy16/loop-engineering/tree/HEAD/starters/issue-triage-opencode/skills/issue-triage) | — | Scan open issues and discussions, deduplicate, prioritize, and propose labels. Provides a clean actionable queue. |
| [`loop-budget`](https://github.com/vamsy16/loop-engineering/tree/HEAD/skills/loop-budget) | — | Check token budget and run-log spend before and after a loop run. Enforces early exit when over budget or when there is no actionable work. |
| [`loop-constraints`](https://github.com/vamsy16/loop-engineering/tree/HEAD/skills/loop-constraints) | — | Read loop-constraints.md at the start of every run and enforce every rule. This skill runs BEFORE triage or any action skill. Constraints are binding. |
| [`loop-triage`](https://github.com/vamsy16/loop-engineering/tree/HEAD/skills/loop-triage) | — | Triage recent changes, CI failures, issues, and conversations. Produces a concise, actionable findings report suitable for a loop to consume. Writes structured output to a state file or Linear board. |
| [`loop-verifier`](https://github.com/vamsy16/loop-engineering/tree/HEAD/skills/loop-verifier) | Use after minimal-fix or any implementer sub-agent — never in the same role as the implementer. | Independent verification agent for loop-produced changes. Finds reasons to reject. Runs tests. Confirms diff scope. |
| [`minimal-fix`](https://github.com/vamsy16/loop-engineering/tree/HEAD/skills/minimal-fix) | — | Produce the smallest possible code change that fixes a specific, well-scoped issue (CI failure, reviewer comment, typo). Use only when the fix target is explicit. Never refactor unrelated code. |
| [`post-merge-scan`](https://github.com/vamsy16/loop-engineering/tree/HEAD/starters/post-merge-cleanup-opencode/skills/post-merge-scan) | — | Scan recent merges to main for tech debt, TODOs, debug code, and small cleanup opportunities. Produces a prioritized fix list. |
| [`pr-review-triage`](https://github.com/vamsy16/loop-engineering/tree/HEAD/starters/pr-babysitter-opencode/skills/pr-review-triage) | — | Watch open PRs, check CI status, review staleness, merge conflicts, and unanswered review comments. Produces a prioritized watchlist. |

#### `browser-use`

🔗 [https://github.com/vamsy16/browser-use](https://github.com/vamsy16/browser-use) · Fork of [`browser-use/browser-use`](https://github.com/browser-use/browser-use) · Language: n/a · Last push: 2026-08-30

**What it is:** 🌐 Make websites accessible for AI agents. Automate tasks online with ease.

**When to use:** When you want websites accessible to AI agents — browser automation with an AI driver.

**Skills inside — 6** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`browser-use`](https://github.com/vamsy16/browser-use/tree/HEAD/skills/browser-use) | — | Direct browser control via CDP for web interaction: automation, scraping, testing, screenshots, and site/app work. |
| [`cloud`](https://github.com/vamsy16/browser-use/tree/HEAD/skills/cloud) | Use this skill whenever you need help with the Cloud REST API (v2 or v3), browser-use-sdk (Python or TypeScript), X-Browser-Use-API-Key authentication, cloud sessions,… | Documentation reference for using Browser Use Cloud — the hosted API and SDK for browser automation. |
| [`open-source`](https://github.com/vamsy16/browser-use/tree/HEAD/skills/open-source) | Use this skill whenever you need help with Agent, Browser, or Tools configuration, is writing code that imports from browser_use, asks about @sandbox deployment,… | Documentation reference for writing Python code using the browser-use open-source library. Also trigger for questions about browser-use installation, prompting strategies, or sensitive data handling. |
| [`qa`](https://github.com/vamsy16/browser-use/tree/HEAD/skills/qa) | Use when you want to test, QA, evaluate, score, or "check how good" a site, page, flow, or app — including a local dev server (e.g. | QA-test a website or web app and return a 1-5 quality score (5 = flawless, 1 = broken) with evidence. "qa test localhost:5173", "does the checkout work?", "rate this landing page"). |
| [`remote-browser`](https://github.com/vamsy16/browser-use/tree/HEAD/skills/remote-browser) | — | Controls an isolated Browser Use Cloud browser from a sandboxed machine with the current Browser Use CLI. |
| [`x402`](https://github.com/vamsy16/browser-use/tree/HEAD/skills/x402) | Use when you ask about x402, pay-per-use, USDC payments, or wants Browser Use Cloud without an API key. | Set up Browser Use Cloud payments with x402 — pay per request from a crypto wallet (USDC on Base mainnet), no signup or API key. |

#### `ai-operating-system-template`

🔗 [https://github.com/vamsy16/ai-operating-system-template](https://github.com/vamsy16/ai-operating-system-template) · Fork of [`audrey-560/ai-operating-system-template`](https://github.com/audrey-560/ai-operating-system-template) · Language: n/a · Last push: 2026-07-15

**What it is:** A clean starter template for building a personal AI Operating System in Claude Code — core skills (/onboard, /audit, /new-project, /skill-builder, /roast), the Readiness Ladder, an example WAT project, and an autopilot starter. No personal data.

**When to use:** When starting a personal AI Operating System in Claude Code — onboard/audit/new-project/skill-builder skills + autopilot starter.

**Skills inside — 5** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`audit`](https://github.com/vamsy16/ai-operating-system-template/tree/HEAD/.claude/skills/audit) | Use for "audit my setup", "how complete is my OS", "what should I build next", "find gaps". | Read-only health check of this AI operating system. Reports how complete the setup is (Memory/Reach/Skills/Autopilot), router blind spots, whether projects follow the /new-project baseline, the standing automation backlog, and… |
| [`new-project`](https://github.com/vamsy16/ai-operating-system-template/tree/HEAD/.claude/skills/new-project) | Use for "new project", "start a project", "scaffold a project", "create a project". | Scaffold a new project under the OS with the WAT baseline (CLAUDE.md + folders) and register it in the router. Every project is a WAT automation (workflows + tools). |
| [`onboard`](https://github.com/vamsy16/ai-operating-system-template/tree/HEAD/.claude/skills/onboard) | Use for "onboard me", "set up my OS", first-time setup. | One-time setup interview for the AI operating system. Branches on business/employee/personal, captures operations + digital footprint + brand, and seeds the automation backlog. |
| [`roast`](https://github.com/vamsy16/ai-operating-system-template/tree/HEAD/.claude/skills/roast) | Use when someone asks to roast an idea, pressure-test or stress-test an idea, validate a business idea, "convene the council", get a brutal second opinion before… | Spins up a 5-persona council that attacks the idea from every angle, then a Judge returns one GO / RESHAPE / KILL verdict with the cheapest test to de-risk it. |
| [`skill-builder`](https://github.com/vamsy16/ai-operating-system-template/tree/HEAD/.claude/skills/skill-builder) | Use when creating new skills, optimizing existing skills, or auditing skill quality. | Guides skill development following Claude Code official best practices. |

#### `browser-harness`

🔗 [https://github.com/vamsy16/browser-harness](https://github.com/vamsy16/browser-harness) · Fork of [`browser-use/browser-harness`](https://github.com/browser-use/browser-harness) · Language: n/a · Last push: 2026-08-30

**What it is:** Browser Harness \| Self-healing harness that enables LLMs to complete any task.

**When to use:** When you need a self-healing harness so LLMs can complete any browser task reliably.

**Install / quick start:**

Paste into Claude Code or Codex:
```text
Install or upgrade browser-harness to the latest stable version with uv using Python 3.12, register the skill from `browser-harness skill`, and connect it to my browser.
```

**Skills inside — 3** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`browser-harness`](https://github.com/vamsy16/browser-harness/tree/HEAD/skills/browser-harness) | — | Always use browser-harness for any web interaction: automation, scraping, testing, or site/app work. |
| [`browser_harness`](https://github.com/vamsy16/browser-harness/tree/HEAD/src/browser_harness) | — | Always use browser-harness for any web interaction: automation, scraping, testing, or site/app work. |
| [`SKILL.md`](https://github.com/vamsy16/browser-harness/tree/HEAD/SKILL.md) | — | Always use browser-harness for any web interaction: automation, scraping, testing, or site/app work. |

#### `browsercode`

🔗 [https://github.com/vamsy16/browsercode](https://github.com/vamsy16/browsercode) · Fork of [`browser-use/browsercode`](https://github.com/browser-use/browsercode) · Language: n/a · Last push: 2026-08-30

**What it is:** The browser-native agent framework

**When to use:** When building browser-native agent applications.

**Skills inside — 2** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`browser-execute`](https://github.com/vamsy16/browsercode/tree/HEAD/packages/bcode-browser/skills/browser-execute) | — | Use ONLY when calling the `browser_execute` tool or driving a real browser via the Chrome DevTools Protocol. Required reading before the first `browser_execute` call in a session. |
| [`effect`](https://github.com/vamsy16/browsercode/tree/HEAD/.opencode/skills/effect) | — | Work with Effect v4 / effect-smol TypeScript code in this repo |

#### `company-skills-marketplace-template`

🔗 [https://github.com/vamsy16/company-skills-marketplace-template](https://github.com/vamsy16/company-skills-marketplace-template) · Fork of [`bradautomates/company-skills-marketplace-template`](https://github.com/bradautomates/company-skills-marketplace-template) · Language: n/a · Last push: 2026-05-10

**What it is:** Fork-and-go template for a private team skills marketplace usable from Claude Code and Codex CLI

**When to use:** When you want a private team skills marketplace usable from Claude Code and Codex CLI — fork-and-go.

**Skills inside — 2** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`example-skill`](https://github.com/vamsy16/company-skills-marketplace-template/tree/HEAD/plugins/team-skills/skills/example-skill) | — | Example skill that confirms the marketplace is wired correctly. Triggers when the user says "test the marketplace", "verify marketplace install", or asks for a marketplace smoke test. |
| [`marketplace-manager`](https://github.com/vamsy16/company-skills-marketplace-template/tree/HEAD/plugins/marketplace-admin/skills/marketplace-manager) | Use when you say "set up the marketplace", "init the marketplace", "add a skill to the team marketplace", "import this skill into the marketplace", "publish to the… | Owner-only tooling for managing a private skills marketplace that serves both Claude Code and Codex CLI from the same repo. |

#### `codegraph`

🔗 [https://github.com/vamsy16/codegraph](https://github.com/vamsy16/codegraph) · Fork of [`colbymchenry/codegraph`](https://github.com/colbymchenry/codegraph) · Language: n/a · Last push: 2026-08-26

**What it is:** Pre-indexed code knowledge graph, auto syncs on code changes, for Claude Code, Codex, Gemini, Cursor, OpenCode, AntiGravity, Kiro, CoPilot, and Hermes Agent — fewer tokens, fewer tool calls, 100% local

**When to use:** When your agent burns tokens re-reading the codebase — a pre-indexed code knowledge graph that auto-syncs, 100% local.

**Skills inside — 2** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`add-lang`](https://github.com/vamsy16/codegraph/tree/HEAD/.claude/skills/add-lang) | Use when you run /add-lang <language> or asks to add/support a new language (e.g. | Add tree-sitter language support to codegraph end-to-end — wire the grammar + extractor, write tests, then benchmark extraction quality and retrieval value on 3 popular real-world repos. Lua, Elixir, Zig, OCaml) in codegraph. |
| [`agent-eval`](https://github.com/vamsy16/codegraph/tree/HEAD/.claude/skills/agent-eval) | Use when you run /agent-eval or asks to test, benchmark, audit, or validate a codegraph version (the local dev build or a published npm version) against a language's… | Benchmark CodeGraph retrieval quality on a real codebase by comparing agent behavior with vs without CodeGraph. |

#### `JARVIS`

🔗 [https://github.com/vamsy16/JARVIS](https://github.com/vamsy16/JARVIS) · Fork of [`affaan-m/JARVIS`](https://github.com/affaan-m/JARVIS) · Language: n/a · Last push: 2026-06-04

**What it is:** JARVIS: a real-time agentic intelligence-gathering platform powered by autonomous web scraping & OSINT, streamed via Meta Ray-Ban smart glasses

**When to use:** For autonomous real-time intelligence gathering (OSINT + web scraping) — e.g., streamed to smart glasses.

**Skills inside — 2** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`JARVIS`](https://github.com/vamsy16/JARVIS/tree/HEAD/.claude/skills/JARVIS) | — | JARVIS Development Patterns — > Auto-generated skill from repository analysis |
| [`YC_hackathon`](https://github.com/vamsy16/JARVIS/tree/HEAD/.claude/skills/YC_hackathon) | — | YC_hackathon Development Patterns — > Auto-generated skill from repository analysis |

#### `agentshield`

🔗 [https://github.com/vamsy16/agentshield](https://github.com/vamsy16/agentshield) · Fork of [`affaan-m/agentshield`](https://github.com/affaan-m/agentshield) · Language: n/a · Last push: 2026-07-22

**What it is:** AI agent security scanner. Detect vulnerabilities in agent configurations, MCP servers, and tool permissions. Available as CLI, GitHub Action, ECC plugin, and GitHub App integration. 🛡️

**When to use:** When you need to audit agent security: config vulnerabilities, MCP servers, and tool permissions. CLI, GitHub Action, or GitHub App.

**Install / quick start:**

```bash
agentshield runtime install      # install the PreToolUse runtime monitor
agentshield runtime status --check
```

**Skills inside — 1** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`agentshield`](https://github.com/vamsy16/agentshield/tree/HEAD/.claude/skills/agentshield) | — | agentshield Development Patterns — > Auto-generated skill from repository analysis |

#### `sequential-thinking-skill`

🔗 [https://github.com/vamsy16/sequential-thinking-skill](https://github.com/vamsy16/sequential-thinking-skill) · Fork of [`thedotmack/sequential-thinking-skill`](https://github.com/thedotmack/sequential-thinking-skill) · Language: n/a · Last push: 2026-02-27

**What it is:** Claude Code skill replicating the Sequential Thinking MCP server — structured reasoning with branching, revision, and persistent state. No MCP required.

**When to use:** When you need structured step-by-step reasoning with branching, revision, and persistent state — no MCP required.

**Install / quick start:**

```bash
npx skills add https://github.com/thedotmack/sequential-thinking-skill --skill sequential-thinking
```

**Skills inside — 1** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`sequential-thinking`](https://github.com/vamsy16/sequential-thinking-skill/tree/HEAD/sequential-thinking) | Use this skill when: (1) Breaking down complex problems into steps, (2) Planning and design with room for revision, (3) Analysis that might need course correction, (4)… | Dynamic, reflective problem-solving through structured sequential thoughts with support for branching, revision, and adaptive depth. |

#### `claude-swarm`

🔗 [https://github.com/vamsy16/claude-swarm](https://github.com/vamsy16/claude-swarm) · Fork of [`affaan-m/claude-swarm`](https://github.com/affaan-m/claude-swarm) · Language: n/a · Last push: 2026-02-11

**What it is:** Multi-agent orchestration for Claude Code — decompose tasks, coordinate agents, visualize everything in a rich terminal UI

**When to use:** When decomposing big tasks across multiple coordinated agents with a rich terminal UI.

*No packaged skills — use the project directly.*

#### `claude-counter`

🔗 [https://github.com/vamsy16/claude-counter](https://github.com/vamsy16/claude-counter) · Fork of [`she-llac/claude-counter`](https://github.com/she-llac/claude-counter) · Language: n/a · Last push: 2026-03-21

**What it is:** A minimal browser extension that shows token count, cache timer, and usage bars on claude.ai.

**When to use:** When you want token count, cache timer, and usage bars on claude.ai (browser extension).

*No packaged skills — use the project directly.*

#### `build-your-own-claude-code`

🔗 [https://github.com/vamsy16/build-your-own-claude-code](https://github.com/vamsy16/build-your-own-claude-code) · Fork of [`codecrafters-io/build-your-own-claude-code`](https://github.com/codecrafters-io/build-your-own-claude-code) · Language: n/a · Last push: 2026-07-30

**What it is:** Definition for the claude-code challenge.

**When to use:** For learning how agent harnesses like Claude Code actually work by building one.

*No packaged skills — use the project directly.*

#### `graphify`

🔗 [https://github.com/vamsy16/graphify](https://github.com/vamsy16/graphify) · Fork of [`Graphify-Labs/graphify`](https://github.com/Graphify-Labs/graphify) · Language: n/a · Last push: 2026-08-29

**What it is:** Turn any codebase, with its docs, SQL schemas, configs, and PDFs, into a queryable knowledge graph. A /graphify skill for Claude Code, Cursor, Codex, and Gemini CLI: local deterministic AST parsing, every edge explained, no vector store.

**When to use:** When you want any codebase + docs + SQL + PDFs turned into a queryable knowledge graph with explained edges.

*No packaged skills — use the project directly.*

#### `headroom`

🔗 [https://github.com/vamsy16/headroom](https://github.com/vamsy16/headroom) · Fork of [`headroomlabs-ai/headroom`](https://github.com/headroomlabs-ai/headroom) · Language: n/a · Last push: 2026-08-30

**What it is:** Compress tool outputs, logs, files, and RAG chunks before they reach the LLM. 20% fewer tokens for coding agents, 60-95% fewer tokens for JSON, same answers. Library, proxy, MCP server.

**When to use:** When token costs hurt — compress tool outputs, logs, files, and RAG chunks before they reach the LLM (60–95% fewer tokens for JSON).

*No packaged skills — use the project directly.*

#### `n8n-nodes-browser-use`

🔗 [https://github.com/vamsy16/n8n-nodes-browser-use](https://github.com/vamsy16/n8n-nodes-browser-use) · Fork of [`browser-use/n8n-nodes-browser-use`](https://github.com/browser-use/n8n-nodes-browser-use) · Language: n/a · Last push: 2026-08-29

**What it is:** n8n community node for Browser Use Cloud — browser-automation agent workflows inside n8n.

**When to use:** When running browser-automation agents inside n8n workflows.

*No packaged skills — use the project directly.*

#### `markitdown`

🔗 [https://github.com/vamsy16/markitdown](https://github.com/vamsy16/markitdown) · Fork of [`microsoft/markitdown`](https://github.com/microsoft/markitdown) · Language: n/a · Last push: 2026-08-19

**What it is:** Python tool for converting files and office documents to Markdown.

**When to use:** When converting files/office documents (PDF, DOCX, XLSX, PPTX) into Markdown for LLMs.

*No packaged skills — use the project directly.*

#### `scrcpy`

🔗 [https://github.com/vamsy16/scrcpy](https://github.com/vamsy16/scrcpy) · Fork of [`Genymobile/scrcpy`](https://github.com/Genymobile/scrcpy) · Language: n/a · Last push: 2026-08-17

**What it is:** Display and control your Android device

**When to use:** When you need to display and control an Android device from your computer.

*No packaged skills — use the project directly.*

---

### 💼 Business Apps & Integrations (4 repos)

*Open-source business applications: CRM, commerce, bookkeeping, trading.*

| Repo | Skills | One-line purpose |
|---|---|---|
| [`bookkeeper-starter`](https://github.com/vamsy16/bookkeeper-starter) | 5 | AI-operated, human-approved bookkeeping for Claude Code — multi-client Google Sheets ledgers,… |
| [`shopify-graphql-admin-mcp`](https://github.com/vamsy16/shopify-graphql-admin-mcp) | — | Connect Claude to your Shopify store, and unlock the full power of Claude for your store. |
| [`stoictradingAI`](https://github.com/vamsy16/stoictradingAI) | — | 🤖 Autonomous Solana trading bot with transparent execution |
| [`twenty`](https://github.com/vamsy16/twenty) | 18 | The open alternative to Salesforce, designed for AI. |

#### `twenty`

🔗 [https://github.com/vamsy16/twenty](https://github.com/vamsy16/twenty) · Fork of [`twentyhq/twenty`](https://github.com/twentyhq/twenty) · Language: n/a · Last push: 2026-08-30

**What it is:** The open alternative to Salesforce, designed for AI.

**When to use:** When you need a modern open-source CRM (the Salesforce alternative) designed for AI — includes 18 development skills for contributing/customizing.

**Skills inside — 18** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`create-app`](https://github.com/vamsy16/twenty/tree/HEAD/packages/twenty-codex-plugin/skills/create-app) | Use when you want to create or scaffold a new Twenty app | Use when you want to create or scaffold a new Twenty app |
| [`develop-app`](https://github.com/vamsy16/twenty/tree/HEAD/packages/twenty-codex-plugin/skills/develop-app) | Use when you want to add or modify Twenty app entities, including objects, layouts, logic functions, and front components inside an existing Twenty app. | Use when you want to add or modify Twenty app entities, including objects, layouts, logic functions, and front components inside an existing Twenty app. |
| [`manage-app`](https://github.com/vamsy16/twenty/tree/HEAD/packages/twenty-codex-plugin/skills/manage-app) | Use when you want to manage or troubleshoot tooling, remotes, sync, build, deploy, logs, CI/CD, or operational workflows for an existing Twenty app. | Use when you want to manage or troubleshoot tooling, remotes, sync, build, deploy, logs, CI/CD, or operational workflows for an existing Twenty app. |
| [`publish-app`](https://github.com/vamsy16/twenty/tree/HEAD/packages/twenty-codex-plugin/skills/publish-app) | Use when you want to prepare or verify a Twenty app for npm or marketplace publication, including README/About copy, package metadata, defineApplication marketplace… | Use when you want to prepare or verify a Twenty app for npm or marketplace publication, including README/About copy, package metadata, defineApplication marketplace metadata, logos, screenshots, and public assets. |
| [`qa-scout`](https://github.com/vamsy16/twenty/tree/HEAD/.claude/skills/qa-scout) | — | Browser QA of a PR against a running Twenty app, post-merge on main or pre-merge via the qa-scout label. |
| [`syncable-entity-builder-and-validation`](https://github.com/vamsy16/twenty/tree/HEAD/.cursor/skills/syncable-entity-builder-and-validation) | Use when implementing business rule validation, uniqueness checks, foreign key validation, or building workspace migration actions for syncable entities. | Create validation logic and migration action builders for syncable entities in Twenty. Validators never throw and never mutate. |
| [`syncable-entity-cache-and-transform`](https://github.com/vamsy16/twenty/tree/HEAD/.cursor/skills/syncable-entity-cache-and-transform) | Use when implementing entity-to-flat conversions, input DTO transpilation to universal flat entities, or cache recomputation for syncable entities. | Create cache services and transformation utilities for syncable entities in Twenty. |
| [`syncable-entity-integration`](https://github.com/vamsy16/twenty/tree/HEAD/.cursor/skills/syncable-entity-integration) | Use when registering builders, validators, and action handlers in modules, creating business services, or exposing entities via GraphQL API with proper exception… | Wire syncable entity services into NestJS modules, create service layer and resolvers for Twenty entities. |
| [`syncable-entity-runner-and-actions`](https://github.com/vamsy16/twenty/tree/HEAD/.cursor/skills/syncable-entity-runner-and-actions) | Use when creating database operations for syncable entities, implementing universal-to-flat entity transpilation, or handling create/update/delete actions in the runner… | Implement action handlers for executing workspace migrations in Twenty. |
| [`syncable-entity-testing`](https://github.com/vamsy16/twenty/tree/HEAD/.cursor/skills/syncable-entity-testing) | Use when writing integration tests for metadata entities, covering validator exceptions, input transpilation errors, and CRUD operations. | Create comprehensive integration tests for syncable entities in Twenty. Tests are MANDATORY for all syncable entities. |
| [`syncable-entity-types-and-constants`](https://github.com/vamsy16/twenty/tree/HEAD/.cursor/skills/syncable-entity-types-and-constants) | Use when creating new syncable entities, defining TypeORM entities, flat entity types, or registering in central constants… | Define types, entities, and central constant registrations for syncable entities in Twenty's workspace migration system. |
| [`twenty-lead-brief`](https://github.com/vamsy16/twenty/tree/HEAD/packages/twenty-apps/internal/twenty-partners/src/skills/twenty-lead-brief) | Use whenever you have a call recording, transcript, Fireflies link, or a lead folder and wants to qualify the deal, summarize the call, write a partner brief, or prep… | Turn a Twenty sales/discovery call into a partner-ready brief and record the lead in the CRM. Trigger even without the word "brief" - "summarize this call", "what did we learn from the X call", "qualify this lead", "scope this… |
| [`twenty-partner-intro`](https://github.com/vamsy16/twenty/tree/HEAD/packages/twenty-apps/internal/twenty-partners/src/skills/twenty-partner-intro) | — | Send the partner introductions for a lead - record them in the CRM and open the ready-to-send emails in Chrome. |
| [`twenty-partner-recap`](https://github.com/vamsy16/twenty/tree/HEAD/packages/twenty-apps/internal/twenty-partners/src/skills/twenty-partner-recap) | Use after a batch of partner calls when you want each partner's CRM record updated with what was said. | Pull recent Fireflies partner meetings, match each to an existing Partner record by attendee email or domain, write a recap (transcript-first, Fireflies summary as fallback), and inject it as a Note on the partner's profile. |
| [`twenty-partner-shortlist`](https://github.com/vamsy16/twenty/tree/HEAD/packages/twenty-apps/internal/twenty-partners/src/skills/twenty-partner-shortlist) | Use when you ask who to introduce, who fits this deal, which partners to consider, or to match a lead to partners. | Shortlist the Twenty partners who fit a lead, with the reason for each, and stop so the user can review. |
| [`twenty-partner-triage`](https://github.com/vamsy16/twenty/tree/HEAD/packages/twenty-apps/internal/twenty-partners/src/skills/twenty-partner-triage) | Use when you want to triage, rank, or prioritize partner applications, find which applicants are worth chasing, run the daily or weekly application review, or asks "who… | Rank the partner-application backlog by net-new value and hand back a short chase-list of applicants worth a personal nudge. Reads the live partners workspace, read-only, never mutates a record. |
| [`twenty-record-presentation`](https://github.com/vamsy16/twenty/tree/HEAD/packages/twenty-claude-skills/skills/twenty-record-presentation) | — | Retrieve and present Twenty CRM records as readable summaries or tables, using the connected Twenty MCP server to discover fields, fetch relevant data, format dates and values, build record links, and avoid raw API output. |
| [`use-twenty-mcp`](https://github.com/vamsy16/twenty/tree/HEAD/packages/twenty-codex-plugin/skills/use-twenty-mcp) | Use when you want Codex to connect to an existing Twenty workspace through MCP, retrieve or inspect workspace records and metadata, or present Twenty CRM data as… | Use when you want Codex to connect to an existing Twenty workspace through MCP, retrieve or inspect workspace records and metadata, or present Twenty CRM data as readable Markdown with formatted dates, values, record links, and… |

#### `bookkeeper-starter`

🔗 [https://github.com/vamsy16/bookkeeper-starter](https://github.com/vamsy16/bookkeeper-starter) · Fork of [`audrey-560/bookkeeper-starter`](https://github.com/audrey-560/bookkeeper-starter) · Language: n/a · Last push: 2026-07-16

**What it is:** AI-operated, human-approved bookkeeping for Claude Code — multi-client Google Sheets ledgers, statement importers, exception queue, monthly close with period locks. Clone it and run /bk-onboard.

**When to use:** For AI-operated bookkeeping: multi-client Google Sheets ledgers, statement importers, exception queue, monthly close with period locks — human-approved.

**Install / quick start:**

```bash
pip install -r requirements.txt
# add Google OAuth credentials.json to project root, then in Claude Code: /bk-onboard
```

**Skills inside — 5** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`bk-import`](https://github.com/vamsy16/bookkeeper-starter/tree/HEAD/.claude/skills/bk-import) | Use for "import statements", "process the inbox", "pull bank data". | Ingest whatever statements are waiting — scan a bookkeeper client's inbox drop-folder (and pull API statements), import/normalize/dedupe them, and report coverage gaps plus exactly what's still missing and how to get it. |
| [`bk-onboard`](https://github.com/vamsy16/bookkeeper-starter/tree/HEAD/.claude/skills/bk-onboard) | Use for "onboard a bookkeeping client", "set up books for X", "new bookkeeper client". | Onboard a new bookkeeping client — interview about their business, tax jurisdiction, bank accounts, payment processors, invoicing and preferences, then generate their complete client workspace (profile, COA, Google Sheet ledger,… |
| [`bk-status`](https://github.com/vamsy16/bookkeeper-starter/tree/HEAD/.claude/skills/bk-status) | Use for "bookkeeping status", "where are the books", "what's outstanding", "any deadlines coming up". | Bookkeeping status dashboard across all clients (or one) — statement coverage and staleness, open exceptions, close-period states, upcoming tax filing deadlines, open invoices. |
| [`invoice`](https://github.com/vamsy16/bookkeeper-starter/tree/HEAD/.claude/skills/invoice) | — | Generate a client invoice end-to-end — PDF, Drive upload, Google Sheets log, and issuance journal entry, with the billing address auto-filled from the customer registry. |
| [`monthly-close`](https://github.com/vamsy16/bookkeeper-starter/tree/HEAD/.claude/skills/monthly-close) | Use when someone asks to close the books, run the monthly close, do month-end, or close a specific month (e.g. | close May") for a bookkeeper client. Imports statements, checks coverage/continuity, reconciles open invoices, logs agency payouts and expenses, clears exceptions, runs bank reconciliation as the final gate, reviews tax, then… |

#### `shopify-graphql-admin-mcp`

🔗 [https://github.com/vamsy16/shopify-graphql-admin-mcp](https://github.com/vamsy16/shopify-graphql-admin-mcp) · Fork of [`colbymchenry/shopify-graphql-admin-mcp`](https://github.com/colbymchenry/shopify-graphql-admin-mcp) · Language: n/a · Last push: 2026-03-24

**What it is:** Connect Claude to your Shopify store, and unlock the full power of Claude for your store.

**When to use:** When connecting Claude to a Shopify store to unlock store management via GraphQL Admin API.

*No packaged skills — use the project directly.*

#### `stoictradingAI`

🔗 [https://github.com/vamsy16/stoictradingAI](https://github.com/vamsy16/stoictradingAI) · Fork of [`affaan-m/stoictradingAI`](https://github.com/affaan-m/stoictradingAI) · Language: n/a · Last push: 2026-05-18

**What it is:** 🤖 Autonomous Solana trading bot with transparent execution

**When to use:** For autonomous Solana trading with transparent execution (use with caution).

*No packaged skills — use the project directly.*

---

### 🧠 Knowledge Management & Productivity (3 repos)

*Second-brain / note-taking / focus tooling built on AI agents.*

| Repo | Skills | One-line purpose |
|---|---|---|
| [`claude-obsidian`](https://github.com/vamsy16/claude-obsidian) | 15 | Self-organizing AI second brain for Obsidian + Claude Code. |
| [`i-have-adhd`](https://github.com/vamsy16/i-have-adhd) | 1 | A skill to stop your coding agent from burying the answer. ADHD-friendly output. |
| [`second-brain`](https://github.com/vamsy16/second-brain) | 8 | AI-powered 'second brain': git-tracked Obsidian vault run by Claude Code that captures, organizes,… |

#### `claude-obsidian`

🔗 [https://github.com/vamsy16/claude-obsidian](https://github.com/vamsy16/claude-obsidian) · Fork of [`AgriciDaniel/claude-obsidian`](https://github.com/AgriciDaniel/claude-obsidian) · Language: n/a · Last push: 2026-08-26

**What it is:** Self-organizing AI second brain for Obsidian + Claude Code. Drop any source and Claude reads, links, and files it into one connected knowledge graph of plain Markdown you own. AI note-taking, personal knowledge management (PKM), and an open-source Notion alternative. Based on Karpathy's LLM Wiki pattern.

**When to use:** When you want a self-organizing AI second brain for Obsidian — drop any source and Claude reads, links, and files it into a connected knowledge graph you own.

**Skills inside — 15** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`autoresearch`](https://github.com/vamsy16/claude-obsidian/tree/HEAD/skills/autoresearch) | Use when you want autonomous or deep research that may access the public web. | Run a bounded, source-grounded research loop, draft a cited dossier, and optionally propose a separately reviewed canonical vault merge. |
| [`canvas`](https://github.com/vamsy16/claude-obsidian/tree/HEAD/skills/canvas) | Use for canvas status, canvas lists, visual maps, zones, spatial layouts, adding vault notes or media to a .canvas file, and requests such as create canvas, add to… | Create, inspect, and update Obsidian JSON Canvas boards with text, file, link, group, and edge nodes. |
| [`defuddle`](https://github.com/vamsy16/claude-obsidian/tree/HEAD/skills/defuddle) | Use for defuddle, clean this URL, strip page clutter, readable Markdown from a web page, or preparing a web source for later wiki ingestion. | Plan and, with explicit network consent, use an optional external Defuddle cleaner to extract article-like HTTPS pages as Markdown. |
| [`obsidian-bases`](https://github.com/vamsy16/claude-obsidian/tree/HEAD/skills/obsidian-bases) | Use for Obsidian Bases, database-like vault views, dynamic tables, reading lists, task trackers, filters, formulas, summaries, and .base file edits. | Explain, draft, and validate Obsidian Bases .base files with filters, formulas, properties, summaries, and table, card, or list views. |
| [`obsidian-markdown`](https://github.com/vamsy16/claude-obsidian/tree/HEAD/skills/obsidian-markdown) | Use when you explicitly requests Obsidian note formatting or syntax help, not for general Markdown or broad vault operations. | Explain, draft, or validate Obsidian Flavored Markdown syntax: properties, wikilinks, embeds, callouts, tags, comments, highlights, block references, math, and Mermaid. |
| [`save`](https://github.com/vamsy16/claude-obsidian/tree/HEAD/skills/save) | — | Save a user-selected answer, decision, insight, or session summary into an Obsidian vault as one reviewed transaction. |
| [`think`](https://github.com/vamsy16/claude-obsidian/tree/HEAD/skills/think) | Use for think this through, deep think, architecture review, postmortem, tradeoff analysis, or challenges to assumptions. | Apply the Fable-derived 10-stage OBSERVE, OBSERVE, LISTEN, THINK, CONNECT, CONNECT, FEEL, ACCEPT, CREATE, GROW loop to consequential or ambiguous reasoning and decisions. |
| [`wiki`](https://github.com/vamsy16/claude-obsidian/tree/HEAD/skills/wiki) | Use for vault setup, scaffolding, workspace selection, cross-project configuration, or choosing the correct wiki sub-skill. | Initialize, adopt, and route work for a separate Obsidian knowledge vault through the portable claude-obsidian core. |
| [`wiki-cli`](https://github.com/vamsy16/claude-obsidian/tree/HEAD/skills/wiki-cli) | — | Detect and use the official Obsidian command-line interface for read-only vault access; use for wiki-cli, Obsidian CLI, Obsidian read, Obsidian search, vault transport, which transport, transport detection, backlinks, tags, or… |
| [`wiki-fold`](https://github.com/vamsy16/claude-obsidian/tree/HEAD/skills/wiki-fold) | Use for manual log compression without modifying child pages. | Create a bounded, extractive, structurally idempotent rollup of recent Obsidian wiki log entries, with dry-run preview by default and one optional transaction apply. |
| [`wiki-ingest`](https://github.com/vamsy16/claude-obsidian/tree/HEAD/skills/wiki-ingest) | Use for a single source or bounded batch, not for saving an assistant answer. | Ingest supplied source material into an Obsidian vault with provenance and claim tracking: pasted text, files staged in the selected vault's inbox or .raw archive, or explicitly approved URLs. |
| [`wiki-lint`](https://github.com/vamsy16/claude-obsidian/tree/HEAD/skills/wiki-lint) | Use for lint, vault health check, audit wiki health, find orphans, find dead links, frontmatter audit, provenance audit, or wiki audit. | Run a deterministic, read-only health check on an Obsidian wiki. Reports graph, link, frontmatter, provenance-ledger, empty-section, and stale-index findings; it does not reason broadly or repair files. |
| [`wiki-mode`](https://github.com/vamsy16/claude-obsidian/tree/HEAD/skills/wiki-mode) | Use for wiki mode, methodology mode, what is my vault mode, set vault mode, switch to PARA, use LYT, Zettelkasten setup, change mode, configure mode, or methodology… | Read or configure the vault filing methodology and suggest destinations for planned knowledge creation under Generic, LYT, PARA, or Zettelkasten. This skill does not save content or migrate notes. |
| [`wiki-query`](https://github.com/vamsy16/claude-obsidian/tree/HEAD/skills/wiki-query) | Use when you selects the vault as the evidence source: query the wiki, query quick, query deep, explain from the wiki, summarize the vault, find in wiki, search the… | Answer an explicitly vault-scoped question from an Obsidian wiki without changing it. Do not route ordinary general-knowledge questions here. |
| [`wiki-retrieve`](https://github.com/vamsy16/claude-obsidian/tree/HEAD/skills/wiki-retrieve) | — | Build and query a vault-local contextual BM25 retrieval index with optional multilingual Nomic cosine reranking; |

#### `second-brain`

🔗 [https://github.com/vamsy16/second-brain](https://github.com/vamsy16/second-brain) · Fork of [`bradautomates/second-brain`](https://github.com/bradautomates/second-brain) · Language: n/a · Last push: 2026-03-29

**What it is:** AI-powered 'second brain': git-tracked Obsidian vault run by Claude Code that captures, organizes, and farms context while you work.

**When to use:** When you want an AI 'Chief of Staff' — a git-tracked Obsidian vault that captures, organizes, and farms context while you work.

**Skills inside — 8** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`create-farmer`](https://github.com/vamsy16/second-brain/tree/HEAD/.claude/skills/create-farmer) | — | Create or schedule a context farmer. Checks existing farmers and offers to build new ones or schedule existing ones. |
| [`daily-review`](https://github.com/vamsy16/second-brain/tree/HEAD/.claude/skills/daily-review) | — | End of day review - compare planned vs actual, update task statuses. Part of chief-of-staff system. |
| [`delegate`](https://github.com/vamsy16/second-brain/tree/HEAD/.claude/skills/delegate) | Use this when you request 'delegate' or 'create a new terminal' or 'new terminal: <command>' or 'fork session: <command>'. | Delegate a task by forking a terminal session to a new terminal window. |
| [`farm`](https://github.com/vamsy16/second-brain/tree/HEAD/.claude/skills/farm) | — | Manually trigger a context farmer subagent. Usage - /farm <name> (e.g., /farm slack) |
| [`history`](https://github.com/vamsy16/second-brain/tree/HEAD/.claude/skills/history) | — | Show recent git activity in readable format. Part of chief-of-staff system. |
| [`new`](https://github.com/vamsy16/second-brain/tree/HEAD/.claude/skills/new) | Use for capturing tasks, ideas, project notes, or people notes. | Quick capture - classify and file natural language input into the vault. Part of chief-of-staff system. |
| [`start-second-brain`](https://github.com/vamsy16/second-brain/tree/HEAD/.claude/skills/start-second-brain) | — | Initialize a new Second Brain vault from a template repo — validate privacy, create folders, push, and onboard the user. |
| [`today`](https://github.com/vamsy16/second-brain/tree/HEAD/.claude/skills/today) | — | Generate daily plan from due tasks and active projects. Part of chief-of-staff vault system. |

#### `i-have-adhd`

🔗 [https://github.com/vamsy16/i-have-adhd](https://github.com/vamsy16/i-have-adhd) · Fork of [`ayghri/i-have-adhd`](https://github.com/ayghri/i-have-adhd) · Language: n/a · Last push: 2026-08-26

**What it is:** A skill to stop your coding agent from burying the answer. ADHD-friendly output.

**When to use:** When agent answers are too long/buried — makes output ADHD-friendly: answer first, detail later.

**Install / quick start:**

Paste into your CLI:
```text
Install the i-have-adhd skill/plugin from https://github.com/ayghri/i-have-adhd, refer to the repo's AGENTS.md for instructions.
```

**Skills inside — 1** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`i-have-adhd`](https://github.com/vamsy16/i-have-adhd/tree/HEAD/skills/i-have-adhd) | — | Shape output for a reader with ADHD: lead with the next action, number multi-step work, restate state across turns, suppress tangents, give specific time estimates, make wins visible. |

---

### 📚 Learning, References & Inspiration (11 repos)

*Curated lists, challenges, prompt references, and inspiration collections.*

| Repo | Skills | One-line purpose |
|---|---|---|
| [`10-projects-10-hours`](https://github.com/vamsy16/10-projects-10-hours) | — | Reference — florinpop17's challenge of building 10 projects in 10 hours on a livestream. |
| [`100Days100Projects`](https://github.com/vamsy16/100Days100Projects) | — | Creating 100 Projects in 100 Days Challenge |
| [`500-AI-Agents-Projects`](https://github.com/vamsy16/500-AI-Agents-Projects) | — | The 500 AI Agents Projects is a curated collection of AI agent use cases across various industries. |
| [`app-ideas`](https://github.com/vamsy16/app-ideas) | — | A Collection of application ideas which can be used to improve your coding skills. |
| [`build-your-own-x`](https://github.com/vamsy16/build-your-own-x) | — | Master programming by recreating your favorite technologies from scratch. |
| [`CL4R1T4S`](https://github.com/vamsy16/CL4R1T4S) | — | LEAKED SYSTEM PROMPTS FOR CHATGPT, CLAUDE, GEMINI, GROK, PERPLEXITY, CURSOR, LOVABLE, REPLIT, AND… |
| [`developer-portfolios`](https://github.com/vamsy16/developer-portfolios) | — | A list of developer portfolios for your inspiration |
| [`ml-starter-kit`](https://github.com/vamsy16/ml-starter-kit) | — | Machine Learning Starter Projects |
| [`project-based-learning`](https://github.com/vamsy16/project-based-learning) | — | Curated list of project-based tutorials |
| [`Project-Ideas-And-Resources`](https://github.com/vamsy16/Project-Ideas-And-Resources) | — | A Collection of application ideas that can be used to improve your coding skills ❤. |
| [`system_prompts_leaks`](https://github.com/vamsy16/system_prompts_leaks) | 49 | Extracted system prompts from Anthropic - Claude Fable 5, Opus 5, Claude Design, Claude Code. |

#### `system_prompts_leaks`

🔗 [https://github.com/vamsy16/system_prompts_leaks](https://github.com/vamsy16/system_prompts_leaks) · Fork of [`asgeirtj/system_prompts_leaks`](https://github.com/asgeirtj/system_prompts_leaks) · Language: n/a · Last push: 2026-08-30

**What it is:** Extracted system prompts from Anthropic - Claude Fable 5, Opus 5, Claude Design, Claude Code. OpenAI - ChatGPT GPT-5.6-Sol, Codex. Google - Gemini 3.5 Flash, 3.1 Pro, Antigravity. xAI - Grok, Cursor, Copilot, VS Code, Perplexity, and more. Updated regularly.

**When to use:** Reference of extracted system prompts (Claude Fable/Opus/Design/Code, ChatGPT GPT-5.6, Codex, Gemini, Grok, Cursor, Copilot, VS Code, Perplexity) — updated regularly. Also ships 49 prompt-as-skill files.

**Skills inside — 49** *(install the repo, then just ask in plain language)*:

| Skill | Use when… | What it does |
|---|---|---|
| [`3d-object`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-design/skills/3d-object) | — | three.js model, downloadable as OBJ or GLB |
| [`animated-video`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-design/skills/animated-video) | — | Timeline-based motion design |
| [`artifact-capabilities`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-code/skills/artifact-capabilities) | — | Runtime capabilities a published Artifact page can be granted — behavior static HTML cannot provide on its own, such as the page reading live or connected data, remembering what people do on it (a poll, a sign-up sheet, a… |
| [`artifact-design`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-code/skills/artifact-design) | — | Design guidance and fundamentals for Artifacts. |
| [`artifact-diagramming`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-code/skills/artifact-diagramming) | — | Diagramming know-how for Artifacts - when a picture earns its place, how to draw one that shows the real mechanism, and the inline-SVG mechanics that keep it legible in both themes. |
| [`batch`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-code/skills/batch) | — | Research and plan a large-scale change, then execute it in parallel across 5–30 isolated worktree agents that each open a PR. |
| [`claude-api-in-prototypes`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-design/skills/claude-api-in-prototypes) | — | Call Claude from your HTML artifacts via window.claude.complete |
| [`claude-in-chrome`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-code/skills/claude-in-chrome) | — | Automates your Chrome browser to interact with web pages - clicking elements, filling forms, capturing screenshots, reading console logs, and navigating sites. Opens pages in new tabs within your existing Chrome session. |
| [`code-review`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-code/skills/code-review) | — | Review the current diff, or a PR number/branch/path target, for correctness bugs and reuse/simplification/efficiency cleanups at the given effort level (low/medium: fewer, high-confidence findings; |
| [`create-design-system`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-design/skills/create-design-system) | — | Skill to use if user asks you to create a design system or UI kit |
| [`dataviz`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-code/skills/dataviz) | — | Produce a chart, graph, dashboard, or any data visualization that reads as one system - elegant, accessible, and consistent in light and dark - BRAND-NEUTRAL, shipping a placeholder palette to swap for your own. |
| [`debug`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-code/skills/debug) | — | Enable debug logging for this session and help diagnose issues |
| [`deep-research`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-code/skills/deep-research) | — | Deep research harness — fan-out web searches, fetch sources, adversarially verify claims, synthesize a cited report. |
| [`design`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-code/skills/design) | Use when someone wants a design, mockup, wireframe, UI or screen design, landing page, poster, flyer, brochure, banner, card, one-pager, or any visual layout they would… | Create a design canvas - a multi-artboard visual design published as an Artifact that runs Claude Design's canvas editor (an early preview of Claude Design inside Claude Code). |
| [`design-sync`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-code/skills/design-sync) | Use when you run /design-sync or says "sync my design system to Claude Design". | Push a React design system to claude.ai/design. This runs a converter that bundles the real component code (from Storybook or a bare package) and uploads it. |
| [`doctor`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-code/skills/doctor) | Use when you ask for a doctor run, checkup, audit, tune-up, or cleanup of their Claude Code setup or configuration. | Health-check the user's Claude Code setup and fix issues: diagnose installation health — what the `claude doctor` terminal diagnostics cover — from local data (duplicate or leftover installs, PATH, unparseable settings files,… |
| [`export-as-pptx-editable`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-design/skills/export-as-pptx-editable) | — | Native text & shapes — editable in PowerPoint |
| [`export-as-pptx-screenshots`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-design/skills/export-as-pptx-screenshots) | — | Flat images — pixel-perfect but not editable |
| [`fewer-permission-prompts`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-code/skills/fewer-permission-prompts) | — | Scan your transcripts for common read-only Bash and MCP tool calls, then add a prioritized allowlist to project .claude/settings.json to reduce permission prompts. |
| [`flier`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-design/skills/flier) | — | Print-ready single page |
| [`frontend-design`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-design/skills/frontend-design) | — | Aesthetic direction for designs outside an existing brand system |
| [`handoff-to-claude-code`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-design/skills/handoff-to-claude-code) | — | Developer handoff package |
| [`hi-fi-design`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-design/skills/hi-fi-design) | — | The design process for high-fidelity, polished work — the system prompt tells Claude to invoke it before starting any design |
| [`html-email`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-design/skills/html-email) | — | Send-ready single-file email |
| [`init`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-code/skills/init) | — | Initialize a new CLAUDE.md file with codebase documentation |
| [`interactive-prototype`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-design/skills/interactive-prototype) | — | Working app with real interactions |
| [`keybindings-help`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-code/skills/keybindings-help) | Use when you want to customize keyboard shortcuts, rebind keys, add chord bindings, or modify ~/.claude/keybindings.json. | Examples: "rebind ctrl+s", "add a chord shortcut", "change the submit key", "customize keybindings". |
| [`loop`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-code/skills/loop) | — | Run a prompt or slash command on a recurring interval (e.g. /loop 5m /foo). Omit the interval to let the model self-pace. |
| [`make-a-deck`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-design/skills/make-a-deck) | — | Slide presentation in HTML |
| [`make-a-doc`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-design/skills/make-a-doc) | — | Page-style document, printable out of the box |
| [`make-tweakable`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-design/skills/make-tweakable) | — | Add in-design tweak controls |
| [`maps-geography`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-design/skills/maps-geography) | — | Accurate maps from real geo data — use for any map, or whenever geography would make a good graphic for a deliverable |
| [`non-storybook`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-code/skills/design-sync/non-storybook) | — | Package source shape — No Storybook - the component list comes from the package's shipped `.d.ts` exports, and there is **no reference render to verify against**. |
| [`options`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-design/skills/options) | — | Present multiple design options as a vertical stack of anchored turns |
| [`run`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-code/skills/run) | Use when asked to run, start, or screenshot the app, or to confirm a change works in the real app (not just tests). | Launch and drive this project's app to see a change working. First looks for a project skill that already covers launching the app; |
| [`run-skill-generator`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-code/skills/run-skill-generator) | Use when you ask to set up the project, get it running, write run instructions, or verify build/run steps work from a clean environment. | Author or improve the run-<unit> skill - a per-project skill that tells agents how to build, launch, and drive this project's app. |
| [`save-as-pdf`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-design/skills/save-as-pdf) | — | Print-ready PDF export |
| [`save-as-standalone-html`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-design/skills/save-as-standalone-html) | — | Single self-contained file that works offline |
| [`schedule`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-code/skills/schedule) | — | Create, update, list, or run scheduled cloud agents (routines) that execute on a cron schedule. |
| [`security-review`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-code/skills/security-review) | — | Complete a security review of the pending changes on the current branch |
| [`setup-cowork`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-cowork/setup-cowork) | Use when: set up cowork, setup cowork, get started with cowork, cowork onboarding, configure cowork, personalize cowork. | Guided Cowork setup — install a matching plugin, try a skill, connect tools. |
| [`setup-writing-style`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-cowork/setup-writing-style) | Use when you ask to set up, learn, or capture their writing voice, or complains that drafts sound generic or unlike them and no my-writing-style profile exists. | Learns how the user writes from their own sent messages and docs, and builds a voice profile so future drafts sound like them instead of generic AI. The profile is saved as the my-writing-style skill. |
| [`simplify`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-code/skills/simplify) | — | Review the changed code for reuse, simplification, efficiency, and altitude cleanups, then apply the fixes. Quality only — it does not hunt for bugs; use /code-review for that. |
| [`storybook`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-code/skills/design-sync/storybook) | — | Storybook source shape — Storybook is the **fidelity oracle, not the runtime**. The converter bundles the package's compiled `dist/` into `_ds_bundle.js` - the same bundle the claude.ai/design agent builds with - and generates… |
| [`update-config`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-code/skills/update-config) | — | Use this skill to configure the Claude Code harness via settings.json. Automated behaviors ("from now on when X", "each time X", "whenever X", "before/after X") require hooks configured in settings.json - the harness executes… |
| [`verify`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-code/skills/verify) | — | Verify that a code change actually does what it's supposed to by exercising it end-to-end and observing behavior — drive the affected flow, not just tests or typecheck. |
| [`web-research`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-design/skills/web-research) | — | Findings grounded in live web sources |
| [`wireframe`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-design/skills/wireframe) | — | Explore many ideas with wireframes and storyboards |
| [`workflow-authoring`](https://github.com/vamsy16/system_prompts_leaks/tree/HEAD/Anthropic/claude-code/skills/workflow-authoring) | — | Reference for writing a Workflow tool script (script API and gotchas, resume, quality patterns, worked examples). Load before authoring a script for a workflow the user already opted into; it does not itself authorize running one. |

#### `10-projects-10-hours`

🔗 [https://github.com/vamsy16/10-projects-10-hours](https://github.com/vamsy16/10-projects-10-hours) · Fork of [`florinpop17/10-projects-10-hours`](https://github.com/florinpop17/10-projects-10-hours) · Language: n/a · Last push: 2024-04-02

**What it is:** Reference — florinpop17's challenge of building 10 projects in 10 hours on a livestream.

**When to use:** Reference — 10 projects built in 10 hours challenge.

*No packaged skills — use the project directly.*

#### `100Days100Projects`

🔗 [https://github.com/vamsy16/100Days100Projects](https://github.com/vamsy16/100Days100Projects) · Fork of [`florinpop17/100Days100Projects`](https://github.com/florinpop17/100Days100Projects) · Language: n/a · Last push: 2024-10-10

**What it is:** Creating 100 Projects in 100 Days Challenge

**When to use:** Reference — the 100 projects in 100 days challenge.

*No packaged skills — use the project directly.*

#### `500-AI-Agents-Projects`

🔗 [https://github.com/vamsy16/500-AI-Agents-Projects](https://github.com/vamsy16/500-AI-Agents-Projects) · Fork of [`ashishpatel26/500-AI-Agents-Projects`](https://github.com/ashishpatel26/500-AI-Agents-Projects) · Language: n/a · Last push: 2026-07-27

**What it is:** The 500 AI Agents Projects is a curated collection of AI agent use cases across various industries. It showcases practical applications and provides links to open-source projects for implementation, illustrating how AI agents are transforming sectors such as healthcare, finance, education, retail, and more.

**When to use:** When brainstorming AI-agent product ideas — 500 curated use cases across industries with open-source implementation links.

*No packaged skills — use the project directly.*

#### `app-ideas`

🔗 [https://github.com/vamsy16/app-ideas](https://github.com/vamsy16/app-ideas) · Fork of [`florinpop17/app-ideas`](https://github.com/florinpop17/app-ideas) · Language: n/a · Last push: 2025-10-11

**What it is:** A Collection of application ideas which can be used to improve your coding skills.

**When to use:** When looking for application ideas to practice coding.

*No packaged skills — use the project directly.*

#### `build-your-own-x`

🔗 [https://github.com/vamsy16/build-your-own-x](https://github.com/vamsy16/build-your-own-x) · Fork of [`codecrafters-io/build-your-own-x`](https://github.com/codecrafters-io/build-your-own-x) · Language: n/a · Last push: 2026-07-14

**What it is:** Master programming by recreating your favorite technologies from scratch.

**When to use:** When learning by recreating technologies from scratch (databases, Git, React, Docker…).

*No packaged skills — use the project directly.*

#### `project-based-learning`

🔗 [https://github.com/vamsy16/project-based-learning](https://github.com/vamsy16/project-based-learning) · Fork of [`practical-tutorials/project-based-learning`](https://github.com/practical-tutorials/project-based-learning) · Language: n/a · Last push: 2026-08-24

**What it is:** Curated list of project-based tutorials

**When to use:** When learning via guided project-based tutorials.

*No packaged skills — use the project directly.*

#### `Project-Ideas-And-Resources`

🔗 [https://github.com/vamsy16/Project-Ideas-And-Resources](https://github.com/vamsy16/Project-Ideas-And-Resources) · Fork of [`The-Cool-Coders/Project-Ideas-And-Resources`](https://github.com/The-Cool-Coders/Project-Ideas-And-Resources) · Language: n/a · Last push: 2024-08-29

**What it is:** A Collection of application ideas that can be used to improve your coding skills ❤.

**When to use:** Another curated list of app ideas + resources for coding practice.

*No packaged skills — use the project directly.*

#### `ml-starter-kit`

🔗 [https://github.com/vamsy16/ml-starter-kit](https://github.com/vamsy16/ml-starter-kit) · Fork of [`techwithprateek/ml-starter-kit`](https://github.com/techwithprateek/ml-starter-kit) · Language: n/a · Last push: 2026-04-18

**What it is:** Machine Learning Starter Projects

**When to use:** Starter projects for machine learning practice.

*No packaged skills — use the project directly.*

#### `CL4R1T4S`

🔗 [https://github.com/vamsy16/CL4R1T4S](https://github.com/vamsy16/CL4R1T4S) · Fork of [`elder-plinius/CL4R1T4S`](https://github.com/elder-plinius/CL4R1T4S) · Language: n/a · Last push: 2026-08-15

**What it is:** LEAKED SYSTEM PROMPTS FOR CHATGPT, CLAUDE, GEMINI, GROK, PERPLEXITY, CURSOR, LOVABLE, REPLIT, AND MORE! - AI SYSTEMS TRANSPARENCY FOR ALL! 👐

**When to use:** Reference of leaked system prompts for major AI products (ChatGPT, Claude, Gemini, Grok, Perplexity, Cursor, Lovable, Replit).

*No packaged skills — use the project directly.*

#### `developer-portfolios`

🔗 [https://github.com/vamsy16/developer-portfolios](https://github.com/vamsy16/developer-portfolios) · Fork of [`emmabostian/developer-portfolios`](https://github.com/emmabostian/developer-portfolios) · Language: n/a · Last push: 2026-08-30

**What it is:** A list of developer portfolios for your inspiration

**When to use:** When designing a developer portfolio — curated examples for inspiration.

*No packaged skills — use the project directly.*

---

### 🧪 Misc & Personal (2 repos)

*Personal and miscellaneous projects.*

| Repo | Skills | One-line purpose |
|---|---|---|
| [`girlsgottagolf`](https://github.com/vamsy16/girlsgottagolf) | — | Example launch site for a women's golf community (Vite + React + TypeScript) — useful as a… |
| [`HyperMamba`](https://github.com/vamsy16/HyperMamba) | — | All Proprietary Research and Development |

#### `HyperMamba`

🔗 [https://github.com/vamsy16/HyperMamba](https://github.com/vamsy16/HyperMamba) · Fork of [`affaan-m/HyperMamba`](https://github.com/affaan-m/HyperMamba) · Language: n/a · Last push: 2025-02-19

**What it is:** All Proprietary Research and Development

**When to use:** Proprietary research & development fork — reference only.

*No packaged skills — use the project directly.*

#### `girlsgottagolf`

🔗 [https://github.com/vamsy16/girlsgottagolf](https://github.com/vamsy16/girlsgottagolf) · Fork of [`audrey-560/girlsgottagolf`](https://github.com/audrey-560/girlsgottagolf) · Language: n/a · Last push: 2026-06-17

**What it is:** Example launch site for a women's golf community (Vite + React + TypeScript) — useful as a landing-page reference.

**When to use:** Example marketing/launch site (women's golf community) — useful as a landing-page pattern reference.

*No packaged skills — use the project directly.*

---

## 4️⃣ Appendix — All 103 Repositories (flat index)

| # | Repository | Type | Category | Skills | Purpose |
|---|---|---|---|---|---|
| 1 | [`10-projects-10-hours`](https://github.com/vamsy16/10-projects-10-hours) | Fork of `10-projects-10-hours` | Learning, References & Inspiration | — | Reference — florinpop17's challenge of building 10 projects in 10 hours on a livestream. |
| 2 | [`100Days100Projects`](https://github.com/vamsy16/100Days100Projects) | Fork of `100Days100Projects` | Learning, References & Inspiration | — | Creating 100 Projects in 100 Days Challenge |
| 3 | [`500-AI-Agents-Projects`](https://github.com/vamsy16/500-AI-Agents-Projects) | Fork of `500-AI-Agents-Projects` | Learning, References & Inspiration | — | The 500 AI Agents Projects is a curated collection of AI agent use cases across various industries. |
| 4 | [`Agent-Reach`](https://github.com/vamsy16/Agent-Reach) | Fork of `Agent-Reach` | Web Scraping & Lead Generation | 1 | Give your AI agent eyes to see the entire internet. Read & search Twitter, Reddit, YouTube, GitHub, Bilibili, XiaoHongShu — one… |
| 5 | [`agentshield`](https://github.com/vamsy16/agentshield) | Fork of `agentshield` | AI Agents, Harnesses & Developer Tooling | 1 | AI agent security scanner. Detect vulnerabilities in agent configurations, MCP servers, and tool permissions. |
| 6 | [`AI-Faceless-Video-Generator`](https://github.com/vamsy16/AI-Faceless-Video-Generator) | Fork of `AI-Faceless-Video-Generator` | Video, Audio & Creative AI | — | Generate a video script, voice and a talking face completely with AI |
| 7 | [`AI-Influencer-Generator`](https://github.com/vamsy16/AI-Influencer-Generator) | Fork of `AI-Influencer-Generator` | Video, Audio & Creative AI | — | Create and customize your AI influencer open-source |
| 8 | [`ai-operating-system-template`](https://github.com/vamsy16/ai-operating-system-template) | Fork of `ai-operating-system-template` | AI Agents, Harnesses & Developer Tooling | 5 | A clean starter template for building a personal AI Operating System in Claude Code — core skills (/onboard, /audit,… |
| 9 | [`ai-site-cloner`](https://github.com/vamsy16/ai-site-cloner) | Fork of `ai-site-cloner` | Design & Front-End Engineering | 2 | Clone any website into a pixel-accurate Next.js app with AI — Playwright-measured extraction (no eyeballing), spec-gated parallel… |
| 10 | [`AI-VFX`](https://github.com/vamsy16/AI-VFX) | Fork of `AI-VFX` | Video, Audio & Creative AI | — | AI-powered tool for creating advanced visual effects (VFX) in videos |
| 11 | [`AI-Youtube-Shorts-Generator`](https://github.com/vamsy16/AI-Youtube-Shorts-Generator) | Fork of `AI-Youtube-Shorts-Generator` | Video, Audio & Creative AI | 1 | Open-source alternative to Opus Clip, Vidyo.ai, Klap & SubMagic. |
| 12 | [`alex-hormozi-coach`](https://github.com/vamsy16/alex-hormozi-coach) | Fork of `alex-hormozi-coach` | Marketing, SEO & Growth | 1 | Free Claude skill that coaches your business in Alex Hormozi's hotline method — numbers first, find the real constraint, prove it… |
| 13 | [`app-ideas`](https://github.com/vamsy16/app-ideas) | Fork of `app-ideas` | Learning, References & Inspiration | — | A Collection of application ideas which can be used to improve your coding skills. |
| 14 | [`autoscraper`](https://github.com/vamsy16/autoscraper) | Fork of `autoscraper` | Web Scraping & Lead Generation | — | A Smart, Automatic, Fast and Lightweight Web Scraper for Python |
| 15 | [`autoshorts`](https://github.com/vamsy16/autoshorts) | Fork of `autoshorts` | Video, Audio & Creative AI | — | AutoShorts is a local-first desktop application for turning long-form video or audio recordings into high-impact, vertical… |
| 16 | [`awesome-design-md`](https://github.com/vamsy16/awesome-design-md) | Fork of `awesome-design-md` | Design & Front-End Engineering | — | A collection of DESIGN.md files analysis by popular brand design systems. |
| 17 | [`banana-claude`](https://github.com/vamsy16/banana-claude) | Fork of `banana-claude` | Design & Front-End Engineering | 1 | AI image generation skill for Claude Code - Creative Director powered by Gemini |
| 18 | [`bookkeeper-starter`](https://github.com/vamsy16/bookkeeper-starter) | Fork of `bookkeeper-starter` | Business Apps & Integrations | 5 | AI-operated, human-approved bookkeeping for Claude Code — multi-client Google Sheets ledgers, statement importers, exception… |
| 19 | [`Brand-building-skills`](https://github.com/vamsy16/Brand-building-skills) | Fork of `Brand-building-skills` | Marketing, SEO & Growth | 29 | Brand building skills for Claude Code and AI agents. strategy, naming, identity, voice, positioning, messaging, auditing, and… |
| 20 | [`browser-harness`](https://github.com/vamsy16/browser-harness) | Fork of `browser-harness` | AI Agents, Harnesses & Developer Tooling | 3 | Browser Harness \| Self-healing harness that enables LLMs to complete any task. |
| 21 | [`browser-use`](https://github.com/vamsy16/browser-use) | Fork of `browser-use` | AI Agents, Harnesses & Developer Tooling | 6 | 🌐 Make websites accessible for AI agents. Automate tasks online with ease. |
| 22 | [`browsercode`](https://github.com/vamsy16/browsercode) | Fork of `browsercode` | AI Agents, Harnesses & Developer Tooling | 2 | The browser-native agent framework |
| 23 | [`build-your-own-claude-code`](https://github.com/vamsy16/build-your-own-claude-code) | Fork of `build-your-own-claude-code` | AI Agents, Harnesses & Developer Tooling | — | Definition for the claude-code challenge. |
| 24 | [`build-your-own-x`](https://github.com/vamsy16/build-your-own-x) | Fork of `build-your-own-x` | Learning, References & Inspiration | — | Master programming by recreating your favorite technologies from scratch. |
| 25 | [`CL4R1T4S`](https://github.com/vamsy16/CL4R1T4S) | Fork of `CL4R1T4S` | Learning, References & Inspiration | — | LEAKED SYSTEM PROMPTS FOR CHATGPT, CLAUDE, GEMINI, GROK, PERPLEXITY, CURSOR, LOVABLE, REPLIT, AND MORE! - AI SYSTEMS TRANSPARENCY… |
| 26 | [`claude-ads`](https://github.com/vamsy16/claude-ads) | Fork of `claude-ads` | Marketing, SEO & Growth | 34 | Claude-first paid-media operations skill for Claude Code across 12 ad platforms (Google, Meta, YouTube, LinkedIn, TikTok,… |
| 27 | [`claude-blog`](https://github.com/vamsy16/claude-blog) | Fork of `claude-blog` | Marketing, SEO & Growth | 33 | Claude Code blog skill suite: 30 sub-skills, 5 agents, 5-gate v1.9.0 Blog Delivery Contract, dual-optimized for Google rankings… |
| 28 | [`claude-counter`](https://github.com/vamsy16/claude-counter) | Fork of `claude-counter` | AI Agents, Harnesses & Developer Tooling | — | A minimal browser extension that shows token count, cache timer, and usage bars on claude.ai. |
| 29 | [`claude-mem`](https://github.com/vamsy16/claude-mem) | Fork of `claude-mem` | AI Agents, Harnesses & Developer Tooling | 21 | Persistent Context Across Sessions for Every Agent – Captures everything your agent does during sessions, compresses it with AI,… |
| 30 | [`claude-obsidian`](https://github.com/vamsy16/claude-obsidian) | Fork of `claude-obsidian` | Knowledge Management & Productivity | 15 | Self-organizing AI second brain for Obsidian + Claude Code. |
| 31 | [`claude-seo`](https://github.com/vamsy16/claude-seo) | Fork of `claude-seo` | Marketing, SEO & Growth | 31 | Universal SEO skill for Claude Code. 25 sub-skills + 18 sub-agents covering technical SEO, E-E-A-T, schema, GEO/AEO, backlinks,… |
| 32 | [`claude-swarm`](https://github.com/vamsy16/claude-swarm) | Fork of `claude-swarm` | AI Agents, Harnesses & Developer Tooling | — | Multi-agent orchestration for Claude Code — decompose tasks, coordinate agents, visualize everything in a rich terminal UI |
| 33 | [`claude-video`](https://github.com/vamsy16/claude-video) | Fork of `claude-video` | Video, Audio & Creative AI | 1 | Give Claude the ability to watch any video. /watch downloads, extracts frames, transcribes, hands it all to Claude. |
| 34 | [`claude-watch`](https://github.com/vamsy16/claude-watch) | Fork of `claude-watch` | Video, Audio & Creative AI | 1 | Give Claude the ability to watch any video — scene-change frames + transcript + a structured report, with a 0-10s hook microscope… |
| 35 | [`claudedesignskills`](https://github.com/vamsy16/claudedesignskills) | Fork of `claudedesignskills` | Design & Front-End Engineering | 23 | A comprehensive collection of Claude Code skills for modern web development, specializing in 3D graphics, animation, and… |
| 36 | [`Clip-Anything`](https://github.com/vamsy16/Clip-Anything) | Fork of `Clip-Anything` | Video, Audio & Creative AI | — | Clip any moment from any video with prompts |
| 37 | [`codegraph`](https://github.com/vamsy16/codegraph) | Fork of `codegraph` | AI Agents, Harnesses & Developer Tooling | 2 | Pre-indexed code knowledge graph, auto syncs on code changes, for Claude Code, Codex, Gemini, Cursor, OpenCode, AntiGravity,… |
| 38 | [`company-skills-marketplace-template`](https://github.com/vamsy16/company-skills-marketplace-template) | Fork of `company-skills-marketplace-template` | AI Agents, Harnesses & Developer Tooling | 2 | Fork-and-go template for a private team skills marketplace usable from Claude Code and Codex CLI |
| 39 | [`competitor-x-ray`](https://github.com/vamsy16/competitor-x-ray) | Fork of `competitor-x-ray` | Marketing, SEO & Growth | 1 | Free Claude skill that x-rays any competitor into their ICP, funnel & monetization — sourced, evidence-tiered, with a designed… |
| 40 | [`content-ideas`](https://github.com/vamsy16/content-ideas) | Fork of `content-ideas` | Marketing, SEO & Growth | 1 | Track competitors across X, Instagram, TikTok, and YouTube, see what they post, what performs, and get content ideas backed by… |
| 41 | [`content-repurposer`](https://github.com/vamsy16/content-repurposer) | Fork of `content-repurposer` | Marketing, SEO & Growth | 1 | Turn one Reel/TikTok into platform-correct Instagram, TikTok & YouTube posts with auto-translated CTAs — then auto-schedule… |
| 42 | [`crawl4ai`](https://github.com/vamsy16/crawl4ai) | Fork of `crawl4ai` | Web Scraping & Lead Generation | — | 🚀🤖 Crawl4AI: Open-source LLM Friendly Web Crawler & Scraper. Don't be shy, join here: https://discord.gg/jP8KfhDhyN |
| 43 | [`crawlee`](https://github.com/vamsy16/crawlee) | Fork of `crawlee` | Web Scraping & Lead Generation | — | Crawlee—A web scraping and browser automation library for Node.js to build reliable crawlers. In JavaScript and TypeScript. |
| 44 | [`curl-impersonate`](https://github.com/vamsy16/curl-impersonate) | Fork of `curl-impersonate` | Web Scraping & Lead Generation | — | curl-impersonate: A special build of curl that can impersonate Chrome & Firefox |
| 45 | [`developer-portfolios`](https://github.com/vamsy16/developer-portfolios) | Fork of `developer-portfolios` | Learning, References & Inspiration | — | A list of developer portfolios for your inspiration |
| 46 | [`distribb-skill`](https://github.com/vamsy16/distribb-skill) | Fork of `distribb-skill` | Marketing, SEO & Growth | 2 | Distribb CLI, Claude, Codex, Hermes, OpenClaw skill for AI-powered SEO. |
| 47 | [`ECC`](https://github.com/vamsy16/ECC) | Fork of `ECC` | AI Agents, Harnesses & Developer Tooling | 287 | The agent harness performance optimization system. Skills, instincts, memory, security, and research-first development for Claude… |
| 48 | [`ExcelToJson`](https://github.com/vamsy16/ExcelToJson) | Original | Original Repositories | — | Java (Maven) utility that converts Excel spreadsheet files into JSON. |
| 49 | [`firecrawl`](https://github.com/vamsy16/firecrawl) | Fork of `firecrawl` | Web Scraping & Lead Generation | 5 | The context API to search, scrape, and interact with the web at scale. 🔥 |
| 50 | [`funnel-spy`](https://github.com/vamsy16/funnel-spy) | Fork of `funnel-spy` | Marketing, SEO & Growth | 1 | Free Claude skill that walks any competitor's funnel end to end — every page, every price, the machine behind it — and delivers a… |
| 51 | [`girlsgottagolf`](https://github.com/vamsy16/girlsgottagolf) | Fork of `girlsgottagolf` | Misc & Personal | — | Example launch site for a women's golf community (Vite + React + TypeScript) — useful as a landing-page reference. |
| 52 | [`git-learning`](https://github.com/vamsy16/git-learning) | Original | Original Repositories | — | i want to learn git |
| 53 | [`google-maps-scraper-kit`](https://github.com/vamsy16/google-maps-scraper-kit) | Fork of `google-maps-scraper-kit` | Web Scraping & Lead Generation | 1 | Run a free open-source Google Maps scraper locally and let Claude drive it on autopilot. |
| 54 | [`graphify`](https://github.com/vamsy16/graphify) | Fork of `graphify` | AI Agents, Harnesses & Developer Tooling | — | Turn any codebase, with its docs, SQL schemas, configs, and PDFs, into a queryable knowledge graph. |
| 55 | [`gsap-skills`](https://github.com/vamsy16/gsap-skills) | Fork of `gsap-skills` | Design & Front-End Engineering | 8 | Official AI skills for GSAP. These skills teach AI coding agents how to correctly use GSAP (GreenSock Animation Platform),… |
| 56 | [`headroom`](https://github.com/vamsy16/headroom) | Fork of `headroom` | AI Agents, Harnesses & Developer Tooling | — | Compress tool outputs, logs, files, and RAG chunks before they reach the LLM. |
| 57 | [`hello-world`](https://github.com/vamsy16/hello-world) | Original | Original Repositories | — | GitHub Pages starter site. |
| 58 | [`higgsfield-skill`](https://github.com/vamsy16/higgsfield-skill) | Fork of `higgsfield-skill` | Video, Audio & Creative AI | 1 | One MCP, 30+ image and video models. Higgsfield skill for Claude Code. |
| 59 | [`hyperframes-cinematic-caption`](https://github.com/vamsy16/hyperframes-cinematic-caption) | Fork of `hyperframes-cinematic-caption` | Video, Audio & Creative AI | 1 | Portable HyperFrames skill for premium spatial editorial captions, animated translucent hero text, and subject-aware video… |
| 60 | [`HyperMamba`](https://github.com/vamsy16/HyperMamba) | Fork of `HyperMamba` | Misc & Personal | — | All Proprietary Research and Development |
| 61 | [`i-have-adhd`](https://github.com/vamsy16/i-have-adhd) | Fork of `i-have-adhd` | Knowledge Management & Productivity | 1 | A skill to stop your coding agent from burying the answer. ADHD-friendly output. |
| 62 | [`JARVIS`](https://github.com/vamsy16/JARVIS) | Fork of `JARVIS` | AI Agents, Harnesses & Developer Tooling | 2 | JARVIS: a real-time agentic intelligence-gathering platform powered by autonomous web scraping & OSINT, streamed via Meta Ray-Ban… |
| 63 | [`lead-gen-kit`](https://github.com/vamsy16/lead-gen-kit) | Fork of `lead-gen-kit` | Marketing, SEO & Growth | 1 | Skill-driven Google Maps lead-gen funnel for Claude Code — cheap discovery, ICP qualification, email rescue, Google Sheets sync. |
| 64 | [`lead-scraper`](https://github.com/vamsy16/lead-scraper) | Fork of `lead-scraper` | Web Scraping & Lead Generation | — | Two-stage B2B lead scraper (Google Maps discovery + website email/phone/social enrichment) built on Botasaurus |
| 65 | [`linkedin-planner`](https://github.com/vamsy16/linkedin-planner) | Fork of `linkedin-planner` | Marketing, SEO & Growth | 1 | Batch-plan a month of LinkedIn posts with an AI assistant and push them to Buffer as drafts. |
| 66 | [`loop-engineering`](https://github.com/vamsy16/loop-engineering) | Fork of `loop-engineering` | AI Agents, Harnesses & Developer Tooling | 14 | Practical patterns, starters & CLI tools for loop engineering with AI coding agents. |
| 67 | [`marketingskills`](https://github.com/vamsy16/marketingskills) | Fork of `marketingskills` | Marketing, SEO & Growth | 50 | Marketing skills for Claude Code and AI agents. CRO, copywriting, SEO, analytics, and growth engineering. |
| 68 | [`markitdown`](https://github.com/vamsy16/markitdown) | Fork of `markitdown` | AI Agents, Harnesses & Developer Tooling | — | Python tool for converting files and office documents to Markdown. |
| 69 | [`microservices-tutorial-config`](https://github.com/vamsy16/microservices-tutorial-config) | Original | Original Repositories | — | Spring Boot configuration files for a microservices tutorial. |
| 70 | [`ml-starter-kit`](https://github.com/vamsy16/ml-starter-kit) | Fork of `ml-starter-kit` | Learning, References & Inspiration | — | Machine Learning Starter Projects |
| 71 | [`MoneyPrinterTurbo`](https://github.com/vamsy16/MoneyPrinterTurbo) | Fork of `MoneyPrinterTurbo` | Video, Audio & Creative AI | — | 利用 AI 大模型和自动化工作流，根据主题或关键词一键生成高清短视频。Generate HD short videos from a topic or keyword with an automated AI workflow. |
| 72 | [`motion-dev-animations-skill`](https://github.com/vamsy16/motion-dev-animations-skill) | Fork of `motion-dev-animations-skill` | Design & Front-End Engineering | 1 | Claude Code skill for Motion.dev -- 120fps web animations, spring physics, scroll effects, gesture interactions |
| 73 | [`n8n-nodes-browser-use`](https://github.com/vamsy16/n8n-nodes-browser-use) | Fork of `n8n-nodes-browser-use` | AI Agents, Harnesses & Developer Tooling | — | n8n community node for Browser Use Cloud — browser-automation agent workflows inside n8n. |
| 74 | [`open-ai-content-repurposing-agent`](https://github.com/vamsy16/open-ai-content-repurposing-agent) | Fork of `open-ai-content-repurposing-agent` | Marketing, SEO & Growth | 3 | An AI agent for content repurposing — turning long-form video into ranked, ready-to-post short clips — backed by real… |
| 75 | [`open-ai-gtm-agent`](https://github.com/vamsy16/open-ai-gtm-agent) | Fork of `open-ai-gtm-agent` | Marketing, SEO & Growth | 4 | Cross-functional GTM strategy and orchestration agents for research, launches, sales, channels, and performance review |
| 76 | [`open-ai-image-agent`](https://github.com/vamsy16/open-ai-image-agent) | Fork of `open-ai-image-agent` | Marketing, SEO & Growth | 20 | AI agent for image and creative production — image generation, thumbnails, and on-brand visual content, powered by muapi.ai. |
| 77 | [`open-ai-seo-agent`](https://github.com/vamsy16/open-ai-seo-agent) | Fork of `open-ai-seo-agent` | Marketing, SEO & Growth | 14 | Free, open-source SEO alternative to Ahrefs and Semrush for Claude, Codex, Cursor, and other AI assistants. |
| 78 | [`open-ai-social-agent`](https://github.com/vamsy16/open-ai-social-agent) | Fork of `open-ai-social-agent` | Marketing, SEO & Growth | 6 | An AI agent for social media management — listening, creator discovery, multi-platform publishing, and trend research across X,… |
| 79 | [`open-ai-video-agent`](https://github.com/vamsy16/open-ai-video-agent) | Fork of `open-ai-video-agent` | Marketing, SEO & Growth | 28 | AI agent for video production — text/image-to-video generation, avatar/UGC talking-head videos, and data-driven ad-creative… |
| 80 | [`open-design`](https://github.com/vamsy16/open-design) | Fork of `open-design` | Design & Front-End Engineering | 385 | 🎨 Best DeepSeek Harness Design Plugin. The open-source Claude Design alternative. 🖥️ Local-first desktop app. |
| 81 | [`premiere-pro-mcp`](https://github.com/vamsy16/premiere-pro-mcp) | Fork of `premiere-pro-mcp` | Video, Audio & Creative AI | 2 | Local-first Adobe Premiere Pro MCP: 285 AI video editing tools, opt-in project context, CEP bridge, and capability-aware UXP. |
| 82 | [`project-based-learning`](https://github.com/vamsy16/project-based-learning) | Fork of `project-based-learning` | Learning, References & Inspiration | — | Curated list of project-based tutorials |
| 83 | [`Project-Ideas-And-Resources`](https://github.com/vamsy16/Project-Ideas-And-Resources) | Fork of `Project-Ideas-And-Resources` | Learning, References & Inspiration | — | A Collection of application ideas that can be used to improve your coding skills ❤. |
| 84 | [`python-training`](https://github.com/vamsy16/python-training) | Original | Original Repositories | — | python training |
| 85 | [`resolve-claude-mcp`](https://github.com/vamsy16/resolve-claude-mcp) | Fork of `resolve-claude-mcp` | Video, Audio & Creative AI | — | Connect DaVinci Resolve Studio to Claude AI through the Model Context Protocol (MCP) |
| 86 | [`Scout`](https://github.com/vamsy16/Scout) | Fork of `Scout` | Web Scraping & Lead Generation | — | Free lead generation tool. Scrape Instagram, Twitch, TikTok, and LinkedIn profiles. |
| 87 | [`Scrapling`](https://github.com/vamsy16/Scrapling) | Fork of `Scrapling` | Web Scraping & Lead Generation | 1 | 🕷️ An adaptive Web Scraping framework that handles everything from a single request to a full-scale crawl! |
| 88 | [`scrapy`](https://github.com/vamsy16/scrapy) | Fork of `scrapy` | Web Scraping & Lead Generation | — | Scrapy, a fast high-level web crawling & scraping framework for Python. |
| 89 | [`scrcpy`](https://github.com/vamsy16/scrcpy) | Fork of `scrcpy` | AI Agents, Harnesses & Developer Tooling | — | Display and control your Android device |
| 90 | [`second-brain`](https://github.com/vamsy16/second-brain) | Fork of `second-brain` | Knowledge Management & Productivity | 8 | AI-powered 'second brain': git-tracked Obsidian vault run by Claude Code that captures, organizes, and farms context while you… |
| 91 | [`seedance-2-generator`](https://github.com/vamsy16/seedance-2-generator) | Fork of `seedance-2-generator` | Video, Audio & Creative AI | — | Open-source Next.js SaaS for Seedance 2.0 , Seedance 2.5 and Seedance 2 Mini video generation — Stripe billing, credits,… |
| 92 | [`sequential-thinking-skill`](https://github.com/vamsy16/sequential-thinking-skill) | Fork of `sequential-thinking-skill` | AI Agents, Harnesses & Developer Tooling | 1 | Claude Code skill replicating the Sequential Thinking MCP server — structured reasoning with branching, revision, and persistent… |
| 93 | [`shopify-graphql-admin-mcp`](https://github.com/vamsy16/shopify-graphql-admin-mcp) | Fork of `shopify-graphql-admin-mcp` | Business Apps & Integrations | — | Connect Claude to your Shopify store, and unlock the full power of Claude for your store. |
| 94 | [`stoictradingAI`](https://github.com/vamsy16/stoictradingAI) | Fork of `stoictradingAI` | Business Apps & Integrations | — | 🤖 Autonomous Solana trading bot with transparent execution |
| 95 | [`super-video-maker-skill`](https://github.com/vamsy16/super-video-maker-skill) | Fork of `super-video-maker-skill` | Video, Audio & Creative AI | 1 | AI video production skill for agents: HeyGen avatars, Seedance b-roll, OpenAI images, Remotion, HyperFrames, screen recording,… |
| 96 | [`system_prompts_leaks`](https://github.com/vamsy16/system_prompts_leaks) | Fork of `system_prompts_leaks` | Learning, References & Inspiration | 49 | Extracted system prompts from Anthropic - Claude Fable 5, Opus 5, Claude Design, Claude Code. |
| 97 | [`Text-To-Video-AI`](https://github.com/vamsy16/Text-To-Video-AI) | Fork of `Text-To-Video-AI` | Video, Audio & Creative AI | — | Generate video from text using AI |
| 98 | [`twenty`](https://github.com/vamsy16/twenty) | Fork of `twenty` | Business Apps & Integrations | 18 | The open alternative to Salesforce, designed for AI. |
| 99 | [`video-use`](https://github.com/vamsy16/video-use) | Fork of `video-use` | Video, Audio & Creative AI | 2 | Edit videos with coding agents |
| 100 | [`voicebox`](https://github.com/vamsy16/voicebox) | Fork of `voicebox` | Video, Audio & Creative AI | 4 | The open-source AI voice studio. Clone, dictate, create. |
| 101 | [`VoiceStudio`](https://github.com/vamsy16/VoiceStudio) | Fork of `VoiceStudio` | Video, Audio & Creative AI | 4 | VoiceStudio is the open-source, fully-local ElevenLabs alternative — voice cloning, voice design, video dubbing, dictation,… |
| 102 | [`Wan2GP`](https://github.com/vamsy16/Wan2GP) | Fork of `Wan2GP` | Video, Audio & Creative AI | 1 | A fast AI Video Generator for the GPU Poor. Supports Wan 2.1/2.2, LTX-2, Qwen Image, Hunyuan Video, LTX Video and Flux. |
| 103 | [`youtubepro`](https://github.com/vamsy16/youtubepro) | Fork of `youtubepro` | Video, Audio & Creative AI | — | Local-first YouTube research, grounded AI insights, script writing, and thumbnail creation. |

---

### Notes & caveats

- Covers **public** repositories only (private repos aren't visible via the API).
- Skills were de-duplicated to their canonical copy (upstream repos sometimes mirror them across `.claude/`, `.agents/`, `.cursor/`, translations, and fixtures).
- Fork purposes reflect the upstream project unless the fork diverges.
- Skill descriptions are trimmed for readability — open the linked skill folder for the full documentation.
- Trading bot (`stoictradingAI`) and leaked-prompt references (`CL4R1T4S`, `system_prompts_leaks`) are for research/reference — review before production use.
