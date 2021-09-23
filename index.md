## balh

This project explores opportunities for an unsupervised generation of animated pixel-art based on the given text prompt. 

As the base, I used PixelDraw by @dribnet, based on the ClipDraw library, which in turn is based on the diffvg library. 

First, I've implemented some handy options, such as smoothness enforcement, palette enforcement, and saturation enforcement. Next, I've exploited the CLIP's "healing" ability and a couple of "demoscene" tricks to keep the coherence between adjacent frames to make several different animations: the infinite panorama, the parallax effect, the 3d swirl around the object, the moving background, the endless looping, and so on. 

I've tried to give a tribute to old-school classics (using prompts like `fallout`, `r-type`, and `Guybrush Threepwood`) and to explore the fractal and space thematics, trying to find the best match between the prompt and the effect in each case. 

The code of some tricks is published already; other hacks are on their way to be publicly available.

## Panorama demos

![Image](https://raw.githubusercontent.com/altsoph/text2pixelart/master/colors2b.mp41.gif)

![Image](https://raw.githubusercontent.com/altsoph/text2pixelart/master/green1a.mp4.gif)


## Parallax demos

![Image](https://raw.githubusercontent.com/altsoph/text2pixelart/master/mars.mp4.gif)

![Image](https://raw.githubusercontent.com/altsoph/text2pixelart/master/parala5a10.mp4.gif)

## Spiral demos

![Image](https://raw.githubusercontent.com/altsoph/text2pixelart/master/romanesco_swirl.mp4.gif)



## text1


[Link](url) and ![Image](src)



## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/altsoph/text2pixelart/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/altsoph/text2pixelart/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
