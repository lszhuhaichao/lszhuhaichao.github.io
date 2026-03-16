---
title: "Image Based Gravity Estimation for VIO/SLAM"
excerpt: "A current research project on calibrating noisy IMU gravity priors from a single RGB image for downstream VIO, SLAM, and visual localization systems."
date: 2026-02-28
status: current
---

## Problem

Gravity estimation is a core ingredient in VIO, SLAM, visual localization, AR, and robotics, but IMU-derived gravity priors often become unreliable under linear acceleration, vibration, drift, and transient motion.

## Method

This project studies single-image gravity prior calibration: given one RGB image and a noisy gravity prior from the IMU, the model predicts a corrected gravity direction together with a per-sample confidence score. The approach combines a prior-correction branch with an image-only branch and adaptively fuses them based on predicted reliability.

## Dataset

The work also includes a large-scale dataset of more than 148K frames with paired VIO-derived gravity ground truth and IMU-derived gravity priors, covering diverse scenes and a broad range of camera orientations.
