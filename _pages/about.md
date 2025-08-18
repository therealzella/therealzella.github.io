---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

About Me
------
I am currently a research assistant in the **Department of Computer Science** at **North Carolina State University**, advised by **Dr. Huining Li**. Previously, I earned my **M.S. in Electrical & Computer Engineering** from **Duke University** and my **B.S. in Information Sciences** from the **University of Illinois Urbana–Champaign**. My research focuses on **AI for healthcare**, with interests in **human-centered AI**, **multimodal large language models**, and methods that connect **language and physiological signals** (e.g., speech, PPG/ECG). I’m currently working on voice-based biomarkers for early dementia screening and signal-to-signal modeling for mobile health monitoring, aiming to build reliable, interpretable systems with clinical impact.

**Current directions**
- **AI for Healthcare (NCSU):** Voice-based biomarkers for early dementia screening and PPG→ECG signal modeling for mobile health monitoring.
- **Computational Social Science / AI for Social Good (with NCSA collaborators):** Prior work analyzing societal impact in large-scale text datasets (e.g., scientific media), leading to peer-reviewed outputs.
- **Multimodal LLMs:** Building and evaluating human-centered multimodal systems that connect text, audio, and biosignals.

For more details, see my [Publications](/publications/) and [CV](/files/Zella_Zhao_CV.pdf).


Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.


For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
