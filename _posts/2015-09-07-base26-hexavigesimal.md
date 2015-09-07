---
layout: post
title: Base26 Hexavigesimal Implementation
---

Recently, I faced an interesting challenge with a valued client. In their system, a user could either choose to have a specific identifier consist of either numbers or alphabet letters. In both cases, the identifiers are unique and sequential. With numbers, the case is simple as the sequence is the expected: 1, 2, 3 ... 10, 11 ... n.
With the alphabet numeric system, letters represent numerics values as follows: A (1), B(2) ... Z(26) .. AA(27) ... n. This sort of alphabetical numeric system is called Hexavigesimal, with a base of 26.

The following is the implementation in both Javascript (with a sample fiddle) and C#.

<iframe width="100%" height="300" src="//jsfiddle.net/LeoJH/yct99wtb/embedded/result,js,resources,html/" allowfullscreen="allowfullscreen" frameborder="0"></iframe>

<br>
**C#**
<script src="https://gist.github.com/leojh/2f22e0f12f7fa7a6018d.js"></script>
