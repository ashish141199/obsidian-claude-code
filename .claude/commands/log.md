---
description: Quick daily note logging with smart linking and topic creation
---

Simple daily logging workflow:

**CRITICAL - Search FIRST, Always:**
- **MANDATORY**: Before logging ANYTHING, search Topics/ for ALL nouns you'll mention
- Use Grep with pattern matching for names, concepts, tools (e.g., "Atharv Kulkarni|Renuka Jagtap|UPI")
- Check for BOTH exact matches AND similar names (e.g., "Renuka" vs "Renuka Jagtap HDFC")
- **NO duplicate topics** - if similar topic exists, use that exact link
- Fast parallel Grep searches - batch all nouns in one search

**File Management Rules:**
- **Link to existing** > Create new (always)
- **Create ONLY if** genuinely new person/concept not in vault
- Search for partial names - some people have full context (e.g., "Renuka Jagtap HDFC" not just "Renuka")

**Workflow:**

1. **SEARCH FIRST** (mandatory):
   ```
   Grep pattern="Noun1|Noun2|Noun3" glob="Topics/*.md"
   ```
   - Extract ALL nouns from log message
   - Batch search in ONE Grep call
   - Read matching files to verify correct topic

2. **Log to today's daily note**:
   - Add under appropriate section
   - 1-2 bullets MAX

3. **Create missing topics** (only if not found):
   - ULTRA BRIEF (1-2 liners)
   - Link to 2-3 related topics
   - Use Topic template

4. **No conversation** - just search → log → create

**Linking philosophy:**
- **ANY noun → [[wiki link]]** - person, place, thing, concept, year
- Examples: [[Platoona]], [[Saurabh Sharma]], [[MVP]], [[2025]]
- Create topic immediately if doesn't exist

**Style:**
- Extreme brevity - fragments OK
- Broken sentences fine if shorter
- NO essays, NO paragraphs
- Pack max info in min words
