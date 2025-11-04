# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Context

This is **[Your full name]'s personal Obsidian vault** - a second brain knowledge management system for the [Your Designation].

**Primary Purpose:** Personal knowledge base with networked thinking, daily journaling, and graph-based idea discovery.

## Vault Architecture

**Folder Structure Philosophy:**
- **Minimal hierarchy** - Designed for maximum network connectivity and graph view insights
- **Flat Topics folder** - All topics live at root level (no subfolders) to maximize cross-linking
- **Link-first thinking** - Everything connects via `[[wiki links]]`, not folder organization

```
Daily Notes/   → Date-based daily journals (YYYY-MM-DD.md)
Topics/        → Atomic idea notes (FLAT - no subfolders ever)
MOCs/          → Maps of Content - hub notes linking related topics
Templates/     → Note templates for consistency
```

## Key Obsidian Configuration

**Daily Notes Settings** (`.obsidian/daily-notes.json`):
- Auto-creates in `Daily Notes/` folder
- Uses `Templates/Daily Note` template
- Date format: `YYYY-MM-DD`
- Template variables: `{{date}}`, `{{date:YYYY-MM-DD}}`

**Template System:**
- `Daily Note.md` - Sections: Today's Focus, Notes & Thoughts, Ideas & Insights, Connections, Quick Capture
- `Topic.md` - Sections: Core Idea, Details & Context, Related Topics, Insights & Questions, Sources & References
- Both templates include frontmatter with tags and metadata

## Working with This Vault

### Critical Rules

**NEVER create subfolders in Topics/** - The flat structure is intentional for graph connectivity. If you see a need to organize topics by category, create a MOC instead.

**Always use wiki-links `[[Topic Name]]`** - This is how the knowledge graph builds. When creating or editing notes, link liberally to other topics, MOCs, and daily notes.

**Preserve template structure** - When creating new templates or modifying existing ones, maintain the frontmatter format and section headers that enable consistent note-taking.

**Respect the networked thinking model:**
- Topics should be atomic (one main idea per note)
- MOCs are for connecting multiple topics into themes
- Daily notes link to topics and MOCs, not the other way around

### When Creating New Notes

**Daily Notes:**
- Only create in `Daily Notes/` folder
- Always use YYYY-MM-DD format
- Apply Daily Note template
- Include links to relevant topics and MOCs in the Connections section

**Topic Notes:**
- Only create in `Topics/` folder (root level, never nested)
- Apply Topic template
- Fill in "Related Topics" section with `[[links]]` to build graph
- Keep each topic focused on a single concept

**MOC Notes:**
- Create in `MOCs/` folder
- These are "hub" notes - should contain many `[[links]]` to related topics
- Group by theme (e.g., Leadership)
- Update as the knowledge base evolves

### Context-Specific Guidance

**This is a personal vault for [Your Full Name]:**
- Maintain professional but personal tone in templates
- Reference his roles

**Graph View Optimization:**
- The entire architecture prioritizes graph connectivity
- Avoid creating isolated notes - always link to at least 2-3 other notes
- When refactoring or improving structure, preserve/enhance linking patterns

**Metadata Standards:**
- Daily notes: `tags: [daily]`, `date:` frontmatter
- Topics: `tags: [topic]`, `status: developing`, `created:` frontmatter
- MOCs: `tags: [moc, index]` frontmatter

## File Naming Conventions

- Daily notes: `YYYY-MM-DD.md` (e.g., `2025-10-11.md`)
- Topics: Descriptive title case (e.g., `Product Market Fit.md`, `Neural Networks.md`)
- Templates: Simple descriptive names (e.g., `Daily Note.md`, `Topic.md`)

## My Personal Preferences

### Content Style
- **ULTRA SHORT AND CONCISE** - Prefer brevity over lengthy explanations
- **Concision > Grammar** - Broken sentences, fragments, abbreviations all OK if shorter
- **Bullet points** - Use bullets liberally, avoid long paragraphs
- **NO ESSAY MODE** - Never write long-form content for topics/notes
- **Heavy interlinking** - Connect everything with `[[wiki links]]`
- **Never leave topics empty** - Every topic needs 1-2 liners minimum, even if brief
- **Atomic notes** - One main idea per topic note
- **EXCEPTION**: Only write long-form when content is for external use (emails, docs to send, presentations)

### Daily Note Workflow
- **Connections go in Topics** - All `[[links]]` in Connections section must point to topic notes
- **Create topics liberally** - When mentioning people, projects, concepts → create topic note
- **Interlink heavily** - Build dense network of connections between notes

### Topic Note Standards
- **EXTREME BREVITY** - 1-2 liners minimum, short bullets preferred, NO LONG SECTIONS
- **Break down everything** - If section has >5 bullets, too long
- **Fragments OK** - "SEO pages auto-gen" > "This involves automatically generating SEO pages"
- **Dense info** - Pack max info in min words
- Always include Related Topics section with links
- Add context tags: `[topic]`, `[technical]`, `[people]`, `[business]`, `[tools]`, `[entertainment]`
- Status: `developing` for active topics

### CRITICAL Linking Philosophy
- **ANY noun → [[wiki link]]** - If you write any word that is a noun (person, place, thing, concept), wrap it in `[[ ]]`
- **ANY year → [[wiki link]]** - Years (2025, 2024, etc.) also get links: [[2025]], [[2024]]
- Don't overthink - more links = better graph connectivity
- Create topic note immediately if important noun doesn't exist yet
- This applies to ALL writing: daily notes, topics, MOCs, commands

## What NOT to Do

❌ Create subfolders in `Topics/` (breaks the flat structure principle)
❌ Organize by date/month folders (defeats networked thinking purpose)
❌ Create standalone notes without any `[[wiki links]]` (isolates from graph)
❌ Mix organizational systems (this is link-based, not folder-based)
❌ Modify `.obsidian/` config files without understanding impact on templates
❌ Write lengthy paragraphs in topic notes (use bullets instead)
❌ Write long sections/explanations (>5 bullets = too long, break down further)
❌ Write complete sentences when fragments work ("Auto-gen pages" not "Automatically generate pages")
❌ Leave topic notes empty or with just frontmatter (always add content)
❌ Create topics without linking them to at least 2-3 other topics
❌ Write nouns without [[wiki links]] - aggressive linking is the foundation of networked thinking
❌ Write essay-style content for internal vault notes (only for external deliverables)
