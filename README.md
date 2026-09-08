# Refactoring Your Developer Identity

Slides for Chris Ayers's talk about doing useful work when the language, framework, or job changes. The audience leaves with a skill they can reuse and a small experiment to try.

## Slides


[View HTML slides](https://chris-ayers.com/refactoring-your-identity/) | [Download PDF](https://chris-ayers.com/refactoring-your-identity/Slides.pdf)

The source deck for this presentation lives in [slides/](./slides/) and is built with [Marp](https://marp.app/).
The [Pages workflow](./.github/workflows/marp-pages.yml) generates and deploys both formats on pushes to `main` or when run manually.

## Overview

The talk is designed for **60 minutes, excluding Q&A**. The 47 slides include brief questions and section breaks, stories, a reflection exercise, and a tour of skills that transfer across stacks.

| Slides | Time | Focus |
| --- | --- | --- |
| 1-14 | About 15 minutes | How technical identity forms, the coding-kata story, and reflection |
| 15-26 | About 15 minutes | Career risks, the re-org story, decision habits, and AI |
| 27-41 | About 20 minutes | Portable skills, how they work together, and the cross-stack story |
| 42-47 | About 10 minutes | Ongoing practice and the 30/60-day plans |

Speaker notes contain delivery cues and room for the talk track. The blank technologies in the coding-kata quote are intentional: Chris supplies them aloud. Use rehearsal to adjust the time spent on each section.

## Resources

Related reading and examples from Chris's blog:

- [New Team, New Focus](https://chris-ayers.com/posts/new-team-new-focus/) and [Promoted to Principal Software Engineer](https://chris-ayers.com/posts/promoted-to-principal-swe/) describe the career change.
- [Snake Oil DevOps](https://chris-ayers.com/posts/snake-oil-devops-beware/) explains the focus on customers and helping people continue after you leave.
- [Copilot or Rubber Ducky?](https://chris-ayers.com/posts/copilot-or-rubber-ducky/) connects explaining a problem with using an AI assistant.
- [How Do You Boil the Ocean?](https://chris-ayers.com/posts/how-do-you-boil-the-ocean/) describes making small improvements and learning from the results.

The deck also discusses David Epstein's *Range* and uses short decision records to make technical choices easier to explain and revisit.

## Connect with Chris Ayers

- Bluesky: [@chris-ayers.com](https://bsky.app/profile/chris-ayers.com)
- LinkedIn: [chris-l-ayers](https://linkedin.com/in/chris-l-ayers/)
- Blog: https://chris-ayers.com/
- GitHub: [Codebytes](https://github.com/codebytes)
- Mastodon: [@Chrisayers@hachyderm.io](https://hachyderm.io/@Chrisayers)

## Exporting the Deck

The tooling follows [codebytes/marp-slides-template](https://github.com/codebytes/marp-slides-template/tree/09376782bcaca03fe7c071ba124862d225b60914), with the generic `custom-default` theme and the talk's existing content.

| Component | Version |
| --- | --- |
| Marp CLI | 4.5.0 |
| Mermaid (for new inline diagrams) | 11.17.2 |
| Font Awesome Free | 7.3.1 |

Open `slides/Slides.md` with the recommended Marp for VS Code extension, or use the CLI from the repository root:

```bash
npm install --global @marp-team/marp-cli@4.5.0

# HTML: export alongside the source so relative image URLs keep working.
marp --theme-set slides/themes --html -- slides/Slides.md

# PDF and PowerPoint: allow the local images and custom themes.
marp --theme-set slides/themes --html --allow-local-files --pdf -- slides/Slides.md
marp --theme-set slides/themes --html --allow-local-files --pptx -- slides/Slides.md
```

These commands produce `slides/Slides.html`, `slides/Slides.pdf`, and `slides/Slides.pptx`; generated exports are ignored by Git. Marp CLI requires Node.js 18 or newer and a supported Chrome/Chromium or Firefox installation for PDF/PPTX exports. The devcontainer supplies Node.js 24 and Marp CLI; enable its optional Chromium feature for those exports.

The Pages workflow builds HTML and PDF for pull requests and `main`, then deploys only `main`. Published files include the [HTML deck](https://chris-ayers.com/refactoring-your-identity/) and [PDF download](https://chris-ayers.com/refactoring-your-identity/Slides.pdf). Configure the repository's Pages source as **GitHub Actions**.

## PDF Releases

Each successful build of `main` also publishes `refactoring-your-identity.pdf` in a [GitHub Release](https://github.com/codebytes/refactoring-your-identity/releases). Release tags use `slides-<run-number>-<run-attempt>` and point to the exact commit that produced the PDF. Reruns receive a new release version rather than overwriting an existing release.

Every build, including pull requests, uploads a downloadable `slides-pdf` workflow artifact. Rerunning the build refreshes that temporary artifact; previously published release copies remain unchanged. Pull requests and manual runs on other branches do not publish releases or deploy Pages. Release publishing uses a separate job with repository write permission; the build job remains read-only.

## Themes and Diagrams

Reusable themes live in `slides/themes/`: `custom`, `custom-default`, `custom-gaia`, and `custom-uncover`. They provide CSS color variables, two/three-column helpers, centered images, Font Awesome icons, and constrained Mermaid sizing. The deck uses `custom-default`, which also includes `lead`, `invert`, and `small` slide classes.

Use `<div class="columns">` or `<div class="columns3">` around column content, and `![center](img/example.svg)` for centered images. New decks should use `marp: true` and `theme: custom-default` in their frontmatter, with speaker notes in HTML comments.

The social-icon color helpers use brand colors on light slides and white logo variants on `invert` slides. The generic blog icon follows the theme's highlight color.

The current deck's diagrams are images and need no Mermaid runtime. For a new inline Mermaid diagram, include this module script once in that deck:

```html
<script type="module">
  import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@11.17.2/dist/mermaid.esm.min.mjs';
  const printStyle = document.createElement('style');
  printStyle.textContent = '@media print { body > .mermaidTooltip { display: none !important; } }';
  document.head.append(printStyle);
  mermaid.initialize({ startOnLoad: true, htmlLabels: false });
</script>

<pre class="mermaid">
flowchart LR
    A[Experiment] --> B[Reflect] --> C[Adapt]
</pre>
```

SVG labels prevent clipping in Marp PDF exports. The print-only tooltip rule prevents a hidden tooltip from adding an extra blank page, without disabling browser tooltips. Mermaid and the theme's CDN-hosted fonts require network access when rendering.

For diagrams that must reopen in draw.io, use the shared [drawio-diagrams skill](https://github.com/codebytes/skills/tree/main/skills/drawio-diagrams). Its generator, examples, and validation instructions are maintained in `codebytes/skills`.

Keep both the source specification and rendered `.drawio.svg` under `slides/img/` for presentation-specific diagrams. The recommended Draw.io Integration extension opens these files for visual editing.

## Shared Agent Skills

Authoring and review skills come from [codebytes/skills](https://github.com/codebytes/skills), rather than copies maintained in this repository. Install the shared Copilot plugin:

```bash
copilot plugin install https://github.com/codebytes/skills
```

| Skill | Use |
| --- | --- |
| [marp-authoring](https://github.com/codebytes/skills/tree/main/skills/marp-authoring) | Edit deck content, speaker notes, and layouts |
| [marp-visuals](https://github.com/codebytes/skills/tree/main/skills/marp-visuals) | Create charts and Mermaid assets |
| [drawio-diagrams](https://github.com/codebytes/skills/tree/main/skills/drawio-diagrams) | Create and validate editable `.drawio.svg` diagrams |
| [marp-slide-review](https://github.com/codebytes/skills/tree/main/skills/marp-slide-review) | Review overflow, clipping, asset failures, and HTML/PDF rendering |

Follow the installed skill's instructions for its scripts and dependencies. See the [shared installation guide](https://github.com/codebytes/skills#install) for other supported hosts. Talk-specific conventions remain in [`.github/copilot-instructions.md`](.github/copilot-instructions.md).

Use `marp-slide-review` before presenting or publishing; VS Code also highlights overflow as you edit. The Pages/PDF workflow invokes Marp CLI directly and does not depend on these skills or run them as a deployment gate.

## Demo / Extension Ideas

While this repo is slide-focused, you may extend it with:

- Example mini ADRs (`/examples/adr-*`)
- A learning debt log template (`/templates/learning-debt.md`)
- Workshop variant (long-form exercises)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Questions or suggestions? Open an issue or start a discussion.