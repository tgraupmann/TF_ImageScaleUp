# TF_ImageScaleUp

## Image Super Resolution (esrgan-tf2)

The `esrgan-tf2` model works amazingly well, out of the box. Take a look at the notebook for details.

## Resources

* [High Fidelity Image Generation Using Diffusion Models](https://ai.googleblog.com/2021/07/high-fidelity-image-generation-using.html)

* AI Model - [esrgan-tf2](https://tfhub.dev/captain-pool/esrgan-tf2/1)

* [UpscalerJS](https://upscalerjs.com/) - Upscale images in JavaScript

* [Miniconda](https://docs.conda.io/en/latest/miniconda.html) - Run commands within the Anaconda Prompt (miniconda3)

```cmd
python -m pip install --upgrade pip
pip uninstall tensorflow
conda install tensorflow
conda install -c conda-forge tensorflow-hub
pip install --no-deps tensorflowjs
```

* [TFJS Python Environment Setup Instructions](https://github.com/tgraupmann/HTML5_AIBoxCamera)

## Screenshot

![image_1](images/image_1.png)

* Open the `Google Colab Project Notebook` - [Test_esrgan_tf2.ipynb](Test_esrgan_tf2.ipynb) <a href="https://colab.research.google.com/github/tgraupmann/TF_ImageScaleUp/blob/main/Test_esrgan_tf2.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

### Work in Progress

A TensorFlow project experiment to unblur images in HD:

* Open the `Google Colab Project Notebook` - [ImageScaleUp.ipynb](ImageScaleUp.ipynb)
