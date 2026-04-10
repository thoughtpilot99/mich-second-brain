# Michel Lieben's Second Brain

A pre-built [Obsidian](https://obsidian.md) knowledge base containing everything [Michel Lieben](https://x.com/MichLieben) has shared publicly about outbound sales, cold email, LinkedIn growth, AI-powered GTM, and scaling a B2B agency from $0 to $7M ARR.

Built using the [Second Brain](https://github.com/NicholasSpisak/second-brain) LLM Wiki pattern (inspired by Andrej Karpathy).

## Why This Exists

Thousands of posts across LinkedIn and X. Threads on cold email. Breakdowns on agency scaling. Playbooks on LinkedIn growth, outbound, AI-powered GTM.

The problem: all of it lives scattered across platforms. A thread from 8 months ago? Buried. A LinkedIn post with the exact framework you need? Gone in 48 hours.

This vault takes all of that and turns it into a structured, interlinked knowledge base where every concept connects to every other concept. Not a PDF. Not a course. A living wiki you own as a folder of markdown files.

## What's Inside

| Layer | Count | Description |
|-------|-------|-------------|
| **Raw Sources** | 26 | Original X posts, LinkedIn posts, and research with full text and engagement data |
| **Entity Pages** | 10 | People, companies, and tools (ColdIQ, Clay, Instantly, Claude Code, etc.) |
| **Concept Pages** | 14 | Frameworks and strategies (Allbound, Tiered Prospecting, Employee Advocacy, etc.) |
| **Cross-references** | 100+ | Every page links to related pages via `[[wikilinks]]` |

## Quick Start (2 minutes)

### Step 1: Clone the repo

```bash
git clone https://github.com/thoughtpilot99/mich-second-brain.git
```

Or download the ZIP from the green "Code" button above.

### Step 2: Open in Obsidian

1. Download [Obsidian](https://obsidian.md) (free, works on Mac/Windows/Linux)
2. Open Obsidian
3. Click "Open folder as vault"
4. Select the `mich-second-brain` folder

That's it. You now have the full knowledge base with backlinks, graph view, and search.

### Step 3: Explore

**Start here:** Open `wiki/index.md` for the full catalog of every page.

**Or use Graph View:** Press `Cmd+G` (Mac) or `Ctrl+G` (Windows) to see how everything connects visually. Every node is a page. Every line is a link between concepts.

**Or search:** Press `Cmd+O` to quick-open any page by name.

## Where to Start Reading

| Page | What You'll Learn |
|------|-------------------|
| [Allbound](wiki/concepts/allbound.md) | How content + outbound + ads work as one engine (the shift from $40K/mo to $90K/mo) |
| [Employee Advocacy](wiki/concepts/employee-advocacy.md) | How 24 employees publishing on LinkedIn added $153K MRR in 90 days |
| [Tiered Prospecting](wiki/concepts/tiered-prospecting.md) | Why ColdIQ cut 40% of their TAM on purpose and reply rates went up |
| [Content to Pipeline](wiki/concepts/content-to-pipeline.md) | Why prospects who see your content 3+ times before a cold email convert at 2-3x |
| [GTM Engineer](wiki/concepts/gtm-engineer.md) | The new role that runs outbound at 71% less cost than traditional SDR teams |
| [Agency Growth Phases](wiki/concepts/agency-growth-phases.md) | The six phases from $0 to $7M ARR -- what works at each stage |
| [Signal-Based Outbound](wiki/concepts/signal-based-outbound.md) | 18 buying signals that tell you who's ready to buy |
| [Cold Email Deliverability](wiki/concepts/cold-email-deliverability.md) | The infrastructure behind 57.59% reply rates |
| [ColdIQ](wiki/entities/coldiq.md) | Full company overview, tech stack, services, and key metrics |

## How the Wiki Works

Every page links to related pages. Click any `[[wikilink]]` to follow the connection.

**Example path:** Start at [Allbound](wiki/concepts/allbound.md) -> see it references [Content to Pipeline](wiki/concepts/content-to-pipeline.md) -> which links to [Employee Advocacy](wiki/concepts/employee-advocacy.md) -> which connects back to [Agency Growth Phases](wiki/concepts/agency-growth-phases.md). The structure teaches you how the ideas relate.

**Entity pages** (people, tools, companies) describe what something is and how it fits into the ecosystem.

**Concept pages** (strategies, frameworks) explain how something works and cross-reference the entities and other concepts involved.

**Raw sources** contain the original posts with full text, URLs, dates, and engagement metrics.

## Vault Structure

```
mich-second-brain/
  raw/                    # 26 original source documents (immutable)
  wiki/
    entities/             # 10 pages: people, companies, tools
    concepts/             # 14 pages: frameworks, strategies, patterns
    synthesis/            # Cross-cutting analysis (add your own)
    sources/              # Source summaries (add via ingestion)
    index.md              # Master catalog of all pages
    log.md                # Chronological record of operations
  output/                 # Reports and generated artifacts
  CLAUDE.md               # AI agent config for extending the wiki
```

## Extending the Wiki With AI

The vault isn't static. You can add your own sources and an AI agent will process them into the wiki automatically.

### Install the Second Brain skills

```bash
npx skills add NicholasSpisak/second-brain
```

This works with [Claude Code](https://claude.ai/download), [Cursor](https://cursor.sh), [Codex](https://openai.com/codex), [Gemini CLI](https://github.com/google-gemini/gemini-cli), and 40+ other AI agents that support the Agent Skills standard.

### Add and process sources

1. **Drop a markdown file into `raw/`** -- an article, a transcript, notes, anything
2. **Run `/second-brain-ingest`** -- the AI reads the source, creates summaries, identifies entities and concepts, adds cross-references, and updates the index
3. **A single source typically touches 10-15 wiki pages** -- the knowledge compounds with every source you add

### Query the wiki

Run `/second-brain-query` and ask any question. The AI searches the wiki, reads relevant pages, and synthesizes an answer with `[[wikilink]]` citations.

Example: "How does ColdIQ's outbound stack work end-to-end?" -> The AI will pull from Clay, Instantly, Tiered Prospecting, Signal-Based Outbound, and Waterfall Enrichment to give you a complete answer.

### Health check

Run `/second-brain-lint` to find broken links, orphan pages, contradictions, and gaps in the knowledge base. The AI will suggest fixes.

## FAQ

**Do I need to pay for anything?**
No. Obsidian is free for personal use. The vault is free. The Second Brain skills are free. You only pay if you want to use an AI agent (like Claude Code) to extend the wiki.

**Can I use this without AI?**
Yes. The vault works perfectly as a read-only knowledge base in Obsidian. AI is only needed if you want to add new sources and have them automatically processed.

**Can I fork this and make my own version?**
Yes. Fork the repo, swap out the raw sources with your own content, and run `/second-brain-ingest` to build a wiki from your knowledge.

**How do I add more of Michel's content?**
Clip articles or posts to markdown (using [Obsidian Web Clipper](https://chromewebstore.google.com/detail/obsidian-web-clipper/cnjifjpddelmedmihgijeibhnjfabmlf)), drop them in `raw/`, and run `/second-brain-ingest`.

## Credits

- Knowledge sourced from [Michel Lieben](https://x.com/MichLieben)'s public content (X, LinkedIn, ColdIQ blog)
- Wiki structure powered by [Second Brain](https://github.com/NicholasSpisak/second-brain) by Nicholas Spisak
- Inspired by [Andrej Karpathy's LLM Wiki pattern](https://github.com/NicholasSpisak/second-brain/blob/main/docs/llm-wiki.md)
