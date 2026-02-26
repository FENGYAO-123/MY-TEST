---
author: Hugo Authors
title: Math Typesetting - use Mathematical notation in blog posts
date: 2023-04-01
description: A brief guide to use KaTeX
weight: 4
---

In this example we will be using KaTex.
<!--more-->

**Note:** The online reference of
[Supported TeX Functions](https://katex.org/docs/supported.html) is a helpful resource.

### Examples

- Block math:

{{< katex display=true >}}
\varphi = 1+\frac{1} {1+\frac{1} {1+\frac{1} {1+\cdots} } }
{{< /katex >}}

- Inline math:

  This is an inline polynomial: {{< katex >}}5x^2 + 2y -7{{< /katex >}}.