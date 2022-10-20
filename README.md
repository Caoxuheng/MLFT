# Unsupervised Feature Transformer with Adaptive Degradation Representation for Blind Hyperspectral and RGB image Fusion (*Pending*)
This is a transformer-based super-resolution algorithm that fuse hyperspectral and multispectral image in a unsupervised manner in coping with unknown degradation in spectral and spatial domain. The uFT fully exploits the long-range information and multi-level feature of the both MSI and HSI. The HR texture is transfered to the LR-HSI by fusing the residual texture information of different level feature extracted from HR-RGB. For an HSI with size of 16x16x31, the uFT can achieve 32x spatial improvement with very high accuracy incoping with blind degradations. The quantitative results outperform exisiting SOTA algorithms.  
***The paper has not been completed, so stay tuned!***
# Flowchart
**None**
# Result presentation
The reconstructed results are uploaded to here.
# Guidance
**None**
# Requirements
## Environment
`Python3.8`  
`torch 1.12`,`torchvision 0.13.0`  
`Numpy`,`Scipy`  
*Also, we will create a Paddle version that implements uMLFT in AI Studio online for free!*
## Datasets
[`CAVE dataset`](https://www1.cs.columbia.edu/CAVE/databases/multispectral/), 
 [`Preprocessed CAVE dataset`](https://aistudio.baidu.com/aistudio/datasetdetail/147509).
# Note
For any questions, feel free to email me at caoxuhengcn@gmail.com.  
If you find our work useful in your research, please cite our paper ^.^
