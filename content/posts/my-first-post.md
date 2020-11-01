---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "My First Post"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2020-11-01T00:10:44-07:00
lastmod: 2020-11-01T00:10:44-07:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

```mermaid
graph TD;
  A-->B;
  A-->C;
  B-->D;
  C-->D;
```

```cpp
auto f() {}              // returns void
auto g() { return f(); } // returns void
auto* x() {}             // error: cannot deduce auto* from void
```