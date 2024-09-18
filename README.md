# InfMAE: A Foundation Model in the Infrared Modality
Official PyTorch implementation of the paper entitled 'InfMAE: A Foundation Model in the Infrared Modality'.

## Pretrain

### Create a conda environment and activate it:
```bash
conda create -n infmae python=3.7
conda activate infmae
```

### Install Pytorch==1.8.0 and torchvision==0.9.0 with CUDA==11.1:
```bash
conda install pytorch==1.8.0 torchvision==0.9.0 cudatoolkit=11.1 -c pytorch -c conda-forge
```

### Install timm==0.3.2:
```bash
pip install timm==0.3.2
```

### Pretrain on Inf30
```bash
python main_pretrain_infmae30.py --world_size 1 --local_rank 0 --rank 0
```

## Dataset
### Inf30 dataset: 
[Google Drive](https://drive.google.com/file/d/1joUmb9gXEI8wfy8YbOsfvH_CYkL7MAsF/view?usp=sharing),

[Baidu Netdisk link](https://pan.baidu.com/s/15cSH-fVpXVzIlGfXC-Cirw?pwd=InfD)

code: InfD 

### Inf50 dataset:
ing

## Pretrain on Inf30

You can download the pre-trained checkpoint [here](https://pan.baidu.com/s/1xofov5UWARRPVHB6586E2w?pwd=Apth).

## Contact
If you have any technical questions, please contact:

Fangcen Liu

QQ：835622020 wechat：Gimini_lfc

email: 835622020@qq.com  or liufc67@gmail.com

## Acknowledgment
The pretraining of our project is based on MAE [GitHub](https://github.com/facebookresearch/mae) and MCMAE [GitHub](https://github.com/Alpha-VL/ConvMAE).
Thanks for their wonderful work.

## License
This code is only freely available for non-commercial research use. If you have other purpose, please contact:

Chenqiang Gao

Email: gaochq6@mail.sysu.edu.cn

Copyright: Chongqing University of Posts and Telecommunications
