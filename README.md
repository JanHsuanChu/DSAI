# <span style="color:#2563eb">📄 README Style Rule — User Guide</span>

> What the readme-style rule does and how to use it when writing or editing READMEs.

---

## <span style="color:#2563eb">📑 Table of Contents</span>

- [What this rule does](#-what-this-rule-does)
- [When it applies](#-when-it-applies)
- [What you need to do](#-what-you-need-to-do)
- [How the rule is used](#-how-the-rule-is-used)
- [Related files](#-related-files)

---

## <span style="color:#2563eb">📋 What this rule does</span>

The **readme-style** rule tells the AI how to format user-facing READMEs in this project. It keeps docs short, easy to scan, and consistent.

**Rule file:** [readme-style.mdc](readme-style.mdc)

It covers length, audience, structure (TOC, headers, links), diagrams, and a short checklist so nothing is missed.

---

## <span style="color:#2563eb">🎯 When it applies</span>

The rule runs when you create or edit files that match **`**/README*.md`** (e.g. `README.md`, `README_my_good_query_user.md`). It does not run for other markdown files unless you mention the rule or the README.

Use it whenever you want a README that is aimed at **people reading the output or using the project**, not only developers.

---

## <span style="color:#2563eb">✅ What you need to do</span>

When writing a user-facing README, the rule asks for:

| Requirement | Meaning |
|-------------|--------|
| **Max 1000 words** | Keep it short; prefer bullets and tables. |
| **Table of contents** | At the top, with clickable links to each section. |
| **Section headers** | One icon (emoji) per section + blue styling: `## <span style="color:#2563eb">📑 Table of Contents</span>`. |
| **Links to files** | Link to the script, main README, and related docs; add a “Related files” section. |
| **Flow diagram** | If you add a Mermaid flowchart, make it fit one screen and use the brown theme from the rule. |
| **User-focused text** | Explain what the user sees or does; avoid API/implementation details unless needed. |

The full checklist and theme snippet are in [readme-style.mdc](readme-style.mdc).

---

## <span style="color:#2563eb">🔄 How the rule is used</span>

When you edit a README that matches the rule, the AI uses this flow to apply the style:

```mermaid
%%{init: {'theme':'base', 'themeVariables': {'primaryColor':'#D2691E', 'primaryBorderColor':'#8B4513', 'lineColor':'#8B4513', 'secondaryColor':'#DEB887', 'tertiaryColor':'#F5DEB3', 'primaryTextColor':'#fff', 'secondaryTextColor':'#333', 'tertiaryTextColor':'#333'}}}%%
flowchart LR
    A([Edit README]) --> B[Rule applies?]
    B --> C[Use TOC + icons + blue]
    C --> D[Add file links]
    D --> E[Keep under 1000 words]
    E --> F([Done])
```

You don’t have to remember every detail; referring to “readme-style” or this README is enough for the AI to follow the rule.

---

## <span style="color:#2563eb">🔗 Related files</span>

| File | Purpose |
|------|--------|
| [readme-style.mdc](readme-style.mdc) | The Cursor rule (full requirements and checklist) |
| [README_my_good_query_user.md](../dsai/01_query_api/README_my_good_query_user.md) | Example README that follows this style |

---

← Back to [.cursor/rules](.)
