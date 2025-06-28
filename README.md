# SiamBS
Specifically, a butterfly-shaped model is constructed to extract the deep feature of an infrared dim and small target. In addition, an interactive head is incorporated into the anchor-free Siamese framework to gain more accurate precise network parameters, helping to improve the stability of the algorithm.
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
