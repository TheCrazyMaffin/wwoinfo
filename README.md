# wwoinfo.github.io
Translated Knowledgebase/Utility for Werewolf Online and it's social media appearance

# Notes for developrers

+ The folders with a name starting with an underscore are used for the page internals. Only folders without an underscore are included in the sitemap.
+ Use relative paths for links within the page
+ I suggest https://www.markdownguide.org/cheat-sheet/ if you need help using MD

## Jump to links
Use *anchors*. Paste `<a name="NAME">` where the link should jump to. Link to this using MD-Syntax `[Text](#NAME)`

## _posts
Files have to follow `YEAR-MONTH-DAY-title.MARKUP`

Place files in `_drafts` if unfinished/waiting to be published. Please keep in mind that anyone can view this repository, hence also drafts.

### Template

```
---
layout: post
title:  "Hello World"
date:   2020-02-24 23:27:43 +0100
categories: CAT1 CAT2 ETC
---

CONTENT
```

## Pages

### Template

```
---
layout: page
title: "PAGE TITLE"
exclude: true # Remove this line if this file should be shown in the header of the page
# permalink: /URL-PATH/ # Not required. Only added if link differs from file path
---
```