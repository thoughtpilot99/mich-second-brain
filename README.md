# Michel Lieben's Second Brain

A pre-built [Obsidian](https://obsidian.md) knowledge base containing Michel Lieben's public knowledge on outbound sales, cold email, LinkedIn growth, AI-powered GTM, and B2B agency scaling.

Built using the [Second Brain](https://github.com/NicholasSpisak/second-brain) LLM Wiki pattern by Andrej Karpathy.

## What's Inside

- **24 raw sources** -- original X posts, LinkedIn posts, and research
- **10 entity pages** -- people, companies, and tools (ColdIQ, Clay, Instantly, Claude Code, etc.)
- **14 concept pages** -- frameworks and strategies (Allbound, Tiered Prospecting, Employee Advocacy, etc.)
- **Full cross-referencing** via `[[wikilinks]]` -- every concept links to related entities and sources

## Quick Start

1. **Clone this repo**
   ```bash
   git clone https://github.com/YOUR_USERNAME/mich-second-brain.git
   ```

2. **Open in Obsidian**
   - Download [Obsidian](https://obsidian.md) (free)
   - Open as vault: File > Open folder as vault > select `mich-second-brain/`

3. **Explore**
   - Start at `wiki/index.md` for the full catalog
   - Use the Graph View (Cmd+G) to see how everything connects
   - Click any `[[wikilink]]` to navigate between pages

## Structure

```
mich-second-brain/
  raw/              # Original source material (immutable)
  wiki/
    sources/        # (reserved for source summaries)
    entities/       # People, companies, tools
    concepts/       # Frameworks, strategies, patterns
    synthesis/      # Cross-cutting analysis
    index.md        # Master catalog of all pages
    log.md          # Chronological record of operations
  output/           # Reports and generated artifacts
  CLAUDE.md         # AI agent config for extending the wiki
```

## Extending the Wiki

Want to add your own sources and grow the knowledge base?

1. **Install the Second Brain skills**
   ```bash
   npx skills add NicholasSpisak/second-brain
   ```

2. **Add sources** -- drop markdown files into `raw/`

3. **Ingest** -- run `/second-brain-ingest` in Claude Code (or any compatible AI agent)

4. **Query** -- ask questions with `/second-brain-query`

5. **Health check** -- run `/second-brain-lint` to find gaps and fix cross-references

## Key Concepts to Start With

| Concept | What It Is |
|---------|-----------|
| [[Allbound]] | Content + outbound + ads as one integrated GTM engine |
| [[Employee Advocacy]] | How 24 employees generated $153K MRR in 90 days |
| [[Tiered Prospecting]] | Segmenting TAM into 3 tiers with matched outreach intensity |
| [[Content to Pipeline]] | Why prospects who see your content 3+ times convert at 2-3x |
| [[GTM Engineer]] | The new role replacing traditional SDR teams at 71% less cost |

## Credits

Knowledge sourced from [Michel Lieben](https://x.com/MichLieben)'s public content (X, LinkedIn, ColdIQ blog). Wiki structure powered by [Second Brain](https://github.com/NicholasSpisak/second-brain).
