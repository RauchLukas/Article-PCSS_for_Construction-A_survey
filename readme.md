# Article - _[Semantic point cloud segmentation with deep learning-based approaches for the construction industry: A Survey](https://doi.org/10.3390/app13169146)_


<p style="text-align: center;">Figure 13: Reported results for semantic segmentation task on the large-scale indoor  <a href="http://buildingparser.stanford.edu/dataset.html">S3DIS</a> benchmark.</p>

![Semantic segmentation benchmark results on the S3DIS dataset](./assets/Figure_13.jpg)

> Authors: ***Lukas Rauch***, _Thomas Braml_   
> Correspondence: _lukas.rauch@unibw.de_   
> DOI: _[https://doi.org/10.3390/app13169146](https://doi.org/10.3390/app13169146)_

## Abstract

Point cloud learning has recently gained strong attention due to its applications in various fields, like computer vision, robotics, and autonomous driving. Point cloud semantic segmentation (PCSS) enables the automatic extraction of semantic information from 3D point cloud data, which makes it a desirable task for construction-related applications as well. Yet, only a limited number of publications have applied deep-learning-based methods to address point cloud understanding for civil engineering problems, and there is still a lack of comprehensive reviews and evaluations of PCSS methods tailored to such use cases. This paper aims to address this gap by providing a survey of recent advances in deep-learning-based PCSS methods and relating them to the challenges of the construction industry. We introduce its significance for the industry and provide a comprehensive look-up table of publicly available datasets for point cloud understanding, with evaluations based on data scene type, sensors, and point features. We address the problem of class imbalance in 3D data for machine learning, provide a compendium of commonly used evaluation metrics for PCSS, and summarize the most significant deep learning methods developed for PCSS. Finally, we discuss the advantages and disadvantages of the methods for specific industry challenges. Our contribution, to the best of our knowledge, is the first survey paper that comprehensively covers deep-learning-based methods for semantic segmentation tasks tailored to construction applications. This paper serves as a useful reference for prospective research and practitioners seeking to develop more accurate and efficient PCSS methods.

<!-- ---  -->
> Keywords: point cloud; semantic segmentation; deep learning; machine learning; construction; automation; open source; dataset; survey

## Bibtext
```Bibtex
@article{rauch:2023,
  title={Semantic Point Cloud Segmentation with Deep-Learning-Based Approaches for the Construction Industry: A Survey},
  author={Rauch Lukas, Braml Thomas},
  journal={Applied Science},
  year={2023},
  publisher={MDPI}
}
```

## Supplementary Material

### Rankings on S3DIS Semantic Segmentation Benchmark (Previrew)
Reported results for semantic segmentation task on the large-scale indoor S3DIS benchmark (including all 6 areas, 6-fold cross validation). 
Ranked in descending order based on mIoU performance. 
> Declaration: C---convolution-based, G---graph-based,  H---hybrid, P---pooling-based, R---RNN-based, T---Transformer-based, V---voxel-based.

| Rank | Year | Model Name | Link                                                                               | Method | mIoU | mAcc  | oAcc  |
|------|------------|----------------------------------|--------------------------------------------------------|------|-------|-------|
| 1    | 2022       | WindowNorm+StratifiedTransformer | [link](https://arxiv.org/pdf/2212.02287v1.pdf)         | T    | 77.60 | 85.8  |
| 2    | 2022       | PointMetaBase-XXL                | [link](https://arxiv.org/pdf/2211.14462v1.pdf)         | MLP  | 77.00 | -     |
| 3    | 2022       | PointNeXt-XL                     | [link](https://arxiv.org/pdf/2206.04670v2.pdf)         | MLP  | 74.90 | 83.0  |
| 4    | 2022       | DeepViewAgg                      | [link](https://arxiv.org/pdf/2204.07548v2.pdf)         | H    | 74.70 | 83.8  |
| 5    | 2022       | RepSurf-U                        | [link](https://arxiv.org/pdf/2205.05740v2.pdf)         | MLP  | 74.30 | 82.6  |
| 6    | 2022       | WindowNorm+PointTransformer      | [link](https://arxiv.org/pdf/2212.02287v1.pdf)         | T    | 74.10 | 82.5  |
| 7    | 2022       | PointNeXt-L                      | [link](https://arxiv.org/pdf/2206.04670v2.pdf)         | MLP  | 73.90 | 82.2  |
| 8    | 2020       | PointTransformer                 | [link](https://arxiv.org/pdf/2012.09164v2.pdf)         | T    | 73.50 | 81.9  |





