---
description: Quick git sync - fetch, pull, commit with one-liner, push (auto-resolve conflicts)
---

Execute git workflow to save vault changes:

1. **Fetch** - Check for remote changes
2. **Pull** if needed - Use `git pull --rebase --strategy-option=theirs` to auto-accept incoming changes
3. **Status check** - Review what changed locally
4. **Commit** with smart one-liner message:
   - Read git diff to understand changes
   - Generate concise commit message (1 line max)
   - Format: "Action: brief description" (e.g., "Add 3 new topic notes", "Update daily note with project insights")
5. **Push** to origin

**Conflict resolution:**
- Always accept incoming changes (theirs) if merge conflicts occur
- Use `--strategy-option=theirs` for automatic resolution

**Commit message style:**
- Short (50 chars max)
- Imperative mood ("Add", "Update", "Fix")
- Descriptive but concise
- Examples:
  - "Add strategy topic notes"
  - "Update project development notes"
  - "Add daily note 2025-10-11"

**Execute:**
```bash
git fetch
git pull --rebase --strategy-option=theirs
git add .
git commit -m "generated message"
git push
```

Always show final status after push to confirm success.
