
修改部分
=================
* 原本程式碼只有跑一次，而且沒有對影片結束做判斷，修改回除非壓按鍵't'才會退出，否則會一直無限跑下去。

安裝
=================
- 1. Install [CUDA](https://developer.nvidia.com/cuda-downloads)

- 2. Install torch with CUDA 12
```shell
pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu124
```

- 3. Install Yolo8
```shell
pip install ultralytics
```
- 4. CV2
```shell
pip install opencv-python
```