---
title: "Multi-Camera Multi-Sensor SLAM"
excerpt: "A SLAM system that fuses multiple cameras and complementary sensors for robust localization and mapping across challenging motion and environment conditions."
date: 2026-03-16
status: current
---

## Problem

Conventional single-camera SLAM systems often degrade under occlusion, motion blur, limited field of view, and sensor-specific failure modes. A more robust system needs to combine complementary observations across multiple cameras and additional sensors.

## Method

This project studies a multi-camera, multi-sensor SLAM pipeline that jointly uses overlapping and non-overlapping cameras together with inertial and auxiliary sensing for state estimation, tracking, and map building. The emphasis is on cross-sensor calibration, synchronized fusion, and consistent optimization across heterogeneous measurements.

## Focus

- Multi-camera geometry and calibration
- Visual-inertial and multi-sensor fusion
- Robust tracking under fast motion and partial sensor failure
- Consistent mapping across wider fields of view
