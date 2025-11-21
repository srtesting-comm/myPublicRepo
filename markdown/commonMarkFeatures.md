# Supported Features Test

This file tests **all features our renderer supports**:  
CommonMark + tables + strikethrough + autolinks + heading IDs.

---

# 1. CommonMark Basics

## Headings
### Heading Level 3
#### Heading Level 4

## Emphasis
- *Italic text*
- **Bold text**
- ***Bold + italic***

## Links
A standard link: [Example](https://example.com)

## Images
![Placeholder](https://via.placeholder.com/80)

## Inline Code
Here is `inline code`.

## Code Block
```
function greet() {
console.log("Hello!");
}
```

Unordered:
- Item one
- Item two
  - Nested item

Ordered:
1. First
2. Second
3. Third

---

# 2. Tables (tableExtension)

| Name   | Role        | Location |
|--------|-------------|----------|
| Alice  | Developer   | Zurich   |
| Bob    | Designer    | London   |
| Cara   | PM          | NYC      |

Aligned:

| Left      | Center     | Right      |
|:----------|:----------:|-----------:|
| value 1   | value 2     | value 3    |
| value a   | value b     | value c    |

---

# 3. Strikethrough (strikethroughExtension)

This text has ~~strikethrough~~ formatting.

More examples:
- ~~obsolete~~ feature  
- Mixed ~~deleted~~ words in a sentence

---

# 4. Autolinks (autolinkExtension)

These should auto-link:

https://example.com  
http://github.com  
user@example.com

---

# 5. Heading IDs (idForHeadings)

## Auto-Generated Heading ID Example
Scroll down to test jumping to a distant heading.

[Jump to the TARGET SECTION](#target-section)

---

# Spacer Section
Lots of blank content below — this is intentional.

Paragraph 1  
Paragraph 2  
Paragraph 3  
Paragraph 4  
Paragraph 5  
Paragraph 6  
Paragraph 7  
Paragraph 8  
Paragraph 9  
Paragraph 10  

---

## TARGET SECTION

🎯 **You should jump here.**  
Clicking the link above should scroll you to this section.

---

# 6. Blockquotes

> This is a blockquote  
> It should render normally


