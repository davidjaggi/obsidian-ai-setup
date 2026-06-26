# Skill: Manage a Project

**When to use**: Creating a new project under `20 Projects/`, or doing any
work inside an existing project folder.

**Project structure**: every project is a self-contained subfolder of
`20 Projects/` and always contains two all-caps files - all-caps file
names in this vault mark load-bearing, machine-maintained files, not
regular notes:

- `INDEX.md` - the structure of the project: outcome, links to its
  Meeting Notes/Tasks/sub-notes. Created once from
  `90 Meta/Templates/Project/INDEX.md`, edited as the project's shape
  changes.
- `CONTEXT.md` - a running log of the project's conversations/work,
  created once from `90 Meta/Templates/Project/CONTEXT.md`. **Append a new
  entry to this file after every interaction with the project** (new
  session, decision made, work done) - never let it go stale, and never
  rewrite past entries.

Other project contents (meeting notes, journals, tasks) live as regular
files directly in the project folder, or in subfolders if there are many
of one kind (e.g. `Meeting Notes/`) - this is the one place in the vault
where that extra nesting is allowed, since the project must stay
self-contained.

**Steps for a new project**:
1. Create `20 Projects/<project name>/`.
2. Add `INDEX.md` and `CONTEXT.md` from the templates above.
3. Fill in the outcome in `INDEX.md`.

**Steps during any interaction with an existing project**:
1. Read `INDEX.md` first to understand the project's shape, then
   `CONTEXT.md` for recent history.
2. Do the requested work.
3. Append a dated entry to `CONTEXT.md` summarizing what changed.
4. If the project's structure changed (new subfolder, new major note),
   update `INDEX.md` to reflect it.

**Depends on**: `90 Meta/Templates/Project/INDEX.md`,
`90 Meta/Templates/Project/CONTEXT.md`
