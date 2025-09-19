[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Status: Active](https://img.shields.io/badge/status-active-success.svg)]()
# Convert Markdown into **WhatsApp Formatted Text** (bold, italic, strikethrough, monospace) with ease.

### ✨ Write in Markdown → Share beautifully on WhatsApp.

## WhatsApp Formatted Text

This tool converts standard **Markdown** into **WhatsApp Formatted Text**.  
WhatsApp officially supports these text styles:

## Supported Formats

- **Bold**  
  Markdown: `**bold**` or `__bold__`  
  WhatsApp: `*bold*`

- _Italic_  
  Markdown: `*italic*` or `_italic_`  
  WhatsApp: `_italic_`

- ~Strikethrough~  
  Markdown: `~~strikethrough~~`  
  WhatsApp: `~strikethrough~`

- `Monospace inline`  
  Markdown: `` `code` ``  
  WhatsApp: `` `code` ``

- ```  
  Monospace block (multi-line)  
  Markdown:  
  \```
  console.log("Hello, world!");
  \```  
  WhatsApp:  
  ```
  console.log("Hello, world!");
  ```

- Lists  
  Markdown:
  ```
  1. First
  2. Second

  * Item A
  - Item B
  ```
  WhatsApp: stays the same.

- Quotes  
  Markdown:
  ```
  > quoted text
  ```
  WhatsApp: stays the same.

- Horizontal line  
  Markdown: `---` or `***`  
  WhatsApp: replaced with  
  ```
  ────────────
  ```

---

## Example

**Input (Markdown):**
```markdown
# Title

1. *Step one*
- _Step two_
* **Step three**

> ~Quoted text~

---

`inline code` and code block:
```
console.log("hi WA");
```
```

**Output (WhatsApp Formatted Text):**
```
Title

1. _Step one_
- _Step two_
* *Step three*

> ~Quoted text~

────────────

`inline code` and code block:
```
console.log("hi WA");
```
```

---

## License
MIT
