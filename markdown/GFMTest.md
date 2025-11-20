# Unsupported GitHub Flavored Markdown (GFM) Features

This file contains examples of features that are *not* supported by our Markdown renderer.  
If the renderer is functioning correctly, none of these should render in the special GitHub way.

---

## 1. Task Lists (GFM Only)

Expected in GFM: checkboxes.  
Expected in our renderer: plain list items, no checkboxes.

- [ ] Task item one  
- [x] Completed task  
- [ ] Another pending task  
  - [ ] Nested task  
  - [x] Nested completed  
- [ ] Final item

---

## 2. @Mentions (GitHub user references)

Expected in GFM: clickable links to users.  
Expected in our renderer: plain text, no linking.

@octocat  
@github  
@some-user  
@team/engineering  
@my-org/my-team

---

## 3. Issue & Pull Request References

Expected in GFM: automatic links to issues/PRs.  
Expected in our renderer: plain text.

#123  
Fixes #57  
Related to issue github/markup#498  
bitbucketserver/project/repo#14  
myorg/myrepo#888  
owner/repo!42 (GitLab merge request reference)  

With text:
> See #12 for details  
> This replaces github/myrepo#200  

---

## 4. GitHub Commit SHA Auto-Linking

Expected in GFM: commit hashes become links.  
Expected in our renderer: plain text.

Commit:  
`e6f4e9d`  
`c0ffee42deadbeef1234567890abcdef12345678`  
Fix introduced in c0ffee4  
Reverted in 1a2b3c4

---

## 5. GitHub-Style Emoji Shortcodes

Expected in GFM: emojis are rendered.  
Expected in our renderer: plain text.

:rocket:  
:smile:  
:warning:  
:+1:  
:-1:  

---

## 6. Typographic Replacements (GFM "smart" punctuation)

Expected in GFM: curly quotes, en/em dashes, ellipsis.  
Expected in our renderer: plain text.

Straight quotes: "test"  
Dashes: a--b, a---b  
Ellipsis: ...  
