---
title: "Rotation revisited: Another unidirectional algorithm -- Raymond Chen"
url: "https://isocpp.org//blog/2026/07/rotation-revisited-another-unidirectional-algorithm-raymond-chen"
date: "2026-07-21"
author: "Blog Staff"
feed_url: "https://isocpp.org/blog/rss"
---
Some time ago, we looked at how to swap two adjacent blocks of memory in constant extra space, and along the way explored how std::rotate accomplishes the same task. I later claimed that the random-access implementations in both libc++ and libstdc++ treat the operation as a permutation decomposed into cycles—but after taking a closer look, I discovered that only libc++ does; libstdc++ uses a different algorithm altogether. Rotation revisited: Another unidirectional algorithm by Raymond Chen From the article: Some time ago, we looked at the problem of swapping two blocks of memory that reside i
