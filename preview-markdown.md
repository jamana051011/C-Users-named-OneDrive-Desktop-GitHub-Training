# Docs-as-Code

This is a beginners session. This session is intended for audience with little knowledge on docs-as-code.

---

## What is Docs-as-Code

**Workflow** treating documentation, the _same way software teams treat code_.


### Like how?

Using the same tools and the environment that the software team uses.

- Source files 
- Version Control Systems 
- MPull request review
- CI/CD pipeline
- Static site generators 
---
Ordered lists are numbered automatically:

1. Write your markdown
2. Preview the rendered output
3. Export or save to the cloud
---
| Software process | Options | 
|------|-------|
|Source files | Markdown, reStructuredText, Asciidoc  |
|Version Control Systems   | GitHub, GitLab, Bitbucket|
|Static site generators   | Mintifly, Vercel, MkDocs and more|

Nested lists work too:

- Cloud integrations
  - GitHub repositories
  - Dropbox folders
  - Google Drive files
  - OneDrive and Bitbucket
- Local features
  - Auto-save to browser storage
  - Image paste from clipboard
----
## Docs-as-code workflow

- [x] Write your markdown file
- [x] Post it in Git-based repositories
- [ ] Raise a pull request and assign to a reviewer
- [ ] Merge the pull request
- [ ] Publish the file


## Links and Images

Link to any page with [inline links-md-tabe generator](https://www.tablesgenerator.com/markdown_tables) or use [reference-style links][dillinger].

Images use a similar syntax:

![Placeholder](https://placehold.co/600x200/2B2F36/35D7BB?text=Your+Image+Here)

[dillinger]: https://dillinger.io

## Blockquotes

> The art of writing is the art of discovering what you believe.
>
> — Gustave Flaubert

Blockquotes can contain other markdown elements:

> **Tip:** Use `Cmd+Shift+Z` to enter zen mode for distraction-free writing.

## Code

Fenced code blocks support syntax highlighting:

```javascript
function greet(name) {
  return `Hello, ${name}.`;
}

console.log(greet("world"));
```

```python
def fibonacci(n):
    a, b = 0, 1
    for _ in range(n):
        a, b = b, a + b
    return a
```

## Tables

| Shortcut | Action |
|----------|--------|
| `⌘ ⇧ Z` | Toggle zen mode |
| `Escape` | Exit zen mode |
| `?` | Keyboard shortcuts |

Tables support alignment:

| Feature | Status | Notes |
|:--------|:------:|------:|
| Markdown editing | Active | Monaco-powered |
| Live preview | Active | Scroll-synced |
| Cloud sync | Available | 5 providers |
| PDF export | Available | Server-rendered |

## Footnotes

Dillinger supports extended markdown syntax including footnotes[^1] and definition lists.

[^1]: Footnotes appear at the bottom of the rendered preview.

## Math

Inline math: $E = mc^2$

Block equations:

$$
\sum_{i=1}^{n} i = \frac{n(n+1)}{2}
$$

---

*Your documents save automatically. Start writing.*
