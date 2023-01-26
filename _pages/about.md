---
permalink: /
title: "Pratik Ratadiya: Personal Website"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! I am Pratik, a second-year Masters in Computer Science and Engineering student at the University of California, San Diego. My research interests lie in Natural Language Processing, AI for Social Good, Anomaly Detection. I think of myself as more of a problem-solver and am also interested in Product Management, Startups, and System design. I have more than 1 year of full-time experience and 16 months of internship experience. **I am currently looking for full-time engineering and research roles in Machine Learning and NLP starting June 2023. If you are hiring, [get in touch](mailto:prratadiya@gmail.com).**

What am I working on right now?
======
- Research Fellow at [NCRI](https://networkcontagion.us/) working on developing AI methods for better social media analysis for underrepresented groups.
- Research member at the [Computing for Social Good (CSG) lab](https://melsherief.eng.ucsd.edu/research) working on dataset creation, researching and developing new AI models for violence and threat detection, especially against protected communities.

Recent Updates
======
- \[11/2022\]: I am happy to start as a research fellow at NCRI! Read our first report [here](https://networkcontagion.us/reports/11-16-22-cyber-social-swarming-precedes-real-world-riots-in-leicester-how-social-media-became-a-weapon-for-violence/)
- \[10/2022\]: Selected amongst the [Top 120 creators](https://members.linkedin.com/creators/us-participants-for-technology-and-innovation) in Tech and Innovation under the Creator Accelerator Program by LinkedIn!

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
