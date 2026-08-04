---
title: "A shocking discovery about gcc’s unidirectional rotation algorithm -- Raymond Chen"
url: "https://isocpp.org//blog/2026/07/a-shocking-discovery-about-gccs-unidirectional-rotation-algorithm-raymond-c"
date: "2026-07-23"
author: "Blog Staff"
feed_url: "https://isocpp.org/blog/rss"
---
Last time, we looked at the rotation algorithm used by gcc libstdc++ for random-access iterators , and I concluded by noting that we’re going to make a shocking discovery. Rotation revisited: A shocking discovery about gcc’s unidirectional rotation algorithm by Raymond Chen From the article: As with all shocking discoveries, this one will shock disappoint you. The discovery is that the gcc libstdc++ algorithm is the same as the forward-iterator algorithm !
