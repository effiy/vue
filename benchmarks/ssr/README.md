---
title: Vue.js SSR Benchmark
tags: [vue, ssr, benchmark, performance, renderToString, renderToStream]
category: benchmark
created: 2020
updated: 2026-10-20
source: external
type: index
status: stable
lifecycle: active
---

# Vue.js SSR Benchmark

---

## 💡 概述

This benchmark renders a table of 1000 rows with 10 columns (10k components), with around 30k normal elements on the page. Note this is not something likely to be seen in a typical app. This benchmark is mostly for stress/regression testing and comparing between `renderToString` and `renderToStream`.

---

## ⚡ 功能

- Stress/regression testing for Vue SSR
- Comparison between `renderToString` and `renderToStream`

---

## 📊 指标

`renderToStream` pipes the content through a stream which provides considerable performance benefits (faster time-to-first-byte and non-event-loop-blocking) over `renderToString`. This can be observed through the benchmark.

Note that the overall completion time for the results is variable, this is due to other system related variants at run time (available memory, processing power, etc). In ideal circumstances, both should finish within similar results.

---

## 🏛️ 设计

「待補充」

---

## 📁 目录

「待補充」

---

## 🔗 资源

「待補充」

---

## 🚀 快速开始

``` bash
npm run bench:ssr
```

---

## ⚙️ 技术栈

- Vue.js
- Node.js SSR