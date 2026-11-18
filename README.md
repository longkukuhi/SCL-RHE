# SCL-RHE

*Understanding and Mitigating Human-Labelling Errors in Supervised Contrastive Learning* · ECCV 2024. [Paper](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/07150.pdf) · [Supplementary material](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/07150-supp.pdf).

Supervised contrastive learning uses class labels to decide which pairs of images should have similar representations. A labelling error can turn two images from different classes into a positive pair. The paper studies how human errors of this kind affect training and introduces SCL-RHE, a contrastive objective designed for datasets with low rates of human annotation error.

## Using this release

This repository currently provides the paper reference. The method, experiments and benchmark comparisons are in the paper. The supplement provides additional analyses of human and synthetic label errors. The default branch contains only this README, with no training scripts or checkpoint download.

## Citation

Zijun Long, Lipeng Zhuang, George Killick, Richard McCreadie, Gerardo Aragon-Camarasa and Paul Henderson. *Understanding and Mitigating Human-Labelling Errors in Supervised Contrastive Learning*. European Conference on Computer Vision, 2024. [Publisher record](https://doi.org/10.1007/978-3-031-72949-2_25).
