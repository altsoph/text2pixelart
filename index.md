## Text2pixelart demos

This project explores opportunities for an unsupervised generation of animated pixel-art based on the given text prompt. 

As the base, I used PixelDraw by @dribnet, based on the ClipDraw library, which in turn is based on the diffvg library. 

First, I've implemented some handy options, such as smoothness enforcement, palette enforcement, and saturation enforcement. Next, I've exploited the CLIP's "healing" ability and a couple of "demoscene" tricks to keep the coherence between adjacent frames to make several different animations: the infinite panorama, the parallax effect, the 3d swirl around the object, the moving background, the endless looping, and so on. 

I've tried to give a tribute to old-school classics (using prompts like `fallout`, `r-type`, and `Guybrush Threepwood`) and to explore the fractal and space thematics, trying to find the best match between the prompt and the effect in each case. 

The code of some tricks is published already; other hacks are on their way to be publicly available.

## Panorama demos

![Image](https://raw.githubusercontent.com/altsoph/text2pixelart/master/colors2b.mp41.gif)

![Image](https://raw.githubusercontent.com/altsoph/text2pixelart/master/green1a.mp4.gif)

[The demo colab is here](https://github.com/altsoph/text2pixelart/blob/main/Pixray_Panorama_Demo.ipynb).

## Parallax demos

![Image](https://raw.githubusercontent.com/altsoph/text2pixelart/master/mars.mp4.gif)

![Image](https://raw.githubusercontent.com/altsoph/text2pixelart/master/parala5a10.mp4.gif)

[More tricks](https://twitter.com/altsoph/status/1434906121618300941)

## Spiral demos

![Image](https://raw.githubusercontent.com/altsoph/text2pixelart/master/escher_swirl_v0.mp4.gif)

![Image](https://raw.githubusercontent.com/altsoph/text2pixelart/master/knot_swirl_bg1.mp4.gif)

![Image](https://raw.githubusercontent.com/altsoph/text2pixelart/master/lorenz_swirl.mp4.gif)

![Image](https://raw.githubusercontent.com/altsoph/text2pixelart/master/romanesco_swirl.mp4.gif)

[More tricks](https://twitter.com/altsoph/status/1437797243956998147)
## Moving background demos

![Image](https://raw.githubusercontent.com/altsoph/text2pixelart/master/apoc4_demo_rev.mp4.gif)

![Image](https://raw.githubusercontent.com/altsoph/text2pixelart/master/matrix2_demo.mp4.gif)

![Image](https://raw.githubusercontent.com/altsoph/text2pixelart/master/guybrush_demo.mp4.gif)

[More tricks](https://twitter.com/altsoph/status/1439992040822087685)
