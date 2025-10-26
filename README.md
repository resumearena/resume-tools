# ResumeArena – Contribute Tools Fast

**ResumeArena** (resumearena.com) is a curated directory of resume builders, templates, interview, and salary tools.
**Note:** The live site may differ from this repo due to ongoing curation, editorial edits, and deployment timing.

> **Review policy:** All submissions are **manually reviewed** and tools may be **tested** (signup, features, pricing claims) before publishing.

---

## Add a New Tool (5 steps)

1. **Fork** the repo → **create a branch**
   `feat/add-<tool-slug>` (or `chore/edit-<tool-slug>`).
2. **Pick a folder:**
   `resume-builders/`, `resume-templates/`, `interview-tools/`, or `salary-tools/`.
3. **Create a file:** `<folder>/<tool-slug>.md` (kebab-case; matches `id`).
4. **Paste & fill the template** (below).
5. **Open a Pull Request** with what/why + sources for factual changes.

---

## Repo Layout

```
resumearena-official-tool-list/
├─ resume-builders/
├─ resume-templates/
├─ interview-tools/
└─ salary-tools/
```

---

## File Template

```md
---
id: <kebab-case-id>
name: <Public Tool Name>
tagline: <Short one-liner>
description: <One sentence>
longDescription: <2–4 lines: who it’s for, strengths/limits>
url: https://...
features:
- <Feature 1>
- <Feature 2>
- <Feature 3>
tags:
- <Tag 1>
- <Tag 2>
pricing:
  type: <Free | Paid | Free & Paid>
  starting: <Free or $x/mo>
  details: <Brief context>
```

**Tips:** Neutral tone, 3–8 features, concise tags (e.g., *AI-Powered*, *ATS*, *Open Source*), direct product URL (no UTM).

---

## Editing an Existing Tool

* Update facts (pricing/features), fix wording, or clarify descriptions.
* Avoid changing `id`/filename unless necessary; explain in PR.

---

## PR Checklist

* [ ] Correct folder & kebab-case filename (matches `id`)
* [ ] All template fields filled
* [ ] Neutral, factual copy
* [ ] Direct URL, no tracking
* [ ] At least 3 features
* [ ] PR description explains **what/why** (+ sources for facts)

---

## Review & Publishing

**Content may be edited for clarity/consistency before publication, and incomplete or misleading submissions may be declined.**

---

## Questions

Open an Issue or Discussion. Thanks for contributing! 🙌
