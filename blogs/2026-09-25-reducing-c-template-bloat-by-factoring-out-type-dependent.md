---
title: "Reducing C++ template bloat by factoring out type-dependent portions of the function -- Raymond Chen"
url: "https://isocpp.org//blog/2026/09/reducing-cpp-template-bloat-by-factoring-out-type-dependent-portions-of-the"
date: "2026-09-25"
author: "Blog Staff"
feed_url: "https://isocpp.org/blog/rss"
---
C++ templates make code reusable, but repeated expansions can quickly increase code size, especially when lambdas are involved. This article explores practical ways to reduce template bloat by separating type-dependent code from the common logic. Reducing C++ template bloat by factoring out type-dependent portions of the function by Raymond Chen From the article: C++ templates let you reuse code, but it comes at a cost: Each template expansion results in a different function.
