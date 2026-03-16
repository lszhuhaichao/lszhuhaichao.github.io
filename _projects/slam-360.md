---
title: "360 SLAM"
excerpt: "A panoramic SLAM system for mapping and localization using 360-degree imagery with robust loop closure and global consistency."
date: 2026-03-01
status: current
---

## Problem

Build a SLAM system that can use 360-degree imagery for mapping and localization across a wide range of environments, especially where large fields of view and long trajectories matter.

## Method

The project uses a panoramic SLAM pipeline with feature extraction and matching on 360 imagery, pose graph optimization, loop closure detection, and global refinement to maintain consistent maps over large-scale scenes.

## My Role

I worked on the core geometry and optimization pipeline, including robust pose estimation, loop closure handling, and improving map consistency across long sequences.

## Demo Video

<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden;">
  <iframe
    src="https://www.youtube.com/embed/fJYtjs3FhHA"
    title="360 SLAM Demo"
    style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: 0;"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
    referrerpolicy="strict-origin-when-cross-origin"
    allowfullscreen>
  </iframe>
</div>

## Focus

- Robust localization from panoramic observations
- Loop closure and drift reduction
- Globally consistent maps from long trajectories
