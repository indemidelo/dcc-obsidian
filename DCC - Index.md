---
tags: [dcc, dcc/hub]
aliases: [DCC Index, DCC Notes]
---

# 📚 Dungeon Crawler Carl — Notes

Index note. The lists below are auto-generated with [Dataview](https://blacksmithgn.github.io/obsidian-dataview/) — you don't need to add links by hand anymore. Just tag a new note correctly (e.g. `dcc/character`, `dcc/mystery`) and it will show up here automatically.

> [!warning] Requires the Dataview plugin
> Install it from **Settings → Community plugins → Browse → search "Dataview"**. Without it, the blocks below will show as plain text instead of live lists.

> [!info] Legend
> - 🟢 Resolved = already answered in the books you've read so far
> - 🔴 Unresolved = still open

---

## 🟢 Resolved mysteries

```dataview
LIST
FROM #dcc/mystery AND #dcc/resolved
SORT file.name ASC
```

## 🔴 Unresolved mysteries

```dataview
LIST
FROM #dcc/mystery AND #dcc/unresolved
SORT file.name ASC
```

---

## 📖 Books read

```dataview
LIST
FROM #dcc/book
SORT number ASC
```

## 🧑 Characters

```dataview
LIST
FROM #dcc/character
SORT file.name ASC
```

## 🗺️ Places/Floors

```dataview
LIST
FROM #dcc/place
SORT floor_number ASC
```

## ✈️ Quests

```dataview
LIST
FROM #dcc/quest
SORT file.name ASC
```

## 💭 Personal theories

```dataview
LIST
FROM #dcc/theory
SORT file.name ASC
```

---

## 🗺️ Connection map (optional)

If you want to visualize the relationships between mysteries in a diagram, you can add a Mermaid block here and update it by hand as your notes connect to each other:

```mermaid
graph TD
    
```

> Tip: to see the connections without writing Mermaid by hand, just use Obsidian's native **Graph view** (the network icon in the sidebar) — it automatically shows all the `[[wikilinks]]` between your notes.
