---
title: "NITR: Needle in the Repo"
excerpt: "A benchmark for evaluating coding agents on maintainability-oriented software engineering tasks with interpretable, dimension-level diagnosis."
date: 2026-04-01
status: current
---

<a href="https://www.cs.ucr.edu/~qzhang/nitr.html">Official Website</a> ·
<a href="https://github.com/ucr-riple/NITR">GitHub</a> ·
<a href="https://arxiv.org/abs/2603.27745">Paper</a>

## Overview

NITR (Needle in the Repo) is a benchmark for evaluating coding agents on repository-grounded software engineering tasks that emphasize maintainability rather than surface-level patch completion alone.

## Focus

The benchmark is organized around interpretable maintainability dimensions such as change locality, reuse, responsibility decomposition, extension structure, dependency control, testability, lifecycle management, and side-effect isolation.

## Goal

The goal is to diagnose where coding agents succeed or fail when they need to make changes that remain local, reusable, testable, and structurally coherent inside an existing codebase.
