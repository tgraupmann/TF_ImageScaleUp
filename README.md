# TF_ImageScaleUp

## Image Super Resolution (esrgan-tf2)

The `esrgan-tf2` model works amazingly well, out of the box. Take a look at the notebook for details.

## Resources

* [High Fidelity Image Generation Using Diffusion Models](https://ai.googleblog.com/2021/07/high-fidelity-image-generation-using.html)

* AI Model - [esrgan-tf2](https://tfhub.dev/captain-pool/esrgan-tf2/1)

* [UpscalerJS](https://upscalerjs.com/) - Upscale images in JavaScript

* [Setup WSL2 and Python](http://tagenigma.com/blog/2020/11/24/windows-subsystem-for-linux-installation-guide-for-windows-10/) - TensorFlow is missing dependencies to work on Windows (TensorFlow Decision Forests)

* [Get started using Python for web development on Windows](https://learn.microsoft.com/en-us/windows/python/web-frameworks)

### WSL2

```sh
sudo apt update && sudo apt upgrade
sudo apt upgrade python3
sudo apt install python3-pip
python3 -m pip install --upgrade pip
pip3 install --upgrade pip
sudo apt install python3-venv
pip3 install tensorflow tensorflowjs tensorflow-hub
```

### Windows

* [Miniconda](https://docs.conda.io/en/latest/miniconda.html) - Run commands within the Anaconda Prompt (miniconda3)

```cmd
python -m pip install --upgrade pip
pip3 uninstall tensorflow tensorflowjs tensorflow-hub jax
conda install tensorflow
conda install -c conda-forge tensorflow-hub
pip3 install tensorflow tensorflowjs tensorflow-hub
```

* [TFJS Python Environment Setup Instructions](https://github.com/tgraupmann/HTML5_AIBoxCamera)

## Screenshot

![image_1](images/image_1.png)

* Open the `Google Colab Project Notebook` - [Test_esrgan_tf2.ipynb](Test_esrgan_tf2.ipynb) <a href="https://colab.research.google.com/github/tgraupmann/TF_ImageScaleUp/blob/main/Test_esrgan_tf2.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

### Work in Progress

A TensorFlow project experiment to unblur images in HD:

* Open the `Google Colab Project Notebook` - [ImageScaleUp.ipynb](ImageScaleUp.ipynb)
