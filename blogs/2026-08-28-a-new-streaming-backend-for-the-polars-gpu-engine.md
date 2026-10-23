---
title: "A new streaming backend for the Polars GPU engine"
url: "https://pola.rs/posts/gpu-streaming-backend/"
date: "2026-08-28"
author: "Brian Tepera, NVIDIA"
feed_url: "https://pola.rs/rss.xml"
---
The Polars GPU engine now runs on a streaming backend built on RapidsMPF. Queries spill past GPU memory and scale from one GPU to many.
