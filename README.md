# GaitAtlas

**Explorer: https://biomechatronics001.github.io/gait-atlas/**
**Gait animation: https://biomechatronics001.github.io/gait-atlas/gait_animation.html**
**Data release (CSV, version 1.0.0): https://doi.org/10.5281/zenodo.24016895**

This repository holds the two web pages of GaitAtlas. The explorer shows lower-limb joint
kinematics, joint kinetics, ground reaction force and EMG from 120 public datasets of unassisted
locomotion in healthy participants, on one 0 to 100 % gait cycle with shared units and sign
conventions. The animation drives a musculoskeletal figure with the joint angles and EMG of a
selected dataset.
Both pages run in a web browser without installation.

## Using the explorer

Choose a measure, a joint or muscle and a locomotion mode. Every dataset that published that
channel is drawn with the median across datasets and the between-dataset band. Select a curve to see its
source record: citation, DOI, participants, leg, cycle definition and the processing applied.
The current view can be exported as CSV or SVG. In level walking, curves can be filtered by
walking speed, and a dataset that published several speeds is drawn as one curve per speed.

The pages show dataset-level mean curves, one per dataset, locomotion mode and channel; they do
not contain participant-level or raw data. Datasets whose licence terms do not cover
redistribution are listed in grey without their curves.

## Citation

Zhou, J., Zhong, S., Zheng, B., Gao, W., Wang, S., Yuan, Y., Zhou, X., & Su, H. (2026).
GaitAtlas: Harmonization and Cross-Study Analysis of Human Gait Kinematics, Kinetics, and EMG
from 120 Public Datasets. Manuscript and data release, version 1.0.0,
https://doi.org/10.5281/zenodo.24016895.

When you use specific curves, also cite the original dataset publications. Select a dataset in
the explorer to see its citation; the explorer's Cite button gives BibTeX.
