---
title: "C++26: More function wrappers -- Sandor Dargo"
url: "https://isocpp.org//blog/2026/07/cpp26-more-function-wrappers-sandor-dargo"
date: "2026-07-09"
author: "Blog Staff"
feed_url: "https://isocpp.org/blog/rss"
---
C++26 completes the type-erased callable wrapper picture. std::copyable_function gives us what std::function should have been from the start: a copyable wrapper with correct const semantics. std::function_ref fills the non-owning niche, offering a lightweight, zero-allocation alternative for callback parameters.
