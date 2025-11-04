---
description: Manage tasks in minimal todo.md checklist
---

Ultra minimal task checklist with smart vault linking:

**CRITICAL - Context Discovery:**
1. **Always read todo.md first** - Check existing tasks
2. **Search vault for related content** - Find Topics, MOCs, Daily Notes related to task
3. **Auto-link everything** - Add `[[wiki links]]` to related topics found
4. **No duplicates** - Search for similar tasks before adding

**Discovery Process (before adding task):**
- Extract key nouns from task description
- Search `Topics/` for related topic notes (use Grep)
- Search `MOCs/` for relevant maps of content
- Check recent `Daily Notes/` for context
- Find all existing `[[links]]` related to task keywords

**Operations:**

1. **Add task**:
   - Search vault for related topics first
   - Append `- [ ] Task with [[related]] [[topics]]` to todo.md
   - Create missing topic notes if important concepts mentioned

2. **Complete task**: Change `[ ]` to `[x]`
3. **List**: Show all tasks
4. **Remove**: Delete completed tasks

**Format:**
```
- [ ] Task description with [[Topic Links]] and [[Another Topic]]
- [x] Completed task with [[Context]]
```

**Linking Rules:**
- **ANY noun → [[wiki link]]** - People, projects, concepts, tools
- **Years → [[wiki link]]** - [[2025]], [[2024]], etc.
- **Never skip linking** - Dense linking = better graph connectivity
- Create topic note immediately if important noun missing

**Style:**
- Brief, concise descriptions
- Heavy interlinking with vault topics
- No sections, no headers, just checkboxes
- If related topics found, always include them in task
