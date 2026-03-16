---
title: "HandAugment"
excerpt: "A depth-based 3D hand pose estimation project combining two-stage hand region extraction and synthetic data augmentation based on MANO."
date: 2020-01-01
status: past
---

## Paper

**HandAugment: A Simple Data Augmentation Method for Depth-Based 3D Hand Pose Estimation**

## Problem

Depth-based 3D hand pose estimation remains difficult because of viewpoint variation, self-occlusion, self-similarity between fingers, and the limited availability of accurately labeled training data.

## Method

This work combines two ideas: a two-stage neural network pipeline for improving hand region extraction from depth images, and a data augmentation strategy based on MANO-driven synthetic depth generation and real-synthetic blending.

## Results

The method achieved first place in the depth-based 3D hand pose estimation task of the HANDS 2019 challenge and showed strong improvements over baseline hand pose estimators.

## Focus

- Depth-based 3D hand pose estimation
- Better hand region extraction from noisy input patches
- Synthetic data augmentation for improved generalization
