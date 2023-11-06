---
permalink: /
title: "Welcome to Huan Zhang's website!  
欢迎来到我的个人网站!"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am Huan Zhang, born in April 1994, currently is an associate research fellow of Zhengzhou University. I am a member of China Computer Federation (CCF) and Chinese Association for Artificial Intelligence (CCAI). Previously, I received my B.S. degree in Computer Science and Technology from Central China Normal University (CCNU) in June 2016, and received my Ph.D. degree in Geoscience Information Engineering from China University of Geosciences (CUG) in June 2023. Besides, I was a visiting student of Monash University from June 2022 to June 2023. After receiving the B.S. degree, I joined the China Unionpay Merchant Service, Wuhan in 2016.7, working as a software engineer until 2018.8. My research area is machine learning and data mining, and my research interests mainly include Bayesian classification, crowdsourcing, defect detection and so on.

我是张欢，1994年4月生，目前担任郑州大学直聘副研究员，也是中国计算机学会和中国人工智能学会的会员。我于2016年6月获得华中师范大学计算机科学与技术学士学位，2023年6月获得中国地质大学（武汉）地学信息工程博士学位，此外，我曾于2022年6月至2023年6月在澳大利亚蒙纳士大学公派联合培养。在获得学士学位后，曾于2016年7月至2018年8月任银联商务有限公司（武汉）软件开发工程师。我的研究领域是机器学习和数据挖掘，研究兴趣主要包括贝叶斯分类、众包学习、缺陷检测等。

News 研究兴趣
======

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
