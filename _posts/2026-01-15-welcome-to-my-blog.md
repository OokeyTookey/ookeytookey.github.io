---
layout: post
title: "Welcome to my blog"
date: 2026-01-15
tags: [devlog]
excerpt: "A short introduction post to check headings, code blocks, quotes, lists and images all look right in the theme."
---

This is the first post, mostly here to sanity-check that everyday markdown renders nicely inside the existing site theme.

## A heading like this

Regular paragraph text sits inside the `.current-blog` box, left-aligned for readability, unlike the centred hero text on the homepage.

### A smaller heading

- A bullet
- Another bullet
- One more, with `inline code`

> A blockquote, for pulling out a quote or a callout.

```js
// A fenced code block
function greet(name) {
  return `Hello, ${name}!`;
}
```

| Engine | Genre     | Status    |
|--------|-----------|-----------|
| Unity  | Puzzle    | Shipped   |
| Godot  | Platformer| Prototype |

[A link back home]({{ '/' | relative_url }}).
