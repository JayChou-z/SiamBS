# SiamBS
<div align=center><img width="800" height="300" src="https://github.com/JayChou-z/SiamBS/blob/main/assets/framework.png"/></div>

Tracking remote and small Unmanned Aerial Vehicles (UAVs) in infrared videos is prone to drift due to weak target signals and complex backgrounds. Downsampling operations as layers deepen often result in the loss of fine-grained target features and center misalignment. For tiny targets, the ground truth is intentionally larger than necessary to enclose the target, inadvertently causing the background to occupy a greater proportion than the target itself, which obscures the distinction between positive and negative samples. To address these issues, a butterfly-shaped Siamese network with an interactive head is proposed. Specifically, Pyramid Squeeze Attention (PSA) with adaptive channel weighting adjusts the reliance of different layers on convolution kernels at multiple scales, while  Spatial Perception Aggregation (SPA) leverages gated frequency-spatial transforms to alleviate weak feature loss. An interactive prediction head dynamically balances the contributions of center-ness and IoU in the quality branch based on training convergence. Moreover, a hierarchical center sampling strategy increases the proportion of definite positive samples, enhancing geometric center alignment of the bounding box. Extensive experiments on public near-infrared UAV benchmarks demonstrate the superior performance of the proposed SiamBS.
### 1.Performance
The long-term tracking evaluation:
<div align=center><img width="300" height="300" src="https://github.com/JayChou-z/BSiamIST/blob/main/precision_long.png"/><img width="300" height="300" src="https://github.com/JayChou-z/BSiamIST/blob/main/success_long.png"/></div>

<div align=center><img width="300" height="300" src="https://github.com/JayChou-z/SiamBS/blob/main/demo.mp4"/><img width="300" height="300" src="https://github.com/JayChou-z/SiamBS/blob/main/demo.mp4"/></div>


## 2.Environment
- python=3.9  
- torch=1.12.1  
- cuda=11.6 
- torchvision=0.13.1


## 3.Datasets

Note: The test set we use consists of the last 18 weak and small single-target sequences from the 22 sequences, and the training set is also selected from these single-target video sequences.
* [train dataset](https://www.scidb.cn/en/detail?dataSetId=808025946870251520&version=V2)
* [test dataset](https://www.scidb.cn/en/detail?dataSetId=720626420933459968&version=V1)
## 4.Model
Download our pretrained model:
[model](https://pan.baidu.com/s/1WDNzGo_Zo4mlZqzjwUsW7A?pwd=jayz) code: jayz

## 5.Results
We provide tracking results for comparison: In the code directory ......

## 6.Acknowledgement
The code is implemented based on[SiamCAR](https://github.com/ohhhyeahhh/SiamCAR). We would like to express our sincere thanks to the contributors.

## 7.Citation
```
@article{
  
}
```
