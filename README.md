# python-template
Template intended for development in a container.

To produce the depth maps from the included `sample.heic`:
```
brew install libheif
heif-convert --with-aux sample.heic sample.jpg
```

https://huggingface.co/docs/diffusers/optimization/mps
```
pip install --pre torch==1.14.0.dev20221007 torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/nightly/cpu
```
