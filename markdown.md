# Markdown Overview

## What is Markdown?
Markdown is a lightweight markup language used for formatting text. It allows you to add headings, lists, links, and more using simple syntax. Markdown files have the `.md` or `.markdown` extensions and are often used for documentation, such as README files.

## Why Use Markdown?
1. **Simple Syntax:** Easy to learn and use for anyone, even non-technical writers.
2. **Readable:** Clean and intuitive formatting, even in raw text.
3. **Platform-Independent:** Markdown files work across platforms and text editors.
4. **Widely Supported:** Markdown is supported by platforms like GitHub, Trello, Reddit, and StackOverflow.

---

## Basic Markdown Syntax

### 1. Headings
Use `#` followed by a space to create headings. The number of `#` symbols determines the heading level.

```markdown
# H1
## H2
### H3
#### H4
##### H5
###### H6

```
Output
# H1
## H2
### H3
#### H4
##### H5
##### H6

### 2. Paragraphs
Leave a blank line between paragraphs.

```markdown
This is paragraph 1.

This is paragraph 2.
```
*Output*

This is paragraph 1.

This is paragraph 2.

### 3. Bold, Italic, and Strikethrough
```markdown
**Bold** or __Bold__

*Italic* or _Italic_

***Bold and Italic*** or ___Bold and Italic___

~~Strikethrough~~
```
*Output*

**Bold** or __Bold__

*Italic* or _Italic_

***Bold and Italic*** or ___Bold and Italic___

~~strikethrough~~

### 4. Links
```markdown
[Link Text](https://example.com)
```
*Output*

[Link Text](https://example.com)

### 5. Lists
#### Unordered Lists
- Use -, *, or + to create unordered lists.
    ```markdown
    - Item 1
    - Item 2
        - Subitem 2.1
        - Subitem 2.2
    ```
    *Output*
    - Item 1
    - Item 2
        - Subitem 2.1
        - Subitem 2.2
#### Ordered Lists
- Use numbers followed by a period (1., 2., etc.) for ordered lists.
    ```markdown
    1. Item 1
    2. Item 2
        1. Subitem 2.1
        2. Subitem 2.2
    ```
    *Output*
    1. Item 1
    2. Item 2
        1. Subitem 2.1
        2. Subitem 2.2

#### Mixed Lists
```
1. Main Step 1
   - Substep 1.1
   - Substep 1.2
2. Main Step 2
   - Substep 2.1
```
*Output*
1. Main Step 1
   - Substep 1.1
   - Substep 1.2
2. Main Step 2
   - Substep 2.1

### 6. Images
```markdown
![Sample Image](./image.jpg)
```
*Output*
![Sample Image](./image.jpg)

### 7. Code Blocks
#### Inline Code
- Use backticks ( ` ) for inline code.
    ```markdown
    This is `inline code`.
    ```
    *Output*

    This is `inline code`.

#### Block Code
- Use triple backticks (```) for multi-line code blocks. Specify the language (optional) for syntax highlighting.
    ```markdown
    ```bash
    # Bash code
    npm install
    ```(Should have closing)
    ```

    *Output*
    ```bash
    # Bash code
    npm install
    ```
    ```javascript
    // JavaScript code
    console.log('Hello, World!');
    ```

### 8. Blockquotes
- Use `>` to create blockquotes.
    ```
    > This is a blockquote.
    > It can span multiple lines.
    ```
    *Output*

    > This is a blockquote.

    > It can span multiple lines.

### 9. Horizontal Rule
- Use `---`, `***`, or `___` to create horizontal rules.
    ```
    ---
    ```
    *Output*
    ---

### 10. Tables
- Use pipes (`|`) and hyphens (`-`) to create tables.

    ```markdown
    | Column 1 | Column 2 |
    |----------|----------|
    | Value 1  | Value 2  |
    | Value 3  | Value 4  |
    ```
    *Output*
    | Column 1 | Column 2 |
    |----------|----------|
    | Value 1  | Value 2  |
    | Value 3  | Value 4  |

### 11. Task Lists
- Use `- [ ]` for unchecked items and `- [x]` for checked items.

    ```markdown
    - [x] Task 1
    - [ ] Task 2
    - [ ] Task 3
    ```

    *Output*
    - [x] Task 1
    - [ ] Task 2
    - [ ] Task 3

### 12. Escaping Characters
- Use a backslash (`\`) to escape special Markdown characters.

    ```markdown
    Use `\` before `*`, `_`, `#`, etc., to escape them.
    ```

## Advanced Features
### 1. Autolinks
URLs are automatically linked without needing `[text](url)`.
```
https://example.com
```
*Output*
https://example.com

### 2. HTML in Markdown
Markdown supports inline HTML for advanced use cases:
```html
<div style="color:red;">This text is red</div>
```
*Output*
<div style="color:red;">This text is red</div>


### 14. Advanced Table Formatting
Alignment options can be added to tables using colons:
```
| Left   | Center | Right |
|:-------|:------:|------:|
| Text 1 | Text 2 | Text 3|
```
*Output*
| Left   | Center | Right |
|:-------|:------:|------:|
| Text 1 | Text 2 | Text 3|


## Markdown Syntax Summary Table

| Feature            | Syntax Example                     |
|---------------------|------------------------------------|
| Headings           | `# H1`, `## H2`, `### H3`         |
| Bold/Italic        | `**Bold**`, `*Italic*`, `~~Strikethrough~~` |
| Lists              | `-` for unordered, `1.` for ordered |
| Links              | `[Link Text](https://example.com)` |
| Images             | `![Alt Text](https://example.com/image.png)` |
| Code Blocks        | ```` `code` ```` or ```` ```language \n code \n ``` ```` |
| Blockquotes        | `> Blockquote`                    |
| Horizontal Rules   | `---`                             |
| Tables             | `| Column 1 | Column 2 |`         |
| Task Lists         | `- [x] Checked, - [ ] Unchecked`  |
| Escaping Characters| `\*Not Bold\*`                    |
| Autolinks          | `https://example.com`             |
| Inline HTML        | `<div>Custom HTML</div>`          |