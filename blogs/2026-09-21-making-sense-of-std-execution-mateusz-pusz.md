---
title: "Making sense of std::execution -- Mateusz Pusz"
url: "https://isocpp.org//blog/2026/09/making-sense-of-stdexecution-mateusz-pusz"
date: "2026-09-21"
author: "Mateusz Pusz"
feed_url: "https://isocpp.org/blog/rss"
---
Threads, std::future , callbacks, and coroutines each answer part of asynchronous C++, and none of them compose. This is the opening article of a series on std::execution , the C++26 model for asynchronous, composable, cancellable work: what each earlier tool stops short of, what the new model actually is, and where the series goes from here. Making sense of std::execution by Mateusz Pusz From the article: At its core a sender is a value that describes work without starting it.
