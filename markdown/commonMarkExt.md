# Supported CommonMark Extensions

This file tests **extensions our renderer supports**:  
CommonMark + tables + strikethrough + autolinks + heading IDs.
---

# 1. Tables (tableExtension)

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

# 2. Strikethrough (strikethroughExtension)

This text has ~~strikethrough~~ formatting.

---

# 3. Autolinks (autolinkExtension)

These should auto-link:

https://example.com  
http://github.com  
user@example.com

---

# 4. Heading IDs (HeadingAnchorExtension)

## Auto-Generated Heading ID Example
Scroll down to test jumping to a distant heading.

[Jump to the TARGET SECTION](#target-section)

---

# Spacer Section
Lots of blank content below, this is intentional.

Paragraph 1  
Paragraph 2  
Paragraph 3  
Paragraph 4  
Paragraph 5
---

## TARGET SECTION

**You should jump here.**  
Clicking the link above should scroll you to this section.

---
