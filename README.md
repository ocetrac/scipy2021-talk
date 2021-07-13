# Ocetrac: morphological image processing for monitoring ocean temperature extremes

### Earth, Ocean, Geo, & Atmospheric Science Talk, SciPy 2021

#### Contributors: 

[Hillary Scannell](https://github.com/hscannell), [Luanne Thompson](https://github.com/luanne1213), [Daniel Whitt](https://github.com/danielwhitt), [David John Gagne](https://github.com/djgagne), [Ryan Abernathey](https://github.com/rabernat) & [Julius Busecke](http://jbusecke.github.io/)

#### Short summary: 

Dangerous hot-water events, called marine heatwaves, cause prolonged periods of thermal stress in the marine environment that can lead to widespread coral bleaching, harmful algal blooms, unproductive fisheries, and even economic loss. Anticipating the paths of destructive marine heatwaves remains a challenge owing to the complex spatiotemporal evolution of these events. We present a novel open source package called Ocetrac that implements morphological image processing and tracking to aid in the analysis of marine heatwave detection and movement. We discuss how this approach can be applied to monitor other extreme ocean conditions, such as deoxygenation and acidification.

### ⚙️ Getting started ⚙️

The code in the presentation has been written using Python 3. To get started, clone the repository using git `git clone https://github.com/ocetrac/scipy2021-talk.git` or by downloading this repostiory as a [Zip file](https://github.com/ocetrac/scipy2021-talk/archive/refs/heads/main.zip).

Install the conda environment:

```bash
conda env create -f environment.yml

conda activate ocetrac-scipy-2021

# Create a kernel for this environment
python -m ipykernel install --user --name=ocetrac-scipy-2021
```

### ⚡ Access the presentation slides ⚡

In the spirit of a truely open source project, we used [`reveal.js`](https://github.com/hakimel/reveal.js) to create this presentation. The slides are linked to the [`Ocetrac`](https://ocetrac.readthedocs.io/en/latest/) docs and can be accessed here https://ocetrac.github.io/scipy2021-talk/.
