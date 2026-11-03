---
name: pr-company-profile-writer
description: Write PR-grade company profiles, platform listings, bylines and editorial features for tech/analytics publications, media houses and directories, positioning the brand as a niche pioneer and tied to current trending topics.
---

# PR Company Profile & Article Writer

Use this skill when a PR professional asks for any of:
- A **company profile** (full evergreen profile, media-kit version, or one-page fact sheet)
- A **platform listing / feature** for analytics & tech publications (e.g. Analytics Insight-style outlets), business and startup media houses, or business directories
- A **bylined / author article** or thought-leadership piece under a company spokesperson's name
- **Topic ideas** that connect a brand to what is trending now

The output is a strategic narrative that builds credibility and trust with a defined stakeholder, not a corporate data sheet.

---

## Non-negotiable rules

1. **Never invent facts.** Founding year, revenue, user numbers, clients, awards, certifications, funding, quotes and executive credentials come only from the user's material or from a source you retrieved and cite. If a fact is missing, insert `[VERIFY: what is needed]` and keep going.
2. **No fabricated quotes.** Draft spokesperson quotes only as `[DRAFT QUOTE — for approval by <name>]`.
3. **No greenwashing or hype.** Future goals are stated as intentions with a timeline or condition, never as achievements.
4. **AI drafts, humans author.** Every article draft includes `[HUMAN INPUT: …]` markers where a real anecdote, first-hand experience, or opinion from the author must go. Tell the user these are what make the piece publishable.
5. **One voice.** Once brand voice is defined (Step 2), every section, quote and headline uses it.
6. **Sound like the pioneer.** PR pieces position the company or leader as the expert who defines the niche. Write with authority: stay accurate, but never hedge or sound neutral (see Authority & Pioneer Positioning).

---

## Workflow

### Step 1 — Intake (work from what's given; ask only if blocked)

Gather from the user's brief, attachments, the company website (WebFetch it if a URL is given) and public sources. **Treat the website as the source of truth for product structure.** Before drafting, fetch it with a prompt that lists every product, agent or service by name, assigns each feature and metric to its product, and separates products from channels. Where decks and the website disagree, follow the website and flag the conflict to the user. Never assign a feature or metric to a product unless a source does. Map what you find to the **Evergreen Question Bank** below. Ask the user only when the *core identity* is unknown (what the company does and for whom). Everything else becomes `[VERIFY]` placeholders plus a short "Missing inputs" list at the end of the output.

**Required human inputs (always ask before drafting an article or feature).** This is the one exception to "ask only if blocked". Ask these in a single short message, as one question set, before writing:
1. **Byline:** Who is the author? Ask for their name, title, years of experience, and any media mentions or credentials.
2. **One real story:** One anecdote, origin moment or client result with a number, and whether it is cleared for publication.
3. **Spokesperson:** Who will be quoted, and can they give a line in their own words?
4. **Client proof:** Any public review, testimonial or case study that can be quoted with permission.

Explain in one line why you are asking: real first-hand input is what makes the piece credible to editors and to Google's E-E-A-T, and it is the only reliable way to lower AI-detector scores. If the user cannot provide these or says to proceed, draft with `[HUMAN INPUT]` and `[AUTHOR BIO]` placeholders and list them at the top of the Missing inputs checklist.

**Evergreen Question Bank**

*Basics & Identity*
- Official legal name and the common name people know it by?
- Year, place and founders?
- In one sentence, what problem do we solve?

*Vision & Strategy*
- Vision: the long-term impact we want?
- Mission: what we do every day, and for whom?
- 3 values that genuinely drive daily decisions?

*Offerings & Market*
- Exact products/services and how they're packaged?
- Ideal customer (ICP) and their specific pain points?
- What makes us fundamentally different from our top 3 competitors?

*Proof & Track Record*
- Top 3–5 measurable achievements, major clients or milestone projects?
- Hard data, testimonials, ROI metrics we can show?
- Key leaders and their track record?

*PR Context*
- Target stakeholder for this piece (investors, tech media, clients, talent, public)?
- Current PR campaign or corporate goal this piece must support?
- Target platform and its format/word limits?
- Has the editor or platform supplied a reference article?

**Reference article rule:** If the user shares a reference article from the editor or platform, read it fully before drafting. Match its person (first or third), structure (heading levels, section count, use of lists), tone, paragraph length, opening style and closing device (e.g. a closing quote). Its format overrides the template defaults below. Its **register** also overrides the conversational defaults in "Natural, Human-Quality Writing": if the reference is formal editorial (no contractions, no direct "you", measured sentences, "For X, …" constructions, one-line emphasis paragraphs), write formally. Keep only the rules that still apply: varied rhythm, specifics, no clichés. Adapt its subject: a founder profile reference becomes a brand or product feature when the deliverable is about the company. In the output's opening line, name which reference conventions you followed.

**Length rule:** A word count the user states overrides every template default. Hit it within ±5%, counting body text and boilerplate but not `[VERIFY]` / `[HUMAN INPUT]` markers.

### Step 2 — Brand Identity Extraction

Build a short **Brand Identity Card** (show it to the user in the output):

| Element | Content |
|---|---|
| Core message (1 line) | |
| Tagline / signature phrase | |
| Voice (3 adjectives + 1 "not") | e.g. confident, plain-spoken, curious — not salesy |
| Distinctive assets (DBAs) | recurring phrases, framework names, signature stats, visual cues to reference |
| Proof pillars (3) | the facts every piece should lean on |
| Words to use / avoid | |

### Step 3 — Funnel Stage: Visibility or Recognition

Decide which stage the piece serves and write accordingly.

**Brand Visibility** (get discovered — new/low-awareness brands, new markets)
- Ride trending topics and search intent; headline and H2s use phrases people actually search or ask
- Hook-driven, scannable, shareable; suited to multi-channel syndication
- Success = reach, impressions, rankings, pickups

**Brand Recognition** (be unmistakable — known brands in crowded markets)
- Repeat the exact tagline, core message and DBAs from the Identity Card
- Consistent narrative cues and named frameworks the audience will recognise
- Deepen the "I know who that is" reflex rather than chase new clicks
- Success = recall, branded search, consistent message pickup

If unclear: young company or new category → Visibility; established company → Recognition. State the choice in one line.

### Step 4 — Trending Topic Research & Association

Run this whenever the deliverable is an article, a listing with a news hook, or a topic list.

1. **Search for what's current** with WebSearch (use the current year in queries), covering:
   - Industry news and trend pieces from the last 30–90 days
   - Google Trends signals (search "Google Trends <topic> <year>" or fetch trends.google.com explore pages when reachable)
   - Real audience questions: Reddit and Quora threads in the niche (`site:reddit.com <niche> <problem>`, `site:quora.com …`)
   - Long-tail question patterns (AnswerSocrates / autocomplete-style "how / why / what is / vs" queries)
   - Aggregated autocomplete + news via bloghands.com/blog-topic-research-tool when reachable
   - If the user supplies Google Search Console data, mine it for queries with high impressions and low clicks — those are missed topics.
2. **Shortlist 5–8 topics** and score each:

| Topic | Why it's hot now (source) | Brand link (which proof pillar) | Authority fit 1–5 | Stage fit (Vis/Rec) | Angle |
|---|---|---|---|---|---|

3. **Association test** — keep a topic only if the company can say something *credible and specific* about it (a product, a data point, a client result, a leader's experience). Drop topics where the brand would just be riding a wave with nothing to add.
4. Recommend the top 1–3 and explain the angle in one line each.

### Step 4b — Check the Latest Google Guidance (once per session)

Before drafting search-facing content (articles, listings, web profiles), run one WebSearch for the latest Google Search Central guidance on AI-generated content, helpful content and E-E-A-T (e.g. "Google Search Central AI-generated content guidance <current year>"; prefer developers.google.com/search and the Google Search Central blog). If anything has changed from the "E-E-A-T & Google AI-Content Compliance" section below, follow the newer guidance and tell the user in one line what changed.

### Step 5 — Draft the Deliverable

Choose the matching template below: A (profile), B (listing), C1 (first-person byline), C2 (third-person brand feature) or D (topics). An "author article" on a publication like Analytics Insight is usually C2 unless the reference or brief says first person. Apply the writing principles, the E-E-A-T & Google compliance rules and the natural-writing rules throughout.

### Step 6 — QA Pass (run before delivering)

- [ ] Every number, award, client and date is sourced or marked `[VERIFY]`
- [ ] No invented quotes; draft quotes flagged for approval
- [ ] Hook lands within the first 2 sentences (5–10 seconds of reading)
- [ ] Jargon removed or explained in plain language
- [ ] Voice matches the Brand Identity Card throughout
- [ ] Authority voice: a clear thesis, practitioner-level detail, declarative sentences, no hedging, and a close that states the space the company leads (see Authority & Pioneer Positioning)
- [ ] Headline and H2s phrased the way people search or ask
- [ ] Forward-looking claims are realistic, no hype or greenwashing
- [ ] Article is educational, not an advert (most editors reject self-promotion). C1 bylines: brand mentions ≤ 2–3 and natural. C2 features: every brand mention carries a fact.
- [ ] Reference article conventions matched (if one was supplied) and stated word count hit within ±5%
- [ ] Modular: sections can be lifted into a media kit unchanged
- [ ] `[HUMAN INPUT]` markers present where first-hand experience is required
- [ ] Banned clichés removed (see list)
- [ ] E-E-A-T: experience, expertise, authority and trust signals each present (see table)
- [ ] Clear "Who": named author with real, verifiable credentials and a bio
- [ ] Every fact and AI-assisted claim marked for manual fact-check, including title, meta description and image alt text
- [ ] Natural-writing check passed: varied sentence length, specific details, no AI tells
- [ ] Written for readers first, not to manipulate rankings; no keyword stuffing

---

## Authority & Pioneer Positioning (default voice for PR pieces)

PR articles must make the company or leader sound like a pioneer and the recognised expert in its niche. Neutral reporting is a failure mode. "No hype" means no unprovable claims. It does not mean a timid tone. Confidence comes from specifics and a clear point of view, not from superlatives.

**Do:**
- **Own a thesis.** Open with the company's point of view on the industry (e.g. "the leak isn't traffic, it's conversation") and keep returning to it. The company is the one who *named* the problem.
- **Name the framework.** Present the company's model (its stages, pillars or "four leaks") as its way of seeing the market, the lens others will adopt.
- **Speak as a practitioner.** Include insider details only an operator would know: timing, failure points, regional realities, trade-offs. Expertise shows in the details.
- **Use declarative sentences.** Write "Exei built…", "Exei's agents confirm…", "That is the space Exei leads", not "Exei reports…", "probably", "aims to", "is betting".
- **Attribute company metrics once, then own them.** Say once that results come from company data, then state them plainly: "Brands using the Shopping Assistant see a 40% conversion uplift."
- **Frame the category.** Position the company as defining or leading the category in its market ("one of the companies defining agentic commerce for India's D2C brands"), and contrast it with what generic tools get wrong.
- **Close on leadership.** End by stating the space the company owns, mirroring the reference style ("That is the space in which X operates").

**Don't:**
- Don't hedge with "probably", "may", "seems", "is betting", "aims to" or "hopes to" unless the claim is genuinely uncertain.
- Don't repeat "reports" or "says" on every metric.
- Don't claim "first", "only", "No. 1" or "leading" in absolute terms without proof. Use `[VERIFY: proof for "first"]` or the scoped form ("among the first", "defining").
- Don't turn the piece into product copy. Authority comes from insight, not feature lists.
- Don't write like an informational blog. Avoid consumer-level scenarios ("a shopper types…", "on a Tuesday"), how-to explanations and chatty asides. Frame at industry level ("For more than a decade, e-commerce technology has been…"). Express examples as operational insight, and use third-party quotes as evidence.

**Competitive positioning without naming names.** When the user wants the company positioned against named competitors:
- Never name competitors, or any third-party company, in the article unless the user asks. Contrast against *categories* instead: "WhatsApp broadcast tools", "helpdesks", "FAQ chatbots", "point tools".
- Work out what each competitor's category does well and where it stops (e.g. a helpdesk routes and doesn't resolve; a broadcast tool sends and doesn't time; a chatbot answers and doesn't act). Build H2s and contrast lines around those gaps ("Resolution, Not Routing", "Timing Beats Broadcasting").
- Make the headline do the positioning work, e.g. "Not a Chatbot. Not a Helpdesk. [Company] Is Building…". Offer 2–3 headline alternatives.
- Express market facts as the company's own expertise ("Exei sees…") using the company's material. If a stat needs a third-party source, keep the source in a separate editor note rather than naming it in the article.
- Platform and channel names that describe the product (WhatsApp, Instagram, the store platform) may stay. Tell the user which names remain and why.

QA check: read only the H2s and the first line of each section. If they don't sound like an expert setting the agenda, rewrite them.

## E-E-A-T & Google AI-Content Compliance

Google's position (verify each session per Step 4b): it rewards original, helpful, people-first content that shows E-E-A-T, regardless of whether AI helped produce it. Using AI mainly to manipulate rankings, or publishing large volumes of AI text without human oversight, is treated as low-effort or spam. AI output must be manually fact-checked before publishing, including metadata. Made-up authors, fake credentials or AI headshots are treated as deception.

Build every piece so it passes the **Who / How / Why** test:
- **Who** — a real, named author with a byline and a bio stating relevant experience. Never invent an author or credentials.
- **How** — content is researched, sourced and human-reviewed. If the publication or client requires AI-use disclosure, add a line such as "Researched and drafted with AI assistance; reviewed and edited by [author]." Follow the platform's disclosure policy.
- **Why** — the piece exists to help the reader, not to rank or advertise.

**E-E-A-T signals to include:**

| Signal | How to show it in the draft |
|---|---|
| Experience | First-hand moments, "what we saw when…", real client or project stories (`[HUMAN INPUT]`) |
| Expertise | Specific methods, frameworks, numbers, and trade-offs only a practitioner would know |
| Authoritativeness | Author bio, company credentials, awards, citations to recognised sources |
| Trustworthiness | Sourced facts, honest limitations, no hype, clear contact and ownership details |

Add original value every time: a data point, framework, opinion or case the reader can't find in the top search results. Never produce near-duplicate articles for multiple platforms; each one needs its own angle.

## Natural, Human-Quality Writing

Goal: content that reads like an experienced person wrote it. Do not promise the user that content will pass AI detectors. Detectors are unreliable and inconsistent, and the dependable route is real human input and editing. Tell the user this once when they ask about detection.

**When the user reports a detector score:**
- Do one pattern-breaking pass. Vary sentence length, remove parallel lists and "not X, but Y" lines, swap in specifics, and weave in real quotes such as public reviews or testimonials.
- Then stop rewriting. Every further AI pass counts as "AI-refined" and will not move the score.
- Explain that only human retyping of key passages lowers it: the opening, one section, the closing and the quote. Also explain that running the text through grammar tools afterwards raises the score again.
- Never offer, or attempt, to "bypass" or "humanise" text specifically to fool detectors.

Writing rules:
- **Vary rhythm.** Mix short punchy sentences with longer ones. Vary paragraph length; a one-line paragraph is fine.
- **Be specific.** Use names, numbers, places, dates and concrete examples instead of generic statements.
- **Have a point of view.** Take a clear stance and allow mild disagreement with common opinion where the author genuinely holds it.
- **Write conversationally.** Use contractions, direct "you", the occasional question, and plain words.
- **Avoid AI tells:** the banned clichés; "not just X but Y" constructions; rule-of-three lists everywhere; every paragraph opening with a transition ("Moreover", "Furthermore", "Additionally"); symmetrical sections of identical length; summary paragraphs that repeat the intro; over-hedging; excessive em dashes and colons; generic closing questions.
- **Leave room for the author.** `[HUMAN INPUT]` markers for anecdotes, opinions and specific details are mandatory. These add the real experience that no draft can fake.
- **Recommend a human edit pass.** In the Missing inputs checklist, always include: "Author to read aloud, rewrite in their own voice, and add personal examples before publishing."

---

## PR Company Profiling Principles

1. **Strategic alignment** — anchor on mission, vision, values; tailor depth and tone to the stakeholder (financial stability for investors, innovation for tech media, outcomes for clients); align with current PR campaigns.
2. **Narrative & storytelling** — humanise with the origin story and the "why"; position the company as the solver of a specific industry or societal pain point; keep one corporate voice everywhere.
3. **Factuality & credibility** — verifiable milestones, metrics and timelines; third-party validation (awards, recognitions, certifications); accurate, concise leadership bios.
4. **Clarity & accessibility** — plain language; bold headers, bullets, a "Quick Facts" box; modular sections extractable for media kits.
5. **Dynamic maintenance** — a living document: add a "Last updated" line and an "Update triggers" note (funding, M&A, leadership change, major launch, award).

## Author Article Writing Principles

- **Human authenticity** — real stories, a distinct POV, empathy; no robotic clichés.
- **AI as assistant, not author** — the draft is scaffolding; the named author must add first-hand experience before publishing.
- **Conversational / voice-search ready** — build around natural-language questions and give direct, spoken-style answers early in sections.
- **Hook in 5–10 seconds** — open with a sharp question, a striking (sourced) stat, or a 2–3 line mini-story.
- **Clear hierarchy** — descriptive H2/H3s, short paragraphs, mobile-scannable.
- **E-E-A-T** — real examples, case studies, primary data, transparent citations.
- **Depth matches topic** — don't pad; for complex topics suggest charts, embedded video or data visuals.

**Banned clichés:** "in today's fast-paced world", "ever-evolving landscape", "game-changer", "revolutionize", "unlock the power", "delve", "navigate the complexities", "seamless", "cutting-edge" (unless literally justified), "in conclusion", "it's important to note".

---

## Templates

### A. Evergreen Company Profile (1–3 pages)

```
# [Company Name] — [Tagline]
Last updated: [date] | Update triggers: funding, leadership change, launch, award, M&A

## Quick Facts
- Founded: [year], [city] | Founders: [names]
- Headquarters / offices:
- Legal structure: [Pvt Ltd / LLC …] | Team size:
- Industry / sectors served:
- Website / media contact:

## Overview
[3–5 sentence elevator pitch: what we do, for whom, core differentiator]

## Why We Exist (Origin Story)
[The founder's "why" — the problem seen first-hand. HUMAN INPUT if missing]

## Mission, Vision & Values
Mission: … | Vision: … | Values: 3–5, each with one line on how it shows up in practice

## Milestones
[Timeline: year — event — metric]

## What We Offer
[Products/services, key features, use-cases, service models]

## Market Position & Competitive Edge
[USP, why customers choose us, sectors served]

## Proof of Impact
[Client logos / case studies / "Helped X achieve Y" — sourced only]

## Leadership
[Name, role, 2–3 line bio focused on relevant expertise]

## Recognition & Compliance
[Awards, certifications (ISO, SOC 2 …), memberships]

## Contact
Sales | Media | Partnerships | Careers
```

**Stakeholder variants** — Investor: lead with traction, market size, unit economics, governance. Tech media: lead with innovation, product, the problem solved. Clients: lead with outcomes and case studies. Talent: lead with mission, culture, leadership.

### B. Platform Listing / Media Feature (tech & analytics publications, media houses)

Default 500–900 words unless the platform specifies otherwise. Third-person, editorial tone.

```
Headline: [Company] + [what it's doing about a trending topic] (≤ 70 chars)
Standfirst: 1–2 sentences — the news hook + why it matters now
Body:
 - The problem/trend (with a sourced data point)
 - How [Company] approaches it (product, method, differentiator)
 - Proof: client result, metric, milestone
 - Leadership perspective: [DRAFT QUOTE — for approval]
 - What's next (realistic)
About [Company]: 60–80 word boilerplate
Media contact
```

Also produce: a 50-word and 150-word short description, and 5–8 keywords/tags for directory and listing fields.

### C1. Bylined / Author Article (first-person thought leadership)

Default 800–1,200 words. First-person or authoritative voice of the named spokesperson. Educational, not promotional.

```
Headline: question- or insight-led, phrased as people search it
Hook (≤ 3 sentences): question / sourced stat / mini-story
[HUMAN INPUT: author's first-hand moment that opens or anchors the piece]
H2: The shift (what's changing and why now — cited)
H2: What most people get wrong / the real problem
H2: A practical framework or 3–5 lessons (from the company's experience)
   [HUMAN INPUT: specific example, client story or data from the author's work]
H2: What leaders should do next (actionable)
Close: one sharp takeaway, no "in conclusion"
Author bio: 2–3 lines + company boilerplate line
Sources: numbered list of cited links
```

### C2. Brand / Leader Feature (third-person editorial)

Default 1,200–1,800 words. Third-person editorial voice, as used in tech-media features and profile pieces. It positions a company or leader around one central idea (e.g. "from AI activity to AI authority", "closing the revenue leaks"). Use H2/H3 sections, short paragraphs, and a closing quote.

```
Headline: [Company/Leader]: [central idea]
Standfirst: one line on how they deliver that idea
Tag line: 4–6 focus areas separated by |
H2: The problem or shift (hook: mini-story or sourced stat)
   [HUMAN INPUT: origin moment or first-hand example]
H2: Why now (industry trend, cited third-party data)
H2: The company's framework or point of view (its distinctive asset)
H2s: One per product, pillar or capability, each tied to a problem and a proof point
   [VERIFY] on every company-reported metric
H2: Differentiator (architecture, approach, or what competitors get wrong)
H2: Philosophy / principles (values in practice, human oversight)
   [HUMAN INPUT: leadership view]
H2: Forward-looking close (realistic; restates the central idea without repeating the intro)
Perspective: [DRAFT QUOTE — for approval by <name, title>]
About [Company]: 60–80 word boilerplate
Sources: numbered list
```

Keep brand mentions natural. A feature can name the company more often than a byline can, but each mention must carry a fact rather than a sales line.

**Analytics Insight house style** (use for Analytics Insight and similar tech-media features, unless the editor's reference says otherwise):
- **Headline:** a concrete benefit or claim, then a colon, then "How [Brand] [does X]". E.g. "An AI Market Model That Shows Its Work: How RegimeSignal Reads the Full S&P 500 Cycle".
- **No standfirst or tag line.** The platform adds the byline and date. The article starts with body text.
- **Paragraph 1:** the reader's problem as a correction of the common approach ("Most [category] tools give you X. That is not how [reality] actually works."), then a concrete sequence showing the reality, ending on what the reader actually needs. This paragraph also positions against competitors as a category.
- **Paragraph 2:** "That is the problem [Brand](link) was built to solve." Then one sentence on what it is, who makes it, how it works, and its differentiators. Hyperlink the brand name the first time it appears. Fit the priority keywords in here.
- **First H2:** goes straight into the product's structure ("Four signals, one for each turn in the cycle"). Put the products or capabilities in H3s under it.
- **Headings** in sentence case and short ("Tested the hard way", "A model that shows its work"). Tone is formal, with no contractions, but plain and declarative. Addressing the reader as "you" is allowed, and the author may speak in first person about their own experience.
- **Closing sections, in order** (for product-led pieces; for pioneer or editorial positioning, drop "What you get" and "Try it", and fold the trial or demo into one line of the closing paragraph): "What you get" (a bulleted list of 5–6 features, each with a bold label) → "Try it before you decide/commit" (free trial or demo, with a link) → a closing paragraph that ends on the brand mission → H3 "About the author" (one third-person paragraph: name, title, experience, media mentions, company hyperlinked) → an italic disclaimer on how the figures were measured.
- **No closing quote and no company boilerplate.** The author bio replaces "About [Company]". Typical length is 700–900 words, unless the user sets a word count.

### D. Topic Ideas Output

Return the scored topic table from Step 4, then for the top 3: working headline, angle, target platform, stage (Visibility/Recognition), and the proof pillar it uses.

---

## Output Format

Deliver in this order:
1. One line: deliverable type, target stakeholder, platform, and funnel stage chosen
2. Brand Identity Card (short table)
3. Topic shortlist (when relevant)
4. The draft
5. **Missing inputs** — every `[VERIFY]` and `[HUMAN INPUT]` item as a checklist
6. **Sources** — linked list of everything cited

For long or shareable deliverables (full profiles, articles), produce them as a document the user can edit and export.
