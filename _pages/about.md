---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


About me
======

I am a second-year master student at Tsinghua University, where I am fortunate to be advised by [Prof. Peng Yang](https://www.sigs.tsinghua.edu.cn/yp_en/main.htm). Recently, I am a visiting student at University of Washington, working with [Prof. Cynthia Chen](https://www.ce.washington.edu/facultyfinder/cynthia-chen).

<!--working with [Prof. Cynthia Chen](https://www.ce.washington.edu/facultyfinder/cynthia-chen).-->

Previously, I graduated from Sun Yat-Sen University with a Bachelor degree in June 2022. During my undergraduate years, I was advised by [Prof. Ming Cai](https://www.researchgate.net/profile/Ming-Cai-18).

I am broadly interested in the applications of machine learning, decision and optimization of stochastic system, markov decision process and network analysis, etc.

Links:  [[My blog]](https://500px.com/p/wjie3210?view=photos)  [[LinkedIn]](https://www.linkedin.com/in/jie-wang-980914221/)

Publications and Preprints
======
1. **J. Wang**, Z. Li, C. Chen **(2023)**. The potential of considering social capital in emergency resource allocation [Working paper]

2. **J. Wang**, P. Yang, **(2023)**. An approximate dynamic programming approach for multi-period production-delivery
scheduling of online orders with due dates
[[PDF]](files/An approximate dynamic programming approach for IPDS of online orders with due dates.pdf)

3. **J. Wang**, Q. Wang, P. Yang, J. Yu, L. Xiao, **(2023)**. Energy consumption analysis and optimization of cold stores considering differential electricity price
[[PDF]](files/Energy consumption analysis and optimization of cold stores.pdf)

4. **J. Wang**, C. Xiong, and M. Cai **(2023)** Autonomous Transportation System collaboration mechanism based on Traffic
semantics: an implementation in Automated Vehicles Crossing an Intersection Scenario [[PDF]](files/Autonomous Transportation System collaboration mechanism based on Traffic semantics.pdf)

5. **J. Wang**, Z. Cai, P. Yang, Y. Chen, B. Chen **(2022)**, An Advanced Control Strategy for Connected Autonomous Vehicles
Based on Micro Simulation Models at Multiple Intersections  [Published in Physica A: Statistical Mechanics and its
Applications] [[PDF]](files/An advanced control strategy for connected autonomous
vehicles based on Micro simulation models at multiple
intersections.pdf)

<!--Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).



Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

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
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.-->
