 - [original repo](https://github.com/wl-zhao/DiffSwap)


1. Conda Environment

```
apt install cmake
conda env create -f environment.yaml
conda activate DiffSwap
```


2. Download Pretrained Weights and Datasets : [link](https://cloud.tsinghua.edu.cn/d/9575c106b9324df7bfe3/)


```
├── checkpoints
│   ├── diffswap.pth
│   ├── glint360k_r100.pth
│   └── shape_predictor_68_face_landmarks.dat
```

3. Run Script

- source and target images should be located at `/data/portrait_jpg/`
- output images are saved at `/data/portrait/swap_res_ori/`

```
bash run.sh
```