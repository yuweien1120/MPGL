# MPGL

**Measurement-prior-guided learning for subpixel keypoint localization in microscopic measurement**

## Overview

MPGL learns subpixel keypoint localization from paired microscopic images acquired before and after stage motion. A shared network predicts corner heatmaps from local image patches, and a differentiable expectation operation recovers continuous subpixel coordinates. Stage displacement magnitudes and known target dimensions supervise the motion and geometry reconstructed from these coordinates, without requiring manually annotated keypoint coordinates.

The displacement supervision uses motion magnitudes and does not require the stage motion to align with the image axes. Dimension supervision constrains the relative positions of keypoints through the known target geometry. The trained localization model is used for displacement and dimension measurement.

## Availability

This repository currently provides a project overview. Research data are planned for public release upon acceptance of the manuscript. The code and model weights are being prepared.
