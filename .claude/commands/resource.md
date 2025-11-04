---
description: Process articles/videos into summarized resource notes with smart linking
---

Resource capture and integration workflow:

**CRITICAL - Search & Link First:**
- **Search existing topics EXTENSIVELY** - Parallel Grep for related concepts before creating
- **Check for existing resources** - Search for article title, author, similar content
- **Prefer linking over duplication** - If similar resource exists, update instead of creating new
- **Fast batch searches** - Scan vault quickly to identify connection opportunities

1. **Understand the resource**:
   - Analyze link/content to identify type (article, video, podcast, paper)
   - Extract title, author, date, source
   - For videos: use transcript if provided, or extract from URL if available
   - Identify main topic, key insights, and core concepts

2. **Search vault for related content**:
   - Grep for related topics, concepts, people, projects
   - Read relevant existing topics to understand context
   - Identify 5-10 potential [[wiki links]] to existing vault notes
   - Find gaps where new topics might be needed

3. **Create resource note** in `Topics/` with naming: `Resource: <title>.md`:
   - **Frontmatter**: `tags: [resource, <type>]` (type: article, video, podcast, paper, etc.)
   - **Core Summary**: 3-5 bullets MAX - key insights only, ultra concise
   - **Source**: Link, author, date, platform
   - **Related Topics**: 5-10 [[wiki links]] to vault topics
   - **Key Concepts**: Brief explanation of main ideas (fragments OK)
   - **Quotes/Highlights**: Notable quotes if relevant (optional, 1-2 max)

4. **Create missing topics if needed**:
   - If resource mentions important concepts not in vault, create topic notes
   - Keep ultra brief (1-2 liners)
   - Link back to resource note

**Processing guidelines:**
- **Video with transcript**: Read transcript, extract key insights, ignore fluff
- **Article**: Focus on main arguments, skip intro/conclusion verbosity
- **Dense summarization**: Pack max info in min words
- **No regurgitation**: Capture insights, not full content
- **Actionable over comprehensive**: What matters, not what's said

**Style:**
- Extreme brevity - fragments encouraged
- NO essay mode - bullets only
- Dense [[links]] to vault topics
- Focus on insights that connect to existing knowledge

**CRITICAL Linking Rule:**
- **ANY noun → [[wiki link]]** - person, place, thing, concept, company, product, year
- Link to existing topics aggressively
- Create topics for important new concepts
- Examples: [[Project Name]], [[Tool Name]], [[Algorithm]], [[Company]], [[2025]]
- More links = better graph connectivity

**Title format:**
`Resource: <descriptive title>.md`

Examples:
- `Resource: How to Build AI Agents.md`
- `Resource: Paul Graham on Startups.md`
- `Resource: Topological Sort Explained.md`
