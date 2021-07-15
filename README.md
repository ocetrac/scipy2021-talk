# Ocetrac: morphological image processing for monitoring ocean temperature extremes

### Earth, Ocean, Geo, & Atmospheric Science Talk, SciPy 2021

#### Contributors (alphabetical): 

[Hillary Scannell](https://github.com/hscannell)(*presenter)

[Ryan Abernathey](https://github.com/rabernat), [Julius Busecke](http://jbusecke.github.io/), [David John Gagne](https://github.com/djgagne), [Luanne Thompson](https://github.com/luanne1213), and [Daniel Whitt](https://github.com/danielwhitt)

#### Short summary: 

Dangerous hot-water events, called marine heatwaves, cause prolonged periods of thermal stress in the marine environment that can lead to widespread coral bleaching, harmful algal blooms, unproductive fisheries, and even economic loss. Anticipating the paths of destructive marine heatwaves remains a challenge owing to the complex spatiotemporal evolution of these events. We present a novel open source package called Ocetrac that implements morphological image processing and tracking to aid in the analysis of marine heatwave detection and movement. We discuss how this approach can be applied to monitor other extreme ocean conditions, such as deoxygenation and acidification.

### ⚙️ Getting started ⚙️

The code in the presentation has been written using Python 3.8. The code and preconfigured environment is all available through the Pangeo Binder below: 

[![Binder](https://binder.pangeo.io/badge_logo.svg)](https://binder.pangeo.io/v2/gh/hscannell/default-binder/ocetrac?urlpath=git-pull%3Frepo%3Dhttps%253A%252F%252Fgithub.com%252Focetrac%252Fscipy2021-talk%26urlpath%3Dlab%252Ftree%252Fscipy2021-talk%252F%26branch%3Dmain)


### ⚡ Access the presentation slides ⚡

In the spirit of a truely open source project, we used [`reveal.js`](https://github.com/hakimel/reveal.js) to create this presentation. The slides are linked to the [`Ocetrac`](https://ocetrac.readthedocs.io/en/latest/) docs and can be accessed here https://ocetrac.github.io/scipy2021-talk/.

To build the html file, run these lines at the terminal within the repository:
```bash
jupyter nbconvert index.ipynb --to slides --reveal-prefix reveal.js --SlidesExporter.reveal_transition=none --SlidesExporter.reveal_scroll=True 
 
mv index.slides.html index.html # renames the html file

```
