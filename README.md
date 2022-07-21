# yolov5-project-1

**To use your GPU:**
1. Install required version of the [CUDA Toolkit](https://developer.nvidia.com/cuda-downloads?target_os=Windows&target_arch=x86_64&target_version=11).

2. Clone the YOLOv5 repository:

```bash
        !git clone https://github.com/ultralytics/yolov5
```

3. Create a virtual environment:

```bash
        conda create --name "environment name"
```        

4. Install [Pytroch CUDA 11.3](https://github.com/ultralytics/yolov5/issues/8395): 

```bash
        pip install torch==1.11.0+cu113 torchvision==0.12.0+cu113 torchaudio==0.11.0 --extra-index-url https://download.pytorch.org/whl/cu113
```

5. In the envrionment install the required yolov5 packages:

```bash
        pip install -r requirements.txt
```