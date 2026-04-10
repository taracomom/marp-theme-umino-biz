---
marp: true
theme: umino-biz
paginate: true
---

# Marp Theme<br>Umino Biz<!--fit-->
<!-- _class: cover-page -->

---

## Image Layout

<div class="flex sa">
<div>

### Use for

- Charts and KPIs
- Screenshots
- Customer photos
- Product diagrams

</div>
<div>

![w:520](images/sample-chart.png)

</div>
</div>

---

## Features

- Teal (#008080) accent for a calm, trustworthy look
- Optimized for Japanese typography (Hiragino Sans / Meiryo)
- Cover, content, and image layouts ready to use
- Box & flexbox utilities for fast composition
- Designed for business decks, proposals, and reports

---

## Box Styles

<div class="box">

`.box` — neutral container for key facts and figures.

</div>

<div class="box-highlight">

`.box-highlight` — call out tips, takeaways, or recommendations.

</div>

<div class="box-warning">

`.box-warning` — flag risks, warnings, or things to avoid.

</div>

---

## Two-Column Layout

<div class="flex sa">
<div>

### Before

- Manual reporting
- Slides take hours
- Hard to keep on-brand

</div>
<div>

### After

- Markdown-driven
- Slides in minutes
- Consistent visual identity

</div>
</div>

---

## Why Markdown Decks?

- Version-controlled with Git
- Edit anywhere, even on mobile
- Perfect for engineering & data teams
- Reusable across web, PDF, and print

---

> "Good slides are not decoration —
> they are an interface to your thinking."

Use blockquotes for pull quotes, customer voices, and callouts.

---

## Installation

```yaml
---
marp: true
theme: umino-biz
paginate: true
---
```

```bash
marp --theme-set umino-biz.css slide.md
```

That's it. See the README for VS Code and Obsidian setup.
