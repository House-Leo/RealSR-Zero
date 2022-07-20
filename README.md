# RealSR-Zero

## RealSR-Zero dataset provided by our paper ["Criteria Comparative Learning for Real-scene Image Super-Resolution"](https://github.com/house-leo/realsr-zero).

## Link: [Google Drive](https://drive.google.com/file/d/1A7wyIuSEBe4zzK9n05e81AD8Xz6LHAU9/view?usp=sharing), [Baidu Drive](https://pan.baidu.com/s/13D5uZUpORZbjlKVRN1doGg?pwd=ljdr)(ljdr)

**RealSR-Zero** consists of **45 LR images**, which are shot by a *iPhone4 device* in different time, place and user. We collect them from internet, and the shooting period is 2011-2013 year. To modeling a challenge real-world scene, only poor-quality image are provided for evaluation. Thus, we adopt label-free quality assessment metric **NIQE**, to verity each method.

> NIQE and MOS result for RealSR-Zero

 | Methods | ESRGAN | Impressionism | DASR | Real-ESRGAN | Ours |    
 |---------|--------|---------------|------|-------------|------|
 | NIQE |  6.066  | 4.961  |   5.838  |   4.575  | **4.409**  |
 | MOS |  4.275  |     3.455     |   4.470 |  3.245   |  **3.050**  |  

> Visualization

![0](comparison/real-zero-1.png)

![1](comparison/real-zero-2.png)

### Citation:
If you find this work useful for your research, please cite:

```
@artical{shi2022realsr,
  title={Criteria Comparative Learning for Real-scene Image Super-Resolution},
  author={Shi, Yukai and Li, Hao and Zhang, Sen and Yang, Zhijing and Wang, Xiao},
  journal={IEEE Transactions on Circuits and Systems for Video Technology},
  year={2022}
}
```

### Contact:
Please contact me if there is any question (Hao Li: haoli@njust.edu.cn) (Yukai Shi: ykshi@gdut.edu.cn).