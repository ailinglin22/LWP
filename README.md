# Learnable Weighted Pooling for 3D Medical Image Classification
This is the Pytorch implementation on the Learnable Rank Pooling method for 3D to 2D image conversion for Alzheimer's Disease image classification. 
Unlike to the Approximate Rank Pooling (ARP) method, our method is a simple but useful learnable rank pooling. The inspiration is based on the Usman's project: [paper](https://openaccess.thecvf.com/content_CVPRW_2019/papers/EarthVision/Rafique_Weakly_Supervised_Fusion_of_Multiple_Overhead_Images_CVPRW_2019_paper.pdf) and [code](https://github.com/mvrl/weakly-supervised-image-fusion). 

Authors:Xin Xing, M.  Usman  Rafique, Gongbo Liang, Hunter Blanton, Yu Zhang, Chris Wang, Nathan Jacobs, and Ai-Ling Lin

Corresponding author: 

Ai-Ling Lin (ai-ling.lin@health.missouri.edu)

Questions on the scripts of the project? Ask me (xxi242@g.uky.edu)

## Abstract:
We address the task of classifying Alzheimer’s disease from 3D volumetricmedical imaging.  We propose a 3D-to-2D approach, where we first projectthe  3D  volume  into  a  2D  image.   This  reduces  computational  complexityand enables the use of pre-trained convolutional neural networks (CNN) fea-ture  extractors.   We  introduce  a  new  3D-to-2D  projection  module,  whichadaptively  selects  the  most  salient  3D  slices.   Our  model  is  an  end-to-endarchitecture.   We  evaluate  our  approach  using  PET  images  from  the  pub-licly available Alzheimer’s Disease Neuroimaging Initiative dataset.  The re-sults show that our approach outperforms a comparable 3D CNN model and3D-to-2D models that use traditional pooling operations.  We find that ourapproach requires similar training time to models using traditional poolingoperations, but 75% less time than the 3D CNN model. 


## Prerequisites
* [Python3](https://www.python.org/)
* [Pytorch](https://pytorch.org/)
* [NiBabel](https://nipy.org/nibabel/)



## Workflow:
![](https://github.com/ailinglin22/LWP/tree/main/imgs/architecture.png)


## Results:
CUvsAD:

![](https://github.com/ailinglin22/LWP/tree/main/imgs/results_1.png)

Multi-class Classification:

![](https://github.com/ailinglin22/LWP/tree/main/imgs/Results_2.png)
