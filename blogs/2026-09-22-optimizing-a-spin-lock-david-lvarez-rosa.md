---
title: "Optimizing a Spin-Lock -- David Álvarez Rosa"
url: "https://isocpp.org//blog/2026/09/optimizing-a-spin-lock-david-alvarez-rosa"
date: "2026-09-22"
author: "dalvrosa"
feed_url: "https://isocpp.org/blog/rss"
---
From a naive exchange loop to a spin-lock 5.7x faster drawing 5.4x less energy, with benchmarks, assembly, and perf counters at each step. Optimizing a Spin-Lock by David Álvarez Rosa From the article: A spin-lock is a lock that never sleeps. Instead of yielding to the scheduler, the thread stays on the CPU and spins .
