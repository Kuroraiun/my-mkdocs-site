# Create links that open in a new tab

By default, Markdown links open in the same browser tab. To open links in a new tab, use HTML `<a>` tags instead of Markdown link syntax.

---

## Why use HTML instead of Markdown?

Standard Markdown links:

```markdown
[Example](https://example.com)
```

Limitations:

* Opens in the same tab
* Cannot control tab behavior

HTML links allow opening links in a new tab.

---

## Basic syntax

Use this format:

```html
<a href="URL" target="_blank">Link text</a>
```

Example:

```html
<a href="https://example.com" target="_blank">Visit Example</a>
```

---

## Recommended syntax (best practice)

Always include security attributes:

```html
<a href="URL" target="_blank" rel="noopener noreferrer">Link text</a>
```

Example:

```html
<a href="https://simplenote.com/"
   target="_blank"
   rel="noopener noreferrer">
   Visit Simplenote
</a>
```

---

## Example: external link

```html
<a href="https://youtube.com/"
   target="_blank"
   rel="noopener noreferrer">
   Watch on YouTube
</a>
```

---

## Example: internal page link

```html
<a href="../getting-started/"
   target="_blank"
   rel="noopener noreferrer">
   Open getting started guide
</a>
```

---

## Example: display URL as text

```html
<a href="https://example.com"
   target="_blank"
   rel="noopener noreferrer">
   https://example.com
</a>
```

---

## Example: use inside lists

```markdown
1. Go to the official website:  
   <a href="https://simplenote.com/"
      target="_blank"
      rel="noopener noreferrer">
      Visit Simplenote
   </a>
```

---

## Quick reference template

Copy and reuse:

```html
<a href="PASTE_URL_HERE"
   target="_blank"
   rel="noopener noreferrer">
   LINK_TEXT_HERE
</a>
```

---

## Summary

| Method                     | Opens in new tab |
| -------------------------- | ---------------- |
| Markdown `[link](url)`     | No               |
| HTML `<a target="_blank">` | Yes              |

---

## Recommendation

Always use:

```html
target="_blank" rel="noopener noreferrer"
```

for best compatibility, security, and user experience.

---
