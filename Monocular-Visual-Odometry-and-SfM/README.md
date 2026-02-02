# Monocular Visual Odometry and SfM

This project evaluates local feature detection, description, and matching methods
under viewpoint and illumination changes, and studies embedding-based image retrieval.

## Methods
- Compared Harris, SIFT, MagicPoint, and SuperPoint
- Evaluated repeatability, localization error, matching score, and NN mAP
- Applied homographic adaptation for improved robustness
- Trained an embedding model for image retrieval on FashionMNIST
- Evaluated retrieval performance using precision@1

### Keypoint Detection
MagicPoint
| Image A | Image B |
|--------|--------|
| ![](pytorch-superpoint/images/magicpoint_sample2.png.png) | ![](pytorch-superpoint/images/magicpoint_sample5.png.png) |

Harris
| Image A | Image B |
|--------|--------|
| ![](pytorch-superpoint/images/harris_sample2.png.png) | ![](pytorch-superpoint/images/harris_sample5.png.png) |

### SuperPoint Matching on My Own Image Pair

| Pair 1 | Pair 2 |
|-------------|--------------|
| ![](pytorch-superpoint/images/superpoint_matching1.png.png) | ![](pytorch-superpoint/images/superpoint_matching2.png.png) |


[Project Report (PDF)](report1.pdf)

