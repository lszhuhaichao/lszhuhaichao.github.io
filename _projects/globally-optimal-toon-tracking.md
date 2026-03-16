---
title: "Globally Optimal Toon Tracking"
excerpt: "A SIGGRAPH 2016 paper on region correspondence and tracking for hand-drawn animation using global optimization over appearance and motion cues."
date: 2016-07-01
status: past
link: "https://ttwong12.github.io/papers/toontrack/toontrack.html"
---

## Paper

**Globally Optimal Toon Tracking**  
ACM Transactions on Graphics (SIGGRAPH 2016 issue)

## Problem

Tracking object and region correspondences across frames in hand-drawn animation is difficult when appearance cues are ambiguous, objects undergo occlusion, or multiple regions share similar visual characteristics.

## Method

This work formulates temporal region correspondence as a global optimization problem over both appearance and motion cues. The correspondence likelihoods are modeled as a network-flow graph and solved with a global optimization algorithm.

## Results

The method was evaluated on multiple animation sequences and showed consistent improvements over prior correspondence methods without requiring user guidance.

## Links

- [Project Page](https://ttwong12.github.io/papers/toontrack/toontrack.html)
