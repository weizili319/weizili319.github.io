---
layout: post
title: "tag1 and tag2"
title_cn: "第一篇博客"
category: Random
tags: [life, movie]
---

### Today

Recently I have finished adding tagging infrastructure into this website. That’s was a bit tricky since Jekyll does not fully support this feature from the box. It is possible to add tags into the post’s YAML front matter and then access them using page varialbes via page.tags. However, there are no built-in means to generate tags page which collects all tags from the posts, sorts them alphabetically and builds a list of the posts assigned to every tag. Let’s take a look at one possible way to implement described functionality.
