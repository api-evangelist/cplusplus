---
title: "Avoiding having to calculate the gcd when doing cycle decomposition -- Raymond Chen"
url: "https://isocpp.org//blog/2026/08/avoiding-having-to-calculate-the-gcd-when-doing-cycle-decomposition-raymond"
date: "2026-08-03"
author: "Blog Staff"
feed_url: "https://isocpp.org/blog/rss"
---
Last time, we looked at how clang’s libcxx implementation of std:: rotate uses cycle decomposition to minimize the number of swaps. Doing so requires calculating the greatest common divisor, but I noted that the OpenJDK implementation of the java standard library uses a trick to avoid doing the gcd calculation . Rotation revisited: Avoiding having to calculate the gcd when doing cycle decomposition by Raymond Chen From the article: The trick is realizing that the total number of elements is equal to the sum of the lengths of each of its cycles, and each of the initial elements belongs to a dif
