---
permalink: /
title: "academicpages is a ready-to-fork GitHub Pages template for academic personal websites"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am applying for the Ph.D. Program and  currently working as research assistant in [Yang Zheng]'s SOC lab(https://zhengy09.github.io/).  Previously, I received my bachelor degree in Mathematics and Applied mathematics, Southeast University,Nanjing, And master degree in Statistics at the University of California, San Diego.

Research Interests
======

Data-enabled predictive control, Control Lyapunov functions, Model predictive control, Linear cruise control, Control barrier functions, Nonlinear multi-agents dynamics,

=======
I am working as a research assistant in  Electrical and Computer Engineering(ECE) at the University of California, San Diego, advised by Prof. [Yang Zheng](https://zhengy09.github.io/).Previously, I received my bachelor degree in Mathematics and Applied Mathematics, Southeast University in Nanjing, and master degree in Statistics at the University of California, San Diego.

Research interests
======
Data-enabled predictive control, Control Lyapunov functions, Model predictive control, Linear cruise control,
Control barrier functions, Nonlinear multi-agents dynamics

Project 1:Coordinating directional switches in pigeon flocks: the role of nonlinear interactions
======
Focus on how white noise induces a switch in the rotation direction of a flock of pigeons. We use sparse Bayesian learning (SBL) method to extract interactions between individuals, and then we find that linear interactions dominate in the smooth part of the trajectory, while the percentage of higher-order nonlinear interactions becomes larger when switching trajectories. With the help of the Focke-Planck equation, an analytical solution is obtained for the mean time for a flock of pigeons to rotate from a complete clockwise rotation to a complete counterclockwise rotation. Since the stationary probability distribution of S(t) (global mean spin) satisfies the bimodal truncated normal distribution, additional calculations are required to correct the theoretical results. The theory agrees well with GPS data, and the results have been published in the journal Royal Society Open Science.[[PDF]](https://royalsocietypublishing.org/doi/epdf/10.1098/rsos.210649)



Project 2:Phase transition in nonlinear dynamics flocks: Natural Intrinsic Period induced by noise disturbance.
======
Introducing the principles of statistical mechanics to analyze second-order dynamical systems with independent noise terms excites me. In courses on stochastic processes, noise is always not considered to be the key to the problem, but in this project, noise is very good. It plays a key role in explaining why the pigeons' rotation direction switches from clockwise to counterclockwise. In the following work, our attention turns to the Vision-cone model, which is an improvement based on the famous Vicsek model. Although there are mature fluid mechanics tools such as Toner-Tu theory, used to describe the abrupt jump of the global order parameter, but we want to start from another perspective and develop some kind of theoretical framework that does not rely on order parameters. In conjunction with the Fokker-Planck equation, we developed a mathematical tool called NIP (natural intrinsic period), combined with sub-index Coefficient of variation. It can well explain how white noise and some dynamic parameters induce the system to produce rich phenomena, such as single ring, twist-like ring, or liquid crystal state. 

Project 3:Project 2:Phase transition in nonlinear dynamics flocks: Natural Intrinsic Period induced by noise disturbance.
------
Summer research

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
