# Contributing to PhenomenaHub

Thank you for your interest in contributing to **PhenomenaHub**! This repository thrives on community collaboration. Whether you want to add a new law or effect, improve an existing description, or expand our multilingual coverage, your help is welcome.

## 🧭 Guiding Principles

- **Accuracy:** Every contribution must be grounded in reliable sources. Cite academic literature, reputable publications, or verified datasets.
- **Objectivity:** Describe laws and effects in a neutral tone. When controversies exist, summarize multiple viewpoints.
- **Clarity:** Write in accessible language. Explain technical terms and avoid unnecessary jargon.
- **Completeness:** Follow the required structure for each entry and include all information fields.
- **Bilingualism:** Provide both English and Chinese versions. Aim for meaning-equivalent translations rather than word-for-word copies.

## ✅ Contribution Checklist

Before submitting a pull request:

1. **Discuss (Optional but Encouraged):** Open an Issue or join Discussions if you plan a large addition or restructuring.
2. **Fork & Branch:** Fork the repository and create a feature branch (e.g., `feat/add-dunning-kruger-effect`).
3. **Follow Structure:** Use the template below for new entries.
4. **Add Both Languages:** Update the paired English and Chinese files.
5. **Cross-reference:** Link related laws/effects across domains when appropriate.
6. **Self-review:** Proofread for spelling, grammar, and factual accuracy.
7. **Pull Request:** Submit a PR with a clear summary of the changes and references consulted.

## 🧱 Entry Template (English)

```markdown
### {Law or Effect Name in English} / {中文名称}
- **Name:** {Full English Name} / {中文名称}
- **Description:** {Minimum 200–300 words explaining the concept, mechanisms, and implications. Include intuitive examples.}
- **Origin:** {Discoverer(s), year, historical context, and primary publication.}
- **Wikipedia Links:** [English](URL) | [中文](URL or `N/A`)
- **Applications:**
  - {Application 1}
  - {Application 2}
  - {Application 3}
- **Related Concepts:** {Link to other PhenomenaHub entries when relevant.}
- **Additional Notes:** {Optional — controversies, critiques, modern extensions, empirical studies, etc.}
```

## 🧱 条目模板（中文）

```markdown
### {英文名称} / {中文名称}
- **名称：** {英文全称} / {中文名称}
- **详细解释：** {不少于 200-300 字，解释概念、机制与影响，包含示例。}
- **出处或发现人：** {提出者、年份、历史背景与主要出版物。}
- **维基百科链接：** [英文](URL) | [中文](URL 或 `暂无`)
- **应用：**
  - {应用场景 1}
  - {应用场景 2}
  - {应用场景 3}
- **相关概念：** {必要时链接到 PhenomenaHub 内其他条目。}
- **其他补充：** {可选 — 包括争议、批评、最新研究等。}
```

## 📂 File Organization

Each domain has two files:

- `docs/DomainName.md` — English version
- `docs/DomainName.zh.md` — Chinese version

Ensure you update both files when adding or modifying content.

## 🧪 Quality Assurance

- Verify that Markdown renders correctly (headings, lists, links).
- Double-check that citations and links are valid.
- Use inclusive language and respect diverse perspectives.
- Note unresolved questions or controversies in **Additional Notes**.

## 🔄 Review Process

1. CI/CD checks (linting, formatting) run automatically.
2. Maintainers review for accuracy, completeness, and style adherence.
3. Revisions may be requested; please respond promptly and courteously.
4. Once approved, your contribution merges into the main branch.

## 🌍 Language Support

If you can contribute in only one language:

- Add your content in the language you know.
- Open an Issue labeled `translation-needed` with a summary of what requires translation.
- Community translators or maintainers will help complete the counterpart.

## 🙌 Thank You

By contributing to PhenomenaHub, you help build a cross-disciplinary map of humanity’s knowledge. We appreciate your time, insight, and dedication!
