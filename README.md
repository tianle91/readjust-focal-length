# python-template
Template intended for development in a container.

To produce the depth maps from the included `sample.heic`:
```
brew install libheif
heif-convert --with-aux sample.heic sample.jpg
```

So far I've found that OpenCV worked best for infilling.
Using stable-diffusion yielded poor noisy results [here](https://colab.research.google.com/drive/1IWzy9WmxbSDrtwdUIF4CqN4A7fjAazT_?usp=sharing).
 