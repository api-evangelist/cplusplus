---
title: "Rotation revisited: Cycle decomposition in clang’s libcxx -- Raymond Chen"
url: "https://isocpp.org//blog/2026/07/rotation-revisited-cycle-decomposition-in-clangs-libcxx-raymond-chen"
date: "2026-07-27"
author: "Blog Staff"
feed_url: "https://isocpp.org/blog/rss"
---
We got distracted by the rotation algorithm in gcc’s libstdc++, but let’s get back to the cycle decomposition algorithm in clang’s libcxx . Rotation revisited: Cycle decomposition in clang’s libcxx by Raymond Chen From the article: The implementation in clang’s libcxx performs the minimum number of swaps, roughly n /2, where n is the total number of elements. It does so by viewing the rotation as a permutation and walking through each of the cycles.
