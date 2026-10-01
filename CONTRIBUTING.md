# Contributing to AoA Community

Thank you for your interest in contributing! This list is community-driven, and we appreciate every addition.

## Where things go

The AoA ecosystem has distinct roles across its repositories:

| Repository | Role | When to use |
| --- | --- | --- |
| [Army of Agents](https://github.com/tandavkrishna27/Army-of-Agents) | Main AoA product. | For the product itself. |
| [AoA Marketplace](https://github.com/tandavkrishna27/aoa-marketplace) | Source of truth for the curated catalog of plugins, skills, agent templates, and team templates. | Submit stable, compatibility-reviewed plugins for the curated catalog. |
| [AoA Marketplace CDN](https://github.com/tandavkrishna27/aoa-marketplace-cdn) | Public distribution mirror of the marketplace catalog. Live catalog: <https://tandavkrishna27.github.io/aoa-marketplace-cdn/catalog.json>. | For catalog distribution; catalog curation belongs in the marketplace source repository. |
| [AoA Skills](https://github.com/tandavkrishna27/AoA-Skills) | AoA skills repository. | For skills maintained in the skills project. |
| [AoA Community](https://github.com/tandavkrishna27/aoa-community) | Community and experimental tools, projects, and resources. | Share experimental plugins, third-party tools, tutorials, books, blog posts, talks, and other AoA-related projects. |

If your plugin is stable and ready for compatibility review, submit it to the [AoA Marketplace](https://github.com/tandavkrishna27/aoa-marketplace). Use this repository for experimental work and community resources.

## How to add an entry

1. **Fork** this repository.
2. **Edit** `README.md` and add your link under the appropriate category.
3. **Submit** a pull request.

### Entry format

Use the following format when adding a link:

```markdown
- [project-name](https://github.com/owner/repo) — A short description of the project.
```

- Start the description with a capital letter.
- End the description with a period.
- Keep descriptions concise (one sentence).
- Use an em dash (—) between the link and the description, not a hyphen.

### Which category?

| Category | What belongs here |
| --- | --- |
| **Official** | Repositories maintained by the AoA team |
| **Plugins** | Pointer to the marketplace; experimental plugins not yet submitted to the curated catalog can be added here |
| **Tools & Utilities** | Bots, bundles, CLIs, dashboards, and helper tools that interact with AoA |
| **Resources** | Guides, books, tutorials, blog posts, videos, and talks |

If none of the existing categories fit, suggest a new one in your PR.

## Quality standards

To keep the list useful, please ensure your submission meets the following criteria:

- **Relevant** — The project must be directly related to [AoA](https://github.com/tandavkrishna27/Army-of-Agents).
- **Public** — The repository or content should be publicly accessible.
- **Maintained** — The project should show recent activity (commits within the last 6 months) or be marked clearly as archived/historical if it's a finished resource.
- **No duplicates** — Check the list first to make sure the project is not already included.
- **Working** — The project should be functional and not in a broken state.

## Pull request guidelines

- Use a clear PR title, e.g., `Add aoa-tool-xyz to Tools & Utilities`.
- One addition per pull request keeps reviews fast.
- Make sure the list is alphabetically ordered within each category.
- Verify that your links work before submitting.

## Updating your entry

If you need to update an existing entry (e.g., change the description or URL), follow the same process: fork, edit, and submit.

## Contribution licensing

By submitting a contribution to this repository, you license that contribution under the terms of this repository's [MIT License](LICENSE). This applies to your contribution to this repository and does not replace or change any third-party terms that may apply to linked projects or materials.

## Code of conduct

Be respectful and constructive. We are all here to make the AoA ecosystem better.

---

Thank you for contributing! 🎉
