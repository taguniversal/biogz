
To generate the scaffolding for a new vertical using the `vertical` archetype, the command is:

```bash
hugo new verticals/<your-new-vertical-name>/index.md --kind vertical
```

### For example:

```bash
hugo new verticals/livestock-waste/index.md --kind vertical
```

This will:

* Create the folder `content/verticals/livestock-waste/`
* Create a file `index.md` inside it
* Populate it using the template from `archetypes/vertical.md` (if it exists)

---

### 🔧 If you don’t have `archetypes/vertical.md`

You can create it to define default frontmatter and structure, e.g.:

```toml
+++
title = "{{ replace .Name "-" " " | title }}"
date = {{ .Date }}
draft = true
description = ""
image = ""
+++

# {{ replace .Name "-" " " | title }}

Intro paragraph...
```

This makes it much easier to spin up new verticals quickly and keep them consistent.

Let me know if you want a better default vertical archetype scaffold!
