# Some stuff learning from random tutorials about tensorflow

## Python setup

* [Install anaconda](https://www.anaconda.com/distribution/)
* Create python environment

```bash
conda -V
conda info -e
conda create -n py364tf15gpu python=3.6.4 pip

activate py364tf15gpu
```

## Tensorflow GPU setup for windows

* [CUDA 9.0](https://developer.nvidia.com/cuda-90-download-archive)
  * Install base (will take a time and may require restart PC)
  * Install patches one by one

* [cuDNN for CUDA **9.0**](https://developer.nvidia.com/rdp/cudnn-download)
  * Take file from archive `cuda/bin/cudnn64_7.dll` and drop it to installed CUDA dir: `C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v9.0\bin`

* Download [tensorflow 1.5](https://pypi.org/project/tensorflow-gpu/1.5.0/#files)
  * Install with `pip` on active py364tf15gpu conda environment

  ```bash
  pip install tensorflow_gpu-1.5.0-cp36-cp36m-win_amd64.whl
  ```
