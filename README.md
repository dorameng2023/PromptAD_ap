PromptAD Few-Shot Anomaly Detection
=================================
Official implementation of [PromptAD: Learning Prompts with only Normal Samples for Few-Shot Anomaly Detection](http://arxiv.org/abs/2404.05231) (CVPR2024)

![RUNOOB 图标](https://github.com/FuNz-0/PromptAD/blob/main/PromptAD.jpg)

## Install
```
conda create -n prompt_ad python==3.10
conda activate prompt_ad
bash install.sh
```
## Data
Download the dataset from [MvTec](https://www.mvtec.com/company/research/datasets/mvtec-ad).

Download the dataset from [VisA](https://github.com/amazon-science/spot-diff?tab=readme-ov-file#data-download).

#### VisA preprocessing
Modify the source and target paths for the VisA dataset in `./dataset/prepare_visa_public.py`
```
python ./dataset/prepare_visa_public.py
```

## Run
```
python run_cls.py  # image-level
python run_seg.py  # pixel-level
```

## Citation
Please cite the following paper if this work helps your project:
```

```

## Acknowledge

We thank the great works [WinCLIP](https://github.com/caoyunkang/WinClip.git) and [CoOp](https://github.com/KaiyangZhou/CoOp.git) for assisting with our work.