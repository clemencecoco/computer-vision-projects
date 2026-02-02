# pytorch-superpoint

It contains the repo SuperPoint using Pytorch for local feature detection and matching experiments.

The codebase is adapted from the course implementation and the
original SuperPoint work by DeTone et al. It is used here as a feature
extraction and matching tool, not as a training framework.

In this homework, the implementation was used to:
- extract keypoints and descriptors from image pairs
- perform feature matching under different image transformations
- evaluate matching quality and geometric consistency

No model training was performed. The focus is on understanding and
analyzing the behavior of interest point detectors in a classical
computer vision pipeline.

Original SuperPoint paper:
DeTone et al., "SuperPoint: Self-Supervised Interest Point Detection and Description", CVPRW 2018.
